# 01 — Individual Problem Scan

> Điền theo Phase 1 + Phase 2 trong `01-worksheet.md`. Tự scan trước, dùng AI sau để phản biện. Không copy ví dụ Weekly Report.

## Thông tin cá nhân

- Họ và tên: LÊ CHÂU TRẦN PHÁT
- Mã học viên: 2A202602545
- Vai trò / bối cảnh (VD: sinh viên năm X, intern PM, ...): INTERN FULLSTACK (có tham gia phụ trợ quy trình tuyển dụng / tìm việc)
- Công việc hằng tuần (3-5 gạch đầu dòng để soi problem):
  - Tham gia phỏng vấn, hỗ trợ lọc CV cho vị trí Intern/Fresher.
  - Sắp xếp lịch phỏng vấn với các ứng viên.
  - Tự chuẩn bị CV và tìm việc ở góc độ cá nhân.

---

## Phase 1 — Scan 5+ problems (tối thiểu 5, khuyến khích 8-10)

**Cách điền:** mỗi dòng = việc gì + ai chịu + đo bằng gì. Cột `Dấu hiệu thật` bắt buộc có số: mất bao lâu (bấm giờ mấy lần), mấy lần/tuần, bao nhiêu người gặp, log/ticket/quote nào.

| # | Lăng kính (Lặp lại / Tốn thời gian / AI có thể tốt hơn / Pain từ người khác) | Problem quan sát được | Ai chịu ảnh hưởng? | Dấu hiệu thật (số + bằng chứng) |
|---|---|---|---|---|
| 1 | Tốn thời gian & Lặp lại | Quá nhiều CV cần sàng lọc, không biết CV nào thực sự đạt chuẩn với JD. | HR / Hiring Manager | Mất 5-10 phút/CV. Một đợt có hàng trăm CV, mất nguyên cả tuần chỉ để lướt và lọc. |
| 2 | AI có thể tốt hơn & Tốn thời gian | Tổng hợp ghi chú (interview notes) sau phỏng vấn để làm báo cáo đánh giá. | HR / Interviewer | Mất 20-30 phút sau mỗi buổi. Thường bị dồn lại cuối ngày, lục lại trí nhớ/nháp rất mệt. |
| 3 | Tốn thời gian & Lặp lại | Phải sửa/thiết kế lại CV và Cover Letter cho khớp với từng JD khác nhau. | Người xin việc (Candidate) | Mất 1-2 tiếng để viết lại cho một vị trí mơ ước, nhưng vẫn trượt vì chưa highlight đúng trọng tâm. |
| 4 | Pain từ người khác | Ứng viên gửi CV xong bị "ghosting", không rõ trạng thái hồ sơ. | Người xin việc | Ứng viên bức xúc chờ đợi hàng tuần, HR mang tiếng xấu trên các forum. |
| 5 | Lặp lại | Sắp xếp lịch phỏng vấn qua lại giữa 3 bên (HR, Ứng viên, Interviewer). | HR | Mất 15-20 phút nhắn tin qua lại/email chỉ để chốt 1 slot trống chung. |


> Gợi ý tự soi: tuần trước mất nhiều thời gian nhất vào việc gì? Việc gì hay trì hoãn? Người khác hay hỏi lại câu gì? Workflow nào ai cũng biết là chậm?

**AI đã dùng ở Phase 1 (nếu có):**
- Prompt đã hỏi: Đã thảo luận với AI đóng vai trò interviewer (dùng slash command /grill-me) để đào sâu các vấn đề tuyển dụng.
- Ý dùng được: Khám phá bài toán ở cả 2 góc độ (HR và Candidate).
- Ý bỏ vì không phải pain thật: Các bài toán quá chung chung như "tìm ứng viên trên mạng".

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
| 1 | Quá nhiều CV cần sàng lọc, không biết CV nào thực sự đạt chuẩn với JD. | Workflow rõ ràng (nhận CV -> đọc -> đánh giá -> loại/pass). Tốn nhiều thời gian nhất của HR. | Đánh giá "đạt chuẩn" đôi khi dựa vào cảm tính hoặc văn hóa công ty, khó lượng hóa. |
| 2 | Tổng hợp ghi chú sau phỏng vấn để làm báo cáo đánh giá. | Đau đầu vì hay quên context nếu dồn lại cuối ngày. AI xử lý ngôn ngữ rất tốt bài toán này. | Quality của ghi chú ban đầu (đầu vào) có thể quá tệ để AI tóm tắt đúng. |
| 3 | Phải sửa/thiết kế lại CV và Cover Letter cho khớp với từng JD. | Đây là nỗi đau cá nhân rất lớn. Có impact rõ ràng (đậu/rớt). | Ứng viên có thể lạm dụng AI làm CV mất đi tính chân thực. |

