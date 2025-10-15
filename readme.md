🎓 BÀI TẬP LỚN CÁ NHÂN MÔN TRÍ TUỆ NHÂN TẠO
Bài toán 8 Quân Xe - 15 Thuật toán AI
Sinh viên thực hiện: Nguyễn Minh Quốc Khánh MSSV: 23110113 Lớp: 251ARIN330585_05CLC Môn học: Trí tuệ nhân tạo Giảng viên: Phan Thị Huyền Trang

📋 THÔNG TIN BÀI TẬP
Yêu cầu đề bài:
Triển khai bài toán 8 quân xe sử dụng 15 thuật toán AI khác nhau bao gồm:

Tìm kiếm không có thông tin
Tìm kiếm có thông tin
Thỏa mãn ràng buộc
Tìm kiếm cục bộ
Tìm kiếm tiến hóa
Tìm kiếm đồ thị
Mục tiêu bài toán:
Đặt 8 quân xe trên bàn cờ 8x8 sao cho không có quân nào tấn công được quân nào khác. Quân xe chỉ di chuyển theo hàng ngang và hàng dọc (không chéo).

🎬 DEMO CHƯƠNG TRÌNH
Demo Tổng Quan - 8 Quân Xe AI

Minh họa tổng quan giao diện và menu chọn thuật toán

🚀 HƯỚNG DẪN CHẠY CHƯƠNG TRÌNH
Bước 1: Kiểm tra yêu cầu hệ thống
# Kiểm tra Python (cần Python 3.7+)
python --version

# Kiểm tra pip
pip --version
Bước 2: Cài đặt thư viện cần thiết
# Chỉ cần cài đặt Pygame cho giao diện đồ họa
pip install pygame
Bước 3: Tải và giải nén file nộp bài
Giải nén file ZIP đã nộp
Mở terminal/command prompt
Di chuyển tới thư mục chứa code:
cd "đường_dẫn_tới_thư_mục/8_Quan_Xe_AI"
🎮 CÁCH CHẠY CHƯƠNG TRÌNH
Option 1: Chạy nhanh giao diện đồ họa (KHUYẾN NGHỊ)
python run.py
Giao diện đẹp mắt, dễ sử dụng
Click chuột để đặt/xóa quân xe
Nhấn SPACE để giải bằng thuật toán hiện tại
Nhấn M để mở menu chọn thuật toán
Nhấn A để bật/tắt hiển thị vùng tấn công
Option 2: Menu đầy đủ các tùy chọn
python main.py
Sau đó chọn:

1: Giao diện đồ họa
2: Giao diện dòng lệnh
3: Hướng dẫn sử dụng
Option 3: Giao diện dòng lệnh (cho máy yếu)
python cli.py
Menu text-based đơn giản
Chọn số 1-15 để chọn thuật toán
Xem kết quả chi tiết
📊 15 THUẬT TOÁN ĐÃ TRIỂN KHAI
🔍 TÌM KIẾM KHÔNG CÓ THÔNG TIN
STT	Thuật toán	Mô tả	Demo
1	BFS - Breadth-First Search	Tìm kiếm theo chiều rộng	BFS Demo
2	DFS - Depth-First Search	Tìm kiếm theo chiều sâu	DFS Demo
3	UCS - Uniform Cost Search	Tìm kiếm chi phí đồng nhất	UCS Demo
4	IDS - Iterative Deepening Search	Tìm kiếm sâu dần	IDS Demo
5	IDL - Iterative Deepening Limited	Tìm kiếm sâu dần có giới hạn	IDL Demo
🎯 TÌM KIẾM CÓ THÔNG TIN
STT	Thuật toán	Mô tả	Demo
6	Greedy - Greedy Best-First	Tham lam theo heuristic	Greedy Demo
7	A* - A-star Search	Tối ưu với heuristic	

🔒 THỎA MÃN RÀNG BUỘC (CSP)
STT	Thuật toán	Mô tả	Demo
8	Backtracking	Quay lui cơ bản	

9	Forward Checking	Kiểm tra tiến	

10	AC-3 - Arc Consistency	Tính nhất quán cung	

🏔️ TÌM KIẾM CỤC BỘ
STT	Thuật toán	Mô tả	Demo
11	Hill Climbing	Leo đồi	

12	Simulated Annealing	Luyện kim mô phỏng	

13	Beam Search	Tìm kiếm chùm	

🧬 TÌM KIẾM TIẾN HÓA
STT	Thuật toán	Mô tả	Demo
14	Genetic Algorithm	Thuật toán di truyền	

🌳 TÌM KIẾM ĐỒ THỊ
STT	Thuật toán	Mô tả	Demo
15	AND-OR Search	Tìm kiếm đồ thị AND-OR	

