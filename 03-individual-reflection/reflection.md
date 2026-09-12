# 03 — Individual Reflection

> Viết bằng lời của bạn (Phase 7 trong `01-worksheet.md`). Có thể dùng AI gợi ý câu hỏi tự soi, không dùng AI viết thay. 8-12 câu, có chuyện cụ thể.

## Thông tin cá nhân

- Họ và tên: Nguyễn Đức Long
- Mã học viên: 2A202602917
- Nhóm: C2
- Candidate problem nhóm chọn: Lên kế hoạch di chuyển thông minh đa biến số (chuyến bay, giao thông real-time, thủ tục sân bay) bằng AI Agent linh hoạt cho sinh viên và người di chuyển xa không thường xuyên.

---

## 1. Tôi đã tham gia vào phần nào?

Ghi việc cụ thể + kết quả cụ thể. Không ghi chung chung kiểu "tham gia thảo luận".

| Hoạt động | Tôi đã làm gì? (việc cụ thể) | Kết quả / ảnh hưởng tới nhóm |
|---|---|---|
| Scan cá nhân | Scan 5 problems bối cảnh Cấp cứu 115 (nghẽn thoại, phân loại Triage, đột quỵ một mình). | Đưa 3 Problem Cards có số liệu AHT và tỷ lệ trễ xe vào ngân hàng ý tưởng nhóm. |
| Pitch Problem Card | Pitch bài toán "Xử lý thoại 115" với workflow 7 bước và điểm nghẽn 60-120s lặp lại. | Giúp nhóm hiểu bài toán có impact thực tế và cách đặt chốt duyệt con người (Human-in-the-loop). |
| Challenge bài của bạn khác | Phản biện bài toán di chuyển sân bay của Tiến về rủi ro trễ chuyến nếu tin hoàn toàn vào AI. | Giúp nhóm điều chỉnh metric từ "0% rủi ro" sang "độ an toàn ≥ 95%" và thêm chốt an toàn. |
| Gom trùng / cluster | Cùng nhóm gom 18 bài toán thành 4 cụm (Phòng trọ, Ngoại ngữ, Y tế, Dev Tool). | Chọn ra shortlist 3 bài tốt nhất để chấm điểm. |
| Chọn candidate problem | Chấm điểm bài di chuyển sân bay (32/35 điểm) và chốt chọn làm đề tài nhóm. | Đạt sự đồng thuận cao nhờ bài toán có workflow rõ ràng và dễ pilot. |
| Validation / research | Chủ trì phỏng vấn 3 người và nghiên cứu các app di chuyển hiện có. | Tìm ra insight: người dùng căng thẳng vì biến số bất ngờ; mở ra ranh giới cho AI Agent. |
| Rule / Workflow / Agent | Cùng bạn nghiên cứu và trả lời 5 câu hỏi phân loại R/W/A. | Thuyết phục nhóm dùng AI Agent linh hoạt kết hợp chốt duyệt con người thay vì Rule tĩnh. |


**Dấu tay rõ nhất của tôi trong artifact cuối (1-2 câu):**

```text
Cùng viết giải thích lập luận chọn kiến trúc Agent thay vì Rule/Workflow đơn giản và chốt bộ chỉ số đo lường thực tế.
```

---

## 2. Bảng dùng AI (mỗi dòng 1 phase có dùng AI — 2 cột cuối bắt buộc)

