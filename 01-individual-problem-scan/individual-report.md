# 01 — Individual Problem Scan

> Điền theo Phase 1 + Phase 2 trong `01-worksheet.md`. Tự scan trước, dùng AI sau để phản biện. Không copy ví dụ Weekly Report.

## Thông tin cá nhân

- Họ và tên: Nguyễn Đức Long
- Mã học viên: 2A202602917
- Vai trò / bối cảnh (VD: sinh viên năm X, intern PM, ...): Hệ thống Tiếp nhận và Điều phối Cấp cứu (Trung tâm 115 / Emergency Dispatch Center).
- Công việc hằng tuần (3-5 gạch đầu dòng để soi problem):
-Tiếp nhận hàng trăm/ngàn cuộc gọi báo cấp cứu.
-Sàng lọc thông tin (Đâu là cuộc gọi trêu đùa/fake, đâu là cấp cứu thật).
-Đánh giá mức độ nguy kịch (Triage) qua mô tả của người gọi.
-Xác định vị trí nạn nhân và phân công xe cấp cứu phù hợp gần nhất.
-Hướng dẫn sơ cứu ban đầu (CPR, cầm máu) qua điện thoại cho người thân trong lúc chờ xe.
-Điều phối lộ trình xe chạy và kết nối thông tin trước với phòng cấp cứu tại bệnh viện.

---

## Phase 1 — Scan 5+ problems (tối thiểu 5, khuyến khích 8-10)

**Cách điền:** mỗi dòng = việc gì + ai chịu + đo bằng gì. Cột `Dấu hiệu thật` bắt buộc có số: mất bao lâu (bấm giờ mấy lần), mấy lần/tuần, bao nhiêu người gặp, log/ticket/quote nào.

| # | Lăng kính (Lặp lại / Tốn thời gian / AI có thể tốt hơn / Pain từ người khác) | Problem quan sát được | Ai chịu ảnh hưởng? | Dấu hiệu thật (số + bằng chứng) |
|---|---|---|---|---|
| 1 |Pain từ người khác |Người gọi khó nói, nói ngọng, tiếng địa phương hoặc hoảng loạn. |Người gặp sự cố, Tổng đài viên. |Gặp 5–10 lần/tuần; bấm giờ xử lý kéo dài > 5 phút/ca; quote: "Người gọi chỉ thều thào, không đọc được địa chỉ". |
| 2 |AI làm tốt hơn |Phân loại sai độ nguy kịch do đánh giá bằng cảm tính. |Bệnh nhân, Đội y tế. |Gặp 10–15% số ca/tuần; làm trễ xe ca nặng 8–12 phút; ticket khiếu nại "Xe đến chậm dù bệnh nhân đã ngất". |
| 3 |Tốn thời gian & AI làm tốt hơn |Xe cấp cứu kẹt xe do lộ trình không cập nhật theo thời gian thực. |Tài xế, Bệnh nhân. |Bấm giờ trễ thêm 5–15 phút/chuyến giờ cao điểm; xảy ra 30+ lần/tuần; log GPS xe lệch 3–5km so với tuyến tối ưu. |
| 4 |Pain từ người khác & Tốn thời gian |Nạn nhân bị tai nạn/đột quỵ khi ở một mình, không ai phát hiện.|Người già, Người sống một mình |Phát hiện trễ 2–12 giờ; ước tính 20–30% người già sống một mình có rủi ro; quote: "Nằm dơ dáy cả đêm mới có người biết". |
| 5 |AI làm tốt hơn |Y bác sĩ trên xe không biết tiền sử bệnh lý của nạn nhân. |Bác sĩ cấp cứu, Bệnh nhân. |Tốn thêm 3–5 phút hỏi người nhà/khám tại chỗ; gặp 40+ ca/tuần; log bệnh án ghi nhận 8% ca dùng nhầm phác đồ ban đầu. |
| 6 |Lặp lại & Tốn thời gian |Tổng đài bị quá tải bởi các cuộc gọi rác, trêu đùa hoặc báo động giả. |Tổng đài viên 115, Người gặp cấp cứu thật. |Chiếm 30–40% tổng lượng cuộc gọi (100–150 ca/ngày); tốn 15–30s/ca để lọc; quote: "Máy réo liên tục nhưng nhấc lên chỉ nghe tiếng cười đùa". |
| 7 |Tốn thời gian & AI làm tốt hơn |Xe đưa bệnh nhân đến bệnh viện đang bị quá tải phòng cấp cứu/giường ICU, phải chuyển viện bãi đáp khác. |Đội kíp xe cấp cứu, Bệnh nhân, Bác sĩ khoa cấp cứu. |Gặp 15–20 ca/tuần; trễ thêm 15–30 phút chuyển viện; log điều phối ghi nhận 12% chuyến xe phải quay đầu hoặc đổi tuyến bệnh viện khẩn cấp. |
| 8 |Lặp lại & Pain từ người khác |Người thân hoảng loạn không biết cách hoặc thực hiện sai kỹ thuật sơ cứu ban đầu (CPR, cầm máu) trong lúc chờ xe. |Nạn nhân, Người thân nạn nhân, Tổng đài viên. |Gặp 20–25 ca/tuần; tổng đài viên mất 2–4 phút giải thích thủ công qua thoại nhưng người gọi vẫn lúng túng; quote: "Tôi không biết ép tim thế nào, chỉ biết khóc thôi". |



