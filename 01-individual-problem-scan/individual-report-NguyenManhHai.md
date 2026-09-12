# 01 — Individual Problem Scan

> Điền theo Phase 1 + Phase 2 trong `01-worksheet.md`. Tự scan trước, dùng AI sau để phản biện. Không copy ví dụ Weekly Report.

## Thông tin cá nhân

- Họ và tên: Nguyễn Mạnh Hải
- Mã học viên: 2A202602988
- Vai trò / bối cảnh (VD: sinh viên năm X, intern PM, ...): Sinh viên mới tốt nghiệp đại học
- Công việc hằng tuần (3-5 gạch đầu dòng để soi problem):

---

## Phase 1 — Scan 5+ problems (tối thiểu 5, khuyến khích 8-10)

**Cách điền:** mỗi dòng = việc gì + ai chịu + đo bằng gì. Cột `Dấu hiệu thật` bắt buộc có số: mất bao lâu (bấm giờ mấy lần), mấy lần/tuần, bao nhiêu người gặp, log/ticket/quote nào.

| # | Lăng kính (Lặp lại / Tốn thời gian / AI có thể tốt hơn / Pain từ người khác) | Problem quan sát được | Ai chịu ảnh hưởng? | Dấu hiệu thật (số + bằng chứng) |
|---|---|---|---|---|
| 1 | Tốn thời gian | Bên nhân sự tổng hợp số lượng nhân sự đi làm trong một tháng của cả công ty rồi viết báo cáo| HR | HR mất 30 phút để tổng hợp thông tin, xử lí số liệu + 15 phút viết báo cáo|
| 2 | Tốn thời gian | Các công việc hành chính, ngoài lề liên quan đến lĩnh vực giáo dục (Chấm điểm, điểm danh, tạo slide bài giảng, trả lời thắc mắc của học sinh,...)| Giáo viên | Trung bình, giáo viên cho biết họ làm việc nhiều hơn 15 giờ mỗi tuần so với quy định trong hợp đồng (rand.org)|
| 3 | Pain từ người khác | Ghi biên bản họp & theo dõi action item thủ công, PM/BA phải note tay rồi nhắc lại từng người, dễ sót việc | PM, BA, team member | Tổng hợp 1 người note và highlight mất 10-20 phút, tổng hợp thành 1 bản meeting minute hoàn chỉnh mất 10 phút |
| 4 | AI có thể tốt hơn | Nhân viên tín dụng thẩm định hồ sơ vay thủ công: thu thập giấy tờ, đối chiếu, chấm điểm rủi ro |chuyên viên thẩm định tín dụng| quy trình thẩm định vay SME thủ công thường mất vài ngày đến 2–3 tuần để tổng hợp, xử lí dữ liệu vay  |
| 5 | AI có thể tốt hơn | Luật sư rà soát hợp đồng (NDA, hợp đồng thương mại) thủ công để tìm điều khoản rủi ro | luật sư | luật sư mất trung bình 92 phút để review 1 bản NDA với độ chính xác trung bình 85% |
| 6 | | | | |
| 7 | | | | |
| 8 | | | | |
| 9 | | | | |
| 10 | | | | |

> Gợi ý tự soi: tuần trước mất nhiều thời gian nhất vào việc gì? Việc gì hay trì hoãn? Người khác hay hỏi lại câu gì? Workflow nào ai cũng biết là chậm?

