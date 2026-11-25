# GDQPAN – Luyện thi Học phần 1

Website trắc nghiệm tĩnh, chạy bằng HTML/CSS/JavaScript và có thể triển khai miễn phí trên GitHub Pages.

## Nội dung
- 5 đề thi, mỗi đề 50 câu (tổng 250 câu).
- Chế độ thi thử: 50 phút, tự động nộp khi hết giờ.
- Chế độ luyện tập: phản hồi đúng/sai ngay sau khi chọn.
- Điều hướng câu hỏi, đánh dấu câu cần xem lại, trộn thứ tự câu hỏi.
- Chấm điểm thang 10 và xem lại đáp án.

## Chạy trên máy
Mở `index.html` bằng trình duyệt. Nếu trình duyệt chặn tải JSON khi mở file trực tiếp, hãy chạy một web server đơn giản trong thư mục này, ví dụ `python -m http.server 8000`, rồi mở `http://localhost:8000`.

## Đưa lên GitHub Pages
1. Tạo repository mới trên GitHub, ví dụ `gdqp-an-quiz`.
2. Tải toàn bộ file trong thư mục này lên repository (giữ nguyên cấu trúc).
3. Vào **Settings → Pages**.
4. Ở **Build and deployment**, chọn **Deploy from a branch**.
5. Chọn branch `main`, folder `/ (root)`, nhấn **Save**.
6. Đợi GitHub tạo website; địa chỉ thường có dạng `https://TEN-TAI-KHOAN.github.io/gdqp-an-quiz/`.

## Nguồn câu hỏi và đáp án
Câu hỏi, lựa chọn và bảng đáp án được trích từ 5 PDF do người dùng cung cấp: Đề số 01–05, Học phần 1 – GDQPAN. Mỗi đề có 50 câu và bảng đáp án chuẩn ở cuối file PDF. Dữ liệu được lưu trong `questions.json` để dễ kiểm tra/chỉnh sửa.