> Gợi ý tự soi: tuần trước mất nhiều thời gian nhất vào việc gì? Việc gì hay trì hoãn? Người khác hay hỏi lại câu gì? Workflow nào ai cũng biết là chậm?

**AI đã dùng ở Phase 1 (nếu có):**
- Prompt đã hỏi: Tôi đang nghiên cứu đề xuất giải pháp AI giúp giảm thời gian phản hồi và xử lý của hệ thống cấp cứu y tế (115) – nơi mỗi phút trễ đều ảnh hưởng đến tính mạng bệnh nhân.

3 vấn đề hiện tại tôi đã chỉ ra:

Tổng đài viên mất thời gian tiếp nhận & phân loại cuộc gọi lặp lại.

Xe cấp cứu di chuyển chậm do tắc đường và thiếu lộ trình tối ưu real-time.

Nạn nhân ngất/đột quỵ một mình không thể tự gọi cấp cứu.

Hãy đề xuất thêm các vấn đề thực tế (Problem Statements) khác trong toàn bộ quy trình cấp cứu (từ lúc xảy ra sự cố đến khi vào phòng mổ).

Yêu cầu đối với các vấn đề bổ sung:

Bắt buộc thỏa mãn 4 tiêu chí: (1) Mang tính lặp lại, (2) Mất nhiều thời gian, (3) AI có khả năng làm tốt hơn con người, (4) Tạo ra Pain Point lớn cho bệnh nhân, bác sĩ hoặc người nhà.

Trình bày ngắn gọn, đi thẳng vào bản chất nút thắt (bottleneck)
- Ý dùng được: Tự động trích xuất thông tin thực địa (địa danh khẩn cấp, mốc lộ trình) và hỗ trợ phân loại từ ngữ thoại nhiễu/tiếng địa phương thành mã chuẩn hóa cho phần mềm điều phối cấp cứu 115.
- Ý bỏ vì không phải pain thật: Hệ thống AI toàn năng (End-to-End) thay thế tổng đài viên hay tự làm phần bản đồ chỉ đường (Chi phí đắt, hạ tầng chưa sẵn sàng, khó cạnh tranh); Bố trí xe nằm chờ thụ động tại bệnh viện thay vì đón đầu điểm nóng tính ngẫu nhiêu cao báo động giả gây lãng phí tài nguyên xe, gây tắc đường khi ít có điểm bãi đỗ điểm trực.

