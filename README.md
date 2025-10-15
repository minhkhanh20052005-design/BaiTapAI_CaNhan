1.Breadth-First Search (BFS)

1.1. Lý thuyết

Thuật toán BFS (tìm kiếm theo chiều rộng) duyệt từng lớp (level) của không gian trạng thái, bắt đầu từ trạng thái gốc. BFS mở rộng tất cả các nút ở độ sâu d trước khi đi xuống d+1.
BFS đảm bảo tìm được lời giải tối ưu về số bước nếu chi phí mỗi bước là như nhau.

1.2. Cách áp dụng trong chương trình

Mỗi trạng thái được biểu diễn bởi một tuple chứa vị trí các quân hậu đã đặt hợp lệ trên bàn.

Bắt đầu từ trạng thái ban đầu (bàn cờ 8x8 rỗng hoặc trạng thái hiện tại).

Dùng hàng đợi deque để lưu các trạng thái cần mở rộng.

Các trạng thái con sinh ra bằng hàm trangThaiTiepTheo() – đặt thêm một hậu hợp lệ vào hàng kế tiếp.

Khi gặp trạng thái mục tiêu (trangThaiMucTieu), thuật toán dừng và dựng lại đường đi bằng trangThaiNguon.

### 1.3. Demo
<p align="center">
  <img src="/BFS.gif" width="600" alt="Demo BFS">
</p>

2.Depth-First Search (DFS)

2.1. Lý thuyết

DFS (tìm kiếm theo chiều sâu) duyệt sâu vào không gian trạng thái, đi theo một nhánh cho đến khi không thể mở rộng, sau đó quay lui để thử nhánh khác.

DFS tiết kiệm bộ nhớ nhưng có thể rơi vào vòng lặp hoặc không tìm được lời giải tối ưu.

2.2. Cách áp dụng trong chương trình

Dùng ngăn xếp stack để lưu các trạng thái.

Tại mỗi bước, lấy trạng thái trên cùng ngăn xếp và sinh các trạng thái con hợp lệ.

Nếu gặp trạng thái mục tiêu thì dừng.

Lưu lại danh sách thuTuDuyet để hiển thị quá trình duyệt.
