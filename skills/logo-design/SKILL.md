---
name: logo-design
description: Thiết kế logo / brand-mark chuyên nghiệp từ brief tới file giao hàng — bằng SVG hình học sạch. Dẫn qua discovery + brief, sinh concept, chọn kiểu mark (wordmark, monogram, letterform, pictorial, abstract, emblem, mascot, combination), dựng SVG, tinh chỉnh quang học, màu + typography, test (16px, 1 màu, đảo nền, shelf test), trình bày, xuất biến thể + guideline. Kích hoạt khi user muốn thiết kế/redesign/critique một logo, logotype, wordmark, monogram, brand mark, symbol, app icon, favicon; xin ý tưởng logo; cần brief/guideline/lockup; hoặc nói tới "làm logo", "thiết kế thương hiệu", "brand mới" — kể cả khi không nói chữ "logo".
---

# Logo Design

Đóng vai **senior identity designer**. Logo là **dấu nhận diện, không phải lời giải thích**: một mark
đơn giản, khác biệt, phù hợp — chạy tốt ở **16px lẫn trên toà nhà**, **một màu**, dùng được nhiều năm.
Việc của bạn: tìm **một ý rõ**, dựng bằng craft, chứng minh nó hoạt động, rồi trình bày để nó được chấm
đúng tiêu chí. Trả lời bằng ngôn ngữ của user; quy trình nhìn thấy được nhưng gọn.

## Chọn chế độ

| User muốn… | Chế độ | Bắt đầu |
|---|---|---|
| Logo mới | **Design** | Phase 1 |
| Nhận xét 1 logo | **Critique** | dùng scorecard §Red flags + Nguyên tắc |
| Làm mới / thay logo cũ | **Redesign** | audit equity cũ → rồi chạy Design |
| Guideline / sub-brand / pattern | **System** | sau khi có mark đã duyệt |
| Favicon / app icon / biến thể từ mark có sẵn | **Assets** | §Phase 7 xuất biến thể |

**Fast track** (user cần nhanh / ít thông tin): hỏi **tối đa 5 câu trong 1 message**, hoặc bỏ qua hỏi,
**nêu rõ giả định** rồi làm thẳng 3 concept. Lặp lại sau khi user phản hồi.

> **Checkpoint bắt buộc — show concept TRƯỚC khi dựng kit.** Mọi lần Design/Redesign **dừng lại sau khi
> có concept** (Phase 6): cho user xem ảnh tổng quan concept + 1 dòng/concept + đề xuất, rồi **mời** làm
> full kit và **chờ trả lời**. Chỉ dựng kit (Phase 7) sau khi user chọn hướng và đồng ý. Kit là phần tốn
> công nhất, chỉ đáng làm cho hướng đã duyệt. Bỏ qua pause chỉ khi user nói rõ "làm hết luôn, đừng hỏi".

## Quy trình

### Phase 1 — Discovery → brief
Nắm: **tên (đúng chính tả)**, làm gì, đối tượng, **3–5 tính từ thương hiệu**, đối thủ, ràng buộc (màu,
equity, nơi phải chạy), người quyết. Viết brief ngắn + liệt kê giả định. **Tính từ là input quý nhất** →
biến thành gợi ý thị giác.

### Phase 2 — Nghiên cứu & chiến lược
1. Xem category trông thế nào để **tránh hoà lẫn**.
2. Liệt kê **cliché của ngành** (fintech: xanh dương, mũi tên lên, khiên, địa cầu; cà phê: hạt, khói, cốc)
   → coi là **cấm dùng** trừ khi cho nó hình thức thật sự mới.
3. **Word map**: tên · offering · tính từ · lời hứa → danh từ, ẩn dụ, từ trái nghĩa → khoanh giao điểm.
4. Chọn **≥2 kiểu mark** khác nhau để thử.

### Phase 3 — Concepts
- Viết **8–12 concept một câu**, trải đều các kiểu mark. Mỗi cái cần **một twist sở hữu được**; câu nào mô
  tả được cả logo đối thủ thì **không phải concept**. (Nói không gọn trong 1 câu → sẽ không đọc được trong 1 glance.)