🎯 CÁCH KIỂM TRA BÀI TẬP
Test cơ bản:
Chạy python run.py - Kiểm tra giao diện có hoạt động
Click vào bàn cờ - Kiểm tra có đặt được quân xe
Nhấn SPACE - Kiểm tra thuật toán có chạy
Nhấn M - Kiểm tra menu có hiển thị 15 thuật toán
Test chi tiết:
Thử từng thuật toán riêng lẻ trong menu
Kiểm tra thông tin nodes expanded và thời gian
Xem kết quả hiển thị có chính xác không
Quan sát demo GIFs - So sánh với kết quả thực tế
Kết quả mong đợi:
Thành công: Tìm được vị trí quân xe với ít xung đột
Nodes expanded: Hiển thị số node đã duyệt
Thời gian: Hiển thị thời gian thực thi
Conflicts: Số xung đột giữa các quân xe
Visual: Giao diện giống như trong demo GIFs
🎨 VISUAL SHOWCASE
Bài tập này có 16 demo GIFs cho thấy:

🎬 Demo tổng quan: Giao diện chính và cách sử dụng
🧠 15 thuật toán AI: Mỗi thuật toán có demo riêng
🎯 So sánh trực quan: Thấy rõ sự khác biệt giữa các thuật toán
📊 Performance metrics: Nodes expanded, time, conflicts
🎮 Interactive: Click, keyboard shortcuts, menu system
📁 CẤU TRÚC FILE CODE
8_Quan_Xe_AI/
├── main.py              # File chính - chạy cái này nếu không biết chạy gì
├── run.py               # Chạy nhanh giao diện đồ họa
├── cli.py               # Giao diện dòng lệnh
├── visualizer.py        # Giao diện đồ họa Pygame
├── algorithms.py        # 15 thuật toán AI (FILE QUAN TRỌNG NHẤT)
├── eight_rooks.py       # Định nghĩa bài toán 8 quân xe
├── constants.py         # Hằng số và enum
├── images/              # Thư mục chứa demo GIFs
│   ├── demo.gif         # Demo tổng quan
│   ├── BFS.gif          # Demo thuật toán BFS
│   ├── DFS.gif          # Demo thuật toán DFS  
│   ├── A_SAO.gif        # Demo thuật toán A*
│   ├── UCS.gif          # Demo thuật toán UCS
│   ├── IDS.gif          # Demo thuật toán IDS
│   ├── IDL.gif          # Demo thuật toán IDL
│   ├── Greedy.gif       # Demo thuật toán Greedy
│   ├── Backtracking.gif # Demo thuật toán Backtracking
│   ├── forward checking.gif # Demo Forward Checking
│   ├── AC3.gif          # Demo thuật toán AC-3
│   ├── Hill.gif         # Demo Hill Climbing
│   ├── simulated.gif    # Demo Simulated Annealing
│   ├── beam search.gif  # Demo Beam Search
│   ├── genetic.gif      # Demo Genetic Algorithm
│   └── AND or tree.gif  # Demo AND-OR Search
└── README.md           # File này
⚠️ XỬ LÝ LỖI THƯỜNG GẶP
Lỗi 1: "Module not found"
# Cài đặt lại pygame
pip install pygame

# Hoặc nếu dùng Python 3:
pip3 install pygame
Lỗi 2: "Can't open file"
# Đảm bảo đang ở đúng thư mục
cd "đường_dẫn_chính_xác_tới_thư_mục_code"

# Hoặc chạy bằng đường dẫn đầy đủ
python "D:\đường_dẫn\8_Quan_Xe_AI\main.py"
Lỗi 3: Giao diện không hiển thị
Kiểm tra đã cài đặt pygame chưa
Thử chạy giao diện dòng lệnh: python cli.py
Kiểm tra máy có hỗ trợ OpenGL
📈 KẾT QUẢ MONG ĐỢI KHI CHẤM BÀI
Điểm tối đa nếu:
✅ Chạy được tất cả 15 thuật toán
✅ Giao diện đẹp, dễ sử dụng
✅ Code có comment rõ ràng
✅ Kết quả chính xác
✅ Hiển thị thống kê chi tiết
Các tính năng nổi bật:
🎨 Giao diện đồ họa trực quan
📊 Hiển thị thống kê chi tiết
🔍 Hiển thị vùng tấn công của quân xe
⚡ 15 thuật toán AI đầy đủ
🚀 Nhiều cách chạy linh hoạt
📞 LIÊN HỆ HỖ TRỢ
Nếu gặp vấn đề khi chạy code, vui lòng liên hệ:

Email: 23110113@student.hcmute.edu.vn
SĐT: 0395990338
Cảm ơn cô đã xem xét bài tập! 🙏