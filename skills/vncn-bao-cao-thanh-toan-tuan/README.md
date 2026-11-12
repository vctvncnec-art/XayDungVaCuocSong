# VNCN E&C – Trợ lý Báo cáo Thanh toán Dự án

Skill hỗ trợ lập báo cáo thanh toán IPC theo tuần dựa trên mẫu VNCN E&C.

## Nội dung
- [SKILL.md](SKILL.md): hướng dẫn chính cho AI Agent.
- [MASTER_PROMPT.md](MASTER_PROMPT.md): prompt có thể sao chép để dùng trong ChatGPT hoặc AI khác.
- [REPORT_TEMPLATE.md](REPORT_TEMPLATE.md): cấu trúc báo cáo chuẩn.
- [DATA_VALIDATION.md](DATA_VALIDATION.md): quy tắc kiểm tra số liệu.

## Quy tắc quan trọng
- Giữ nguyên tên công ty: **CÔNG TY CP ĐẦU TƯ XÂY DỰNG VÀ KỸ THUẬT VNCN E&C**.
- Sản lượng làm tròn 1 chữ số thập phân.
- Kế hoạch tiền về 0 và thực hiện 0 thì tỷ lệ là 0%.
- Không tự tạo dữ liệu.
- Phải kiểm tra và xin xác nhận trước khi xuất PDF.

## Lấy nội dung trên web
Thư mục Skill nằm trong repository:
`vctvncnec-art/XayDungVaCuocSong`

- Trang GitHub: https://github.com/vctvncnec-art/XayDungVaCuocSong/tree/main/skills/vncn-bao-cao-thanh-toan-tuan
- Skill raw URL: https://raw.githubusercontent.com/vctvncnec-art/XayDungVaCuocSong/main/skills/vncn-bao-cao-thanh-toan-tuan/SKILL.md
- Master Prompt raw URL: https://raw.githubusercontent.com/vctvncnec-art/XayDungVaCuocSong/main/skills/vncn-bao-cao-thanh-toan-tuan/MASTER_PROMPT.md

## Cách gọi nhanh trong ChatGPT
Mở Skill trên GitHub hoặc raw URL, sao chép toàn bộ nội dung `SKILL.md` và đưa vào cuộc trò chuyện mới. Sau đó gửi dữ liệu dự án và yêu cầu:
“Thực hiện theo Skill VNCN E&C – Trợ lý Báo cáo Thanh toán Dự án. Hãy tiếp nhận, kiểm tra dữ liệu và chỉ xuất PDF sau khi tôi xác nhận.”

## Cách dùng trong một AI Agent hỗ trợ Skills
Đưa thư mục `vncn-bao-cao-thanh-toan-tuan` vào thư mục Skills/Agent Skills mà công cụ đó hỗ trợ. File `SKILL.md` là điểm vào chính. Đọc các file tham chiếu khi cần.

Lưu ý: việc đặt Skill trong GitHub giúp lưu trữ và truy cập nội dung qua web; không tự động cài Skill vào mọi cuộc trò chuyện ChatGPT. Muốn gọi tự động trong một môi trường AI Agent, cần môi trường đó hỗ trợ nạp Skills hoặc cấu hình truy cập URL GitHub.
