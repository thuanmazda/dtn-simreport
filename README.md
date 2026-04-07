# Đánh giá và So sánh hiệu năng mạng vô tuyến (Chuẩn 802.11b và 802.11g)

Kho lưu trữ Bài tập lớn bộ môn Truyền số liệu và Mạng. Dự án này tập trung vào việc kiểm thử, đo lường và phân tích sự khác biệt về mặt hiệu năng giữa các thế hệ mạng vô tuyến. Quá trình nghiên cứu được thực hiện qua hai giai đoạn liên kết chặt chẽ: mô phỏng hệ thống trên phần mềm và kiểm thử trực tiếp trên các thiết bị mạng thực tế.

## 📥 Tải bản báo cáo hoàn chỉnh (Định dạng PDF)
Xem kết quả phân tích cuối cùng, vui lòng tải xuống tệp tin văn bản đã được chúng tôi đóng gói sẵn tại mục quản lý phiên bản phát hành của kho lưu trữ này:

👉 **[Tải xuống tệp tin Báo cáo hoàn chỉnh tại đây](https://github.com/thuanmazda/dtn-simreport/releases/latest)**

---

## 📂 Cấu trúc kho lưu trữ

Toàn bộ dự án được phân chia thành hai thư mục chính chứa mã nguồn định dạng chuẩn, giúp người đọc dễ dàng theo dõi và biên dịch lại tài liệu:

### 1. Thư mục Báo cáo kết quả Mô phỏng
*   **Thư mục lưu trữ:** `BAO_CAO_KET_QUA_MO_PHONG...`
*   **Nội dung:** Chứa mã nguồn trình bày các phân tích về cách thức hoạt động của mạng vô tuyến trong môi trường lý tưởng.
*   **Điểm nhấn kỹ thuật:** Ứng dụng phương pháp gửi gói tin mở rộng trực tiếp từ bộ định tuyến trung tâm nhằm tạo ra tải trọng lớn, từ đó bộc lộ rõ sự chênh lệch về thời gian phản hồi và khả năng xử lý phân mảnh dữ liệu của các chuẩn mạng khác nhau.

### 2. Thư mục Báo cáo kết quả Thực nghiệm
*   **Thư mục lưu trữ:** `BAO_CAO_KET_QUA_THUC_NGHIEM...`
*   **Nội dung:** Chứa mã nguồn phân tích các số liệu đo đạc thực tế giữa chuẩn mạng 802.11b và 802.11g trên băng tần 2.4 Gigahertz.
*   **Điểm nhấn kỹ thuật:** Bao gồm các bài thí nghiệm chuyên sâu nhằm đánh giá sự suy hao cường độ tín hiệu vô tuyến dựa trên khoảng cách vật lý, độ trễ và mức độ dao động tín hiệu, sự chênh lệch về giới hạn băng thông thực tế và hiện tượng thắt cổ chai hiệu năng khi hệ thống chạy ở chế độ hỗn hợp.

---

## 🛠️ Công cụ và Thiết bị sử dụng

Để tái hiện lại dự án này một cách chính xác nhất, chúng ta đã kết hợp các công cụ sau:
*   **Hệ thống biên dịch:** Ngôn ngữ đánh dấu văn bản LaTeX.
*   **Mô phỏng mạng:** Phần mềm giả lập hệ thống mạng chuyên nghiệp của Cisco.
*   **Thiết bị thực tế:** Bộ định tuyến vô tuyến phân quyền và thiết bị di động thông minh.
*   **Phần mềm đo lường:** Các ứng dụng phân tích thông số phần cứng thiết bị, đo lường thời gian phản hồi máy chủ và kiểm tra tốc độ luân chuyển dữ liệu nội bộ không phụ thuộc vào gói cước viễn thông.

---
*Tài liệu được soạn thảo và lưu trữ nhằm mục đích lưu trữ mã nguồn và chia sẻ kiến thức học thuật.*
