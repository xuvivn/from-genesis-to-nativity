# Từ Sáng Thế Đến Giáng Sinh — Kho Dữ Liệu Luyện Kể Chuyện 5 Cấp Độ

Kho dữ liệu nguồn tiếng Việt phục vụ ứng dụng luyện kể chuyện (*storytelling practice app*), kết nối một mạch sử thi liền lạc từ **Khởi Nguyên Sáng Thế** qua **Hành Trình Về Đất Hứa**, **Thời Kỳ Xây Dựng Đền Thờ**, **Hai Đứa Trẻ Giáng Sinh & Bình Minh Bên Sông Jordan**, và khép lại bằng phần **Ngoại Truyện: Từ Thánh Nicholas Đến Ông Già Noel**.

---

## Kiến Trúc 5 Cấp Độ Luyện Kể Chuyện (Level 0 → Level 4)

| Cấp độ | Thư mục | Mục đích luyện tập | Biến thể & Phạm vi |
| :--- | :--- | :--- | :--- |
| **Level 0** | [level-0-khong-gian-boi-canh/](level-0-khong-gian-boi-canh/00-tong-quan-linh-hon-su-thi.md) | **Không gian bối cảnh & Linh hồn câu chuyện** — nắm tinh thần văn hóa, nhịp điệu kể, thông điệp ẩn dụ theo lứa tuổi, cách phát âm tên cổ và đọc thêm văn bản gốc trước khi kể. | `00-tong-quan-linh-hon-su-thi.md` + 5 tệp theo Quyển (`quyen-1`..`quyen-5`) + thư viện [`van-ban-co/`](level-0-khong-gian-boi-canh/van-ban-co/) (25 tệp sách gốc đọc thêm) |
| **Level 1** | [level-1-toan-van/](level-1-toan-van/) | **Toàn văn câu chuyện** — văn phong kể chuyện đọc thành tiếng hoàn chỉnh, giàu hình ảnh và đi kèm *Lưu ý giọng kể*. | 3 biến thể × 5 Quyển (15 tệp): `6-10-tuoi-chuan/`, `3-5-tuoi-mam-non/`, `11-cong-thieu-nien-nguoi-lon/` |
| **Level 2** | [level-2-dan-y-chi-tiet/](level-2-dan-y-chi-tiet/) | **Dàn ý chi tiết** — luyện kể không nhìn toàn văn nhưng giữ trọn nhân vật, chi tiết bản địa hóa và nhịp cảm xúc theo lứa tuổi. | 3 biến thể (7 tệp): `ban-dia-hoa-6-10-tuoi/` (`quyen-1`..`5`), `mam-non-3-5-tuoi/`, `thieu-nien-nguoi-lon-11-cong/` |
| **Level 3** | [level-3-dan-y-tom-tat/](level-3-dan-y-tom-tat/dan-y-tom-tat-28-phan-canh.md) | **Dàn ý tóm tắt** — 1 bản khung xương duy nhất bám sát cốt truyện gốc (4–6 ý/phân cảnh). | 1 tệp duy nhất bao phủ đủ 28 phân cảnh |
| **Level 4** | [level-4-tranh-goi-nho/](level-4-tranh-goi-nho/bo-tranh-goi-nho.md) | **Tranh gợi nhớ thuần hình ảnh** — mỗi phân cảnh 1 bức tranh vẽ tay truyền thống, không chữ gợi ý, giúp người kể tự tuôn chảy bằng ngôn ngữ sống của mình. | `bo-tranh-goi-nho.md` + thư mục `images/` + `prompts-28-phan-canh.md` |

---

## Cấu Trúc 5 Quyển & 28 Phân Cảnh Chuẩn Hóa

Chỉ mục máy đọc được cho ứng dụng nằm tại [story-index.json](story-index.json). Toàn bộ các cấp độ dùng chung 28 mã định danh chuẩn (`canh-01` .. `canh-28`):