### 2.2. Problem Cards chi tiết (lặp lại cho cả 3 cards)

---

#### Problem Card #1 — Lọc CV (CV Screening)

```text
Problem 1 câu: HR mất hàng giờ đồng hồ mỗi ngày để đọc thủ công hàng trăm CV, đối chiếu với JD để tìm ra ứng viên phù hợp, rất dễ bỏ sót hoặc đánh giá cảm tính.

Actor: HR / Hiring Manager

Thời điểm / bối cảnh: Giai đoạn đầu của đợt tuyển dụng khi lượng CV gửi về ồ ạt.

Current workflow 3-7 bước:
1. Nhận thông báo CV ứng tuyển từ email/platform.
2. Mở từng file PDF/Word.
3. Đọc lướt tìm keyword (kinh nghiệm, kỹ năng) đối chiếu với JD.
4. Đánh giá Pass / Fail / KIP.
5. Ghi chú lý do vào hệ thống nội bộ hoặc Excel.
6. Handoff danh sách Pass cho Hiring Manager.

Bottleneck: Bước 3 và 4. Mất 5-10 phút cho mỗi CV để đọc và tìm keyword thủ công.

Impact: Mất nguyên 1 tuần chỉ để lọc CV (khoảng 20-30 tiếng). Dễ loại nhầm CV tốt do mệt mỏi.

Success metric: Giảm thời gian lọc mỗi CV xuống dưới 2 phút. Tỷ lệ CV pass vòng lọc được Hiring Manager đồng ý phỏng vấn tăng lên.

Non-AI alternative: Dùng form hỏi trắc nghiệm (Google Forms) bắt ứng viên tự khai báo số năm kinh nghiệm để tự động lọc loại.

AI hypothesis: AI đọc CV và JD, trích xuất thông tin, so sánh và chấm điểm độ match, highlight các điểm thiếu sót. HR chỉ việc đọc bản tóm tắt và duyệt.

Quick gut:
[ ] No AI / process fix
[ ] Rule
[x] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #1** (ASCII / Mermaid / ảnh đính kèm):

```text
CURRENT STATE — 5-10 phút/CV

[1 Mở CV: 0.5'] → [2 Đọc & dò keyword: 5'] <-- bottleneck → [3 Đánh giá Pass/Fail: 2'] → [4 Nhập Excel: 1.5']

FUTURE STATE — 1.5 phút/CV

