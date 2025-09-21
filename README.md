# 🩺 Trợ lý Soạn thảo Bệnh án

Đây là một ứng dụng web được xây dựng bằng Streamlit và vận hành bởi mô hình ngôn ngữ lớn của Google (Gemini), với mục tiêu hỗ trợ các bác sĩ, sinh viên y khoa và nhân viên y tế trong việc soạn thảo bệnh án một cách nhanh chóng và chuẩn hóa.

## Giới thiệu

Trong môi trường lâm sàng bận rộn, việc soạn thảo một bệnh án đầy đủ, logic và chi tiết tốn rất nhiều thời gian. Ứng dụng này ra đời để giải quyết vấn đề đó bằng cách tự động cấu trúc lại các thông tin thô do người dùng nhập thành một bệnh án hoàn chỉnh theo đúng 10 đề mục y khoa tiêu chuẩn.

## Tính năng chính

* **Giao diện nhập liệu trực quan:** Dễ dàng nhập thông tin hành chính, bệnh sử, tiền căn và kết quả thăm khám.
* **Soạn thảo tự động bởi AI:** Sử dụng API của Google Gemini để phân tích và tự động điền thông tin vào các đề mục chuẩn của một bệnh án.
* **Cấu trúc chuẩn y khoa:** Kết quả đầu ra luôn tuân thủ 10 đề mục quan trọng: Hành chính, Lý do vào viện, Bệnh sử, Tiền căn, Lược qua các cơ quan, Khám thực thể, Tóm tắt bệnh án, Biện luận và Chẩn đoán sơ bộ, Chẩn đoán phân biệt, và Đề nghị cận lâm sàng.
* **Hỗ trợ ra quyết định:** Phần biện luận và đề nghị cận lâm sàng được AI suy luận dựa trên kiến thức từ các y văn uy tín, cung cấp một góc nhìn tham khảo hữu ích.

## Hướng dẫn sử dụng

1.  Truy cập vào đường link của ứng dụng.
2.  Điền đầy đủ thông tin của bệnh nhân vào các trường dữ liệu trên giao diện.
3.  Nhấn nút "⚕️ Soạn thảo Bệnh án".
4.  Chờ trong giây lát để AI xử lý và nhận kết quả bệnh án hoàn chỉnh ở phía dưới.

## Công nghệ sử dụng

* **Ngôn ngữ:** Python
* **Giao diện:** Streamlit
* **Mô hình AI:** Google Gemini API
* **Triển khai:** Streamlit Cloud

## Tuyên bố miễn trừ trách nhiệm

Ứng dụng này là một công cụ hỗ trợ và chỉ mang tính chất tham khảo. Kết quả do AI tạo ra không thể thay thế cho chẩn đoán, đánh giá và quyết định lâm sàng của bác sĩ có chuyên môn. Người dùng phải chịu hoàn toàn trách nhiệm khi sử dụng thông tin từ ứng dụng này.