**AI đã dùng ở Phase 1 (nếu có):**
- Prompt đã hỏi: Tôi là AI Engineer. Tôi đang tìm kiếm các bài toán, pain point vận hành cụ thể có thể tối ưu bằng AI cho mảng báo cáo năng suất, quy trình báo cáo, quy trình quản trị dự án về lĩnh vực như IT project management, giáo dục, giao thông,... Hãy gợi ý cho tôi 5 quy trình nghiệp vụ thủ công, tốn nhiều thời gian và gây rò rỉ hiệu suất kèm con số thống kê ước tính về tổn thất
- Ý dùng được: Các ý trong problem scan
- Ý bỏ vì không phải pain thật: Các ý liên quan tới điều khiển giao thông do painpoint còn mơ hồ.

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
| 1 | Luật sư rà soát hợp đồng (NDA) tìm điều khoản rủi ro thủ công | Actor rõ + bottleneck 1 bước (đọc/đối chiếu điều khoản) | Đa phần kết quả đo lấy từ nghiên cứu ngoài (LawGeex), chưa phải số đo tại nơi quan sát thực tế của mình |
| 2 | Chuyên viên tín dụng thẩm định hồ sơ vay SME thủ công | Actor cụ thể; impact tài chính trực tiếp và lớn (vài ngày-3 tuần chờ duyệt ảnh hưởng dòng tiền khách vay); workflow tách được 3-7 bước rõ ràng | Chưa chắc có tiếp cận/quan sát trực tiếp quy trình này để vẽ workflow và phỏng vấn thật cho Phase 2 |
| 3 | Ghi biên bản họp & theo dõi action item thủ công | Actor cụ thể (PM/BA); số đo tự bấm giờ đáng tin (10-20 phút note + 10 phút tổng hợp); bottleneck rõ ở bước chuyển note thô sang bản minute hoàn chỉnh | Impact hiện còn thấp (~30 phút/cuộc họp) so với 2 case trên; cần làm rõ tần suất họp/tuần và hậu quả khi sót action item |

### 2.2. Problem Cards chi tiết (lặp lại cho cả 3 cards)

---

#### Problem Card #1 — Luật sư rà soát hợp đồng NDA tìm điều khoản rủi ro thủ công

```text
Problem 1 câu:
Luật sư mất nhiều thời gian đọc và đối chiếu thủ công từng điều khoản trong hợp đồng NDA để tìm rủi ro pháp lý, dễ bỏ sót do giới hạn về sự chú ý và khối lượng hợp đồng lớn.

Actor:
Luật sư / paralegal tại bộ phận pháp chế doanh nghiệp (in-house legal) hoặc law firm.

Thời điểm / bối cảnh:
Khi đối tác/khách hàng gửi NDA hoặc hợp đồng thương mại cần rà soát trước khi ký, thường có deadline gấp trước một cuộc họp hoặc thương vụ (deal).

Current workflow 3-7 bước:
1. Nhận file hợp đồng từ đối tác qua email
2. Đọc toàn bộ văn bản để nắm ngữ cảnh
3. Đối chiếu từng điều khoản với checklist rủi ro chuẩn (bảo mật, phạt vi phạm, thời hạn, luật áp dụng, giới hạn trách nhiệm...)
4. Đánh dấu (highlight/comment) các điều khoản bất lợi hoặc còn thiếu
5. Soạn bản redline/phản hồi gửi lại bên soạn thảo hoặc trình cấp trên duyệt
6. Chờ phản hồi, có thể lặp lại vòng đàm phán điều khoản
7. Ký kết sau khi hai bên thống nhất

Bottleneck:
Bước 3 — đối chiếu từng điều khoản với checklist rủi ro thủ công: tốn nhiều thời gian nhất và dễ bỏ sót khi luật sư phải xử lý nhiều hợp đồng cùng lúc.

Impact:
Trung bình 92 phút/hợp đồng, độ chính xác chỉ ~85% (nghiên cứu LawGeex) — tức khoảng 15% điều khoản rủi ro có thể bị bỏ sót. Với khối lượng hợp đồng lớn, tổng thời gian rà soát và rủi ro pháp lý tích lũy đáng kể; một điều khoản bị bỏ sót có thể dẫn đến tranh chấp hoặc thiệt hại tài chính về sau.

Success metric:
Giảm thời gian rà soát trung bình xuống dưới 30 phút/hợp đồng và tăng tỷ lệ phát hiện điều khoản rủi ro lên trên 95%, đo bằng số điều khoản rủi ro bị bỏ sót khi kiểm tra chéo với bản do luật sư senior rà soát độc lập.

Non-AI alternative:
Chuẩn hóa checklist rủi ro dùng chung cho cả team, đào tạo thêm nhân sự, hoặc thuê thêm paralegal để tăng số người review song song — chỉ tăng throughput chứ không cải thiện được độ chính xác vốn giới hạn bởi khả năng chú ý của con người.

AI hypothesis:
Dùng AI (LLM contract-review) quét toàn bộ hợp đồng, so khớp với checklist rủi ro/điều khoản chuẩn, tự động gắn cờ và giải thích các điều khoản bất thường hoặc còn thiếu. Luật sư chỉ cần tập trung review các điểm được AI đánh dấu thay vì đọc toàn văn bản từ đầu, rút ngắn đáng kể thời gian rà soát mà vẫn giữ người ra quyết định cuối cùng.

Quick gut:
[ ] No AI / process fix
[ ] Rule
[x] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #1** (ASCII / Mermaid / ảnh đính kèm):

```text
CURRENT STATE — 92 phút

