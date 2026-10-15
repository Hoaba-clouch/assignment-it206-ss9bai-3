# [Vận dụng chuyên sâu - 3] THIẾT KẾ CẶP SPRINT REVIEW VÀ SPRINT RETROSPECTIVE

## Phần 1 - Kiểm tra Increment

Dưới đây là kết quả kiểm tra Increment cho các PBI của Sprint 12:

| PBI | Trình bày là Done / Nói rõ chưa Done | Điều kiện Done làm căn cứ |
| :-------- | :---------------------------------- | :----------------------------------------------------------------------------------------------------------------------------------- |
| PBI-51 | Done | Đạt tiêu chí chấp nhận (32/32 ca đạt); đã tích hợp trên môi trường thử nghiệm; kiểm thử quan trọng đã chạy, không còn lỗi mức nghiêm trọng cao. |
| PBI-52 | Chưa Done | Bị chặn do chính sách đồ điện tử còn hai phiên bản, không đạt tiêu chí chấp nhận về tính nhất quán, dẫn đến 114 hội thoại chưa kết luận. |
| PBI-53 | Chưa Done | Lỗi mức cao còn mở; 3/50 ca phân loại sai, chưa đạt tiêu chí chấp nhận và chưa hoàn thành kiểm thử quan trọng. |
| PBI-54 | Done | Đạt trên môi trường thử nghiệm; đã tích hợp; đã qua kiểm tra quyền riêng tư; kiểm thử quan trọng đã chạy, không còn lỗi mức nghiêm trọng cao. |
| PBI-58 | Chưa Done | Đang chờ kiểm thử; 2/12 mẫu còn số điện thoại, chưa đạt tiêu chí chấp nhận và chưa hoàn thành kiểm tra quyền riêng tư. |

## Phần 2 - Chuẩn bị và lịch trình Sprint Review

### Danh sách chuẩn bị Sprint Review

1.  **Chốt mục tiêu và người tham gia:**
    *   Mục tiêu: Đánh giá xem Increment có giúp khách nhận hướng dẫn đổi hàng nhất quán và khiếu nại nghiêm trọng được chuyển cho nhân viên cùng đủ ngữ cảnh để xử lý hay không. Mời Chủ cửa hàng thí điểm, Đại diện chính sách đổi trả, Đại diện bảo vệ dữ liệu. Sửa thư mời về PBI-58.
2.  **Kiểm tra Increment:**
    *   Xác nhận PBI-51 và PBI-54 đã Done; PBI-52, PBI-53, PBI-58 chưa Done. Thông báo rõ với Product Owner rằng PBI-58 chưa hoàn thành kiểm tra quyền riêng tư và còn 2 mẫu hiển thị số điện thoại, cần sửa lại thông tin trong thư mời.
3.  **Chọn User Journey:**
    *   Xây dựng User Journey từ các PBI đã Done: "Là một khách hàng, tôi liên hệ để báo hàng lỗi kỹ thuật (PBI-51) và nhận được hướng dẫn đổi trả nhất quán. Sau đó, là một nhân viên tiếp nhận, tôi xem lịch sử hội thoại của khách (PBI-54) để có đủ ngữ cảnh xử lý." (Chỉ dùng PBI-51 và PBI-54).
4.  **Chuẩn bị kỹ thuật:**
    *   Kiểm tra môi trường tích hợp, tài khoản và dữ liệu thử nghiệm cho demo PBI-51 và PBI-54. Đảm bảo kết nối ổn định cho Đại diện bảo vệ dữ liệu tham gia từ xa. Chuẩn bị phương án dự phòng khi sự cố, nhưng không dùng video cho phần chưa ổn định.
5.  **Chuẩn bị trao đổi:**
    *   Chuẩn bị câu hỏi mở để thảo luận, ví dụ: "Khi chính sách đồ điện tử chưa chốt, AI nên phản hồi thế nào để giảm thời gian chờ mà vẫn đảm bảo tính chính xác?" Mang theo Product Backlog để ghi nhận hai yêu cầu trái chiều về chính sách đồ điện tử, kèm bối cảnh (114 hội thoại chưa kết luận, mức rủi ro cửa hàng chưa rõ). Scrum Master nhắc nhở nhóm không hứa hẹn về việc bổ sung PBI ngay lập tức.
6.  **Chia thời gian:**
    *   Phân bổ phần lớn thời gian cho việc trải nghiệm sản phẩm Done và thảo luận. Đảm bảo phần trao đổi với Đại diện chính sách đổi trả diễn ra trong 30 phút đầu buổi Review. Đảm bảo tổng thời gian không quá 75 phút.

### Lịch trình Sprint Review

**Thời gian tối đa: 75 phút**

