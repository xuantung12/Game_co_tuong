# Game_co_tuong
Đánh cờ online với người lạ:
Ghép ngẫu nhiên với người chơi khác hoặc tạo phòng riêng.
Giao tiếp theo thời gian thực nhờ Socket.IO.
Hỗ trợ chat trực tiếp trong trận đấu.
Hỗ trợ gửi/nhận tin nhắn thời gian thực thông qua WebSocket.

Chơi offline với máy (AI):
Đối thủ máy sử dụng các thuật toán:
Static Evaluation Function
Minimax
Alpha-Beta Pruning
Mức độ thông minh của máy có thể được điều chỉnh.

Chế độ giải đố (Puzzle):
Người chơi giải các thế cờ định sẵn.
Hệ thống phân loại độ khó từ 1 đến 10 sao.
Trạng thái và lịch sử các thế cờ được lưu trữ bằng MySQL.

Học cờ qua các khóa học:
Các khóa học được admin thêm vào từ back-end.
Bài học có thể bao gồm text, hình ảnh, hoặc video.
Người dùng có thể theo dõi quá trình học và nâng cao kỹ năng.

Theo dõi trận đấu đang diễn ra:
Người dùng có thể xem live các ván đấu online.
Có thể học hỏi chiến thuật từ những người chơi khác.

Cộng đồng và chat:
Tính năng chat cộng đồng dành cho người chơi đã đăng nhập.
################################
Front-end:
React.js: Phát triển UI linh hoạt, component-based, Tailwind CSS: Tạo giao diện đẹp mắt, dễ tùy biến, responsive. JavaScript (ES6+): Logic xử lý tương tác người dùng, socket.IO (Client): Kết nối thời gian thực để chơi cờ và chat.
Back-end:
Node.js + Express: API phục vụ dữ liệu khóa học, puzzle, đăng nhập,.. .Socket.IO (Server): Giao tiếp hai chiều cho các trận đấu online và chat.
MySQL: Lưu trữ:
Thông tin người dùng, khóa học, tin nhắn, thế cờ puzzle và trạng thái bàn cờ, danh sách tài khoản của người chơi 

Giao diện trang quản lí 
![image](https://github.com/user-attachments/assets/0728e0fd-8eea-4c40-bacd-a0b20865cf43)
![image](https://github.com/user-attachments/assets/e2589844-8c4c-4ff8-b394-524053d0cc3f)
![image](https://github.com/user-attachments/assets/d08e0b5b-4e8d-48a0-8c96-ca108e6823f6)




