# Web AR Game Project Proposal: Flying Cow Ranch

## 1. Mục tiêu (Objective)
* **Chủ đề chính:** 棲地環境 (Habitat Environment)
* Giúp du khách hiểu được mối quan hệ giữa môi trường sống và hành vi của động vật thông qua trải nghiệm khám phá sinh thái kết hợp Web AR Game.
* Trò chơi tập trung vào hai mục tiêu:
  * **Giáo dục sinh thái:** Giúp người chơi hiểu cách các yếu tố như ánh sáng, cấu trúc thảm thực vật, nguồn thức ăn và nơi trú ẩn ảnh hưởng đến môi trường sống của sinh vật.
  * **Khuyến khích khám phá:** Tạo động lực để du khách khám phá các khu vực ít được chú ý trong trang trại, đặc biệt là khu sinh thái bươm bướm.

---

## 2. Vấn đề và đối tượng mục tiêu (Hook / Problem Analysis)

### 2.1. Những vấn đề được ghi nhận tại trang trại
* **Vấn đề 1: Khó khăn trong việc khám phá các khu vực xa**
  * 飛牛牧場 có diện tích rộng, khiến việc di chuyển đến tất cả các khu vực trở nên khó khăn, đặc biệt đối với gia đình có trẻ nhỏ và người lớn tuổi.
  * Một số khu vực cần nhiều thời gian đi bộ hơn, làm giảm động lực khám phá của du khách.
* **Vấn đề 2: Hoạt động tham quan tập trung ở một số địa điểm**
  * Các khu vực như cho dê ăn và xem hoạt động liên quan đến bò sữa có sức hấp dẫn cao nhờ trải nghiệm trực tiếp.
  * Trong khi đó, những khu vực như sinh thái bươm bướm có ít hoạt động tương tác hơn, khiến du khách có thể bỏ qua hoặc chưa dành đủ thời gian khám phá.
* **Vấn đề 3: Khó quan sát và hiểu về động vật trong môi trường tự nhiên**
  * Bươm bướm có kích thước nhỏ và thường xuyên di chuyển, khiến việc quan sát đặc điểm và sự khác biệt giữa các loài trở nên khó khăn.
  * Một số loài sinh vật khó quan sát do tập tính hoạt động hoặc môi trường sống tự nhiên.
  * Nếu chỉ cung cấp thông tin bằng bảng giới thiệu, du khách có thể thiếu cơ hội tương tác và vận dụng kiến thức sinh thái.
* **Vấn đề 4: Thông tin điều hướng chưa hỗ trợ đầy đủ cho hành trình khám phá**
  * Bản đồ và biển chỉ dẫn cần được đánh giá, cải thiện để du khách dễ xác định vị trí, lựa chọn tuyến đường và biết khoảng cách hoặc thời gian di chuyển dự kiến.

### 2.2. Đối tượng mục tiêu (Target Audience)
* Gia đình có trẻ em muốn kết hợp vui chơi và học hỏi.
* Du khách muốn tìm hiểu thiên nhiên thông qua trải nghiệm tương tác.
* Những người chưa có nhiều kiến thức về sinh thái nhưng muốn khám phá môi trường sống của động vật.

---

## 3. Giải pháp (Solution)

### 3.1. Hành trình khám phá theo tuyến đường và checkpoint
* Thiết kế một tuyến khám phá thử nghiệm từ khu vực cho dê ăn đến khu sinh thái bươm bướm, với các checkpoint được bố trí tại những địa điểm phù hợp.
* Mỗi checkpoint có thể bao gồm:
  * **QR Code:** Mở trò chơi trên trình duyệt điện thoại, không yêu cầu cài đặt ứng dụng riêng.
  * **Thông tin tuyến đường:** Hiển thị điểm đến tiếp theo, số checkpoint và thời gian đi bộ dự kiến nếu đã được khảo sát.
  * **Nhiệm vụ sinh thái:** Giới thiệu một đặc điểm của môi trường sống và yêu cầu người chơi quan sát, lựa chọn hoặc giải quyết thử thách.
  * **Tiến độ hành trình:** Hiển thị số checkpoint đã hoàn thành và số điểm còn lại.
* Người chơi có thể chọn tiếp tục, nghỉ ngơi hoặc kết thúc hành trình bất cứ lúc nào. Trò chơi khuyến khích khám phá nhưng không gây áp lực phải hoàn thành toàn bộ tuyến đường.
* *Lưu ý:* Web AR Game hỗ trợ điều hướng và tạo động lực khám phá, nhưng không thể tự giải quyết vấn đề khoảng cách vật lý. Vì vậy, bản đồ, thời gian di chuyển và các phương án hỗ trợ tiếp cận vẫn cần được xem xét riêng.