| Thời gian | Hoạt động | Ai đóng góp |
| :-------- | :------------------------------------------------------------------------------------------------ | :----------------------------------------------------------------------------------------------------------------------------------------------- |
| 0-5 phút | **Mở đầu:** Scrum Master chào mừng, giới thiệu mục tiêu Sprint Review, nhắc lại Sprint Goal. | Scrum Master |
| 5-15 phút | **Tổng quan Increment:** Product Owner trình bày Sprint Goal, các PBI đã Done (PBI-51, PBI-54) và chưa Done (PBI-52, PBI-53, PBI-58). Nêu rõ trạng thái PBI-58 là chưa Done. | Product Owner |
| 15-30 phút | **Demo User Journey 1:** Developers demo PBI-51 (hướng dẫn đổi hàng lỗi kỹ thuật). Mời Chủ cửa hàng thí điểm và Đại diện chính sách đổi trả trải nghiệm và góp ý. Thảo luận về câu hỏi "Khi chính sách đồ điện tử chưa chốt, AI nên phản hồi thế nào?". | Developers, Chủ cửa hàng thí điểm, Đại diện chính sách đổi trả, Scrum Master (giữ thời gian) |
| 30-45 phút | **Demo User Journey 2:** Developers demo PBI-54 (hiển thị lịch sử cho nhân viên tiếp nhận). Mời Chủ cửa hàng thí điểm và Đại diện bảo vệ dữ liệu (tham gia từ xa) trải nghiệm và góp ý về tính năng và quyền riêng tư. | Developers, Chủ cửa hàng thí điểm, Đại diện bảo vệ dữ liệu, Scrum Master (giữ thời gian) |
| 45-60 phút | **Thảo luận và góp ý:** Thảo luận chung về các Feedback nhận được, rủi ro và hướng đi tiếp theo của sản phẩm. Làm rõ các điểm chưa rõ (ví dụ: mức rủi ro Chủ cửa hàng thí điểm chấp nhận). | Product Owner, Developers, Scrum Master, Stakeholders |
| 60-70 phút | **Cập nhật Product Backlog:** Product Owner xem xét các ý kiến, ưu tiên Product Backlog, và ghi nhận các đề xuất mới (không hứa hẹn thành PBI ngay). Nhắc lại PBI-52, PBI-53 và PBI-58 chưa Done. | Product Owner, Developers, Scrum Master |
| 70-75 phút | **Kết thúc:** Scrum Master tóm tắt các điểm chính, cảm ơn người tham gia và kết thúc buổi Review. | Scrum Master |

## Phần 3 - Kế hoạch Sprint Retrospective

### Người tham gia Sprint Retrospective

Chỉ gồm Scrum Team: Product Owner, Scrum Master và Developers.

### Bảng Data | Khía cạnh | Insight

| Data | Khía cạnh | Insight |
| :------------------------------------------------------------------------------------------------ | :-------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Ngày 4: Khánh Vy (Developer phụ trách kiểm thử) mới có quyền truy cập đầy đủ môi trường thử nghiệm. | Quy trình/Công cụ | Quy trình cấp quyền truy cập môi trường thử nghiệm cho Developers chưa được thực hiện hiệu quả hoặc chưa được chuẩn hóa ngay từ đầu Sprint, dẫn đến chậm trễ trong việc kiểm thử và tích hợp, ảnh hưởng đến tiến độ hoàn thành PBI. |
| Ngày 5: Developers và nhân viên CSKH phát hiện đang hiểu khác nhau về "khiếu nại nghiêm trọng". | Tương tác/Con người | Thiếu sự thống nhất và hiểu rõ ràng về định nghĩa thuật ngữ nghiệp vụ quan trọng ("khiếu nại nghiêm trọng") giữa Developers và nhân viên CSKH từ đầu Sprint. Điều này dẫn đến sự sai lệch trong việc phát triển và kiểm thử tính năng (PBI-53), gây ra lỗi phân loại sai. |

### Bảng Improvement

| Hành động | Người/nhóm theo dõi | Khi kiểm tra | Bằng chứng |
| :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :------------------ | :------------------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Trước Ngày 1 Sprint 13, Developers và các nhân viên CSKH (đại diện người dùng) cùng họp để thống nhất định nghĩa rõ ràng về "khiếu nại nghiêm trọng" bằng cách đưa ra ít nhất 3 ví dụ cụ thể cho cả trường hợp "nghiêm trọng" và "không nghiêm trọng", và ghi nhận lại. | Scrum Team | Sprint Retrospective Sprint 13 | Số ca phân loại sai khiếu nại nghiêm trọng do hiểu khác đã giảm xuống 0; có tài liệu nội bộ ghi lại các ví dụ đã thống nhất, dễ dàng tra cứu. |
