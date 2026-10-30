# K26CNTT2_IT108_Session14_Ex04

# 💬 Báo cáo Bài tập: Khắc phục tình trạng trôi thông tin trong nhóm làm việc
**Môn học:** Nhập Môn Công Nghệ Thông Tin (Buổi 15: Không gian cộng tác đám mây)  
**Học viên:** Lê Hồ Thanh Thảo (N26DTCN030)  
**Repository:** `K26CNTT2_IT108_Session14_Ex04`

---

## 1. Mục tiêu
- So sánh hiệu quả giao tiếp giữa ứng dụng chat cá nhân và Công cụ doanh nghiệp chuyên nghiệp (Lark, Slack).
- Đánh giá sự đánh đổi (`Trade-off`) về khả năng quản lý tin nhắn, tìm kiếm dữ liệu và tối ưu hiệu suất làm việc nhóm.

---

## 2. Bối cảnh & Yêu cầu bài toán
> **Tình huống:** Startup của bạn đang gặp tình trạng trôi tin nhắn nghiêm trọng trên Zalo. Một thông báo hạn nộp bài (`deadline`) quan trọng bị ghi đè bởi 50 tin nhắn meme và tán gẫu.  
> 
> **Yêu cầu:** Phân tích, so sánh và đề xuất giải pháp chuyển đổi sang không gian làm việc doanh nghiệp (`Enterprise Workspace` như Lark Suite) dựa trên các tiêu chí nghiệp vụ cụ thể.

---

## 3. Yêu cầu đầu ra

### Phần 1: Bảng so sánh 5 tiêu chí giữa App chat cá nhân và Enterprise Workspace

| Tiêu chí | App chat cá nhân (Ví dụ: Zalo, Messenger) | Công cụ doanh nghiệp (Ví dụ: Lark Suite, Slack) |
| :--- | :--- | :--- |
| **1. Phân loại tin nhắn (Channel / Thread)** | Gộp chung tất cả vào một đoạn chat nhóm duy nhất; thông tin công việc dễ bị trôi lấp bởi meme và chat phiếm. | Chia nhỏ theo kênh chuyên môn (`#dev`, `#marketing`) và phân luồng thảo luận từng chủ đề (`Thread`), giúp thông tin tập trung. |
| **2. Khả năng tìm kiếm file và dữ liệu cũ** | Hạn chế, dung lượng lưu trữ file đính kèm có thời hạn (hết hạn sẽ bị xóa), khó tìm lại tài liệu sau thời gian dài. | Hệ sinh thái lưu trữ đám mây tích hợp sẵn, hỗ trợ tìm kiếm nâng cao theo từ khóa, người gửi và lưu trữ vĩnh viễn an toàn. |
| **3. Khả năng quản lý công việc (Task Integration)** | Tin nhắn trôi qua là quên; không hỗ trợ tạo Task/Deadline trực tiếp gắn liền với nội dung trò chuyện. | Tích hợp công cụ quản lý công việc (như Lark Base, Task), cho phép gán người phụ trách, hạn chót và theo dõi trạng thái ngay trong app. |
| **4. Ranh giới công việc và cá nhân** | Dễ bị lẫn lộn (thông báo công việc dồn dập ngoài giờ hành chính cùng tin nhắn cá nhân), gây áp lực tâm lý. | Tách biệt rõ ràng; dễ dàng thiết lập chế độ làm việc tập trung, tắt thông báo ngoài giờ hoặc phân ca trực linh hoạt. |
| **5. Bảo mật và Quản trị dữ liệu** | Phụ thuộc vào tài khoản cá nhân, khi nhân sự nghỉ việc khó thu hồi quyền truy cập hoặc kiểm soát lịch sử chia sẻ. | Quản trị viên tập trung (`Admin Control`), dễ dàng phân quyền, thu hồi tài khoản và kiểm soát an toàn dữ liệu (`Data Loss Prevention`). |

---

### Phần 2: Đánh giá & Giải pháp tối ưu hóa hiệu suất

#### 1. Tại sao các công ty IT chọn Lark/Slack thay vì Zalo để tiết kiệm hàng trăm giờ họp?
* **Loại bỏ các cuộc họp báo cáo tiến độ thủ công:** Nhờ khả năng tích hợp bảng biểu, cập nhật tiến độ công việc tự động (`Daily Status`) ngay trên nền tảng doanh nghiệp, các thành viên có thể nắm bắt khối lượng công việc mà không cần tốn hàng giờ ngồi họp trực tiếp.
* **Giao tiếp bất đồng bộ (`Asynchronous Communication`):** Cho phép lập trình viên tập trung sâu vào code (`Deep Work`) mà không bị làm phiền bởi thông báo nhảy liên tục, từ đó tối ưu hóa năng suất lập trình và giảm thiểu gián đoạn tư duy.

#### 2. Giải pháp khắc phục hiện tượng "Tin nhắn phẳng một hàng"
Để giải quyết triệt để vấn đề thông báo quan trọng bị ghi đè bởi hàng loạt tin nhắn rác, đội ngũ cần áp dụng ngay các quy tắc vận hành sau:
* **Sử dụng tính năng Ghim tin nhắn (`Pinned Messages`):** Mọi thông báo về deadline, link họp quan trọng phải được ghim lên đầu kênh để bất kỳ thành viên nào mở app cũng thấy ngay lập tức.
* **Quy hoạch rõ ràng Channel / Thread:** Cấm đăng meme, chat tán gẫu vào kênh thông báo chính (`#announcement`). Tạo riêng một kênh giải trí (ví dụ: `#random`) để xả stress mà không làm loãng luồng công việc chung.
* **Tận dụng Bot thông báo tự động:** Cài đặt các tiện ích tự động hóa để nhắc nhở deadline trước 24h, giúp mọi thành viên không bị bỏ sót nhiệm vụ quan trọng.
