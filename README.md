# Từ Sáng Thế Đến Giáng Sinh — Kho Dữ Liệu Luyện Kể Chuyện 5 Cấp Độ

Kho dữ liệu nguồn tiếng Việt phục vụ ứng dụng luyện kể chuyện (*storytelling practice app*), kết nối một mạch sử thi liền lạc gồm **5 Quyển (180 Chương — 129,145 từ toàn văn)** dành thống nhất cho **độ tuổi 9–10**, bám sát bộ tác phẩm kể chuyện kinh điển của **Jakob Streit** (*And There Was Light*, *Journey to the Promised Land*, *We Will Build a Temple*, *Königskind und Hirtenkind*, *Sankt Nikolaus*).

---

## Kiến Trúc 5 Cấp Độ Luyện Kể Chuyện (Level 0 → Level 4)

| Cấp độ | Thư mục | Mục đích luyện tập | Phạm vi dữ liệu |
| :--- | :--- | :--- | :--- |
| **Level 0** | [level-0-khong-gian-boi-canh/](level-0-khong-gian-boi-canh/00-tong-quan-linh-hon-su-thi.md) | **Không gian bối cảnh & Linh hồn câu chuyện** — nắm tinh thần văn hóa, nhịp điệu kể cho tuổi 9–10, cách phát âm tên cổ và đọc thêm văn bản cổ trước khi kể. | `00-tong-quan-linh-hon-su-thi.md` + 5 tệp theo Quyển + thư viện [`van-ban-co/`](level-0-khong-gian-boi-canh/van-ban-co/) (25 tệp sách cổ) |
| **Level 1** | [level-1-toan-van/](level-1-toan-van/) | **Toàn văn câu chuyện** — văn phong kể chuyện đọc thành tiếng hoàn chỉnh sánh ngang độ dài và chi tiết sách gốc Jakob Streit, kèm *Lưu ý giọng kể*. | 5 tệp (`quyen-1`..`quyen-5`), bao phủ trọn vẹn **180 Chương** (129,145 từ) |
| **Level 2** | [level-2-dan-y-chi-tiet/](level-2-dan-y-chi-tiet/) | **Dàn ý chi tiết** — luyện kể không nhìn toàn văn nhưng giữ trọn nhân vật, đối thoại, hình ảnh biểu tượng và nhịp cảm xúc từng chương. | 5 tệp (`quyen-1`..`quyen-5`), khớp chính xác **180 Chương** |
| **Level 3** | [level-3-dan-y-tom-tat/](level-3-dan-y-tom-tat/dan-y-tom-tat-cac-chuong.md) | **Dàn ý tóm tắt** — 1 bản khung xương duy nhất tóm lược mạch cốt lõi từng chương. | 1 tệp duy nhất bao phủ đủ **180 Chương** |
| **Level 4** | [level-4-tranh-goi-nho/](level-4-tranh-goi-nho/bo-tranh-goi-nho.md) | **Tranh gợi nhớ thuần hình ảnh** — 28 bức tranh vẽ tay truyền thống gắn theo các Cụm Chương, giúp người kể tự tuôn chảy bằng ngôn ngữ sống của mình. | `bo-tranh-goi-nho.md` + thư mục `images/` + `prompts-28-phan-canh.md` |

---

## Cấu Trúc 5 Quyển & 180 Chương Chuẩn Hóa

Chỉ mục máy đọc được cho ứng dụng nằm tại [story-index.json](story-index.json).

