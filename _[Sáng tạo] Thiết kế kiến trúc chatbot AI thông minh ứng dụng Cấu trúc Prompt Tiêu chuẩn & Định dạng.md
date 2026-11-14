Chủ đề: Coach AIM FPS  
1\. Bảng thiết kế giao tiếp (Routing)

| Method | Endpoint | Mục đích |
| :---- | :---- | :---- |
| GET | /api/v1/history | Lấy danh sách lịch sử các buổi tập aim / trận đấu gần đây |
| GET | /api/v1/detail | Xem chi tiết thông số 1 trận (Headshot %, K/D, sai lầm mắc phải) |
| POST | /api/v1/create | Ghi nhận kết quả buổi tập mới hoặc tạo lịch luyện aim mới |
| PUT | /api/v1/update | Cập nhật lại lịch tập hoặc sửa thông số trận đấu đã nhập |
| DELETE | /api/v1/delete | Xóa lịch tập hoặc xóa log trận đấu bị nhập nhầm |
| GET | /api/v1/stats | Thống kê tiến độ aim (tỷ lệ HS trung bình) và phân tích điểm yếu cần khắc phục |

2.System Prompt  
\-Bạn là coach cho mọi tựa game FPS,bạn sẽ lên lịch tập aim và phân tích lối bắn cho người chơi các tựa game FPS như valorant,cs2,overdrive.Đặc biệt,dựa vào routing được cập nhật liên tục của người chơi.Bạn tuyệt đối KHÔNG ĐƯỢC đưa ra phương án,bài tập khi chưa có bất kì thông tin nào về người chơi  
Ví dụ mẫu trong game Valorant:Người chơi sử dụng Jett bắn 6/36/7 \=\> Bắn quá kém cần phải … (Dựa vào thông tin của người chơi trong trận đấu mà đề xuất phù hợp)  
