# Chương 3 - Hàm

## 1. Truyền tham trị, tham biến và tham số ngầm định

tham số ngầm định là các tham số mặc định trong hàm

## 2. Đa năng hóa hàm (function overload)

overloading

với các hàm có cùng tên, cùng mục đích, cùng chức năng nhưng khác kiểu trả về, tham số

bonus: đa năng hóa toán tử

## 3. Con trỏ hàm và tham số hóa hàm

Mỗi hàm đều được lưu trữ với địa chỉ riêng trong bộ nhớ ảo

không dùng con trỏ hàm với các hàm có tham số ngầm định được

## 4. Khái quát hóa hàm (function templates)

Khi bạn có một hàm mà có nhiều kiểu dữ liệu trả về khác nhau
thì bạn sẽ dùng overloading đúng không?
Bạn sẽ phải viết đi viết lại rất nhiều hàm giống nhau và chỉ khác kiểu dữ liệu vào ra

## 5. Biểu thức lamda và hàm nặc danh

Lambda hay còn gọi là hàm nặc danh, nó có thể dùng để truyền vào một hàm khác và sử dụng một lần.
Khác với các cách dùng hàm thông thường buộc phải định nghĩa hàm sau đó dùng tên hàm truyền vào một hàm khác.
Bạn có thể thao tác trực tiếp bằng cách sử dụng hàm nặc danh nhưng thường chỉ sử dụng cho các tác vụ nhỏ.
