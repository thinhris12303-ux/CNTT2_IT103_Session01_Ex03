# Bài tập UX Copywriting: Tối ưu Microcopy màn hình Giỏ hàng (ShopeeFood)

## 1. Bảng tổng hợp chẩn đoán và viết lại Microcopy

| Vị trí | Chữ hiển thị hiện tại | Bước 1: Chẩn đoán nhanh lỗi UX | Bước 2: Viết lại Microcopy mới | Số ký tự (Giới hạn) |
| :--- | :--- | :--- | :--- | :--- |
| **1. Nút bấm chính (CTA)** | Gửi dữ liệu | Từ ngữ kỹ thuật khô khan, không nêu rõ hành động đặt món hay tổng số tiền khách cần thanh toán. | **Đặt đơn - 88.000đ** | **17 / 20 ký tự** |
| **2. Nhắc ưu đãi phí ship** | Bạn chọn chưa đủ món nên không được giảm phí giao hàng! | Giọng văn tiêu cực, đổ lỗi cho khách hàng (*"chưa đủ món"*), thiếu thông tin cụ thể về số tiền cần mua thêm. | **Mua thêm 28.000đ để được giảm 15.000đ phí ship!** | **50 / 60 ký tự** |
| **3. Báo ví không đủ tiền** | Lỗi 402: Payment_Declined. Giao dịch bị từ chối. | Dùng mã lỗi kỹ thuật khó hiểu (`402`, `Payment_Declined`), không giải thích lý do và thiếu hướng dẫn khắc phục (lối ra). | **Số dư ví không đủ. Vui lòng nạp thêm hoặc đổi thanh toán.** | **59 / 60 ký tự** |

---

## 2. Chi tiết kiểm đếm ký tự & Giải thích Heuristic #9

* **Nút bấm chính (CTA):** `Đặt đơn - 88.000đ` (**17 ký tự** $\le 20$)
  * *Giải thích:* Hành động rõ ràng ("Đặt đơn") đi kèm minh bạch tổng chi phí cuối cùng ($72.000đ + 16.000đ = 88.000đ$).
* **Nhắc ưu đãi phí ship:** `Mua thêm 28.000đ để được giảm 15.000đ phí ship!` (**50 ký tự** $\le 60$)
  * *Giải thích:* Chuyển từ giọng văn từ chối sang khích lệ, chỉ rõ con số mục tiêu còn thiếu ($100.000đ - 72.000đ = 28.000đ$) và lợi ích nhận được.
* **Báo ví không đủ tiền:** `Số dư ví không đủ. Vui lòng nạp thêm hoặc đổi thanh toán.` (**59 ký tự** $\le 60$)
  * *Giải thích:* Áp dụng đúng nguyên tắc **Heuristic #9** — loại bỏ hoàn toàn mã lỗi hệ thống, thông báo nguyên nhân bằng tiếng Việt tự nhiên và đưa ra 2 giải pháp khắc phục trực tiếp (nạp tiền hoặc đổi phương thức thanh toán).