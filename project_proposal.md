# Web AR Game Project Proposal: Flying Cow Ranch

## 1. Mục tiêu (Objective)
* **Chủ đề:** [棲地環境] - Sự khác biệt trong hành vi của động vật sống ở rừng nhiều tầng và khu vực đất trống.

---

## 2. Vấn đề & Nỗi đau (Hook / Problem Analysis)
* **Quy mô trang trại lớn:** 飛牛牧場 quá rộng, khiến khách du lịch (đặc biệt là trẻ em và người già) gặp khó khăn trong việc di chuyển tới mọi khu vực.
* **Sự tập trung cục bộ của khách tham quan:** 
  * Khách hàng chủ yếu tập trung ở khu vực cho dê ăn và khu xem vắt sữa bò do có các hoạt động tương tác trực tiếp, mới lạ và dễ thu hút trẻ em.
  * Ngược lại, khu sinh thái bươm bướm và các khu vực khác thiếu các hoạt động hấp dẫn; bươm bướm có kích thước nhỏ, bay liên tục nên khó quan sát rõ ràng hoặc nhận biết sự khác biệt giữa các loài.
  * Nhiều khu vực khác trong trang trại khách không thể tiếp cận hoặc không thể thấy động vật do tập tính sinh hoạt của chúng.
* **Hạn chế về hệ thống chỉ dẫn:** Bản đồ hiện tại của 飛牛牧場 chưa đủ rõ ràng, dễ gây nhầm lẫn. Cần bổ sung các bảng chỉ dẫn nổi bật tại các ngã rẽ và đường nhỏ, đảm bảo ăn khớp với bản đồ tổng thể của trang trại.

---

## 3. Giải pháp (Solution)

### 3.1. Thiết kế Lộ trình & Checkpoint
* **Hệ thống Checkpoint:** Biến mỗi địa điểm tham quan trong trang trại thành một checkpoint độc lập.
* **Đa dạng hóa Route:** Thiết kế nhiều lộ trình (routes) khác nhau để khách du lịch tự do lựa chọn khám phá.
* **QR Code điều hướng:** Đặt mã QR tại mỗi checkpoint để giới thiệu thông tin và gợi ý các hướng đi tiếp theo.

### 3.2. Trạm dừng chân & Web AR tương tác trên đường đi
* **Tăng cường phương tiện hỗ trợ & Trạm dừng (Check-points kiến thức):**
  * Bổ sung phương tiện di chuyển (cân nhắc yếu tố bảo tồn sinh thái trang trại).
  * Thiết lập các trạm dừng trung gian giữa các checkpoint chính (ví dụ: 5 trạm dừng trên đoạn đường từ khu dê ăn đến khu sinh thái bươm bướm).
  * Mỗi trạm trang bị QR code, mini-game, Web AR để giới thiệu về các loài bươm bướm sắp tới hoặc kiến thức môi trường sống ngay tại chỗ.
* **Duy trì động lực khám phá:** 
  * Cung cấp thông tin trực quan về tổng số trạm và tiến độ hoàn thành hiện tại để kích thích tâm lý không muốn bỏ lỡ của người chơi (sau khi đi được hơn nửa chặng đường).
  * Kết hợp nhân viên hướng dẫn tại chỗ (đặc biệt tại khu bươm bướm) để chỉ cách quan sát và cung cấp kiến thức chuyên sâu.

### 3.3. Hệ thống Phần thưởng & Thử thách
* Áp dụng cơ chế phần thưởng tăng dần theo khoảng cách và độ khó của điểm đến (càng xa, càng ít người tới, phần thưởng càng cao).
* Phần thưởng bao gồm: Huy hiệu kỹ thuật số, nhân vật mới trong game, coupon ưu đãi.
* Tích hợp các câu hỏi quiz và thử thách tương tác.

### 3.4. Tính năng Quét AR cốt lõi
* **Khám phá cấu trúc môi trường rừng:** Tìm hiểu nơi trú ẩn, nguồn thức ăn và điều kiện sống của các loài sinh vật phù hợp với khu vực.
* **Tự tạo lập môi trường sống:** Người dùng tự chọn các thông số về ánh sáng, thời gian, độ cao để mô phỏng môi trường, từ đó hệ thống hiển thị loài động vật tương ứng phù hợp.
* **Thử thách ghép nối môi trường:** Người chơi nhận thẻ thông tin sinh vật, quan sát các môi trường mô phỏng và lựa chọn môi trường thích hợp nhất (có giải thích chi tiết kể cả khi trả lời sai).

### 3.5. Định hướng Phát triển Tương lai (Future Expansion)
* **Chế độ quan sát nâng cao:** Thêm chế độ sáng/tối cho động vật hoạt động về đêm/sáng sớm, phân tầng sinh thái rừng, và chế độ theo mùa.
* **Sự kiện theo chủ đề (Events):** Mô phỏng các tình huống thực tế như sự thay đổi di cư của động vật khi con người ít xuất hiện (thời kỳ COVID-19) hoặc nơi trú ẩn của động vật khi có bão lớn. Mỗi sự kiện kéo dài từ 1 tuần đến nửa tháng.

---

## 4. Giá trị mang lại (Value)
* Nâng cao kiến thức cho du khách về sinh vật và môi trường sống tự nhiên của chúng.
* Không đòi hỏi hệ thống AI nhận diện phức tạp hay bản đồ định vị quá rườm rà; chỉ cần các mô hình 3D sinh vật và địa điểm. Có thể tận dụng dữ liệu và hình ảnh từ cộng đồng iNaturalist để hỗ trợ quá trình xây dựng mô hình.
* Thêm hoạt động phong phú cho trang trại, góp phần phân bổ lại lượng khách du lịch đều hơn đến các khu vực ít người qua lại.

---

## 5. Điểm yếu & Hạn chế (Weaknesses / Constraints)
* **Yêu cầu nhân lực chuyên môn:** Cần thêm nhân lực có kiến thức sinh học để hướng dẫn trực tiếp du khách (đặc biệt là với bươm bướm). Với các loài động vật hoạt động về đêm/sáng sớm mà khách khó thấy thực tế, giải pháp AR sẽ bù đắp phần kiến thức này.
* **Giới hạn phạm vi giải quyết:** Game chỉ đóng vai trò giảm rào cản thông tin và tạo động lực khám phá trong phạm vi khả thi, không thể hoàn toàn giải quyết triệt để vấn đề diện tích quá rộng lớn của trang trại.