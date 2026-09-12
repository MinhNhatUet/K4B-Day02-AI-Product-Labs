# 03 — Individual Reflection

> Viết bằng lời của bạn (Phase 7 trong `01-worksheet.md`). Có thể dùng AI gợi ý câu hỏi tự soi, không dùng AI viết thay. 8-12 câu, có chuyện cụ thể.

## Thông tin cá nhân

- Họ và tên: Ngô Đinh Minh Nhật
- Mã học viên: 2A202602569
- Nhóm: Hôm nay ăn gì
- Candidate problem nhóm chọn: workflow

---

## 1. Tôi đã tham gia vào phần nào?

Ghi việc cụ thể + kết quả cụ thể. Không ghi chung chung kiểu "tham gia thảo luận".

| Hoạt động | Tôi đã làm gì? (việc cụ thể) | Kết quả / ảnh hưởng tới nhóm |
|---|---|---|
| Scan cá nhân |Góp 3 problem|2 problem được đánh giá cao |
| Pitch Problem Card |Pitch 3 candidate problems: #4 "Tìm và chọn tài liệu cho khóa luận", #5 "Check deadline", #6 "Tập hợp các task sau buổi họp" |Cả 3 vào vòng trình bày 9-12 candidates ban đầu |
| Challenge bài của bạn khác |Đặt ra các câu hỏi cho 3 best pitch card của Dương, Thân và Duy| |
| Gom trùng / cluster | | |
| Chọn candidate problem |Đánh giá để chọn đề tài đặt đồ ăn | |
| Validation / research | | |
| Workflow nhóm |Bổ sung và cải thiện workflow | |
| Problem Statement | | |
| Rule / Workflow / Agent |Workflow |Cải thiện workflow |
| Decision |Làm workflow | |

**Dấu tay rõ nhất của tôi trong artifact cuối (1-2 câu):**

```Em định hình khung làm việc cho toàn nhóm qua việc bổ sung, cải thiện workflow và trực tiếp thiết kế workflow cho artefact. Bên cạnh đó, bạn cũng đóng vai trò cốt lõi trong khâu lọc ý tưởng ban đầu khi đóng góp các problem chất lượng và đưa cả 3 candidate pitch của mình vào top đầu.

```

---

## 2. Bảng dùng AI (mỗi dòng 1 phase có dùng AI — 2 cột cuối bắt buộc)

| Phase | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai / hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| Scan | Gợi ý thêm các pain points thường gặp  | Mở rộng góc nhìn về cấc paint point lặp lại | Đưa ra một số ý tưởng chung chung, thiếu ngữ cảnh thực tế cá nhân. | Lọc giữ lại 3 problem gần gũi nhất có thể vẽ được workflow rõ ràng. |
| Problem Card | check lại cấu trúc workflow và gợi ý metric đo lường. | Định hình nhanh các bước trong workflow| Đưa ra metric thiếu thực tế. | Điều chỉnh metric về thời gian thực tế |
| Workflow | Gợi ý mô hình phân nhánh cho luồng chọn món ăn nhóm. | Gợi ý việc kết hợp giữa Rule lọc cứng và AI xếp hạng giải thích. | Thiết kế luồng quá phức tạp, muốn AI tự tương tác với API app đặt món. | Cắt gọt luồng thành Workflow 7, xác định rõ bước nào là Rule (lọc giá/ETA), bước nào là AI, giữ người dùng kiểm tra. |
| Research | `Không dùng` |  |  | Tự tải/tra cứu app LunchFoods và GrabFood để đánh giá khoảng trống thị trường |
| Problem Statement | Phản biện v0 để tìm ra các từ ngữ mơ hồ. | Chỉ ra field "Impact" mới dừng ở mức ước lượng, chưa có số đo thực nghiệm. | Đề xuất sửa văn phong mang tính "marketing" hơn là phân tích kỹ thuật/workflow. | Sửa lại Boundary rõ ràng (không tự thanh toán/đặt món) và ghi chú rõ điểm cần khảo sát thực tế ở Phase 4.1. |
| Rule / Workflow / Agent | Hỏi ma trận độ phức tạp vs độ mơ hồ của bài toán chọn món. | Xác nhận bài toán nằm ở vùng độ mơ hồ cao + độ phức tạp cao. | Khuyên nên hướng tới xây Agent tự động hoàn toàn để gây ấn tượng. | Giữ lập trường hạ mức xuống **Workflow** vì quy trình rẽ nhánh định trước, giữ actor ở vị trí đưa ra quyết định cuối cùng. |
| Decision | Giúp draft tiêu chí cho thử nghiệm pilot nhỏ nhất. | Gợi ý 3 chỉ số đo lường nhanh khi test với dataset mẫu. | Đánh giá quá tối ưu rằng nhóm đã đủ điều kiện để "Go" ngay. | Đổi thành **Not Yet** vì nhóm chưa thu thập đủ bằng chứng validation thực tế (chưa có dataset menu & khảo sát người dùng). |

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
Khi lắng nghe top 3 problems của các thành viên khác, em nhận ra bất kỳ bài toán nào cũng có pain point thực tế, nhưng điểm khác biệt lớn nhất nằm ở tính khả thi khi kiểm chứng và khả năng dựng workflow rõ ràng. Trong quá trình thảo luận, nhóm từng có lúc nghiêng về phía "solution-first", muốn thử áp dụng Agent để AI tự động tra cứu hay chọn món thay người dùng cho tối tân. Tuy nhiên, sau khi phân tích kỹ ma trận độ mơ hồ và độ phức tạp, em cùng nhóm đã tỉnh táo hạ mức xuống Workflow: AI chỉ làm nhiệm vụ hiểu câu lệnh và xếp hạng đi kèm giải thích ngắn, còn việc ra quyết định cuối cùng vẫn hoàn toàn thuộc về người dùng. Đóng góp rõ nhất của e, vào artifact cuối là việc bổ sung và chuẩn hóa workflow luồng công việc (before/after), giúp nhóm xác định chính xác điểm nghẽn nằm ở khâu so sánh thông tin song song chứ không phải thao tác đặt hàng. Nếu làm lại, e, sẽ challenge nhóm mạnh mẽ hơn ở khâu Validation ngay từ đầu để thu thập số liệu khảo sát thật trước khi chốt Problem Statement v1, tránh việc baseline thời gian chọn món vẫn đang dừng ở mức ước lượng.
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