[1 Nhận & đọc hợp đồng: 15'] → [2 Đối chiếu checklist rủi ro: 50'] → [3 Đánh dấu điều khoản: 15'] → [4 Soạn phản hồi: 12']  <-- bottleneck (bước 2)

FUTURE STATE — ~25 phút

[1 AI quét & gắn cờ rủi ro: 2'] → [2 Luật sư review điểm được gắn cờ: 15'] → [3 Luật sư duyệt & soạn phản hồi review: 8']  <-- human boundary (luật sư luôn quyết định cuối)

Fallback: nếu AI bỏ sót hoặc gắn cờ sai (false negative/positive), luật sư vẫn đọc lướt toàn văn bản như bước kiểm tra chéo cuối; hợp đồng có giá trị/rủi ro cao bắt buộc review thủ công đầy đủ trước khi ký.
```

File đính kèm (nếu vẽ riêng): `01-individual-problem-scan-workflow-card-1.png`

---

#### Problem Card #2 — Chuyên viên tín dụng thẩm định hồ sơ vay SME thủ công

```text
Problem 1 câu:
Chuyên viên tín dụng phải thu thập, đối chiếu và chấm điểm rủi ro cho từng hồ sơ vay của doanh nghiệp vừa và nhỏ hoàn toàn bằng tay, khiến quá trình duyệt vay kéo dài và mức độ đánh giá rủi ro không đồng đều giữa các hồ sơ.

Actor:
Chuyên viên thẩm định tín dụng tại ngân hàng/tổ chức tài chính, phụ trách hồ sơ vay của khách hàng doanh nghiệp SME.

Thời điểm / bối cảnh:
Khi doanh nghiệp nộp hồ sơ xin vay vốn lưu động hoặc đầu tư và cần được thẩm định trước khi giải ngân; khách hàng thường cần vốn gấp để kịp cơ hội kinh doanh nên áp lực về thời gian xử lý khá lớn.

Current workflow 3-7 bước:
1. Tiếp nhận hồ sơ vay cùng các giấy tờ pháp lý, tài chính từ khách hàng
2. Kiểm tra tính đầy đủ và hợp lệ của giấy tờ (đăng ký kinh doanh, báo cáo tài chính, sao kê ngân hàng...)
3. Đối chiếu thông tin trong hồ sơ với dữ liệu tín dụng và lịch sử vay của khách hàng
4. Phân tích tài chính, tính các chỉ số rủi ro (dòng tiền, đòn bẩy, khả năng trả nợ)
5. Chấm điểm tín dụng và soạn báo cáo thẩm định
6. Trình cấp có thẩm quyền phê duyệt
7. Thông báo kết quả và giải ngân nếu hồ sơ được duyệt

Bottleneck:
Cụm bước 3-4 — đối chiếu dữ liệu và phân tích tài chính thủ công: tốn nhiều thời gian nhất vì phải tổng hợp dữ liệu từ nhiều nguồn khác nhau rồi tính toán bằng tay hoặc Excel.

Impact:
Cả quy trình thường mất từ vài ngày đến 2-3 tuần cho một hồ sơ SME. Doanh nghiệp chờ vốn lâu có thể lỡ mất cơ hội kinh doanh, còn ngân hàng cũng có nguy cơ mất khách vào tay đối thủ xử lý nhanh hơn.

Success metric:
Rút ngắn thời gian thẩm định trung bình xuống còn 1-2 ngày cho hồ sơ đơn giản, trong khi vẫn giữ nguyên hoặc cải thiện tỷ lệ nợ xấu — tức không đánh đổi tốc độ lấy rủi ro.

Non-AI alternative:
Tuyển thêm nhân sự thẩm định hoặc đơn giản hóa checklist hồ sơ. Cách này chỉ giải quyết được phần throughput (xử lý được nhiều hồ sơ hơn cùng lúc), chứ không cải thiện được tốc độ phân tích tài chính hay tính nhất quán trong chấm điểm rủi ro.

AI hypothesis:
Dùng AI để tự động trích xuất dữ liệu từ giấy tờ (OCR kết hợp NLP), đối chiếu chéo với dữ liệu tín dụng sẵn có, và đưa ra điểm rủi ro sơ bộ kèm giải thích. Chuyên viên tín dụng khi đó chỉ cần rà soát lại kết quả và đưa ra quyết định cuối cùng, thay vì tự tay tổng hợp và tính toán từ đầu.

Quick gut:
[ ] No AI / process fix
[ ] Rule
[x] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #2:**

```text
CURRENT STATE — ước tính ~10 ngày làm việc

[1 Tiếp nhận & kiểm tra hồ sơ: 1 ngày] → [2 Đối chiếu dữ liệu tín dụng: 3 ngày] → [3 Phân tích tài chính & chấm điểm: 4 ngày] → [4 Trình duyệt: 2 ngày]  <-- bottleneck (bước 2-3)

FUTURE STATE — ước tính ~3 ngày

[1 AI trích xuất & đối chiếu dữ liệu tự động: 0,5 ngày] → [2 AI đề xuất điểm rủi ro sơ bộ: 0,5 ngày] → [3 Chuyên viên rà soát & trình duyệt: 2 ngày]  <-- human boundary (quyết định cho vay luôn do người ký duyệt)

Fallback: nếu điểm rủi ro AI đưa ra không khớp với đánh giá định tính của chuyên viên, hồ sơ được chuyển sang quy trình thẩm định thủ công đầy đủ như hiện tại, đặc biệt với các khoản vay giá trị lớn hoặc hồ sơ có dấu hiệu bất thường.
```

File đính kèm: `01-individual-problem-scan-workflow-card-2.png`

---

#### Problem Card #3 — Ghi biên bản họp & theo dõi action item thủ công

```text
Problem 1 câu:
PM/BA phải tự tay ghi chép nội dung cuộc họp, sau đó tổng hợp lại thành biên bản và nhắc từng người thực hiện action item, dễ bỏ sót việc vì toàn bộ quá trình làm thủ công.

Actor:
Project Manager hoặc Business Analyst chịu trách nhiệm điều phối cuộc họp và theo dõi tiến độ công việc sau họp.

Thời điểm / bối cảnh:
Sau mỗi cuộc họp dự án (họp sprint, họp với khách hàng, họp nội bộ team), cần chốt lại nội dung đã thống nhất và phân công việc rõ ràng cho từng người.

Current workflow 3-7 bước:
1. Tham gia họp và ghi chú thủ công các điểm quan trọng, quyết định, việc cần làm
2. Highlight lại các action item và người phụ trách ngay trong lúc họp hoặc ngay sau đó
3. Tổng hợp note thô thành bản meeting minutes hoàn chỉnh, rõ ràng
4. Gửi biên bản cho các bên liên quan để xác nhận
5. Theo dõi tiến độ action item, chủ động nhắc từng người nếu chưa hoàn thành

Bottleneck:
Bước 3 (tổng hợp note thô thành biên bản hoàn chỉnh) và bước 5 (theo dõi, nhắc việc rải rác sau họp) — tốn thời gian và dễ bỏ sót action item nếu không ghi chú đủ kỹ ngay từ đầu.

Impact:
Trung bình mỗi cuộc họp tốn 10-20 phút để ghi note/highlight và thêm khoảng 10 phút để tổng hợp thành biên bản hoàn chỉnh. Với tần suất họp dày (vài cuộc/tuần), thời gian này cộng dồn khá lớn, chưa kể chi phí cơ hội khi action item bị quên khiến dự án trễ deadline.

Success metric:
Giảm thời gian tổng hợp biên bản xuống gần như bằng 0 (có ngay sau khi họp kết thúc), đồng thời tỷ lệ action item bị bỏ sót hoặc trễ hạn giảm rõ rệt so với hiện tại.

Non-AI alternative:
Dùng template biên bản họp và checklist action item chuẩn để giảm thời gian soạn thảo. Cách này chỉ giúp thống nhất hình thức trình bày, chứ không giải quyết được việc ghi chép trong họp và nhắc việc sau họp vẫn phải làm thủ công.

AI hypothesis:
Dùng AI ghi âm và tóm tắt cuộc họp tự động (speech-to-text kết hợp summarization), tự động trích xuất action item kèm người phụ trách và deadline, sau đó tự động gửi nhắc nhở định kỳ cho từng người. PM/BA chỉ cần rà soát lại bản tóm tắt AI tạo ra trước khi gửi chính thức cho các bên liên quan.

Quick gut:
[ ] No AI / process fix
[ ] Rule
[ ] Workflow
[x] Agent
[ ] Chưa biết
```

**Draft workflow Card #3:**

```text
CURRENT STATE — ~30 phút/cuộc họp (chưa tính thời gian nhắc việc rải rác về sau)

[1 Ghi note trong họp: 15'] → [2 Tổng hợp thành biên bản: 10'] → [3 Gửi & theo dõi action item: 5'+]  <-- bottleneck (bước 2 và việc nhắc việc rải rác sau đó)

FUTURE STATE — ~5 phút

[1 AI ghi âm & tóm tắt tự động: 0'] → [2 PM/BA rà soát bản tóm tắt & action item: 5'] → [3 AI tự động gửi nhắc nhở định kỳ]  <-- human boundary (PM/BA luôn duyệt nội dung trước khi gửi chính thức)

Fallback: nếu AI tóm tắt sai hoặc bỏ sót action item quan trọng, PM/BA vẫn giữ note tay của riêng mình trong cuộc họp để đối chiếu, và có thể chỉnh sửa trực tiếp bản tóm tắt trước khi gửi cho các bên liên quan.
```

File đính kèm: `01-individual-problem-scan-workflow-card-3.png`

---

### 2.3. Card muốn pitch nhất (chuẩn bị 2 phút)

**Card tôi muốn pitch nhất:**

```text
Problem Card #1 — Luật sư rà soát hợp đồng NDA tìm điều khoản rủi ro thủ công
```

**Vì sao (2-3 câu: workflow gì, số đo gì, impact gì):**

```text
 Theo nghiên cứu luật sư mất trung bình 92 phút để rà soát một bản NDA nhưng độ chính xác chỉ đạt khoảng 85%, nghĩa là gần một phần sáu số điều khoản rủi ro có thể bị bỏ sót dù đã bỏ ra nhiều thời gian. Workflow hiện tại có bottleneck rất cụ thể ở bước đối chiếu từng điều khoản với checklist rủi ro, và đây cũng chính là bước mà nghiên cứu bên ngoài (LawGeex) đã chứng minh AI có thể làm nhanh hơn (26 giây) lẫn chính xác hơn (94%) con người. Impact ở đây không chỉ dừng ở việc tiết kiệm thời gian mà còn giảm rủi ro pháp lý thật sự cho doanh nghiệp, nên đây là câu chuyện dễ thuyết phục người nghe hơn hai case còn lại.
```

**Câu hỏi tôi muốn nhóm challenge (1-2 câu hỏi đúng chỗ yếu):**

```text
Số liệu 92 phút và 85% chính xác mình đang lấy từ nghiên cứu LawGeex (dữ liệu nước ngoài, năm 2018) — liệu có áp dụng được cho bối cảnh pháp lý và loại hợp đồng ở Việt Nam không, hay cần tự đo lại từ đầu để đáng tin hơn?
Nếu AI bỏ sót một điều khoản rủi ro quan trọng (false negative) trong một hợp đồng giá trị lớn, ai là người chịu trách nhiệm pháp lý cuối cùng, và quy trình fallback hiện tại (luật sư đọc lướt lại toàn văn bản) đã đủ chặt để tránh rủi ro đó chưa? Bộ test trong LawGeex chưa đa dạng, vậy AI có thể đạt được độ chính xác khi áp dụng bộ dữ liệu rộng hơn không?
```

**AI phản biện Card (nếu có):**
- Điểm yếu AI chỉ ra:
- Tôi sửa gì:

### Self-check nộp phần 01
- [x] Có 5+ problems + top 3 Cards đủ field
- [x] Mỗi Card có workflow trước/sau + bottleneck + metric + fallback
- [x] Đã chọn 1 card pitch + câu hỏi challenge