### 3.2. Gameplay cốt lõi: Habitat Explorer
* Tại mỗi checkpoint, người chơi hoàn thành một nhiệm vụ liên quan đến mối quan hệ giữa sinh vật và môi trường sống.
* **Vòng lặp gameplay:**
  1. **Khám phá:** Quét QR Code để mở nhiệm vụ.
  2. **Quan sát:** Xem mô hình, hình ảnh hoặc môi trường sinh thái được mô phỏng bằng Web AR.
  3. **Lựa chọn:** Trả lời câu hỏi hoặc lựa chọn môi trường phù hợp với sinh vật.
  4. **Phản hồi:** Hệ thống giải thích vì sao lựa chọn đúng hoặc chưa phù hợp.
  5. **Tiến triển:** Nhận huy hiệu hoặc mở khóa thông tin mới.
* **Ví dụ nhiệm vụ:**
  * Người chơi nhận một thẻ thông tin về một loài sinh vật và được giới thiệu các đặc điểm về nguồn thức ăn, nơi trú ẩn hoặc điều kiện sống của loài đó. Sau đó, người chơi lựa chọn môi trường phù hợp nhất trong số các môi trường mô phỏng.
  * Sau khi trả lời, hệ thống giải thích mối liên hệ giữa các đặc điểm của môi trường và nhu cầu sống của sinh vật.
  * Nội dung chính không chỉ là tìm đáp án đúng, mà còn giúp người chơi hiểu vì sao một môi trường phù hợp hoặc không phù hợp với một loài sinh vật.

### 3.3. Web AR: Mô phỏng và khám phá môi trường sống
* Web AR là phương tiện trực quan hóa kiến thức, không phải mục tiêu duy nhất của trò chơi.
* **Các tính năng trong phiên bản đầu tiên gồm:**
  * **Khám phá môi trường:** Hiển thị mô hình hoặc hình ảnh trực quan về cấu trúc môi trường sống, nơi trú ẩn và nguồn thức ăn.
  * **So sánh môi trường:** Cho phép người chơi so sánh các môi trường có đặc điểm khác nhau, chẳng hạn về ánh sáng hoặc độ che phủ của thảm thực vật.
  * **Thử thách ghép nối:** Yêu cầu người chơi lựa chọn môi trường phù hợp với sinh vật dựa trên thông tin đã học.
  * **Giải thích kiến thức:** Cung cấp phản hồi ngắn gọn sau mỗi câu trả lời, giúp người chơi hiểu nguyên nhân thay vì chỉ ghi nhớ đáp án.
* Các loài sinh vật và thông tin sinh thái cần được lựa chọn dựa trên dữ liệu đáng tin cậy, đồng thời ưu tiên những loài và môi trường có liên quan đến nội dung giáo dục của trang trại.
* Nếu động vật thật không xuất hiện trong lúc tham quan, mô hình AR có thể hỗ trợ việc học. Tuy nhiên, giao diện cần phân biệt rõ hình ảnh mô phỏng với sinh vật đang được quan sát ngoài thực tế.

### 3.4. Phần thưởng và động lực khám phá
* Áp dụng hệ thống phần thưởng để khuyến khích người chơi hoàn thành các nhiệm vụ và ghé thăm những khu vực ít được chú ý.
  * **Huy hiệu kỹ thuật số:** Nhận sau khi hoàn thành nhiệm vụ.
  * **Tiến độ khám phá:** Theo dõi số checkpoint đã hoàn thành.
  * **Mở khóa nội dung:** Thu thập thông tin về các loài sinh vật sau mỗi nhiệm vụ.
  * **Phần thưởng bổ sung:** Có thể thử nghiệm coupon hoặc quà tặng nếu trang trại có khả năng phối hợp.
* Phần thưởng nên gắn với hoạt động học tập và khám phá, thay vì chỉ dựa vào khoảng cách di chuyển. Nếu muốn khuyến khích đến các khu vực xa, cần cân nhắc thời gian đi bộ, mức độ tiếp cận và sự phù hợp đối với trẻ em và người lớn tuổi.

### 3.5. Phạm vi phát triển theo giai đoạn
* **Giai đoạn 1 — MVP (Minimum Viable Product)**
  * Một tuyến khám phá đã được khảo sát.
  * Ba checkpoint chính, bao gồm khu sinh thái bươm bướm nếu địa điểm được xác nhận phù hợp.
  * QR Code để truy cập trò chơi và xem thông tin tuyến đường.
  * Một nhiệm vụ sinh thái tại mỗi checkpoint.
  * Một trải nghiệm Web AR hoặc mô phỏng môi trường sống.
  * Hệ thống câu hỏi, giải thích đáp án và theo dõi tiến độ.
  * Huy hiệu kỹ thuật số cơ bản.
* **Giai đoạn 2 — Future Expansion**
  * Sau khi đánh giá phản hồi của người dùng và tính khả thi của phiên bản đầu tiên, có thể mở rộng với:
  * Các tuyến đường khám phá khác.
  * Chế độ ngày và đêm để minh họa sự khác biệt về thời gian hoạt động của các loài.
  * Nội dung theo mùa và các sự kiện sinh thái có cơ sở khoa học.
  * Nhiều môi trường mô phỏng, loài sinh vật và nhiệm vụ nâng cao.
  * Coupon, phần thưởng hợp tác với trang trại và hoạt động hướng dẫn trực tiếp.
  * *Những tính năng mở rộng không thuộc phạm vi bắt buộc của MVP.*

---