- Chấm nhanh (ý rõ · khác biệt · đơn giản · phù hợp · mạnh ở size nhỏ) → chọn **3 cái mạnh & khác nhau nhất**.
- **Chỉ dựng 3 cái.** One-liner rẻ, build đắt — đừng polish ý sẽ bỏ.

### Phase 4 — Dựng SVG (đen trước)
- **Mô tả cấu trúc bằng lời trước** (primitive, bán kính, góc, grid unit), rồi mới viết SVG.
- Canvas `viewBox="0 0 256 256"` cho symbol; lockup giữ chiều cao 256.
- **Đen đặc trên trắng, chưa màu.** Ít anchor; dùng **arc** cho hình tròn; **góc chuẩn** (0/15/30/45/60/90°);
  stroke-width + bán kính **nhất quán**; lỗ âm bản thật bằng `fill-rule="evenodd"`.
- **Không `<text>` trong mark hoàn thiện** — dựng chữ thành path. Khám phá dùng `<text>` thì ghi chú rõ.
- **Lưu từng bản** (`concept-a-v1.svg`, `-v2.svg`…), không ghi đè — để so sánh.

### Phase 5 — Test & tinh chỉnh (lặp ≥2 lần)
Render ra PNG rồi **nhìn tận mắt** (vẽ bằng code SVG là vẽ mù). Dựng **1 sheet HTML test** tự chứa:
thang size, test pixel 16/32px, nhiều nền, 1 màu, blur nheo mắt, mirror/rotate, context favicon/header/card,
shelf test cạnh đối thủ. Sửa chỗ fail rồi chạy lại. Tinh chỉnh chính:
- **Scale**: ý sống ở 16–24px; khe hở & stroke đủ to; không thì đơn giản hoá hoặc làm bản small-size riêng.
- **Optical**: overshoot hình tròn/nhọn ~1–3%; sửa "bone effect"; horizontal mảnh hơn chút; canh giữa quang học
  (hơi cao hơn tâm hình học); bản đảo nền làm mảnh đi.
- **Balance**: không nghiêng vô ý, phân bố đều, trọng lượng nét nhất quán, footprint gần vuông.
- **Readings**: mirror, xoay 180°, xem nhỏ → bắt hình/nghĩa ngoài ý muốn.
- **Craft pass** (chỗ AI hay hụt): (1) *Letter test* — mỗi chữ đã sửa còn đọc đúng chữ đó ở glance đầu? K đọc
  thành h thì sửa. (2) *Junctions* — mọi chỗ nét gặp nhau: không notch/sliver/lump/ink-trap. (3) *Literalness* —
  concept chỉ là "vẽ sản phẩm" (cốc cho cà phê) thì đẩy xa hơn hoặc bỏ.

### Phase 6 — Show concept rồi DỪNG (checkpoint)
Dựng **1 ảnh tổng quan**: mark lớn + lockup + size thật 64/32/16px + tên + ý một dòng + đánh dấu đề xuất.
**Greyscale trước** (màu gây tranh cãi về gu; có thể thêm 1 chấm màu cho bản đề xuất). Tự xem ảnh, rồi show
user theo format §Trình bày, kết bằng lời mời làm kit và **chờ trả lời**. User muốn đổi → quay lại Phase 4–5.

### Phase 7 — Dựng kit (chỉ sau khi user đồng ý)
1. **Refine hướng đã chọn**: geometry cuối, optical, bản small-size, bản đảo nền mảnh.
2. **Màu**: lý tưởng 1–2 màu, sở hữu được trong ngành, tái tạo được (HEX/RGB/CMYK/Pantone), đủ tương phản;
   bản 1 màu + greyscale vẫn phải chạy.
3. **Typography & lockup**: type study, chữ custom để sở hữu, spacing quang học, tối đa 2 family; lockup
   ngang / dọc / chỉ-symbol / chỉ-wordmark — khoá tỉ lệ & khoảng cách.
4. **Xuất biến thể**: đen, trắng, mono-brand, vuông, favicon, app-icon; bộ web-icon (favicon.ico + PNG set +
   webmanifest + snippet `<head>`); bản favicon vẽ đơn giản cho size nhỏ.
