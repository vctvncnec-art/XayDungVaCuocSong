# QUY TẮC KIỂM TRA DỮ LIỆU – BÁO CÁO THANH TOÁN TUẦN

## 1. Bảng kiểm đầu vào
| Trường | Bắt buộc cho KPI/biểu đồ | Cần cho thuyết minh khi mục đó xuất hiện |
|---|---|---|
| Tên dự án | Có | Có |
| Tuần/tháng/năm | Có | Có |
| Kế hoạch sản lượng tuần | Có | Có |
| Thực hiện sản lượng tuần | Có | Có |
| Kế hoạch tiền về tuần | Có | Có |
| Thực hiện tiền về tuần | Có | Có |
| Lũy kế sản lượng tháng | Không | Có |
| Kế hoạch lũy kế tháng | Không | Có |
| Tổng kế hoạch dòng tiền tháng | Không | Có |
| Nguyên nhân không đạt | Không | Chỉ khi người dùng muốn/đã có nội dung |
| Khó khăn/kiến nghị | Không | Chỉ khi người dùng muốn/đã có nội dung |

Không có số liệu trong nguồn không đồng nghĩa số liệu bằng 0.

## 2. Công thức
- Tỷ lệ hoàn thành = Thực hiện / Kế hoạch × 100, khi kế hoạch > 0.
- Nếu kế hoạch = 0 và thực hiện = 0: 0%.
- Nếu kế hoạch = 0 và thực hiện > 0: không xác định; hỏi người dùng.
- Nếu kế hoạch > 0 và thực hiện = 0: 0%.
- Tỷ lệ sản lượng làm tròn 1 chữ số thập phân.
- Tính từ số liệu gốc trước khi làm tròn.

## 3. Kiểm tra nhất quán
1. Tên dự án ở tiêu đề, bảng và chân trang phải giống nhau.
2. Tuần/tháng/năm phải giống nhau trên toàn báo cáo.
3. KPI phải trùng bảng chi tiết.
4. Biểu đồ cột phải dùng đúng số liệu KPI/bảng.
5. Biểu đồ vòng phải dùng đúng tỷ lệ đã tính.
6. Tỷ lệ trong thuyết minh phải khớp bảng.
7. Số lũy kế phải được phân biệt với số phát sinh trong tuần.
8. Kế hoạch dòng tiền tháng không được nhầm với kế hoạch tiền về tuần.
9. Đơn vị phải nhất quán; nếu có chuyển đổi phải lưu phép tính.
10. Mọi chênh lệch giữa tỷ lệ ghi trong nguồn và tỷ lệ tính lại phải được nêu ra.

## 4. Các tình huống phải hỏi
- Thiếu tên dự án hoặc kỳ báo cáo.
- Không đọc rõ một chữ số hoặc đơn vị.
- Có nhiều số liệu khác nhau cho cùng chỉ tiêu/kỳ.
- Kế hoạch bằng 0 nhưng thực hiện lớn hơn 0.
- Số lũy kế thấp hơn số phát sinh tuần mà không có giải thích/cơ sở kỳ.
- Tỷ lệ nguồn khác tỷ lệ tính lại.
- Nguyên nhân hoặc kiến nghị chưa được xác nhận.
- Không rõ dữ liệu là tỷ đồng, triệu đồng hay đơn vị khác.

## 5. Mẫu bảng sai khác
| STT | Hạng mục | Dữ liệu nguồn | Kết quả kiểm tra | Cần người dùng xác nhận |
|---|---|---|---|---|
| 1 | [ ] | [ ] | [ ] | [ ] |

## 6. Trạng thái dữ liệu
- **Đã xác minh:** đọc rõ, có nguồn và logic phù hợp.
- **Tính toán:** kết quả được tính từ dữ liệu đã xác minh.
- **Cần xác nhận:** thiếu, mờ, mâu thuẫn hoặc cần quy ước.
- **Không áp dụng:** người dùng xác nhận mục đó không áp dụng.

Chỉ chuyển sang tạo PDF khi không còn điểm “Cần xác nhận” ảnh hưởng đến báo cáo và người dùng đã xác nhận bảng chốt.