### Quyển I: Khởi Nguyên Và Ánh Sáng Đầu Tiên (`canh-01` – `canh-08`)
1. `canh-01-khoi-nguyen-va-cuoc-chien-anh-sang` — Khởi Nguyên Thế Giới Và Cuộc Chiến Giữa Ánh Sáng Với Bóng Tối
2. `canh-02-bay-ngay-sang-the` — Bảy Ngày Sáng Thế Và Sự Tạo Dựng Con Người Đầu Tiên
3. `canh-03-muon-hoa-va-muon-thu-buoi-dau` — Muôn Hoa, Cây Cỏ Và Loài Vật Giữa Ánh Sáng Và Bóng Tối
4. `canh-04-vuon-dia-dang-va-buoc-chan-xuong-tran` — Vườn Địa Đàng, Trái Cấm Và Những Giọt Nước Mắt Đầu Tiên Trên Mặt Đất
5. `canh-05-cain-abel-va-hat-giong-su-song` — Cain, Abel, Người Em Mới Seth Và Ba Hạt Giống Cây Sự Sống
6. `canh-06-con-chau-cain-va-ngon-lua-van-minh` — Ba Con Trai Của Cain: Thuần Hóa Muôn Thú, Tiếng Đàn Thiên Giới Và Lò Rèn Sắt
7. `canh-07-enoch-nguoi-giu-anh-sang` — Ánh Sáng Của Enoch Giữa Đêm Tối Ngẫu Tượng
8. `canh-08-con-tau-noah-va-cau-vong-giao-uoc` — Con Tàu Của Noah, Cơn Đại Hồng Thủy Và Chiếc Cầu Vồng Giao Ước

### Quyển II: Hành Trình Về Đất Hứa (`canh-09` – `canh-15`)
9. `canh-09-thap-babel-va-abram-buoc-ra-khoi-lua` — Ngai Bảy Tầng Của Nimrod, Tháp Babel Và Chàng Trai Abram Bước Ra Khỏi Lò Lửa
10. `canh-10-abraham-goc-cay-thieng-va-le-hien-te-isaac` — Lời Hứa Dưới Trời Sao, Cây Cổ Thụ Của Abraham Và Phép Thử Trên Núi Moriah
11. `canh-11-chiec-thang-anh-sang-cua-jacob` — Hai Anh Em Esau – Jacob, Chiếc Thang Ánh Sáng Và Cuộc Hòa Giải
12. `canh-12-joseph-chiec-ao-ngu-sac-va-nguoi-ban-banh-mi` — Chiếc Áo Ngũ Sắc Của Joseph, Giấc Mơ Pharaoh Và Cuộc Đoàn Tụ Nước Mắt
13. `canh-13-moses-bui-gai-chay-va-bien-do-re-nuoc` — Hài Nhi Moses Trên Sông Nile, Bụi Gai Bốc Cháy Và Biển Đỏ Rẽ Đôi
14. `canh-14-muoi-dieu-ran-den-tam-va-cai-nhin-tu-nui-nebo` — Mười Điều Răn Trên Đỉnh Sinai, Ngôi Đền Tạm Và Cái Nhìn Cuối Cùng Từ Núi Nebo
15. `canh-15-vua-saul-tieng-dan-david-va-giac-mo-cay-the-gioi` — Vua Saul, Tiếng Đàn Chăn Cừu Của David Và Giấc Mơ Cây Thế Giới