**Self-check Phase 1:**
- [x] Đủ 5+ dòng, mỗi dòng có actor + số đo cụ thể
- [x] Dùng ít nhất 3/4 lăng kính
- [x] Không có dòng chung chung kiểu "mất nhiều thời gian"

---

## Phase 2 — Top 3 Problem Cards

### 2.1. Chọn top 3

Giữ bài nào: actor cụ thể, workflow vẽ được 3-7 bước, bottleneck ở 1 bước, impact đo được. Loại bài quá rộng.

| Rank | Problem (copy từ bảng scan) | Vì sao chọn (2-3 ý) | Điều còn chưa chắc |
|---|---|---|---|
| 1 |Người gọi khó nói, nói ngọng, tiếng địa phương hoặc hoảng loạn. |Bottleneck trực tiếp gây trễ toàn bộ chuỗi cấp cứu (60–180s); actor và workflow tiếp nhận hiện tại cực kỳ rõ ràng; tác động giảm AHT ngay lập tức và dễ đo lường bằng số liệu. |Độ chính xác của AI Speech-to-Text khi người gọi hoảng loạn, nói ngọng, nói tiếng địa phương hoặc lẫn nhiều tạp âm môi trường. |
| 2 |Phân loại sai độ nguy kịch do đánh giá bằng cảm tính. |Ảnh hưởng sinh tử trực tiếp đến bệnh nhân nặng; loại bỏ yếu tố cảm tính cá nhân của tổng đài viên; dễ tích hợp thành màn hình gợi ý dạng Co-pilot. |Trách nhiệm pháp lý y khoa nếu AI gợi ý phân loại sai và rào cản kết nối với dữ liệu bệnh án điện tử (EHR) hiện có. |
| 3 |Nạn nhân bị tai nạn/đột quỵ khi ở một mình, không ai phát hiện. |Xóa bỏ khoảng trống trễ 2–12 giờ của quy trình truyền thống; giải quyết đúng pain point của nhóm người yếu thế; tận dụng tốt phần cứng di động/IoT sẵn có. |Tỷ lệ báo động giả (False Positive) cao gây lãng phí tài nguyên xe cấp cứu và tâm lý từ chối bật chia sẻ vị trí/sức khỏe liên tục của người dùng.|

### 2.2. Problem Cards chi tiết (lặp lại cho cả 3 cards)

---

## Problem Card #1 — Emergency Dispatch Input Bottleneck

**Problem 1 câu:**
Tổng đài viên 115 mất từ 60–180 giây xử lý thoại cho mỗi cuộc gọi do người gọi hoảng loạn, nói ngọng hoặc không thể nói, dẫn đến nghẽn hạ tầng tiếp nhận và trễ thời gian xuất xe.

**Actor:**
Tổng đài viên tiếp nhận cuộc gọi 115 (Emergency Dispatcher).

**Thời điểm / bối cảnh:**
Ngay khi có cuộc gọi khẩn cấp đổ về tổng đài 115, đặc biệt tăng cao vào các giờ cao điểm giao điểm hoặc thiên tai.

**Current workflow:**
```text
1. Bắt máy tiếp nhận cuộc gọi 115
2. Hỏi vị trí nạn nhân (giao tiếp thoại)
3. Hỏi triệu chứng / tình trạng cấp cứu
4. Giao tiếp lặp lại do người gọi hoảng loạn / nói ngọng / thều thào
5. Gõ nhập tay địa chỉ & triệu chứng vào phần mềm điều phối
6. Xác nhận lại thông tin với người gọi
7. Chuyển thông tin cho bộ phận điều xe
```

**Bottleneck:**
Bước 4 & 5 — Giao tiếp lặp lại và nhập tay thủ công mất từ 60 đến 120 giây, cực kỳ dễ sai lệch địa chỉ.

