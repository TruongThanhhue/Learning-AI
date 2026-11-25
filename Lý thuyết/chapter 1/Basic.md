### BASIC PYTHON FOR AI (MEMORIZATION MATTERS)
Hàm loss: Đo lường mức độ Supprise
loss = log(1/(P~E~)) = log(P^-1^) = -log( P )

#### Softmax funtion:
![alt text](image.png)
![alt text](image-1.png)
Nhưng nếu gặp những con số lớn hơn thì sẽ bị overflow

Khi đó chúng ta áp dụng công thức này để giải quyết vấn đề:
![alt text](image-2.png)
#### Đạo hàm cho hàm liên tục
##### Example: DERIVATIVE
![alt text](image-3.png)
Trong đó đường màu xanh lá cây là tiếp tuyến của đồ thị
Mà đạo hàm tại một điểm = độ dốc của đường tiếp tuyến tại điểm đó -> tan(alpha) là giá trị đạo hàm

Nếu 2 điểm nằm ở bên phải -> tan > 0
Nếu 2 điểm nằm ở bên trái -> tan < 0
Nếu 2 điểm bất kỳ i,j -> ta lấy x~i~ - giá trị đạo hàm tại điểm i (i'). Tương tự với j để dịch dần tọa độ x của 2 điểm về phía đỉnh
![alt text](image-4.png)
![alt text](image-5.png)
Cheat sheet
![alt text](image-6.png)