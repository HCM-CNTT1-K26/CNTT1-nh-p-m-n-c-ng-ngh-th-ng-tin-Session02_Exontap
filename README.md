# CNTT1-nh-p-m-n-c-ng-ngh-th-ng-tin-Session02_Exontap

## Phần 1 – Lĩnh vực CNTT & Đơn vị lưu trữ

1. **Ứng viên:** Chọn **Ứng viên B**.
* Cyber Arena cần duy trì phòng máy vận hành liên tục, sửa chữa phần cứng kịp thời và đảm bảo hạ tầng mạng ổn định cho khách chơi game cũng như livestream.


2. **Thứ tự tăng dần:**
* Byte < KB < MB < GB < TB



---

## Phần 2 – Mô hình IPO & Lĩnh vực CNTT

1. **Bảng IPO:**

| Thành phần | Hệ thống quay/xem lại trận đấu |
| --- | --- |
| **Input** | Tín hiệu hình ảnh và thao tác từ màn hình chơi game |
| **Process** | Phần mềm xử lý và nén/mã hóa (encode) video |
| **Output** | File video trận đấu để xem và phân tích |
| **Storage** | Ổ cứng SSD dùng lưu trữ video |

2. **Lĩnh vực CNTT liên quan:**

* **Mạng máy tính và Truyền thông:** Đảm bảo đường truyền kết nối ổn định để phát livestream trực tiếp.
* **Kỹ thuật phần mềm:** Sử dụng phần mềm ghi hình, quản lý và phân tích trận đấu.

---

## Phần 3 – Dung lượng & Tốc độ mạng

1. **Dung lượng lưu trữ:**

* Dung lượng 20 trận: $20 \times 500 = 10.000\text{ MB}$
* Đổi sang GB: $10.000 \div 1024 \approx 9,77\text{ GB}$
* SSD 512 GB **chứa đủ**. Còn trống: $512 - 9,77 = 502,23\text{ GB}$.

2. **Tốc độ mạng:**

* Tốc độ tối đa theo MB/s: $100 \div 8 = 12,5\text{ MB/s}$
* Thời gian upload video 200 MB: $200 \div 12,5 = 16\text{ giây}$
* Thực tế lâu hơn do: Băng thông bị chia sẻ nội bộ hoặc suy hao đường truyền do nhiễu mạng.

---

## Phần 4 – Phần cứng & Mô hình DIKW

1. **Nâng cấp:** Chọn **CPU**.
* Vừa chơi game vừa livestream đòi hỏi CPU xử lý mã hóa video và tác vụ nặng liên tục. Nếu CPU yếu sẽ gây nghẽn hệ thống làm giật lag.


2. **Mô hình DIKW:**

| Tầng | Nội dung | Lý do |
| --- | --- | --- |
| **Data** | Video quay cảnh tuyển thủ bị hạ gục ở phút 15-20. | Dữ liệu thô gồm hình ảnh và mốc thời gian chưa qua phân tích. |
| **Information** | Tuyển thủ bị hạ gục do thiếu tầm nhìn trên bản đồ. | Dữ liệu đã được xử lý để tìm ra nguyên nhân cụ thể. |
| **Knowledge** | Kiểm soát tầm nhìn bằng mắt giúp hạn chế bị hạ gục. | Rút ra tri thức chiến thuật từ thực tế trận đấu. |
| **Wisdom** | Yêu cầu tuyển thủ mua thêm mắt cho các trận sau. | Ra quyết định hành động sáng suốt để khắc phục lỗi. |
