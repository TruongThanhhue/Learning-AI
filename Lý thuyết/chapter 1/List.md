# List
## Cấu trúc:
```python
list_name = [element-1,...element-n]
```
element ở trong [] và các element được ngăn cách bởi dấu ,
Ví dụ:
![alt text](image-7.png)
## Slicing
Truy cập theo phạm vi
### Cú pháp
```python
list[start:end:step]
```
### append() method
Dùng để thêm giá trị vào cuối danh sách
![alt text](image-8.png)
### insert() method 
Dùng để thêm giá trị vào một index cụ thể trong danh sách
![alt text](image-9.png)
### extend() method
Dùng để mở rộng danh sách cũ bằng cách thêm danh sách mới vào cuối list cũ
![alt text](image-10.png)
### Updating
Có thể cập nhật giá trị mới của chỉ mục thông qua toán tử =
![alt text](image-11.png)
### Xóa element khỏi list
- Sử dụng remove() và pop()
![alt text](image-12.png)
- Sử dụng từ khóa `del` để xóa đối tượng hoặc clear() để xóa tất cả thành phần, trả về danh sách rỗng
![alt text](image-13.png)
- Sử dụng index() để trả về vị trí đầu tiên có giá trị mà mình truyền vào
- reverse() dùng để đảo ngược chuỗi
![alt text](image-14.png)
- Hàm count(): Truyền vào 1 phần tử. Hàm count sẽ đếm xem phần tử đó xuất hiện mấy lần trong danh sách.
- Hàm copy(): Dùng để sao chép các giá trị danh sách này vào trong danh sách mới.
![alt text](image-15.png)
- Hàm sort(): Giúp sắp xếp giá trị trong danh sách theo tăng dần hoặc giảm dần.
![alt text](image-16.png)
### Toán tử +,*
Phép +: Dùng để nối danh sách
Phép *: Dùng để lặp lại danh sách
![alt text](image-17.png)
## Built-in Function for list
- Hàm len(): Trả về độ dài danh sách, có bao nhiêu phần tử ?
- Hàm min(): Trả về phần tử có giá trị nhỏ nhất trong danh sách
- Hàm max(): Trả về phần tử có giá trị lớn nhất trong danh sách
![alt text](image-18.png)
- Hàm sum(): Trả về tổng
    - Cấu trúc: `sum(iterable, start)` (sau khi tính sum của list + thêm giá trị start nếu có)
![alt text](image-19.png)
- Hàm zip(): Các danh sách ánh xạ index với nhau và trả về kết quả
    - Cấu trúc: `zip(*iterators)`
Ví dụ: list1= [1,2,3]
       list2= [4,5,6]
Trả về kết quả [list1[0], list2[0]] = 1,4
               [list1[1], list2[1]] = 2,5
               [list1[2], list2[2]] = 3,6
![alt text](image-20.png)
Nếu độ dài khác nhau. Nó sẽ lấy ánh xạ theo danh sách có độ dài nhỏ hơn.
![alt text](image-21.png)
- Hàm reverse():
    - Cấu trúc `reversed(iterable)`
![alt text](image-22.png)
- Hàm enumerate(): Tiến hành nén các giá trị tương ứng của index với giá trị của index ấy
    - Cấu trúc: `enumerate(iterable, start)`
![alt text](image-23.png)