**Impact:**
Mất 60–180s/cuộc gọi cho hàng trăm ca mỗi ngày. 15% ca cấp cứu bị trễ xe do sai địa chỉ. Xe xuất phát chậm làm giảm tỷ lệ sống của nạn nhân (mỗi phút trễ giảm 7-10% cơ hội sống).

**Success metric:**
Rút ngắn thời gian tiếp nhận (AHT) từ 180 giây xuống < 30 giây; giảm tỷ lệ sai lệch địa chỉ xuống < 1%.

**Non-AI alternative:**
Bắt buộc người dân gọi qua App điền Form bấm sẵn vị trí GPS, nhưng thất bại vì người hoảng loạn hoặc lớn tuổi không thể mở App bấm thao tác trong lúc khẩn cấp.

**AI hypothesis:**
AI Real-time Speech-to-Text & Entity Extraction tự động chuyển giọng nói thành văn bản, tự bóc tách Vị trí & Triệu chứng điền thẳng vào form cho tổng đài viên bấm xác nhận.

**Quick gut:**
- [x] Agent

**Draft current workflow:**
```text
CURRENT STATE — 180 giây

[1 Bắt máy: 5']
→ [2 Hỏi vị trí: 30']
→ [3 Hỏi triệu chứng: 30']
→ [4 Giao tiếp lặp lại (hoảng loạn): 60']  <-- bottleneck
→ [5 Nhập tay phần mềm: 30']              <-- bottleneck
→ [6 Xác nhận lại: 20']
→ [7 Chuyển điều xe: 5']
```

**Draft future workflow:**
```text
FUTURE STATE — 25 giây

[1 Bắt máy + AI nghe song song: 3']
→ [2 AI Real-time STT & bóc tách Vị trí/Triệu chứng: 2']
→ [3 Auto-fill form trên màn hình Dispatcher: 0']
→ [4 Tổng đài viên review + bấm chốt: 15']  <-- human boundary
→ [5 Auto-chuyển lệnh xuất xe: 5']


Fallback: Giọng quá nhiễu / mất sóng → AI trả về luồng thoại truyền thống để tổng đài viên hỏi thủ công.
```

---

## Problem Card #2 — Emergency Triage Misclassification

**Problem 1 câu:**
Tổng đài viên đánh giá phân loại sai mức độ nguy kịch (Triage Fail) do cảm tính cá nhân, làm trễ các ca ngừng tuần hoàn/đột quỵ và gây lãng phí xe ICU cho ca nhẹ.

**Actor:**
Tổng đài viên tiếp nhận & Điều phối viên y tế.

**Thời điểm / bối cảnh:**
Ngay sau khi đã trích xuất xong thông tin ban đầu, trước khi phát lệnh chọn dòng xe cấp cứu (xe thường vs xe chuyên dụng ICU).

**Current workflow:**
```text
1. Đọc thông tin triệu chứng sơ bộ
2. Tự suy đoán mức độ nặng/nhẹ dựa trên kinh nghiệm cá nhân
3. Tra cứu sổ tay / bảng phân loại y khoa thủ công (nếu không nhớ)
4. Ra quyết định loại xe cần điều động (ICU hay xe cấp cứu thường)
5. Ghi chú lý do phân loại vào hệ thống
```

**Bottleneck:**
Bước 2 — Đánh giá định tính bằng cảm tính dẫn đến 10-15% số ca/tuần bị phân loại sai cấp độ ưu tiên.

**Impact:**
Các ca nặng bị trễ xe từ 8–12 phút vàng. Gây lãng phí tài nguyên xe chuyên dụng ICU cho các ca không thực sự nguy kịch.

**Success metric:**
Giảm tỷ lệ phân loại sai (Triage Error) từ 15% xuống < 2%; đảm bảo 100% ca ngừng tim/đột quỵ được cấp chỉ số ưu tiên tối cao trong < 5 giây.

**Non-AI alternative:**
Áp dụng cây quyết định tĩnh (If/Else Decision Tree Form) bắt nhập liệu từng bước, nhưng tốn 2-3 phút thao tác gây trễ giờ xuất xe.

