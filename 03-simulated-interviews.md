# 3. Phỏng vấn mô phỏng

> **CẢNH BÁO: DỮ LIỆU MÔ PHỎNG — KHÔNG PHẢI PHỎNG VẤN NGƯỜI DÙNG THẬT.**  
> Toàn bộ persona, câu trả lời và trích dẫn dưới đây là hư cấu, chỉ dùng để luyện kỹ năng phỏng vấn. Không có file ghi âm thật đi kèm và nội dung này không được dùng để tuyên bố validation.

## Lượt luyện 1 — Minh, học Python trực tuyến

### Hồ sơ mô phỏng

- 20 tuổi, sinh viên năm hai.
- Học một khóa Python theo video để chuẩn bị cho bài tập trên lớp.
- Tình huống gần nhất: ba ngày trước, vướng ở list slicing.

### Transcript rút gọn

**Interviewer:** Trong bảy ngày gần đây, có lần nào bạn đang học mà không hiểu một phần cụ thể không?

**Minh:** Có, tối thứ Hai mình học phần list trong Python. Đến đoạn slicing có số âm thì mình không hiểu vì sao kết quả lại ra như vậy.

**Interviewer:** Bạn kể lại từ lúc nhận ra mình không hiểu được không?

**Minh:** Video đưa ví dụ `a[-4:-1]`. Mình đoán nó lấy từ cuối danh sách, nhưng không hiểu vì sao phần tử cuối không xuất hiện. Mình tua lại hai lần và dừng video để tự viết các vị trí ra giấy.

**Interviewer:** Việc đầu tiên bạn làm là tua lại video à?

**Minh:** Đúng. Đầu tiên mình lùi khoảng một phút. Sau hai lần vẫn không hiểu nên mình mở Google.

**Interviewer:** Bạn nhớ mình đã tìm gì không?

**Minh:** Gần như là “python negative list slicing”. Mình mở Stack Overflow trước nhưng câu trả lời dùng nhiều thuật ngữ hơn video. Sau đó mình mở một trang tutorial có hình minh họa.

**Interviewer:** Điều gì khiến bạn biết trang thứ hai đã đủ?

**Minh:** Nó đánh số từng vị trí âm và nói điểm kết thúc không được tính. Mình quay lại chạy ba ví dụ trong notebook. Khi kết quả đúng với phần mình tự đoán thì mình tiếp tục video.

**Interviewer:** Từ lúc bị kẹt đến lúc tiếp tục mất khoảng bao lâu?

**Minh:** Khoảng 20 hoặc 25 phút. Video chỉ còn mười phút nhưng hôm đó mình mất gần một tiếng mới xong.

**Interviewer:** Bạn có biết ngay mình đang thiếu kiến thức nền nào không?

**Minh:** Mình biết là liên quan index, nhưng không biết chính xác quy tắc endpoint. Không phải mình quên cả phần list.

**Interviewer:** Gần đây có lần nào tương tự không?

**Minh:** Có một lần với vòng lặp lồng nhau, nhưng lần đó mình hỏi bạn cùng phòng luôn vì bạn ấy ngồi cạnh. Nhanh hơn tìm trên mạng.

**Interviewer:** Khoảnh khắc tốn công nhất trong câu chuyện này là lúc nào?

**Minh:** Lọc xem bài nào giải thích đúng đúng chỗ mình vướng. Nhiều trang giải thích cả list từ đầu.

### Facts ghi nhận

- Sự kiện cụ thể xảy ra ba ngày trước trong bài list slicing.
- Minh tua lại video hai lần, viết vị trí ra giấy, tìm Google, mở ít nhất hai nguồn và chạy ba ví dụ.
- Tổng thời gian tự ước lượng: 20–25 phút.
- Minh xác định được vùng kiến thức là index nhưng chưa biết quy tắc endpoint.
- Nguồn đầu tiên quá nhiều thuật ngữ; nguồn thứ hai có hình minh họa phù hợp hơn.
- Ở một sự kiện khác, hỏi người ở gần là cách giải quyết nhanh hơn.

### Diễn giải tạm thời của nhóm

- Có dấu hiệu của pain “tìm đúng lát cắt kiến thức”, không hẳn “không biết gì đang thiếu”.
- Việc nguồn ngoài giải thích quá rộng hoặc lệch trình độ có thể quan trọng hơn việc thiếu nguồn.
- Sự sẵn có của người hỗ trợ có thể làm pain giảm mạnh.

### Evidence làm giả thuyết yếu đi

- Minh khoanh vùng được vấn đề khá nhanh.
- Workaround cuối cùng đã giải quyết được tình huống trong khoảng 20–25 phút.
- Khi có bạn ở gần, Minh không cần quy trình chẩn đoán phức tạp.

### Lỗi của interviewer

