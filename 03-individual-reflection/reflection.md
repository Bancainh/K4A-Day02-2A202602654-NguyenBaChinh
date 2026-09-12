# 03 — Individual Reflection

> Viết bằng lời của bạn (Phase 7 trong `01-worksheet.md`). Có thể dùng AI gợi ý câu hỏi tự soi, không dùng AI viết thay. 8-12 câu, có chuyện cụ thể.

## Thông tin cá nhân

- Họ và tên: Nguyễn Bá Chính
- Mã học viên: 2A202602654
- Nhóm: 3 zone A 
- Candidate problem nhóm chọn: AI IELTS Speaking Coach

---

## 1. Tôi đã tham gia vào phần nào?

Ghi việc cụ thể + kết quả cụ thể. Không ghi chung chung kiểu "tham gia thảo luận".

| Hoạt động | Tôi đã làm gì? (việc cụ thể) | Kết quả / ảnh hưởng tới nhóm |
|---|---|---|
| Scan cá nhân | Tìm ra 3 bài toán từ kinh nghiệm học Khoa học Dữ liệu và luyện thuật toán (Tiền xử lý Data bằng Pandas, Dò lỗi LeetCode, AI Hallucination). | Góp vào pool 12 bài toán của nhóm những use-case rất đậm tính kỹ thuật và logic. |
| Pitch Problem Card | Pitch mạnh bài "Code tiền xử lý dữ liệu Data" vì workflow 5 bước quá rõ ràng và thời gian đo lường cụ thể (từ 45p xuống 10p). | Nhóm hiểu rõ cách cấu trúc một bài toán có metric định lượng tốt. |
| Challenge bài của bạn khác | Phản biện bài "Tính macro & Lên danh sách đi chợ" của Hòa. | Giúp nhóm nhận ra rủi ro AI bịa đặt số liệu toán học, từ đó không chọn bài này làm candidate cuối cùng. |
| Gom trùng / cluster | Gợi ý gom bài tìm Research gap của Trâm Anh và phần Check đạo văn vào cụm "Nghiên cứu học thuật". | Giúp nhóm phân loại nhanh 12 ý tưởng thành 4 cụm rành mạch trong chưa đầy 10 phút. |
| Chọn candidate problem | Thay vì cố chấp bảo vệ bài Data của mình, tôi đổi ý vote 5 điểm cho bài IELTS Speaking của Hòa. | Giúp nhóm đạt đồng thuận nhanh chóng, chọn được bài toán có actor, workflow và metric rõ. |
| Validation / research | Trực tiếp phỏng vấn 2 bạn sinh viên đang tự ôn IELTS. | Đem về 2 câu quote nguyên văn để làm bằng chứng cho điểm nghẽn "không biết sai grammar ở đâu". |
| Workflow nhóm | Đề xuất thêm bước "Fallback" vào Future Workflow. | Giúp quy trình có phương án xử lý khi Speech-to-Text nghe nhầm do tiếng ồn. |
| Problem Statement | Trực tiếp gọt giũa phần "Bottleneck" và "Boundary" ở bản v0 và v1. | Làm rõ ranh giới: AI chỉ hỗ trợ phân tích và gợi ý; người học vẫn phải tự sửa và nói lại. |
| Rule / Workflow / Agent | Tranh luận bảo vệ việc chọn Workflow thay vì Agent. | Giúp nhóm tránh mở scope thành một Agent đối thoại tự chủ khi pilot chưa có bằng chứng cần thiết. |
| Decision | Lên kịch bản chi tiết cho phần "Pilot nhỏ nhất". | Chốt được 3 metric cần đo nếu nhóm triển khai thử nghiệm: feedback latency, actionable feedback và tỷ lệ transcript sai. |

**Dấu tay rõ nhất của tôi trong artifact cuối (1-2 câu):**

```text
Dấu tay rõ nhất của tôi nằm ở phần workflow và boundary. Tôi đề xuất fallback khi Speech-to-Text sai, đồng thời góp phần gọt lại Problem Statement để AI chỉ hỗ trợ phân tích, còn người học phải tự kiểm tra, sửa và nói lại; đây cũng là cơ sở để nhóm chọn Workflow thay vì Agent cho pilot.
```

---

## 2. Bảng dùng AI (mỗi dòng 1 phase có dùng AI — 2 cột cuối bắt buộc)