| Phase | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai / hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| Scan | Gợi ý thêm góc nhìn problem cho tổng đài 115. | Gợi ý góc nhìn "Bác sĩ thiếu tiền sử bệnh lý". | Đề xuất ý tưởng viễn tưởng như "AI tự chỉ đường xe cấp cứu". | Bỏ ý viễn tưởng, giữ bài toán thực tế nghẽn thoại 115 kèm số liệu AHT. |
| Problem Card | Phản biện 3 Problem Cards để tìm điểm yếu workflow. | Chỉ ra AI Speech-to-Text dễ sai khi giọng bị nhiễu hoặc hoảng loạn. | Nhận định hời hợt là "tự động hóa 100% không cần con người". | Giữ vai trò AI làm Co-pilot gợi ý, bắt buộc con người bấm chốt duyệt. |
| Workflow | Vẽ sơ đồ workflow trước/sau dạng ASCII. | Format khung [1 ...] → [2 ...] gọn và đẹp. | Gán thời gian xử lý của AI bằng 0s không thực tế. | Sửa thời gian gọi API thành 1-2s và thêm bước con người kiểm tra. |
| Research | Tìm thông tin app quản lý lịch trình (TripIt, FlightAware). | Cung cấp nhanh tính năng chính của các app hiện có. | Đưa link bị hỏng và số liệu không rõ nguồn. | Tự vào trang chủ đối soát lại tính năng để viết takeaway chính xác. |
| Problem Statement | Tham khảo cách viết Boundary và điểm can thiệp AI. | Gợi ý câu từ chuẩn cho phần ranh giới "Làm / Không làm". | Đưa metric chung chung kiểu "tối ưu 100%". | Sửa thành chỉ số đo được: thời gian < 10 phút, độ an toàn ≥ 95%. |
| Rule / Workflow / Agent | So sánh Workflow tĩnh và AI Agent khi có biến số. | Phân tích rõ vì sao Rule tĩnh không xử lý được kẹt xe, delay bay. | AI suýt thuyết phục nhóm chọn Agent tự động hoàn toàn. | Giữ quan điểm làm Agent kết hợp con người duyệt để tránh rủi ro trễ chuyến. |
| Decision | Gợi ý checklist câu hỏi Go / Not Yet / No-Go. | Đưa khung tiêu chuẩn tự kiểm trước khi Pilot. | Đưa kế hoạch Pilot quá cồng kềnh, khó làm ngay. | Thu hẹp Pilot xuống dạng thử nghiệm trên 5-10 chuyến bay thật của sinh viên. |

> Nếu phase nào không dùng AI, ghi `Không dùng` và vì sao tự làm.

---

## 3. Reflection câu hỏi mở

Chọn 3-4 câu trong 6 câu dưới để viết thành đoạn 8-12 câu (không trả lời bullet 1 dòng):
- Tôi học được gì khi nghe top 3 problems của các bạn khác?
- Nhóm có lúc nào bị solution-first, đòi làm Agent cho ngầu không?
- Tôi có thay đổi ý kiến sau khi bị challenge không, vì sao đổi?
- Tôi đóng góp gì thật sự vào artifact cuối, phần nào có dấu tay của tôi?
- Điều khó nhất khi viết Problem Statement là gì, metric hay boundary?
- Nếu làm lại, tôi sẽ challenge nhóm mạnh hơn ở điểm nào?

**Reflection:**

```text
Mỗi người có một suy nghĩ sáng tạo khác nhau và ra nhiều problem lạ. Với 1 vài chủ đề nhóm có đòi làm agent có vẻ over-kill so với bài toán, nhưng đã được nhóm thảo luận kết luận không phù hợp. Tôi không đổi ý kiến mà tinh chỉnh 1 vài điểm cho phù hợp khi challenge. Tôi có đóng góp vào so sánh rule/workflow/agent và cùng viết sơ đồ cho artifact.Khó nhất khi viết problem statement là boundary, challenge mạnh ở điểm lợi ích/chi phí có thực sự hiểu quả
```

---

## 4. Tự kiểm cuối bài (check trước khi nộp repo)

- [x] [12đ] Cá nhân có 5+ problems + top 3 Problem Cards
- [x] [12đ] Tôi đã pitch rõ + challenge nhóm đúng trọng tâm (ghi ở bảng mục 1)
- [x] Nhóm có nhật ký hội tụ từ candidates về 1 bài
- [x] [15đ] Nhóm có workflow trước/sau
- [x] [20đ] Nhóm có PS v0/v1 với metric + boundary rõ
- [x] [15đ] Nhóm có so sánh No AI / Rule / Workflow / Agent
- [x] [10đ] Nhóm có Go / Not Yet / No-Go + lý do rõ
- [x] [10đ] Reflection này có vai trò thật + AI giúp/sai ở đâu + điều học được + nếu làm lại đổi gì
- [x] [6đ] Tôi tự giải thích được mạch problem → workflow → metric → boundary → độ phù hợp AI



