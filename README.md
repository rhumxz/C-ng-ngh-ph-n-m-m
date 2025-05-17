# Cong_nghe_phan_mem
Bối cảnh:
 Sinh viên ngành Công nghệ Phần mềm thường gặp nhiều thách thức trong quá trình học tập, bao gồm:
Khó tiếp cận giảng viên ngoài giờ học


Cần sự hỗ trợ ngay lập tức cho các câu hỏi kỹ thuật


Gặp khó khăn trong việc định hướng giữa khối lượng tài liệu học tập khổng lồ


Các khái niệm kỹ thuật phức tạp cần được giải thích cá nhân hóa


Giảng viên thiếu thời gian để trả lời các câu hỏi lặp đi lặp lại


Khó khăn trong việc theo dõi tiến độ học tập và khoảng trống kiến thức của từng sinh viên


Vì vậy, có nhu cầu phát triển một trợ lý ảo thông minh có thể hỗ trợ theo thời gian thực, trả lời câu hỏi và hướng dẫn sinh viên trong quá trình học tập và làm dự án, đồng thời giảm tải khối lượng công việc lặp lại cho giảng viên.

Giải pháp đề xuất
Phát triển trợ lý ảo AI tên là “Hannah” chuyên biệt cho giáo dục Công nghệ Phần mềm


Triển khai giao diện trò chuyện thân thiện, có khả năng tương tác thời gian thực với sinh viên


Xây dựng hệ thống quản lý tri thức toàn diện dành riêng cho nội dung ngành Công nghệ Phần mềm


Phát triển hệ thống kiểm duyệt và đảm bảo chất lượng có sự giám sát của giảng viên


Tích hợp với các tài nguyên học tập và tài liệu học thuật


Triển khai phân tích dữ liệu để theo dõi mức độ tương tác của sinh viên và các câu hỏi thường gặp



Yêu cầu chức năng
Giao diện sinh viên
Trò chuyện thời gian thực với Hannah để hỏi kỹ thuật và nhận hướng dẫn


Truy cập tài liệu học tập và tài nguyên được chọn lọc


Hỗ trợ cụ thể theo từng dự án và xử lý sự cố


Theo dõi tiến độ và đưa ra gợi ý cá nhân hóa


Chia sẻ và giải thích đoạn mã nguồn (code snippet)


Làm rõ yêu cầu bài tập (không giải bài trực tiếp)


Hỏi đáp thông tin học vụ và hành chính


Giao diện giảng viên
Duyệt và phê duyệt câu trả lời của Hannah


Thêm phản hồi tùy chỉnh cho các câu hỏi thường gặp


Theo dõi chất lượng và độ chính xác của các cuộc trò chuyện


Tạo và cập nhật nội dung cơ sở tri thức chuyên môn


Xem phân tích các câu hỏi và vấn đề sinh viên gặp phải


Xác định lỗ hổng kiến thức chung của sinh viên


Đánh dấu các cuộc trò chuyện cần sự can thiệp của con người


Giao diện quản trị viên
Quản lý tài khoản người dùng và phân quyền


Cấu hình hệ thống và tích hợp


Giám sát hiệu suất và mức độ sử dụng hệ thống


Quản lý cấu trúc cơ sở tri thức


Quản lý phiên bản và cập nhật nội dung


Tạo báo cáo và bảng phân tích hệ thống


Quản lý tham số mô hình và dữ liệu huấn luyện



Hệ thống quản lý tri thức
Kho lưu trữ có cấu trúc cho tài liệu các môn học Công nghệ Phần mềm


Hệ thống phân loại và gắn thẻ nội dung


Kiểm soát phiên bản tài liệu học tập


Chức năng tìm kiếm theo ngữ cảnh


Tích hợp với cơ sở dữ liệu học thuật và tài nguyên bên ngoài


Hỗ trợ các loại nội dung đa phương tiện


Kết nối API với tài nguyên lập trình và phát triển



Yêu cầu phi chức năng
Tương thích đa nền tảng (web, di động)


Rõ ràng trong việc phân biệt giữa phản hồi của AI và con người



3.2. Nội dung đề xuất chính (bao gồm kết quả và sản phẩm)
Lý thuyết và thực hành (tài liệu):
 Sinh viên cần áp dụng quy trình phát triển phần mềm và sử dụng UML 2.0 trong việc mô hình hóa hệ thống.
 Tài liệu bao gồm: Yêu cầu người dùng, Đặc tả yêu cầu phần mềm, Thiết kế kiến trúc, Thiết kế chi tiết, Triển khai hệ thống, Tài liệu kiểm thử, Hướng dẫn cài đặt, mã nguồn và gói phần mềm triển khai.

Công nghệ phía máy chủ:
AI Engine: NVidia ChatRTX (mã nguồn mở) làm mô hình nền tảng


Backend: Python với FastAPI


Cơ sở dữ liệu: PostgreSQL (dữ liệu có cấu trúc), MongoDB (lưu log hội thoại)


Tìm kiếm: Elasticsearch cho truy vấn cơ sở tri thức


Quản lý nội dung: Django CMS


Bộ nhớ đệm: Redis



Công nghệ phía khách:
Frontend: React.js với TypeScript


UI Framework: Material-UI


Giao tiếp thời gian thực: WebSockets


Quản lý trạng thái: Redux


Ứng dụng di động: React Native



Sản phẩm:
Trợ lý AI Hannah


Giao diện trò chuyện (Web & Di động)


Tích hợp cơ sở tri thức


Hệ thống phản hồi theo ngữ cảnh


Cổng quản lý dành cho giảng viên


Giao diện duyệt và kiểm tra phản hồi


Hệ thống quản lý nội dung


Bảng điều khiển phân tích


Hệ thống quản lý tri thức


Kho nội dung có cấu trúc


Hệ thống tìm kiếm và truy xuất


Quản lý phiên bản nội dung


Bảng điều khiển quản trị


Công cụ giám sát hệ thống


Giao diện quản lý người dùng


Các tùy chọn cấu hình hệ thống



Các gói công việc đề xuất:
Gói công việc 1: Phân tích và thiết kế hệ thống


Gói công việc 2: Phát triển trợ lý AI


Gói công việc 3: Hệ thống quản lý tri thức


Gói công việc 4: Phát triển giao diện giảng viên, web và di động


Gói công việc 5: Chuẩn bị đầy đủ các tài liệu: Phân tích & thiết kế hệ thống, Kế hoạch kiểm thử, Hướng dẫn cài đặt, Hướng dẫn sử dụng