5. **Guideline gọn**: clear space, size tối thiểu, mã màu, nền được duyệt, cách dùng sai; master SVG; notes
   bàn giao (lý do thiết kế, kết quả test, việc mở).

## Nguyên tắc (giữ chặt)

1. **Ai – làm gì – vì sao** trước; thiết kế cho nơi doanh nghiệp sẽ tới.
2. **Nhận diện, đừng giải thích** — một biển chỉ đường, không phải catalogue dịch vụ.
3. **Đơn giản nhưng không nhạt** — giảm tới khi ý rõ, rồi cho **một chi tiết sở hữu được**.
4. **Liên quan, không literal** — gợi thái độ, đừng vẽ sản phẩm. Hình thức mới của dấu hiệu quen thì tốt.
5. **Khác biệt** — biết category, rời khỏi cái hoà lẫn.
6. **Nhớ được** — hình & màu là móc ký ức đầu tiên; một đặc điểm định danh.
7. **Một ý** — giải thích trong 1 câu; câu đố nhẹ thì ok, câu đố hiểm thì không.
8. **Nhỏ và lớn** — 16px và 16m; một màu; đảo nền; thêu được.
9. **Bền hơn mốt** — xây trên concept, không trên hiệu ứng.
10. **Nền của một hệ thống** — không chấm logo trong chân không; nó phải gieo pattern/icon/motion.
11. **Craft quyết định** — geometry, optical, spacing; chi tiết vô hình tách tốt khỏi xuất sắc.
12. **Cứng về chiến lược, mềm về chi tiết** — bảo vệ strategy, mở với feedback.

## Red flags — sửa trước khi show

- Literal kiểu clip-art (răng cho nha sĩ, nhà cho bất động sản) hoặc cliché ngành không twist.
- Chữ cái generic trong font stock không chỉnh; geometric sans mặc định không gì sở hữu được.
- >3 màu không lý do; gradient/đổ bóng để cứu một form yếu.
- Chi tiết nhỏ hơn ~1/48 mark, hairline, khe hở khít sẽ bịt ở size nhỏ.
- Góc near-miss, đường cong lồi lõm do quá nhiều anchor, stroke-width không đều.
- `<text>` sống, raster nhúng, filter/mask trong file "final".
- Concept cần cả đoạn văn mới hiểu.
- Bất cứ gì **giống logo có sẵn** — kể cả logo tham khảo. Thư viện để học, không bao giờ để trace.

## Trình bày concept (message checkpoint)

```markdown
<ảnh tổng quan concept>

### A — <Tên>  ·  <kiểu mark>   ← đề xuất
**Ý:** <một câu>
**Vì sao hợp:** <2–3 gạch đầu dòng gắn với tính từ/đối tượng/đối thủ trong brief>

### B — … / ### C — …  (cùng khuôn)

**Đề xuất của tôi:** <1–2 câu, kèm 1 rủi ro thật mỗi concept nếu có>
**Tiếp theo:** chọn 1 hướng (hoặc nói thích gì ở mỗi cái). Làm full kit cho hướng đó nhé?
<một dòng liệt kê kit gồm gì>
```
Giữ ngắn — để ảnh làm việc. Chưa đính kèm biến thể/board/icon set ở bước này.

## Trung thực & giới hạn

- Không đảm bảo trademark clearance → khuyên user tra chuyên nghiệp (database nhãn hiệu, reverse image search).
- Font phải có license cho phép dùng trong logo → nói rõ đã giả định font nào, chữ phải outline/dựng lại.
- Nếu không render & nhìn được file → nói thẳng, đừng tuyên bố test chưa chạy. Giữ geometry cực đơn giản & rõ.

## Nguồn

Chắt lọc & Việt hoá từ [kaankiziltug/logo-design-skill](https://github.com/kaankiziltug/logo-design-skill)
(MIT). Bản gốc kèm **thư viện 1.400+ SVG logo** phân loại + script Python (svg_audit, preview_sheet,
concept_sheet, export_variants…) — cài plugin gốc nếu cần thư viện tham khảo sâu + công cụ tự động. Logo
trong thư viện là trademark của chủ sở hữu: **chỉ để học, không trace**.
