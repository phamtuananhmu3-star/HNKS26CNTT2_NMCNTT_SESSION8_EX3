# Báo cáo: Giảm chi phí vận hành Chatbot AI với Markdown

## Phần 1. Phân tích bài toán
- **Cơ chế Token của AI:** Các mô hình ngôn ngữ lớn (LLM) xử lý văn bản bằng cách chia nhỏ thành các đơn vị gọi là token (từ hoặc cụm ký tự). 
- **Lý do Markdown giúp AI xử lý nhanh và tiết kiệm hơn:** Định dạng HTML chứa rất nhiều thẻ rườm rà (như `<div>`, `<span>`, `<style>`) làm tăng vọt số lượng token đầu vào. Ngược lại, Markdown sử dụng các ký tự đại diện tối giản (như `#`, `*`), giúp giảm đáng kể lượng token, từ đó tiết kiệm chi phí gọi API và tăng tốc độ phản hồi của hệ thống "Chuyên gia nông nghiệp AI".

## Phần 2. So sánh & Đánh giá

| Tiêu chí | Định dạng HTML | Định dạng Markdown |
| :--- | :--- | :--- |
| **Số lượng ký tự/Token** | Cao (nhiều thẻ cú pháp thừa) | Thấp, cực kỳ tinh gọn |
| **Độ dễ đọc (Human-readable)** | Thấp (khó đọc trực tiếp do lẫn mã lệnh) | Cao, trực quan, dễ đọc ngay cả khi dạng thô |
| **Hiệu quả xử lý của AI** | Chậm hơn, tốn chi phí token hơn | Nhanh hơn, tối ưu chi phí vận hành |

### Giải pháp tối ưu cho hệ thống "GreenTech"
Hệ thống nên sử dụng **Markdown** làm chuẩn truyền tải dữ liệu. Điều này giúp giảm lượng token truyền tải, tiết kiệm chi phí máy chủ/API đáng kể khi phục vụ lượng lớn người nông dân, đồng thời giúp đội ngũ kỹ thuật dễ dàng kiểm tra và bảo trì nội dung hơn.