### Quyển I: Khởi Nguyên Và Ánh Sáng Đầu Tiên (`67 Chương` — 36,131 từ)
- Toàn văn: [level-1-toan-van/quyen-1-khoi-nguyen-va-anh-sang.md](level-1-toan-van/quyen-1-khoi-nguyen-va-anh-sang.md)
- Dàn ý chi tiết: [level-2-dan-y-chi-tiet/quyen-1-khoi-nguyen-va-anh-sang.md](level-2-dan-y-chi-tiet/quyen-1-khoi-nguyen-va-anh-sang.md)
- **Phần I: Bảy Ngày Sáng Thế:**
  - Chương 1: Khởi Nguyên Của Thế Giới
  - Chương 2: Michael Và Con Rồng
  - Chương 3: Ngày Sáng Tạo Thứ Nhất
  - Chương 4: Ngày Thứ Hai
  - Chương 5: Ngày Thứ Ba
  - Chương 6: Ngày Thứ Tư
  - Chương 7: Hoa Nhung Tuyết Và Các Loài Hoa Trên Đỉnh Núi Cao
  - Chương 8: Chuyện Về Các Loài Cây Có Độc
  - Chương 9: Vì Sao Hoa Hồng Có Gai
  - Chương 10: Ngày Thứ Năm
  - Chương 11: Ngày Thứ Sáu
  - Chương 12: Chim Bồ Câu Và Chú Cừu Non
  - Chương 13: Sự Tạo Dựng Con Người
  - Chương 14: Ngày Thứ Bảy
  - Chương 15: Trong Vườn Địa Đàng
  - Chương 16: Sự Sa Ngã
  - Chương 17: Trên Mặt Đất
- **Phần II: Con Cháu Của Cain:**
  - Chương 18: Cain Và Abel
  - Chương 19: Giấc Mơ Của Cain Và Abel
  - Chương 20: Cain Hạ Gục Con Sói
  - Chương 21: Khi Eve Khóc
  - Chương 22: Cain Đã Giết Abel Như Thế Nào
  - Chương 23: Adam Chôn Abel Trong Ngôi Mộ Đầu Tiên Trên Mặt Đất
  - Chương 24: Seth, Người Em Mới Của Cain
  - Chương 25: Thiên Thần Trao Cuốn Sách Sự Sống Cho Adam
  - Chương 26: Cái Chết Của Adam
  - Chương 27: Các Con Trai Của Cain
  - Chương 28: Jabal, Người Thuần Hóa Loài Vật
  - Chương 29: Jubal Mang Âm Nhạc Đến Cho Loài Người
  - Chương 30: Thubal-Cain, Nhà Phát Minh Và Thợ Rèn
  - Chương 31: Các Con Trai Của Cain Và Những Ngôi Nhà Đầu Tiên
  - Chương 32: Ba Con Dao
  - Chương 33: Jubal Chơi Nhạc Cho Muôn Thú
  - Chương 34: Jubal Chơi Nhạc Cho Loài Người
  - Chương 35: Chuyện Về Những Kẻ Đồng Hành Gian Ác Và Việc Làm Tội Lỗi
  - Chương 36: Kenos Trong Hang Rừng
  - Chương 37: Jubal Thoát Khỏi Hiểm Nguy Lớn Như Thế Nào
  - Chương 38: Cái Chết Của Seth
  - Chương 39: Enos Đã Mang Việc Thờ Ngẫu Tượng Đến Cho Loài Người Như Thế Nào
  - Chương 40: Ánh Sáng Thiện Lương Trở Lại Mặt Đất Nhờ Enoch
  - Chương 41: Enoch Dâng Lễ Vật Đầu Tiên
  - Chương 42: Enoch Tìm Thấy Hang Động Sách Thánh
  - Chương 43: Những Chuyến Du Hành Của Enoch
  - Chương 44: Ngọn Núi Của Chúa Và Các Tư Tế
  - Chương 45: Enoch Thăng Thiên
