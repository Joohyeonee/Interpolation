# Interpolation

0. Interpolation : 픽셀 좌표를 간격이 1인 2-dimensional grid의 교차점으로 봤을 때, 이미지 확대 시 픽셀과 픽셀 사이 공간을 보간할 때 주변 픽셀의 값을 가져다 씀
1. Bicubic Interpolation : 픽셀 값이 인접한 그리드로 부드럽게 이어지게 하기 위해 1차 미분 연속을 만족하도록 하는 가장 낮은 차수의 방정식을 사용
2. Bilinear Interpolation : 주변 픽셀(가장 가까운 4개 화소)에 가중치를 곱한 값을 더해서 보간(선형 보간)하는 방식을 화소 당 3번 수행
3. Lanczos Interpolation : 
