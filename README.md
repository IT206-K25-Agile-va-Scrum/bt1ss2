# [Vận dụng cơ bản] CHUẨN HÓA NHỊP SPRINT CỦA ĐỘI RIKKEIGO

> 👤 **Học viên:** Đỗ Hoàng Sơn | **Mã SV:** PTIT-HCM-066
> 🏫 **Môn học:** IT206-K25-Agile-va-Scrum

---

## Nhiệm vụ 1: Phân tích các quy tắc vận hành Sprint của đội RikkeiGo

Sau khi rà soát cách làm việc thực tế của đội RikkeiGo qua 3 Sprint vừa qua, tôi đã đối chiếu từng quy tắc với cẩm nang Scrum Guide và ghi nhận lại các điểm bất hợp lý trong bảng phân tích dưới đây.

- Đội đang gặp vấn đề nghiêm trọng về tính minh bạch khi độ dài Sprint trôi nổi không cố định.
- Việc demo code chưa test làm sai lệch hoàn toàn khái niệm Increment chuẩn Scrum.
- Bỏ qua Retrospective khiến đội mất đi cơ hội cải tiến quy trình, dẫn đến lỗi lặp đi lặp lại.

| Quy tắc | Đúng/Sai | Vi phạm sự kiện/Artifact nào | Trụ cột bị ảnh hưởng | Hậu quả thực tế |
| --- | --- | --- | --- | --- |
| QT1. Độ dài Sprint linh hoạt: tuần nhiều việc thì kéo dài 3–4 tuần, ít việc thì rút còn 1 tuần. | Sai | Sprint (Timebox) | Minh bạch (Transparency) | Khách hàng và các bên liên quan không thể dự đoán được thời điểm phát hành phiên bản mới, làm mất nhịp độ ổn định của dự án. |
| QT2. Cuối Sprint, đội trình diễn cho người dùng thử mọi thứ đã code, kể cả phần chưa kiểm thử, để họ thấy đội làm việc chăm chỉ. | Sai | Sprint Review & Increment | Minh bạch (Transparency) | Tạo cảm giác giả tạo về tiến độ, đưa sản phẩm lỗi đến tay người dùng thử khiến họ hoài nghi về chất lượng. |
| QT3. Sau buổi Sprint Review, Đức cập nhật lại Product Backlog dựa trên góp ý của người dùng thử. | Đúng | — | — | Product Owner là người chịu trách nhiệm tối cao về Product Backlog. Việc lắng nghe phản hồi từ Sprint Review để cập nhật Backlog là hành động hoàn toàn chuẩn xác. |
| QT4. Sprint vừa rồi không có sự cố nào nên đội bỏ buổi Sprint Retrospective cho đỡ tốn thời gian. | Sai | Sprint Retrospective | Thích nghi (Adaptation) | Triệt tiêu cơ hội tự nhìn nhận lại nội bộ, khiến đội bỏ sót các cải tiến nhỏ và lặp lại các vấn đề tiềm ẩn trong các Sprint sau. |

## Nhiệm vụ 2: Viết lại các quy tắc sai thành chuẩn Scrum

Dựa trên các lỗi đã chỉ ra ở phần phân tích, tôi đã biên soạn lại bộ quy tắc mới giúp Scrum Master Lan và Product Owner Đức áp dụng ngay lập tức từ Sprint tiếp theo:

- Quy tắc 1 (Sửa lại): Độ dài Sprint phải được cố định nghiêm ngặt trong suốt dự án (ví dụ: đúng 2 tuần cho mọi Sprint), tạo nhịp độ nhịp nhàng và giúp các bên liên quan luôn biết chính xác thời điểm bản cập nhật ra mắt.
- Quy tắc 2 (Sửa lại): Chỉ mang đến buổi Sprint Review những phần tính năng đã hoàn thành đạt chuẩn Definition of Done - DoD (đã viết code, đã kiểm thử ổn định, không còn lỗi nghiêm trọng) để trình diễn và lấy góp ý thực tế.
- Quy tắc 4 (Sửa lại): Buổi Sprint Retrospective là sự kiện bắt buộc cuối mỗi Sprint cho dù dự án diễn ra suôn sẻ, nhằm giúp cả đội liên tục thanh tra và tìm kiếm cải tiến cách vận hành.

---

## 📁 Danh sách tệp tin nộp bài trong Repository
- 📝 `bt1.docx`: Báo cáo tài liệu phân tích nghiệp vụ hoàn chỉnh.