## 4. Giá trị mang lại (Value Proposition)

* **Đối với du khách**
  * Học kiến thức sinh thái thông qua tương tác thay vì chỉ đọc thông tin.
  * Có thêm lý do để khám phá các khu vực ngoài những điểm tham quan phổ biến.
  * Biết được tiến độ hành trình và chủ động lựa chọn mức độ tham gia.
* **Đối với 飛牛牧場**
  * Bổ sung hoạt động giáo dục sinh thái cho trải nghiệm tham quan.
  * Tạo cơ hội thu hút du khách đến các khu vực ít được chú ý.
  * Có thể bắt đầu thử nghiệm với số lượng checkpoint và nội dung hạn chế trước khi đầu tư mở rộng.
* **Đối với tính khả thi của dự án**
  * Sử dụng QR Code và Web AR để hạn chế yêu cầu cài đặt ứng dụng riêng.
  * Không bắt buộc phải phát triển hệ thống AI nhận diện động vật hoặc định vị thời gian thực.
  * Có thể tận dụng hình ảnh và thông tin quan sát từ các nguồn như iNaturalist để nghiên cứu và tham khảo, nhưng cần kiểm tra độ tin cậy. Nguồn này chỉ cung cấp hình ảnh để hỗ trợ chứ không trực tiếp cung cấp sẵn mô hình 3D.

---

## 5. Hạn chế và phương án xử lý (Constraints & Mitigation)

* **Hạn chế 1: Khoảng cách di chuyển**
  * *Vấn đề:* Web AR không làm giảm khoảng cách vật lý giữa các địa điểm.
  * *Phương án xử lý:* Thử nghiệm một tuyến đường ngắn và hợp lý; cung cấp bản đồ, thời gian di chuyển dự kiến và quyền kết thúc hành trình bất cứ lúc nào. Phương tiện di chuyển bổ sung chỉ được xem xét sau khi đánh giá tính khả thi và tác động đến môi trường.
* **Hạn chế 2: Độ chính xác của kiến thức sinh thái**
  * *Vấn đề:* Thông tin sai lệch có thể làm giảm giá trị giáo dục của trò chơi.
  * *Phương án xử lý:* Xây dựng nội dung dựa trên nguồn đáng tin cậy, xác minh loài và môi trường tại trang trại, đồng thời nhờ người có chuyên môn kiểm tra nội dung khi có thể.
* **Hạn chế 3: Nguồn lực phát triển và vận hành**
  * *Vấn đề:* Nhiều tuyến đường, mô hình 3D và nội dung theo mùa sẽ làm tăng chi phí phát triển, cập nhật và kiểm tra thông tin.
  * *Phương án xử lý:* Ưu tiên MVP với số lượng checkpoint và tính năng giới hạn. Hướng dẫn trực tiếp từ nhân viên có thể là hoạt động bổ sung, nhưng không nên là điều kiện bắt buộc để trò chơi hoạt động.
* **Hạn chế 4: Khả năng tiếp cận của người chơi**
  * *Vấn đề:* Trẻ em, người lớn tuổi và du khách có khả năng di chuyển khác nhau có thể gặp khó khăn trên các tuyến đường dài.
  * *Phương án xử lý:* Cho phép lựa chọn tuyến đường và dừng chơi linh hoạt; ưu tiên tuyến phù hợp với đối tượng mục tiêu và kiểm tra tính dễ đọc của giao diện trên điện thoại.

---

## 6. Đánh giá hiệu quả (Evaluation)
Để xác định liệu trò chơi có thực sự giải quyết vấn đề hay không, có thể đánh giá bằng các chỉ số sau:
* **Mức độ tham gia:** Số lượt bắt đầu chơi và tỷ lệ hoàn thành từng checkpoint.
* **Mức độ khám phá:** Số lượt ghé thăm các checkpoint ngoài khu vực tham quan phổ biến.
* **Hiệu quả học tập:** So sánh kết quả trả lời câu hỏi trước và sau khi trải nghiệm, hoặc đánh giá mức độ hiểu thông qua câu hỏi tình huống.
* **Trải nghiệm người dùng:** Thu thập phản hồi về độ dễ sử dụng, mức độ thú vị và sự phù hợp của thời gian di chuyển.
* *Các chỉ số này cần được thu thập trong giai đoạn thử nghiệm; chưa nên giả định trước rằng trò chơi chắc chắn sẽ tăng lượng khách đến các khu vực ít được chú ý.*

---

## 7. Kết luận (Pitch)
Habitat Explorer biến hành trình khám phá 飛牛牧場 thành một trải nghiệm học tập tương tác, nơi mỗi checkpoint giúp du khách hiểu thêm về mối quan hệ giữa sinh vật và môi trường sống.

Thay vì cố gắng xây dựng một hệ thống lớn ngay từ đầu, dự án bắt đầu với một tuyến đường thử nghiệm, một số nhiệm vụ sinh thái và một trải nghiệm Web AR cốt lõi. Cách tiếp cận này giúp kiểm tra cả hiệu quả giáo dục lẫn khả năng khuyến khích khám phá trước khi mở rộng sản phẩm.