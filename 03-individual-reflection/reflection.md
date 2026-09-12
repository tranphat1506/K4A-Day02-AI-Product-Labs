# 03 — Individual Reflection

> Viết bằng lời của bạn (Phase 7 trong `01-worksheet.md`). Có thể dùng AI gợi ý câu hỏi tự soi, không dùng AI viết thay. 8-12 câu, có chuyện cụ thể.

## Thông tin cá nhân

- Họ và tên: LÊ CHÂU TRẦN PHÁT
- Mã học viên: 2A202602545
- Nhóm: Nhóm 1 (Tạm định)
- Candidate problem nhóm chọn: Lọc CV (CV Screening)

---

## 1. Tôi đã tham gia vào phần nào?

Ghi việc cụ thể + kết quả cụ thể. Không ghi chung chung kiểu "tham gia thảo luận".

| Hoạt động | Tôi đã làm gì? (việc cụ thể) | Kết quả / ảnh hưởng tới nhóm |
|---|---|---|
| Scan cá nhân | Chuẩn bị 5 problems về tuyển dụng (HR & Candidate). | Giúp nhóm có góc nhìn đa chiều về quy trình tuyển dụng. |
| Pitch Problem Card | Thuyết trình Problem "Lọc CV" trong 2 phút. Nhấn mạnh vào thời gian mất 5-10 phút/CV. | Thuyết phục được nhóm chọn bài toán này làm Candidate cuối cùng. |
| Challenge bài của bạn khác | Đặt câu hỏi về "Data access" khi bạn khác đề xuất bài toán tổng hợp data từ Slack. | Nhóm nhận ra bài toán Slack quá rộng và bỏ qua để focus vào Lọc CV. |
| Gom trùng / cluster | Đề xuất gom các bài toán "Viết đánh giá phỏng vấn" và "Lọc CV" vào nhóm "Tối ưu Document cho HR". | Giúp nhóm phân loại 12 ideas nhanh hơn. |
| Chọn candidate problem | Vote 5 điểm cho Lọc CV và giải thích lý do. | Đồng thuận chốt bài toán. |
| Validation / research | Tìm kiếm các tool ATS hiện có và cách dùng AI Vision để scan CV. | Nhóm biết được AI hiện tại hoàn toàn có thể trích xuất entity từ file PDF. |
| Workflow nhóm | Vẽ luồng trước/sau trên giấy, xác định rõ bottleneck là khâu "đọc lướt tìm keyword". | Nhóm chốt được thời gian target giảm từ 90 phút xuống 15 phút. |
| Problem Statement | Viết phần Actor và Impact. | PS v1 rõ ràng hơn về đối tượng chịu ảnh hưởng. |
| Rule / Workflow / Agent | Lập luận bảo vệ mức "Workflow", phản đối việc xây dựng "Agent" tự động loại ứng viên. | Nhóm thống nhất chỉ dùng AI để draft, con người review (Human Boundary). |
| Decision | Vote "Go" và đề xuất làm pilot nhỏ với 20 CV cũ. | Nhóm có hướng đi rõ ràng cho bước tiếp theo. |

**Dấu tay rõ nhất của tôi trong artifact cuối (1-2 câu):**

```text
Tôi là người bảo vệ quan điểm "Phải có Human Boundary", yêu cầu HR phải là người quyết định cuối cùng thay vì để AI tự động đánh rớt CV, giúp bản Problem Statement của nhóm trở nên thực tế và an toàn hơn.
```

---

## 2. Bảng dùng AI (mỗi dòng 1 phase có dùng AI — 2 cột cuối bắt buộc)

| Phase | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai / hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| Scan | Đóng vai Interviewer hỏi đáp để tìm pain point. | Gợi ý được góc nhìn từ phía Ứng viên (Tailor CV, Ghosting). | AI gợi ý một số vấn đề quá vĩ mô (vd: định hướng nghề nghiệp). | Bỏ qua các ý vĩ mô, chỉ giữ lại các thao tác có workflow rõ ràng (Lọc CV, Sửa CV). |
| Problem Card | Nhờ AI cấu trúc lại Draft Workflow cho đẹp. | Trình bày luồng Before/After dễ nhìn. | AI tự động bỏ mất bước "Nhập Excel" ở luồng cũ. | Tự thêm lại bước nhập Excel vì đây là thao tác tốn thời gian thật sự. |
| Workflow | (Không dùng) | | | Tự vẽ tay cùng nhóm để tranh luận dễ hơn. |
| Research | Tìm kiếm các giải pháp trích xuất CV hiện tại. | Liệt kê nhanh các API của OpenAI/Anthropic. | AI đưa ra một số tool ATS quá đắt đỏ và không phù hợp với quy mô công ty nhỏ. | Chọn lọc lại, chỉ tập trung vào giải pháp "Workflow tự động hóa nhẹ nhàng" thay vì mua tool ATS lớn. |
| Problem Statement | Phản biện PS v0. | Nhận ra thiếu phần Success Metric. | Gợi ý metric chung chung như "tăng độ hài lòng". | Đổi metric thành con số cụ thể: "giảm thời gian lọc mỗi CV xuống dưới 2 phút". |
| Rule / Workflow / Agent | Hỏi AI sự khác biệt nếu áp dụng Agent cho bài toán này. | Giải thích rõ rủi ro nếu Agent tự hành động. | Khuyên nên dùng Agent để tự động email ứng viên. | Bác bỏ ý này vì rủi ro "Ghosting" hoặc gửi nhầm email là rất cao. |
| Decision | (Không dùng) | | | Tự quyết định dựa trên thảo luận nhóm. |

> Nếu phase nào không dùng AI, ghi `Không dùng` và vì sao tự làm.

---

## 3. Reflection câu hỏi mở

Chọn 3-4 câu trong 6 câu dưới để viết thành đoạn 8-12 câu (không trả lời bullet 1 dòng):

**Reflection:**

```text
Qua buổi Lab, điều lớn nhất tôi học được khi nghe các Problem của bạn khác là: những ý tưởng nghe có vẻ "rất AI" chưa chắc đã là một bài toán tốt nếu thiếu đi workflow thực tế. Nhóm tôi ban đầu cũng có xu hướng "solution-first", có bạn đề xuất làm hẳn một Agent tự động scan mạng xã hội để tìm ứng viên cho ngầu. Tuy nhiên, sau khi bị challenge về tính khả thi và "dấu hiệu thật", chúng tôi nhận ra việc giải quyết cái "đau" ngay trước mắt (đọc hàng trăm CV mỏi mắt) bằng một Workflow đơn giản lại mang tới giá trị cao hơn. Tôi đã kiên quyết bảo vệ quan điểm không để AI tự quyết định loại ứng viên (Human Boundary), và tôi tự hào vì đây là dấu ấn rõ rệt nhất của mình trong bản nộp nhóm. Nếu làm lại, tôi sẽ challenge nhóm mạnh hơn ở phần Success Metric, ép các bạn phải đưa ra được những con số baseline đo lường được thay vì chỉ ước lượng cảm tính như lúc đầu.
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