- Câu “Bạn có biết ngay mình đang thiếu kiến thức nền nào không?” đưa khái niệm “kiến thức nền” vào miệng interviewee.
- Chưa hỏi Minh đã cân nhắc dừng học hay chưa.
- Chưa hỏi bằng chứng có thể quan sát như lịch sử tìm kiếm hoặc ghi chú.

---

## Lượt luyện 2 — Lan, học thống kê ứng dụng

### Hồ sơ mô phỏng

- 27 tuổi, nhân viên marketing học khóa phân tích dữ liệu buổi tối.
- Tình huống gần nhất: năm ngày trước, không hiểu p-value trong ví dụ A/B testing.

### Transcript rút gọn

**Interviewer:** Lần gần nhất bạn không hiểu một phần bài học là khi nào?

**Lan:** Tối thứ Ba, phần A/B testing. Giảng viên nói p-value nhỏ hơn 0,05 nên bác bỏ giả thuyết gốc. Mình theo được phép tính nhưng không hiểu câu kết luận thực sự có nghĩa gì.

**Interviewer:** Ngay trước lúc bị kẹt bạn đang làm gì?

**Lan:** Mình xem video và chép công thức. Đến câu hỏi quiz, hai đáp án nghe gần giống nhau nên mình chọn sai.

**Interviewer:** Sau khi thấy đáp án sai, bạn làm gì đầu tiên?

**Lan:** Mình đọc phần giải thích dưới quiz. Nó lặp lại câu trong video nên vẫn không rõ. Mình hỏi ChatGPT bằng cách dán câu hỏi vào.

**Interviewer:** Bạn hỏi chính xác như thế nào?

**Lan:** Mình không nhớ nguyên văn, đại khái hỏi giải thích vì sao đáp án B đúng. Câu trả lời đầu dài và có thêm confidence interval. Mình hỏi lại “giải thích như cho người làm marketing”.

**Interviewer:** Sau câu trả lời đó chuyện gì xảy ra?

**Lan:** Ví dụ tỷ lệ click làm mình hiểu hơn. Nhưng khi quay lại quiz mình vẫn phân vân vì câu chữ khác. Mình nhắn cho một đồng nghiệp học cùng ngành vào sáng hôm sau.

**Interviewer:** Vậy AI không hiệu quả lắm đúng không?

**Lan:** Không hẳn. Nó giúp mình hình dung, nhưng mình cần người xác nhận xem mình diễn giải câu hỏi của khóa học có đúng không.

**Interviewer:** Tình huống này ảnh hưởng thế nào đến kế hoạch hôm đó?

**Lan:** Mình định học xong module trong tối đó nhưng dừng sau khoảng 40 phút. Sáng hôm sau đồng nghiệp gửi voice message giải thích, trưa mình mới làm lại quiz.

**Interviewer:** Khoảnh khắc khó chịu nhất là gì?

**Lan:** Không biết mình đang hiểu sai khái niệm hay chỉ đọc sai câu hỏi. Càng đọc nhiều nguồn mình càng thấy mỗi nơi diễn đạt một kiểu.

### Facts ghi nhận

- Lan gặp khó sau khi trả lời sai một câu quiz về p-value.
- Lan đọc feedback, hỏi ChatGPT hai lượt, dừng học và nhắn đồng nghiệp vào hôm sau.
- Kế hoạch hoàn thành module trong tối đó bị lùi đến trưa hôm sau.
- Ví dụ theo bối cảnh marketing giúp hiểu hơn nhưng không đủ để Lan tự tin chọn đáp án.
- Lan cần phân biệt giữa hiểu sai khái niệm và hiểu sai cách diễn đạt câu hỏi.

### Diễn giải tạm thời của nhóm

- “Chẩn đoán khái niệm nền” có thể chưa đủ; một phần pain nằm ở việc kiểm tra cách diễn giải trong đúng ngữ cảnh đánh giá.
- Nhu cầu xác nhận từ con người có thể là một tiêu chí tin cậy quan trọng.
- Hậu quả quan sát được là trì hoãn hoàn thành module, không chỉ cảm giác khó chịu.

### Evidence làm giả thuyết yếu đi

- Vấn đề không rõ ràng là thiếu kiến thức nền; có thể là cách viết câu hỏi.
- Một lời giải thích ngắn chưa đưa Lan trở lại bài ngay.
- Lan coi xác nhận của đồng nghiệp đáng tin hơn câu trả lời tự động.

### Lỗi của interviewer

- Câu “Vậy AI không hiệu quả lắm đúng không?” vừa kết luận hộ vừa dẫn dắt.
- Chưa dựng đủ timeline của 40 phút, nhất là thời gian ở từng nguồn.
- Chưa hỏi Lan có từng gặp vấn đề tương tự trong module khác không.

---

## Lượt luyện 3 — Huy, học Excel cho công việc

### Hồ sơ mô phỏng

