# Project1
Quản lí dữ nhân sự trên cơ sở dữ liệu ở xa sử dụng cơ sở dữ liệu tự định nghĩa
HumanResources là client, Server là máy chủ. Client và Server kết nối với nhau qua socket ở chế độ có kết nối (TCP), khi có yêu cầu lấy dữ liệu từ client, server sẽ tạo luồng xử lí client đó, phân loại các yêu cầu xử lí dữ liệu (Select, Update, Delete, Insert) để lấy dữ liệu từ file .txt. Server đọc file .txt rồi chuyển lên các lớp lớp đối tượng trong Models rồi gửi về cho client. Client cũng sẽ có các lớp đối tượng đó để đọc được object mà Server gửi. Client đưa các thông tin lên giao diện, khi cần gửi object cho server, client lại chuyển dữ liệu về các lớp trong Models gửi đến cho Server để Server lưu xuống file .txt