- **Phần III: Con Tàu Của Noah:**
  - Chương 46: Ông Lão Methusala
  - Chương 47: Đâu Là Ngôi Nhà Của Người Công Chính?
  - Chương 48: Sự Ra Đời Của Noah
  - Chương 49: Cơn Giận Của Cậu Bé Noah
  - Chương 50: Thành Phố Trăm Ngẫu Tượng
  - Chương 51: Mệnh Lệnh
  - Chương 52: Vị Vua Đội Vương Miện Đen
  - Chương 53: Raphael Dẫn Noah Tới Cuốn Sách Sự Sống
  - Chương 54: Mệnh Lệnh Đóng Con Tàu
  - Chương 55: Sem, Ham, Jafet Và Các Loài Vật
  - Chương 56: Liệu Con Tàu Có Bị Phá Hủy Không?
  - Chương 57: Tập Hợp Các Loài Vật
  - Chương 58: Bước Vào Con Tàu
  - Chương 59: Chiếc Quan Tài Của Adam
  - Chương 60: Con Tàu Được Niêm Phong Và Mưa Bắt Đầu Rơi
  - Chương 61: Cơn Đại Hồng Thủy
  - Chương 62: Nỗi Khốn Khổ Trong Con Tàu
  - Chương 63: Chuyến Bay Của Quạ Và Thông Điệp Của Bồ Câu
  - Chương 64: Thế Giới Mới
  - Chương 65: Lễ Tạ Ơn
  - Chương 66: Ác Quỷ Trong Vườn Nho Của Noah
  - Chương 67: Sem Và Các Thiên Thần

### Quyển II: Hành Trình Về Đất Hứa (`56 Chương` — 50,193 từ)
- Toàn văn: [level-1-toan-van/quyen-2-hanh-trinh-ve-dat-hua.md](level-1-toan-van/quyen-2-hanh-trinh-ve-dat-hua.md)
- Dàn ý chi tiết: [level-2-dan-y-chi-tiet/quyen-2-hanh-trinh-ve-dat-hua.md](level-2-dan-y-chi-tiet/quyen-2-hanh-trinh-ve-dat-hua.md)
- **Phần I: Abraham:**
  - Chương 1: Vua Nimrod
  - Chương 2: Tháp Babel
  - Chương 3: Sự Ra Đời Của Abram
  - Chương 4: Abram Và Nimrod
  - Chương 5: Sự Hỗn Loạn Ngôn Ngữ
  - Chương 6: Abram Hành Hương Tới Canaan
  - Chương 7: Cây Của Abraham
  - Chương 8: Cuộc Viếng Thăm Của Ba Vị Khách
  - Chương 9: Sự Hủy Diệt Thành Sodom
- **Phần II: Isaac:**
  - Chương 10: Cậu Bé Isaac
  - Chương 11: Lễ Hiến Tế Isaac
  - Chương 12: Isaac Và Rebecca
- **Phần III: Jacob:**
  - Chương 13: Jacob Và Esau
  - Chương 14: Lời Chúc Phúc Của Isaac
  - Chương 15: Cuộc Chạy Trốn Của Jacob
  - Chương 16: Jacob Nơi Xứ Lạ
  - Chương 17: Đất Canaan – Cuộc Hòa Giải
- **Phần IV: Joseph:**
  - Chương 18: Joseph Bị Bán
  - Chương 19: Joseph Ở Ai Cập
  - Chương 20: Joseph Trong Ngục Tối
  - Chương 21: Giấc Mơ Của Pharaoh
  - Chương 22: Những Năm Tháng Đói Kém
  - Chương 23: Hành Trình Dài Tới Ai Cập
  - Chương 24: Một Pharaoh Mới
- **Phần V: Moses:**
  - Chương 25: Chào Đời Và Thời Thơ Ấu
  - Chương 26: Những Hòn Than Hồng
  - Chương 27: Moses Và Người Ai Cập
  - Chương 28: Moses Ở Xứ Midian
  - Chương 29: Cuộc Chiến Với Pharaoh
  - Chương 30: Cuộc Xuất Hành
  - Chương 31: Mara Và Sin
  - Chương 32: Dân Amalekites
  - Chương 33: Tại Núi Sinai
  - Chương 34: Mười Điều Răn
  - Chương 35: Con Bê Vàng
  - Chương 36: Đền Tạm
  - Chương 37: Hoang Địa Zin
  - Chương 38: Con Rắn Đồng
  - Chương 39: Bileam Lại Xuất Hiện
- **Phần VI: Joshua:**
  - Chương 40: Joshua Tiếp Nhận Quyền Lãnh Đạo
  - Chương 41: Ngôi Mộ Vô Danh
  - Chương 42: Vượt Sông Jordan
  - Chương 43: Chiếm Thành Jericho
  - Chương 44: Trong Vùng Đất Canaan