- 31 tuổi, nhân viên vận hành.
- Học video về PivotTable để làm báo cáo nội bộ.
- Tình huống gần nhất: hôm qua, số tổng trong PivotTable không giống bảng gốc.

### Transcript rút gọn

**Interviewer:** Hôm qua bạn nhận ra mình không hiểu ở điểm nào?

**Huy:** Video kéo trường doanh thu vào Values là ra tổng. Mình làm giống vậy nhưng file của mình lại hiện số lượng dòng. Mình không biết vì sao.

**Interviewer:** Bạn làm gì ngay sau đó?

**Huy:** Mình tua lại đoạn video một lần. Sau đó xóa PivotTable và làm lại từ đầu vì nghĩ mình kéo nhầm. Kết quả vẫn vậy.

**Interviewer:** Rồi sao nữa?

**Huy:** Mình tìm YouTube bằng điện thoại. Video đầu tiên dài 18 phút nên mình kéo nhanh. Có đoạn bảo đổi Count thành Sum, nhưng nút Sum của mình bị mờ.

**Interviewer:** Bạn xử lý tiếp thế nào?

**Huy:** Mình gửi ảnh màn hình vào nhóm chat công ty. Một bạn hỏi cột doanh thu có phải đang lưu dạng text không. Mình kiểm tra thì đúng là có dấu nháy ở một số ô. Sau khi đổi sang số và refresh thì PivotTable tính Sum được.

**Interviewer:** Bạn đã thiếu khái niệm nền về kiểu dữ liệu phải không?

**Huy:** Có thể, nhưng mình từng biết chuyện số lưu dạng text rồi. Mình không nghĩ nó liên quan đến PivotTable nên không kiểm tra.

**Interviewer:** Mất bao lâu từ lúc kẹt đến lúc làm được?

**Huy:** Khoảng 35 phút. Nếu không có nhóm chat chắc mình sẽ gửi file cho trưởng nhóm hoặc làm SUM thủ công.

**Interviewer:** Việc đó có hậu quả gì?

**Huy:** Báo cáo vẫn kịp vì hạn là cuối ngày, nhưng mình phải bỏ phần học tiếp theo để quay lại công việc.

**Interviewer:** Điều gì tốn công nhất?

**Huy:** Mình làm lại đúng các bước mà không biết lỗi nằm trong dữ liệu đầu vào. Video chỉ dùng file mẫu sạch.

### Facts ghi nhận

- Huy tua lại video, dựng lại PivotTable, tìm video khác rồi hỏi nhóm chat.
- Nguyên nhân là dữ liệu số bị lưu dạng text, không phải thao tác PivotTable.
- Tổng thời gian tự ước lượng: khoảng 35 phút.
- Báo cáo vẫn đúng hạn nhưng Huy bỏ phần học tiếp theo.
- Huy từng biết về kiểu dữ liệu nhưng không liên hệ kiến thức đó với triệu chứng hiện tại.

### Diễn giải tạm thời của nhóm

- Pain có thể là nhận diện mối liên hệ giữa triệu chứng hiện tại và kiến thức đã biết, không đơn thuần là “học lại kiến thức nền”.
- Chẩn đoán cần xem cả dữ liệu hoặc thao tác thực tế; chỉ dựa trên lịch sử học có thể không đủ.
- File mẫu quá sạch làm giảm khả năng chuyển kiến thức sang dữ liệu công việc.

### Evidence làm giả thuyết yếu đi

- Huy không thật sự thiếu kiến thức về kiểu dữ liệu.
- Lỗi phụ thuộc vào file thực tế và có thể không chẩn đoán được chỉ từ nội dung bài học.
- Pain chưa đủ lớn để làm trễ deliverable công việc.

### Lỗi của interviewer

- Câu “Bạn đã thiếu khái niệm nền… phải không?” áp đặt nguyên nhân.
- Chưa hỏi Huy đã xem chính xác phần nào trong video 18 phút.
- Chưa hỏi lần gần nhất trước đó gặp lỗi tương tự để kiểm tra tần suất.

## Tổng hợp mẫu hình từ hoạt động mô phỏng

> Phần này chỉ cho thấy guide có khả năng khai thác những loại thông tin nào; nó không chứng minh các mẫu hình tồn tại ngoài đời.

| Chủ đề để kiểm tra ngoài thực địa | Minh | Lan | Huy |
|---|---|---|---|
| Không xác định chính xác điểm vướng | Một phần | Có | Có |
| Rời bài để tìm nguồn khác | Có | Có | Có |
| Nguồn ngoài lệch ngữ cảnh/trình độ | Có | Có | Có |
| Cần xác nhận từ người khác | Khi có sẵn | Có | Có |
| Dừng hoặc trì hoãn việc học | Không | Có | Có |
| Vấn đề chắc chắn là thiếu kiến thức nền | Chưa chắc | Chưa chắc | Không hẳn |

