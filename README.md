## 1. Phân tích nghiệp vụ
### 1. Phân rã quá trình nghiệp vụ
Các bước thực hiện:
- Nhận mã đơn hàng.
- Khởi tạo quá trình.
- Kiểm tra mã đơn hàng tồn tại hay không.
- Nếu không tồn tại, từ chối truy xuất mã đơn hàng.
- Xác thực quyền vận đơn bằng token.
- Nếu xác thực thất bại, từ chối truy xuất mã đơn hàng.
- Thông báo có vấn đề khi vận đơn.
- Lấy thông tin khách hàng dựa vào token.
- Lấy thông tin đơn hàng.
- Lấy thông tin các mặt hàng.
- Lấy thông tin người giao hàng.
- Lấy các trạng thái của đơn hàng.
- Gửi trả tất cả dữ liệu và kết thúc quá trình.
### 2. Loại bỏ những hành động không cần thiết
- **Nhận mã đơn hàng.**
- Khởi tạo quá trình.
- Kiểm tra mã đơn hàng tồn tại hay không.
- Nếu không tồn tại, từ chối truy xuất mã đơn hàng.
- Xác thực quyền vận đơn bằng token.
- Nếu xác thực thất bại, từ chối truy xuất mã đơn hàng.
- Thông báo có vấn đề khi vận đơn.
- Lấy thông tin khách hàng dựa vào token.
- Lấy thông tin đơn hàng.
- Lấy thông tin các mặt hàng.
- Lấy thông tin người giao hàng.
- Lấy các trạng thái của đơn hàng.
- Gửi trả tất cả dữ liệu và kết thúc quá trình.
### 3. Xác định ứng viên thực thể dịch vụ

Các bước không bất khả tri sẽ được in đậm:  
- **Khởi tạo quá trình.**
- **Kiểm tra mã đơn hàng tồn tại hay không.**
- **Nếu không tồn tại, từ chối truy xuất mã đơn hàng.**
- **Xác thực quyền vận đơn bằng token.**
- **Nếu xác thực thất bại, từ chối truy xuất mã đơn hàng.**
- **Thông báo có vấn đề khi vận đơn.**
- Lấy thông tin khách hàng dựa vào token.
- Lấy thông tin đơn hàng.
- Lấy thông tin các mặt hàng.
- Lấy thông tin người giao hàng.
- Lấy các trạng thái của đơn hàng.
- **Gửi trả tất cả dữ liệu và kết thúc quá trình.**

Từ đó ta sẽ có các ứng viên sau:  