- **Phần VII: Saul Và David:**
  - Chương 45: Samuel Và Saul
  - Chương 46: Saul Trở Thành Vua
  - Chương 47: Cậu Bé Chăn Cừu David
  - Chương 48: Ai Sẽ Là Vị Vua Mới?
  - Chương 49: David Và Saul
  - Chương 50: David Và Goliath
  - Chương 51: Trong Hang Đá
  - Chương 52: Cái Chết Của Saul Và Jonathan
  - Chương 53: David Làm Vua
  - Chương 54: Đại Hội Đồng
  - Chương 55: Giấc Mơ Của David
  - Chương 56: Những Bài Thánh Vịnh Của David

### Quyển III: Chúng Ta Sẽ Xây Một Đền Thờ (`32 Chương` — 24,313 từ)
- Toàn văn: [level-1-toan-van/quyen-3-chung-ta-se-xay-mot-den-tho.md](level-1-toan-van/quyen-3-chung-ta-se-xay-mot-den-tho.md)
- Dàn ý chi tiết: [level-2-dan-y-chi-tiet/quyen-3-chung-ta-se-xay-mot-den-tho.md](level-2-dan-y-chi-tiet/quyen-3-chung-ta-se-xay-mot-den-tho.md)
- **Cụm 1: Vua Solomon:**
  - Chương 1: Solomon Lên Ngôi Vua
  - Chương 2: Lễ Hiến Tế Và Lời Cầu Nguyện Của Solomon
  - Chương 3: Phán Quyết Của Solomon
  - Chương 4: Sự Giàu Có Và Vinh Quang Của Solomon
  - Chương 5: Xây Dựng Đền Thờ
  - Chương 6: Sự Phân Chia Vương Quốc
- **Cụm 2: Tiên Tri Elijah:**
  - Chương 7: Tiên Tri Elijah
  - Chương 8: Trên Núi Carmel
  - Chương 9: Elijah Trên Núi Horeb
- **Cụm 3: Tobias:**
  - Chương 10: Tobias
  - Chương 11: Cùng Với Raguel Và Sarah
- **Cụm 4: Isaiah:**
  - Chương 12: Isaiah
  - Chương 13: Lời Tiên Tri
- **Cụm 5: Tiên Tri Jeremiah:**
  - Chương 14: Tiên Tri Jeremiah
  - Chương 15: Jeremiah Bị Ném Xuống Giếng Nước
  - Chương 16: Jeremiah Đã Cứu Hòm Giao Ước Như Thế Nào
  - Chương 17: Quân Babylon Phá Hủy Đền Thờ
- **Cụm 6: Daniel:**
  - Chương 18: Daniel
  - Chương 19: Giấc Mơ Của Nebuchadnezzar
  - Chương 20: Ba Chàng Trai Trong Lò Lửa
  - Chương 21: Bữa Tiệc Của Belshazzar
  - Chương 22: Từ Thần Bel Tới Tháp Babel
  - Chương 23: Daniel Trong Hang Sư Tử
  - Chương 24: Lời Tiên Tri Của Daniel
- **Cụm 7: Nehemiah:**
  - Chương 25: Nehemiah
  - Chương 26: Công Cuộc Tái Thiết Gian Nan
- **Cụm 8: Jonah:**
  - Chương 27: Jonah
- **Cụm 9: Heliodorus:**
  - Chương 28: Heliodorus
- **Cụm 10: Job:**
  - Chương 29: Job
  - Chương 30: Cuộc Thử Thách
- **Cụm 11: Judas Maccabeus:**
  - Chương 31: Judas Maccabeus
  - Chương 32: Liên Minh Với Rome