### Quyển III: Chúng Ta Sẽ Xây Một Đền Thờ (`canh-16` – `canh-22`)
16. `canh-16-solomon-trai-tim-thong-tue-va-ngoi-den-tho` — Trái Tim Thông Tuệ Của Vua Solomon Và Ngôi Đền Thờ Jerusalem
17. `canh-17-tien-tri-elijah-ngon-lua-trung-thuc-va-co-xe-lua` — Tiên Tri Elijah: Hũ Bột Không Vơi, Ngọn Lửa Trên Núi Carmel Và Cỗ Xe Lửa
18. `canh-18-hanh-trinh-cua-tobias-va-thien-than-chua-lanh` — Chuyến Đi Của Chàng Trẻ Tobias Và Thiên Thần Chữa Lành Raphael
19. `canh-19-isaiah-va-jeremiah-loi-tien-tri-giua-tro-tan` — Đôi Môi Chạm Lửa Của Isaiah Và Jeremiah Giấu Hòm Giao Ước Trước Giờ Đền Thờ Sụp Đổ
20. `canh-20-daniel-lo-lua-va-hang-su-tu-babylon` — Daniel Và Các Bạn Trẻ Nơi Xứ Lưu Đày: Lò Lửa Và Hang Sư Tử Babylon
21. `canh-21-jonah-con-ca-khong-lo-va-long-bao-dung` — Tiên Tri Jonah Trong Bụng Cá Khổng Lồ Và Bài Học Về Lòng Thương Xót
22. `canh-22-xay-lai-thanh-quach-job-va-ngon-lua-maccabeus` — Xây Lại Tường Thành, Lòng Kiên Trung Của Job Và Ngọn Lửa Phục Hưng Đền Thờ

### Quyển IV: Hai Đứa Trẻ Giáng Sinh Và Bình Minh Bên Sông Jordan (`canh-23` – `canh-27`)
23. `canh-23-loi-bao-tin-trong-den-tho-va-cuoc-gap-go-hai-nguoi-me` — Lời Báo Tin Trong Đền Thờ, Cuộc Hội Ngộ Của Hai Người Mẹ Và Hai Ngọn Sáng Đêm Đông
24. `canh-24-dua-tre-dong-doi-vua-va-nhung-nha-thong-thai` — Đứa Trẻ Dòng Dõi Vua, Ba Nhà Thông Thái Phương Đông Và Cuộc Chạy Trốn Trong Đêm
25. `canh-25-dua-tre-muc-dong-va-tinh-ban-o-nazareth` — Đứa Trẻ Dòng Dõi Mục Đồng, Tiếng Hát Trên Đồng Cỏ Và Hai Gia Đình Ở Nazareth
26. `canh-26-nam-thu-muoi-hai-trong-den-tho-va-xuong-moc-nazareth` — Năm Thứ Mười Hai Trong Đền Thờ, Nỗi Đau Mùa Đông Và Người Thợ Mộc Khôn Ngoan
27. `canh-27-john-ben-bo-bien-chet-va-phep-rua-tren-song-jordan` — John Giữa Cộng Đồng Áo Trắng, Tiếng Gọi Hoang Địa Và Bình Minh Trên Sông Jordan

### Quyển V (Ngoại Truyện): Hạt Giống Yêu Thương Đêm Đông (`canh-28`)
28. `canh-28-ngoai-truyen-thanh-nicholas-va-ong-gia-noel` — Ngoại Truyện: Từ Chiếc Áo Choàng Đỏ Của Thánh Nicholas Đến Ông Già Noel Đêm Giáng Sinh

---

## Phong Cách Tranh Gợi Nhớ (Level 4)

- **Phân cảnh 01–08:** Tranh than chì đen kết hợp phấn tiên màu vàng đất ấm trên giấy mỹ thuật ngà, gợi phong vị huyền thoại nguyên thủy bằng nét phác tay mộc mạc.
- **Phân cảnh 09–28:** Tranh màu nước đơn sắc tông nâu mực cổ và nâu đất ấm kết hợp nét chì mềm trong khung loang mờ tự nhiên trên giấy trắng, không chứa chữ viết hay chi tiết kỹ thuật số.
- Xem chi tiết bộ đề bài vẽ đồng bộ cho toàn bộ 28 cảnh tại [prompts-28-phan-canh.md](level-4-tranh-goi-nho/prompts-28-phan-canh.md).
