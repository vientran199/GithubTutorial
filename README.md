Ứng Dụng Encrypt/Decrypt
Mô tả
•	Ứng dụng được viết bằng ngôn ngữ C#.
•	Ứng dụng giúp Encrypt/Decrypt trên mã hoá Ceasar, mã hoá Rail Fence.
Hướng dẫn sử dụng
Clone ứng dụng về bằng lệnh: git clone path-git hoặc download file zip.
•	Chạy ứng dụng được build sẵn: 
-	Truy cập vào đường dẫn thư mục bạn mới tải về \NetworkSecurity\bin\Debug\netcoreapp3.1.
-	Chạy file NETWORK_SECURITY_APP.exe.
•	Chạy ứng dụng bằng IDE Visual Studio:
-	Mở thư mục NetworkSecurity bằng Visual Studio.
-	Nhấn tổ hợp phép Ctrl + F5.
•	Chạy ứng dụng bằng Visual Studio Code:
-	Download và cài đặt .Net Framework trên trang https://dotnet.microsoft.com/download/dotnet-framework.
-	Mở thư mục NetworkSecurity bằng Visual Studio Code.
-	Cài các tiện ích cần thiết trên Visual Studio Code: C#, Code Runner.
-	Chạy bằng tổ hợp phím Ctrl + Alt + N.
Cửa sổ ứng dụng như sau:
 

Hướng dẫn sử dụng ứng dụng:
     Ứng dụng với 2 phần Encrypt và Decrypt.
     Encrypt
•	Chọn cách mã hoá ở mục Technique với 3 lựa chọn:
-	Mã hoá Ceasar
-	Mã hoá Rail Fence
-	Mã hoá kết hợp giữa Ceasar và Rail Fence
•	Nhập giá trị key vào mục Input Key.
•	Nhập đoạn văn bản cần mã hoá vào phần Input text.
•	Nhấn Encrypt để mã hoá. Kết quả được lưu trong file Result.txt ở Desktop.

     Decrypt
•	Nhập văn bản đã mã hoá vào Input Text.
•	Nhấn Decrypt để giải mã.
•	Hộp thoại mới xuất hiện, nhấn next đến khi nhận được đoạn văn bản có ý nghĩa nhấn correct để kết thúc.