### Quyển IV: Hai Đứa Trẻ Giáng Sinh Và Bình Minh Bên Sông Jordan (`15 Chương` — 9,547 từ)
- Toàn văn: [level-1-toan-van/quyen-4-hai-dua-tre-giang-sinh.md](level-1-toan-van/quyen-4-hai-dua-tre-giang-sinh.md)
- Dàn ý chi tiết: [level-2-dan-y-chi-tiet/quyen-4-hai-dua-tre-giang-sinh.md](level-2-dan-y-chi-tiet/quyen-4-hai-dua-tre-giang-sinh.md)
- **Phần I: Đứa Trẻ Dòng Dõi Vua Và Đứa Trẻ Mục Đồng:**
  - Chương 1: Hai Câu Chuyện Giáng Sinh
  - Chương 2: Đứa Trẻ Dòng Dõi Vua
  - Chương 3: Đứa Trẻ Dòng Dõi Mục Đồng
  - Chương 4: Những Cuộc Trò Chuyện Của Hai Bà Maria
  - Chương 5: Năm Thứ Mười Hai
  - Chương 6: Giêsu Trong Đền Thờ
  - Chương 7: Nỗi Đau Ập Đến
  - Chương 8: Người Thợ Mộc Khôn Ngoan
- **Phần II: John Người Làm Phép Rửa Và Bình Minh Bên Sông Jordan:**
  - Chương 9: John Người Làm Phép Rửa
  - Chương 10: Cuộc Gặp Gỡ Kỳ Lạ
  - Chương 11: John Sống Cùng Phái Essenes
  - Chương 12: Bên Bờ Biển Chết
  - Chương 13: Người Rao Giảng Trong Hoang Địa
  - Chương 14: Lễ Rửa Tội Của Giêsu
  - Chương 15: Về Cái Chết Của Vị Tiền Hô

### Quyển V (Ngoại Truyện): Hạt Giống Yêu Thương Đêm Đông (`10 Chương` — 8,961 từ)
- Toàn văn: [level-1-toan-van/quyen-5-ngoai-truyen-ong-gia-noel.md](level-1-toan-van/quyen-5-ngoai-truyen-ong-gia-noel.md)
- Dàn ý chi tiết: [level-2-dan-y-chi-tiet/quyen-5-ngoai-truyen-ong-gia-noel.md](level-2-dan-y-chi-tiet/quyen-5-ngoai-truyen-ong-gia-noel.md)
- **Phần I: Cuộc Đời Và Những Câu Chuyện Của Thánh Nicholas Thành Myra:**
  - Chương 1: Cậu Bé Thành Patara Và Tiếng Chuông Buổi Sáng
  - Chương 2: Ba Túi Vàng Qua Khung Cửa Sổ Đêm Khuya
  - Chương 3: Chuyến Hải Trình Xa Xôi Và Cơn Bão Giữa Biển Lớn
  - Chương 4: Cánh Cửa Nhà Thờ Thành Myra Lúc Bình Minh
  - Chương 5: Phép Lạ Đoàn Tàu Lúa Mì Trong Mùa Đói Kém
  - Chương 6: Đôi Tay Ngăn Thanh Gươm Và Ba Người Vô Tội
  - Chương 7: Đôi Giày Nhỏ Bên Bậc Thềm Đêm Gió Lạnh
  - Chương 8: Ba Vị Tướng Trong Ngục Tối Kinh Đô
  - Chương 9: Buổi Chiều Bình Yên Cuối Đời Ở Thành Myra
- **Phần II: Hành Trình Huyền Thoại Mùa Đông Khắp Thế Gian:**
  - Chương 10: Từ Chiếc Áo Choàng Đỏ Thành Myra Đến Ông Già Noel Đêm Giáng Sinh

---

## Phong Cách Tranh Gợi Nhớ (Level 4)

- **Tranh 01–08 (Quyển I):** Tranh than chì đen kết hợp phấn tiên màu vàng đất ấm trên giấy mỹ thuật ngà, gợi phong vị huyền thoại nguyên thủy bằng nét phác tay mộc mạc.
- **Tranh 09–28 (Quyển II–V):** Tranh màu nước đơn sắc tông nâu mực cổ và nâu đất ấm kết hợp nét chì mềm trong khung loang mờ tự nhiên trên giấy trắng, không chứa chữ viết hay chi tiết kỹ thuật số.
- Xem chi tiết đề bài vẽ đồng bộ tại [prompts-28-phan-canh.md](level-4-tranh-goi-nho/prompts-28-phan-canh.md).
