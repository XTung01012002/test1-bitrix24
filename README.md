Bước 1: chạy file backend, câu lệnh :cd backend / npm start
Bước 2: truy cập ngrok, gõ câu lệnh: ngrok http 8088
![i2](https://github.com/user-attachments/assets/8ffea0f8-6c0f-4466-af12-e371c1ca25d7)

Bước 3: dán link  https://cc5e-116-97-106-196.ngrok-free.app(dòng forwarding đối với máy khác) vào trong bitrix24
![i3](https://github.com/user-attachments/assets/7796dc63-21bf-443a-8538-03d83b94426a)

Bước 4: copy client_id và client_secret dán vào file env backend.
Bước 5: dán link  https://cc5e-116-97-106-196.ngrok-free.app/api vào file env frontend.
Bước 6: chạy file frontend, câu lệnh : cd frontend/npm start. Hiển thị giao diện 
![i1](https://github.com/user-attachments/assets/96f2c595-353d-4644-b93b-af001eb1cb4d)

Dữ liệu khi thêm vào sẽ lưu vào db mongodb vào bitrix24 thông qua crm.contact.add, các dữ liệu thêm sửa xóa thay đổi trong cả db và bitrix24