| Phase | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai / hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| Scan | Dùng AI để gợi ý 8-10 vấn đề bám theo 5 công việc hằng tuần của tôi. | AI giúp tách các công việc lớn thành bottleneck cụ thể, có thể đo bằng thời gian hoặc tần suất. | Một số gợi ý ban đầu quá rộng, như "học tập điều mới" hoặc "sống hiệu quả", chưa phải workflow có pain rõ. | Tôi loại các ý tưởng mang tính mục tiêu phát triển bản thân và giữ lại các vấn đề có actor, workflow và số đo cụ thể. |
| Problem Card | Dùng AI để phản biện Card #3 về AI Hallucination. | AI chỉ ra boundary cuối còn lỏng nếu Agent đưa nguồn hoặc trích dẫn sai. | AI không tự giải quyết được bài toán kiểm chứng nguồn; dùng một AI để kiểm tra AI vẫn có nguy cơ tạo thành vòng lặp sai. | Tôi bổ sung yêu cầu Agent phải trích dẫn đúng dòng tài liệu gốc kèm link trực tiếp để con người kiểm tra nhanh. |
| Workflow | Không dùng AI để viết workflow cuối; tôi tự xây dựa trên bottleneck và thảo luận nhóm. | Tự làm giúp tôi giữ rõ human boundary và fallback thay vì đẩy thêm tự động hóa chỉ vì "có thể dùng AI". | — | Tôi chủ động thêm fallback cho lỗi Speech-to-Text và giữ bước người học review, sửa rồi nói lại. |
| Research | Không dùng AI làm nguồn kết luận chính; tôi dựa vào các nguồn/tool đã được nhóm ghi nhận và kiểm tra trong research. | Cách này giúp phân biệt rõ điều đã có bằng chứng với giả định cần validate thêm. | — | Tôi giữ kết luận ở mức nhóm đã xác nhận: không build AI scorer đơn thuần mà tập trung recurring-error tracking, personalized feedback và adaptive practice. |
| Problem Statement | Dùng AI để phản biện Problem Statement v0. | AI giúp chỉ ra các điểm mơ hồ như "cải thiện Speaking" quá chung và boundary về Pronunciation quá rộng. | AI không thể thay nhóm quyết định metric phù hợp hoặc xác nhận độ chính xác band score. | Tôi cùng nhóm bỏ metric "AI chấm band chính xác", thu hẹp AI vào vocabulary, grammar, fluency/coherence và dùng feedback latency + actionable feedback làm metric chính. |
| Rule / Workflow / Agent | Không dùng AI để quyết định thay nhóm; tôi tham gia tranh luận dựa trên workflow thực tế. | Việc tự so sánh No AI / Rule / Workflow / Agent giúp nhìn rõ mức tự động hóa cần thiết. | — | Tôi bảo vệ phương án Workflow kết hợp Rule vì pipeline đã cố định, dễ đo và dễ đặt human boundary; chưa cần Agent. |
| Decision | Không dùng AI để chốt Go/No-Go; nhóm tự đối chiếu evidence, metric, risk và khả năng pilot. | Cách này tránh để công nghệ quyết định trước khi problem và workflow đủ rõ. | — | Tôi cụ thể hóa pilot 3 người và 3 metric: feedback latency, số actionable feedback và tỷ lệ transcript sai. |

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
Ban đầu tôi khá tin vào bài toán tiền xử lý dữ liệu vì workflow rất rõ và tôi đo được thời gian từ khoảng 45 phút xuống còn 10 phút. Tuy nhiên, khi nghe các candidate khác, đặc biệt AI IELTS Speaking Coach, tôi nhận ra một problem tốt không chỉ dễ đo mà còn phải có pain thật và khoảng trống mà các công cụ hiện tại chưa giải quyết tốt. Vì vậy tôi đổi vote sang bài IELTS Speaking của Hòa thay vì cố bảo vệ ý tưởng của mình. Qua quá trình validation, tôi cũng hiểu rằng pain chính không phải thiếu câu hỏi luyện Speaking mà là người học không biết lỗi nào đang lặp lại và nên sửa lỗi nào trước. Phần tôi đóng góp rõ nhất vào artifact cuối là workflow, fallback và boundary, nhất là việc giữ người học ở vị trí kiểm duyệt transcript và quyết định feedback nào được áp dụng. Khi nhóm thảo luận Rule, Workflow hay Agent, tôi thấy rất rõ nguy cơ solution-first: Agent nghe có vẻ "xịn" nhưng lại làm scope rộng, khó kiểm soát và chưa cần thiết cho pilot. Điều khó nhất khi viết Problem Statement không phải chỉ là metric, mà là đặt boundary đủ chặt để AI hỗ trợ đúng chỗ mà không giả vờ thay thế giáo viên hay examiner. Việc dùng AI trong quá trình làm cũng cho tôi một bài học quan trọng: AI rất tốt để gợi ý và phản biện, nhưng những kết luận cuối cùng vẫn phải quay về evidence, workflow và giới hạn thực tế. Nếu làm lại, tôi sẽ challenge nhóm mạnh hơn ngay từ đầu về chất lượng feedback và cách xác minh feedback sai, thay vì chỉ tập trung vào việc AI có thể làm được gì. Sau bài này, tôi hiểu rõ hơn mạch problem → workflow → metric → boundary → độ phù hợp AI, và tôi sẽ ưu tiên giải quyết bottleneck thật trước khi nghĩ đến việc dùng công nghệ phức tạp hơn.
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