![image](https://user-images.githubusercontent.com/66776021/232264184-34121b7d-4f90-4123-8a96-ef8445a11ded.png)

![image](https://user-images.githubusercontent.com/66776021/232264189-b72dd034-2f84-4be1-956c-5890ff4ac42f.png)

![image](https://user-images.githubusercontent.com/66776021/232264196-d9c3e3c8-0ead-4827-adc9-c05c7fbd5979.png)

![image](https://user-images.githubusercontent.com/66776021/232264207-1043adab-36ec-4704-8090-593907809622.png)

![image](https://user-images.githubusercontent.com/66776021/232264223-f013611b-4577-40bb-83c6-8e590285de86.png) 

### 4. Xác định logic quy trình cụ thể
Các bước không bất khả tri:  
- Khởi tạo quá trình.
- Kiểm tra mã đơn hàng tồn tại hay không.
- Nếu không tồn tại, từ chối truy xuất mã đơn hàng.
- Xác thực quyền vận đơn bằng token.
- Nếu xác thực thất bại, từ chối truy xuất mã đơn hàng.
- Gửi trả tất cả dữ liệu và kết thúc quá trình.

Ta chọn “Khởi tạo quá trình” là ứng viên năng lực dịch vụ cho ứng viên dịch vụ “TheoDoiTrangThaiDonHang”.
![image](https://user-images.githubusercontent.com/66776021/232264174-bbc3298b-9039-47f3-81ea-94bd3ba70ff8.png)

### 5. Xác định các tài nguyên
Các tài nguyên:
- /Quá trình theo dõi trạng thái đơn hàng/
- /Khách hàng/
- /Đơn hàng/
- /Trạng thái đơn hàng/
- /Mặt hàng/
- /Shipper/
- /Thực thể gửi thông báo/
### 6. Kết hợp tài nguyên với các hàm

![image](https://user-images.githubusercontent.com/66776021/234339240-e10ff833-894f-4b23-8064-7bb0851411ed.png)

![image](https://user-images.githubusercontent.com/66776021/234339074-65cd8d4a-936e-4834-a672-829215add064.png)

![image](https://user-images.githubusercontent.com/66776021/234339688-4314db56-9576-491f-ad61-9858a64a1f00.png)

![image](https://user-images.githubusercontent.com/66776021/234339849-955d49b1-f2af-4e33-85c5-e4d577aa956a.png)

![image](https://user-images.githubusercontent.com/66776021/234341379-c459f56b-428c-42c2-88cf-a669123790c6.png)

![image](https://user-images.githubusercontent.com/66776021/234341570-358b78f1-cc2b-4995-ba62-5fcd31bd2510.png)


### 7. Áp dụng hướng dịch vụ
### 8. Xác định ứng viên thành phần dịch vụ
![image](https://user-images.githubusercontent.com/66776021/234342082-f9ee304d-7fce-4dff-9f5b-e9ed6ff28218.png)
### 9. Phân tích yêu cầu xử lý
### 10. Xác định ứng viên dịch vụ tiện tích
Còn lại bước bất trả tri là “Thông báo có vấn đề khi vận đơn”, ta sẽ rút gọn còn “Gửi thông báo qua gmail” và cho vào trong ứng viên dịch vụ tiện ích gọi là “ThongBao”.

![image](https://user-images.githubusercontent.com/66776021/234343041-3e6f1334-f76f-44b4-8270-12e4db6ec29c.png)
### 11. Xác định các ứng viên vi dịch vụ
Bước "Xác thực khách hàng".

![image](https://user-images.githubusercontent.com/66776021/234344088-ee086358-1593-4814-bb15-57c4ef1b8393.png)

### 12. Áp dụng hướng dịch vụ
### 13. Xem xét lại các ứng viên thành phần dịch vụ
![image](https://user-images.githubusercontent.com/66776021/234345902-ebca93ed-458b-4f47-b902-f9ee9dfd15cc.png)
### 14. Xem xét cách thức nhóm ứng viên chức năng

## 2. Thiết kế REST API và micro service

### 1. Task service

TheoDoiTrangThaiDonHang

- GET/task/{id}/{userToken}
- DELETE/task/{id}/{userToken}

![image](https://user-images.githubusercontent.com/66776021/237040778-12faf1bc-7632-47ec-a61c-b6f2f41fa29f.png)

### 2. Micro Service

XacThucNguoiDung

- POST/confirm/{userToken}

![image](https://user-images.githubusercontent.com/66776021/237041034-3b45493b-fa55-4b84-a014-7b93266ba460.png)

### 3. Entity Service

DonHang

- GET/donHang/{id}
- POST/donHang/{id}

![image](https://user-images.githubusercontent.com/66776021/237043343-4824c26e-8ecf-4ff1-a2c9-f7dc57a6dc0a.png)

TrangThaiDonHang

- GET/trangThaiDonHang/{id}
- POST/trangThaiDonHang/{id}

![image](https://user-images.githubusercontent.com/66776021/237043666-569205b1-62af-407c-9a13-af5bdac6e54e.png)

KhachHang

- GET/khachHang/{id}
- POST/khachHang/{id}

![image](https://user-images.githubusercontent.com/66776021/237043924-e2c00515-1401-4c5c-8223-f79c3fc49750.png)

MatHang

- GET/matHang/{id}
- POST/matHang/{id}

![image](https://user-images.githubusercontent.com/66776021/237044286-f89a4296-f3da-49f2-8f7e-d9eb855b045c.png)

Shipper

- GET/shipper/{id}
- POST/shipper/{id}

![image](https://user-images.githubusercontent.com/66776021/237044516-5c20de59-e7af-406d-85fa-bbcd4a89fd6e.png)

### Utility Service

ThongBao

- POST/notification/

![image](https://user-images.githubusercontent.com/66776021/237045722-ef91b181-c3a8-4079-9c58-3d40caeeee8f.png)

## 3. Công nghệ sử dụng
- IDE: Elipse, Intellji (những IDE này có những chức năng phục vụ cho webservice được tích hợp sẵn)
- Platform: JDK, Javascript (có những công cụ phù hợp cho việc làm web)
- Server: Tomcat Apache Server (Server dễ thiết lập và dễ sửa dụng)
- Framework: Spring Framework (cung cấp một mô hình lập trình và cấu hình toàn diện cho các ứng dụng web dựa trên Java hiện đại)
- Database: MySQL (đơn giản, dễ quản lý, dễ dùng, dễ sửa chữa)
- Test tool: Selenium, Junit
- Microservice: kubernetes, minikube
- Virtual machine: docker desktop, virtualbox
- Discovery Service: Spring Eureka
- API gateway: Spring Gateway

## 4. Triển khai
- Chạy các project trong wordspace bắt đầu từ discoveryservice để khởi động Eureka server
- Tiếp đó chạy gateway để chuẩn bị điều hướng các service khi gọi tới 
- Chạy tiếp KhachHangService, DonHangService, MatHangService, ShipperService, TTDHService, ThongBao, XacThucNguoiDung, TheoDoiTrangThaiDonHang để triển khai các service đó lên server
- Khi đã thực hiện chạy hoàn tất các bước trên, dùng trình duyệt để kiểm tra, nếu thành công thì kết quả như hình dưới đây. 
- ![image](https://github.com/jnp2018/team-project-n1_8/assets/103521567/ef3eb80e-9aab-4083-8165-98c9e705644f)