**AI hypothesis:**
Clinical Decision AI Agent phân tích ngữ nghĩa lời thoại và âm thanh nhịp thở background để gợi ý thang điểm nguy kịch (Triage Score) và đề xuất dòng xe phù hợp tức thì.

**Quick gut:**
- [x] Workflow (+ Copilot)

**Draft current workflow:**
```text
CURRENT STATE — 180 giây

[1 Đọc triệu chứng: 15']
→ [2 Nhận định cảm tính: 60']  <-- bottleneck
→ [3 Tra cứu bảng chuẩn y khoa: 60']
→ [4 Chọn loại xe: 30']
→ [5 Ghi chú hệ thống: 15']
```

**Draft future workflow:**
```text
FUTURE STATE — 15 giây

[1 AI phân tích văn bản & âm thanh nhịp thở: 2']
→ [2 AI tính Triage Score & gợi ý loại xe: 1']
→ [3 Tổng đài viên review & bấm duyệt: 10']  <-- human boundary
→ [4 Điều xe xuất phát: 2']

Fallback: Trường hợp triệu chứng mơ hồ → Hệ thống tự động đẩy cảnh báo cần Bác sĩ trực ban tham vấn khẩn.
```

---

## Problem Card #3 — Unwitnessed Emergency Detection

**Problem 1 câu:**
Nạn nhân bị té ngã, đột quỵ hoặc tai nạn khi ở một mình không thể tự bấm gọi 115, dẫn đến thời gian phát hiện bị trễ từ 2 đến 12 giờ và bỏ lỡ hoàn toàn thời gian vàng cấp cứu.

**Actor:**
Nạn nhân (người già, người sống một mình) & Trung tâm tiếp nhận tín hiệu SOS.

**Thời điểm / bối cảnh:**
Khi nạn nhân gặp sự cố bất ngờ tại nhà hoặc nơi vắng vẻ mà không có ai xung quanh.

**Current workflow:**
```text
1. Nạn nhân gặp sự cố (té ngã/đột quỵ)
2. Bị ngất hoặc mất khả năng vận động/nói năng
3. Nằm chờ thụ động tại hiện trường
4. Người thân / hàng xóm phát hiện ra (sau nhiều giờ)
5. Người phát hiện gọi 115
6. Xe cấp cứu bắt đầu được điều động
```

**Bottleneck:**
Bước 3 — Nạn nhân hoàn toàn bất động và không thể phát tín hiệu, tạo ra khoảng trống thời gian chết từ 2 đến 12 giờ.

**Impact:**
20–30% người già sống đơn độc đối mặt rủi ro này. Tỷ lệ tử vong hoặc thương tật vĩnh viễn tăng mạnh do trễ thời gian vàng cấp cứu.

**Success metric:**
Rút ngắn thời gian phát hiện và gửi cảnh báo từ 2-12 giờ xuống < 60 giây. Tỷ lệ báo động giả (False Alarm) < 5%.

**Non-AI alternative:**
Trang bị nút bấm SOS vật lý trên tường hoặc đeo cổ, nhưng hoàn toàn vô hiệu khi nạn nhân bị ngất xỉu hoặc chấn thương sọ não.

**AI hypothesis:**
Spatial AI / Vision AI (qua Camera/Smartwatch) phân tích gia tốc và tư thế chuyển động bất thường để tự động kích hoạt đếm ngược SOS và phát thông tin vị trí về trung tâm cấp cứu.

**Quick gut:**
- [x] Agent (Autonomy)

**Draft current workflow:**
```text
CURRENT STATE — 4 đến 12 giờ

[1 Sự cố xảy ra: 0']
→ [2 Bất động / Ngất: 0']
→ [3 Nằm chờ thụ động: 4 - 12 giờ]  <-- bottleneck cực nặng
→ [4 Người khác phát hiện: 5']
→ [5 Gọi 115: 3']
→ [6 Điều xe: 5']
```

