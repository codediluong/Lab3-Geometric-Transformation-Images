# Lab3-Geometric-Transformation-Images
# Công nghệ sử dụng
Ngôn ngữ: Python
Thư viện:
Pillow (PIL): xử lý ảnh cơ bản như đọc, chuyển đổi và lưu ảnh.

NumPy: xử lý mảng ảnh dạng ma trận.

Matplotlib: hiển thị ảnh.

imageio: đọc ảnh theo chuẩn imageio (nếu cần).

scipy.ndimage là một module trong thư viện SciPy, dùng để xử lý ảnh
# Title
Chọn đối tượng trong ảnh là phép trích ảnh nhỏ trong ảnh lớn ban đầu. ( Bài tập 1 )

# Giải thích cách hoạt động
1. ** import mấy cái thư viện
![image](https://github.com/user-attachments/assets/4fa51e11-7156-406d-a683-aa6366d96933)
2. ** Đọc ảnh từ file ảnh
![image](https://github.com/user-attachments/assets/6ab3e97e-0e6c-430f-a72d-eeb743b501c4)
3. ** Cắt vùng theo tọa độ vị trí trái kiwi - ** In tọa độ ảnh ra
![image](https://github.com/user-attachments/assets/02a996d1-9f6a-4eee-81d2-f2cace3d1e6b)
4. ** Lưu ảnh kiwi thành file mới kiwi.jpg
![image](https://github.com/user-attachments/assets/8963ac30-5a63-4fa6-b6a3-97e15314a84c)
5. ** Hiển thị ảnh
![image](https://github.com/user-attachments/assets/ca7f6445-9b9a-4be9-b328-faa25de5d8db)

# Tile 
Tịnh tiến đơn
![image](https://github.com/user-attachments/assets/cc67f081-cca8-4919-8ae7-40dcf031790b)

# Giải thích cách hoạt động
1. ** import mấy cái thư viện
![image](https://github.com/user-attachments/assets/80eddcf0-4757-49cf-b868-6a21872e31cc)
2. ** Đọc ảnh từ file ảnh và chuyển sang dạng xám - dùng hàm nd.shift để dịch ảnh
![image](https://github.com/user-attachments/assets/960d62a2-48ae-4a22-aad5-c0fe8e442084)
3. ** Hiển thị ảnh
![image](https://github.com/user-attachments/assets/ed34b4ab-7c16-482f-9603-089d1549fd71)

# Title
Thay đổi kích thước ảnh là tăng hoặc giảm không gian của ảnh.
# Giải thích cách hoạt động
1. ** import mấy cái thư viện
![image](https://github.com/user-attachments/assets/230c1859-4cb8-45f9-b82d-d8b40f46da18)
2. ** Đọc ảnh từ file và in tọa độ ảnh ra
![image](https://github.com/user-attachments/assets/67a07b94-24b1-46ff-8235-78b2fa7e44ff)
3. ** Phóng to ảnh lên 2 lần và in ra tọa độ ảnh
![image](https://github.com/user-attachments/assets/d7ec00ce-d866-4c9d-b38e-ec184cb1b5bf)
4. ** Phóng to ảnh lên 2 lần theo chiều cao và chiều rộng và in ra tọa độ ảnh
![image](https://github.com/user-attachments/assets/826da907-be63-4af6-aa02-fa9428c98ced)
5. ** Thu nhỏ ảnh còn 50% chiều cao, 90% chiều rộng và in ra tọa độ ảnh
![image](https://github.com/user-attachments/assets/5b6229f6-fbb9-4ff4-a350-93b988cd4c18)
6. ** Hiển thị ảnh ở lần thay đổi thứ 3
![image](https://github.com/user-attachments/assets/2a82e65c-8140-44a5-82c2-0d66caf78d75)

# Title
Dùng hàm rotate(image, degree) để xoay một ảnh với
Image: là ảnh trong bộ nhớ
Degree: là góc xoay
![image](https://github.com/user-attachments/assets/141850d5-c2eb-4dcb-b8dd-a0a9ffd287ab)
## Giải thích cách hoạt động
1. ** Import thư viện
![image](https://github.com/user-attachments/assets/416d217e-9b69-4b9f-b305-ad29cfbc9990)
2. ** Đọc ảnh từ file và in tọa độ ảnh ra
![image](https://github.com/user-attachments/assets/9c8c46e5-16b8-4ba8-8457-41091798d76c)
3. ** Dùng hàm nd.rotate để xoay ảnh và hiển thị ảnh ra
![image](https://github.com/user-attachments/assets/a5a1e8ca-1c06-4237-bfd5-095e83f1f6c9)
4. ** Dùng hàm nd.rotate để xoay ảnh và hiển thị ảnh ở góc 200 độ 
![image](https://github.com/user-attachments/assets/30543874-0bdb-4665-b86b-250feb8d4e84)

# Title
Bài tập 2
# Giải thích cách hoạt động
1. ** Import thư viện
![image](https://github.com/user-attachments/assets/342d533a-4318-446d-84a3-e71344342467)
2. ** Đọc ảnh từ file và tìm tọa độ trái dưa hấu từ ảnh gốc, lưu ảnh dưa hấu vừa tìm thành file mới watermelon.jpg
![image](https://github.com/user-attachments/assets/f9a82812-c8f5-4bfe-9576-ec751a607e9e)
3. ** Dùng hàm subplot để chia vùng vẽ thành 1 hàng, 2 cột và hiển thị ảnh ra
![image](https://github.com/user-attachments/assets/1116e886-7ac4-4ec8-aea7-92a4ed0c29be)
4. ** Đọc ảnh từ file và tìm tọa độ trái đu đủ từ ảnh gốc, lưu ảnh đu đủ vừa tìm thành file mới Papaya.jpg
5. ** Dùng hàm subplot để chia vùng vẽ thành 1 hàng, 2 cột và hiển thị ảnh ra ở ô thứ 2
![image](https://github.com/user-attachments/assets/a4a36913-491d-4bf5-8967-881a3431dadb)

# Title
Bài tập 3
# Giải thích cách hoạt động
1. ** Import thư viện
![image](https://github.com/user-attachments/assets/25f7c2c1-63d6-4d52-b33d-0e3b725320e4)
2. ** Đọc ảnh từ file và tìm tọa độ sau đó dùng hàm rotate xoay ảnh ở góc 45 độ lưu ảnh thành file mới Moutain_rotated.jpg
![image](https://github.com/user-attachments/assets/35c84bf7-ea81-4e0e-9b7f-cac4b2995959)
3. ** Dùng hàm subplot để chia vùng vẽ thành 1 hàng, 2 cột và hiển thị ảnh ra
![image](https://github.com/user-attachments/assets/09c3fff1-27e1-44e5-acba-12a5878d22e4)
4. ** Đọc ảnh từ file và tìm tọa độ sau đó dùng hàm rotate xoay ảnh ở góc 45 độ lưu ảnh thành file mới Boat_rotated.jpg
![image](https://github.com/user-attachments/assets/0b1a2a0a-3d51-4fc5-9cf7-53364ccf2cd3)
5. ** Dùng hàm subplot để chia vùng vẽ thành 1 hàng, 2 cột và hiển thị ảnh ra ở ô thứ 2
![image](https://github.com/user-attachments/assets/c0a81d3b-4391-4025-8f36-f53a1f2564a9)

# Title
Bài Tập 4
# Giải thích cách hoạt động
1. ** Import thư viện
![image](https://github.com/user-attachments/assets/a98b70af-c0bd-4475-a36d-f9e56ea277a2)
2. ** Đọc ảnh từ file và in tọa độ ảnh ra
![image](https://github.com/user-attachments/assets/9067313f-3a74-4649-a234-f0daf1bbbb3a)
3. ** Dùng hàm nd.zoom phóng to 5 lần theo chiều cao và chiều rộng
![image](https://github.com/user-attachments/assets/7f3bfca1-28fa-4102-8bef-a106332482d7)


# Title
Tạo Menu lựa chọn
# Giải thích cách hoạt động
1. ** Dùng hàm def menu để hiện thị menu theo yêu cầu và in ra các lựa chọn
![image](https://github.com/user-attachments/assets/707eae18-7664-49e5-8db5-b6fc7e908e31)
2. ** Vòng lặp while true
Vòng lặp này giúp menu lặp lại liên tục cho đến khi người dùng chọn thoát (hoặc có lệnh break).
Mỗi lần lặp, gọi hàm menu() để lấy lựa chọn của người dùng.
Dựa vào giá trị trả về (ch), chương trình sẽ thực hiện chức năng tương ứng (tịnh tiến, xoay, phóng to, thu nhỏ, coordinate map).
Nếu lựa chọn không hợp lệ, in ra thông báo và lặp lại menu.
Khi gặp lệnh break (ở lựa chọn "Coordinate Map"), vòng lặp sẽ dừng và chương trình kết thúc.

![image](https://github.com/user-attachments/assets/a537d21e-1d0c-4d47-aacc-9c49b74ba19f)

![image](https://github.com/user-attachments/assets/9ac5d43b-06bc-4e30-b265-bb3f3527389d)

![image](https://github.com/user-attachments/assets/7c64d622-b2e1-4fb6-a4e9-27b89968158f)

















































   

