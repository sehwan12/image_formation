# image_formation
<p>
체스보드 이미지를 이용해 camera calibration과  distortion correction의 예제 적용
</p>
-camera calibration 결과
<p>
Camera matrix (K) = 
[[691.78152606,   0,         440.76293613]
 [  0,         302.00108243 ,339.81891315]
 [  0,           0,          1       ]]
</p>
<p>
 왜곡 계수Distortion coefficient (k1, k2, p1, p2, k3, ...) = [ 0.1720582,  -0.36951614,  0.00771096,  0.00702065,  0.22987809]
</p>
 -distortion correction
 *original
 <img src="https://github.com/sehwan12/image_formation/assets/58384653/4bd8cad1-2350-4f4e-a6cf-3a88a84bfa00">
 *modified(왜곡 수정된 버전)
<img src="https://github.com/sehwan12/image_formation/assets/58384653/f777ff28-769f-44c8-ad7a-6929f98ebb30">