**Draft future workflow:**
```text
FUTURE STATE — 60 giây

[1 AI IoT/Wearable phát hiện va chạm/bất động: 2']
→ [2 Hệ thống đếm ngược 30s + rung báo động: 30']
→ [3 Người dùng không hủy → AI gửi GPS & Audio lên 115: 3']
→ [4 Tổng đài viên xác nhận call-back: 15']  <-- human boundary
→ [5 Tự động xuất xe: 10']

Fallback: Nếu mất kết nối Internet/GPS → Chuyển sang tự động gửi tin nhắn SMS SOS qua sóng di động GSM truyền thống kèm tọa độ CELL ID trạm phát sóng gần nhất.
```

---

### 2.3. Card muốn pitch nhất (chuẩn bị 2 phút)

**Card tôi muốn pitch nhất:**

```text
Problem Card #1 — Emergency Dispatch Input Bottleneck (Tổng đài 115: Xử lý thoại & trích xuất thông tin cuộc gọi khẩn cấp)
```

**Vì sao (2-3 câu: workflow gì, số đo gì, impact gì):**

```text
Bài toán tập trung vào điểm nghẽn trực tiếp nhất ở bước 4 & 5 trong quy trình 7 bước tiếp nhận 115 hiện tại, nơi tổng đài viên phải giao tiếp lặp lại 60-120 giây do người gọi hoảng loạn hoặc nói ngọng và gõ tay thông tin địa chỉ vào hệ thống.
Giải pháp AI Speech-to-Text & Entity Extraction hoạt động song song giúp tự động bóc tách vị trí/triệu chứng, cắt giảm thời gian tiếp nhận (AHT) từ 180 giây xuống < 30 giây và giảm tỷ lệ sai lệch địa chỉ xuống < 1%.
Tác động cực kỳ lớn và trực tiếp đến tính mạng con người vì mỗi phút trễ xe làm giảm 7-10% cơ hội sống của nạn nhân trong các ca ngừng tim/tai nạn nặng.
```

**Câu hỏi tôi muốn nhóm challenge (1-2 câu hỏi đúng chỗ yếu):**

```text
1. Làm thế nào để đảm bảo độ chính xác của AI Speech-to-Text khi người gọi hoảng loạn, thều thào, nói tiếng địa phương nặng hoặc môi trường xung quanh có nhiều tiếng ồn nhiễu lớn?
2. Nếu AI bóc tách sai thông tin địa chỉ mà tổng đài viên do áp lực thời gian bấm chốt nhanh không kịp phát hiện, rào cản kiểm soát rủi ro (Human boundary) cần được thiết kế như thế nào để ngăn chặn xe cấp cứu đi nhầm chỗ?
```

**AI phản biện Card (nếu có):**
- Điểm yếu AI chỉ ra: AI nhận định rằng việc kỳ vọng AI thay thế hoàn toàn giao tiếp thoại là bất khả thi do hạ tầng thoại 115 thường có chất lượng âm thanh kém và người dân hoảng loạn không nói tròn câu. Ngoài ra, rào cản tích hợp trực tiếp vào phần mềm Dispatch cũ của các Trung tâm 115 hiện nay rất cao.
- Tôi sửa gì: Chuyển vai trò AI từ "Auto-dispatch" sang "Co-pilot nghe song song": AI chỉ đóng vai trò lắng nghe bóc tách dữ liệu để gợi ý điền trước vào form (Auto-fill draft), bắt buộc phải có bước Tổng đài viên review + bấm chốt xác nhận (Human-in-the-loop boundary) trước khi phát lệnh điều xe.

### Self-check nộp phần 01
- [x] Có 5+ problems + top 3 Cards đủ field
- [x] Mỗi Card có workflow trước/sau + bottleneck + metric + fallback
- [x] Đã chọn 1 card pitch + câu hỏi challenge