[1 AI trích xuất & chấm điểm độ match với JD: 0.1'] → [2 HR đọc highlight & lý do của AI: 1'] <-- human boundary → [3 HR chốt Pass/Fail: 0.4']

Fallback: nếu AI chấm sai hoặc không đọc được PDF format lạ → HR mở file gốc đọc tay (quy trình cũ).
```


---

#### Problem Card #2 — Tổng hợp Interview Notes

```text
Problem 1 câu: Sau mỗi buổi phỏng vấn, Interviewer mất 20-30 phút để ngồi nhớ lại và gõ lại báo cáo đánh giá ứng viên từ những dòng ghi chú nháp lộn xộn.

Actor: Interviewer (Hiring Manager / Tech Lead)

Thời điểm / bối cảnh: Kết thúc buổi phỏng vấn ứng viên.

Current workflow 3-7 bước:
1. Phỏng vấn ứng viên, vừa hỏi vừa take note nháp (trên giấy hoặc notepad).
2. Phỏng vấn xong, quay lại làm việc chuyên môn.
3. Cuối ngày, mở form đánh giá của HR.
4. Nhìn nháp, lục lại trí nhớ để viết thành các đoạn văn mạch lạc (Điểm mạnh, Điểm yếu, Đánh giá fit).
5. Submit form cho HR.

Bottleneck: Bước 4. Việc chuyển từ nháp lộn xộn sang văn bản chỉn chu rất tốn công và hay quên chi tiết.

Impact: Mất 20-30 phút mỗi ứng viên. Thường nộp báo cáo đánh giá trễ hạn cho HR.

Success metric: Giảm thời gian viết báo cáo xuống dưới 5 phút/ứng viên. Báo cáo đủ 3 phần (Mạnh, Yếu, Fit).

Non-AI alternative: Làm template đánh giá dạng checklist/rating scale thay vì bắt viết text tự do.

AI hypothesis: Interviewer chỉ cần paste note nháp (thậm chí note dạng keyword rời rạc), AI sẽ dựa vào template để sinh ra bản báo cáo hoàn chỉnh. Interviewer review lại.

Quick gut:
[ ] No AI / process fix
[ ] Rule
[x] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #2:**

```text
CURRENT STATE — 25 phút

[1 Take note nháp: 0'] → [2 Lục lại trí nhớ cuối ngày: 5'] → [3 Viết thành văn bản: 15'] <-- bottleneck → [4 Submit: 5']

FUTURE STATE — 5 phút

[1 Take note nháp: 0'] → [2 Paste nháp cho AI: 0.5'] → [3 AI generate báo cáo: 0.5'] → [4 Interviewer review & edit: 3'] <-- human boundary → [5 Submit: 1']

Fallback: AI viết quá chung chung, Interviewer tự gõ lại tay.
```


---

#### Problem Card #3 — Tailor CV

```text
Problem 1 câu: Ứng viên mất 1-2 tiếng để chỉnh sửa CV và Cover Letter cho khớp với từng JD riêng biệt mà vẫn không chắc chắn đã highlight đúng ý nhà tuyển dụng.

Actor: Người xin việc (Candidate)

Thời điểm / bối cảnh: Khi tìm thấy một Job Description ưng ý và muốn nộp đơn.

Current workflow 3-7 bước:
1. Đọc JD, bôi đen các yêu cầu công việc.
2. Mở file CV gốc (Word/Canva).
3. Sửa lại title, viết lại phần Summary.
4. Chỉnh sửa bullet point trong Experience để có chứa keyword của JD.
5. Viết Cover letter mới.
6. Xuất PDF và nộp.

Bottleneck: Bước 3 và 4. Mất rất nhiều thời gian suy nghĩ cách diễn đạt lại kinh nghiệm cũ cho hợp JD mới.

Impact: Mất 1-2 tiếng cho 1 công ty. Gây nản chí, dẫn đến việc ứng viên rải CV chung chung (spam) và bị loại.

Success metric: Thời gian tạo ra 1 bản CV tailor + Cover letter giảm xuống dưới 15 phút.

Non-AI alternative: Chỉ làm 1 bản CV thật tốt và chấp nhận rải, không tailor nữa.

AI hypothesis: Ứng viên cung cấp CV gốc và JD. AI đối chiếu và đề xuất viết lại các bullet point, sinh ra draft Cover Letter. Ứng viên tự review và xuất file.

Quick gut:
[ ] No AI / process fix
[ ] Rule
[x] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #3:**

```text
CURRENT STATE — 90 phút

[1 Đọc JD: 10'] → [2 Viết lại Summary: 15'] → [3 Sửa bullet points: 30'] <-- bottleneck → [4 Viết Cover Letter: 30'] → [5 Nộp: 5']

FUTURE STATE — 15 phút

[1 Cung cấp CV gốc + JD cho AI: 2'] → [2 AI suggest điểm cần sửa & draft Cover letter: 1'] → [3 Candidate review & update lại CV: 10'] <-- human boundary → [4 Nộp: 2']

Fallback: AI viết sáo rỗng (hallucinate kinh nghiệm), Candidate tự viết lại CV gốc.
```

---

### 2.3. Card muốn pitch nhất (chuẩn bị 2 phút)

**Card tôi muốn pitch nhất:**

```text
Problem Card #1: Lọc CV (CV Screening)
```

**Vì sao (2-3 câu: workflow gì, số đo gì, impact gì):**

```text
Đây là vấn đề tốn nhiều thời gian nhất (bottleneck) của quy trình tuyển dụng đầu vào. Việc đọc tay hàng trăm CV mất từ 5-10 phút/CV là cực kỳ nhàm chán và lặp lại. Nếu giải quyết được, impact sẽ tiết kiệm được 20-30 tiếng/tuần cho HR và đẩy nhanh thời gian tuyển dụng (Time-to-hire).
```

**Câu hỏi tôi muốn nhóm challenge (1-2 câu hỏi đúng chỗ yếu):**

```text
Tiêu chí "đạt chuẩn" của một CV thường bị phụ thuộc vào đánh giá cảm tính hoặc "linh cảm" của HR, liệu AI có thể lượng hóa được những tiêu chí mềm này không?
```

**AI phản biện Card (nếu có):**
- Điểm yếu AI chỉ ra: AI (Claude/ChatGPT) có thể bỏ sót ứng viên có kinh nghiệm tương đương nhưng dùng từ ngữ khác (không đúng keyword).
- Tôi sửa gì: Đưa thêm "Human Boundary" (HR đọc highlight & lý do của AI) thay vì để AI tự động reject ứng viên.

### Self-check nộp phần 01
- [x] Có 5+ problems + top 3 Cards đủ field
- [x] Mỗi Card có workflow trước/sau + bottleneck + metric + fallback
- [x] Đã chọn 1 card pitch + câu hỏi challenge
