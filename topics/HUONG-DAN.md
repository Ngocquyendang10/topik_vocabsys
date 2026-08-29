# Hướng dẫn viết & sửa bài "Từ vựng theo chủ đề"

Thư mục này chứa toàn bộ bài viết của tab **Từ vựng theo chủ đề**.
Bạn chỉ cần đụng tới 2 loại file, **không bao giờ phải mở `index.html` nữa**:

| File | Việc của nó |
| --- | --- |
| `danh-muc.txt` | Quyết định có những thẻ nào ở trang tổng hợp (tên, màu, mô tả, thứ tự) |
| `ten-bai.md` | Nội dung của một bài viết |
| `audio/` | (nếu cần) Thư mục chứa file mp3 cho bài đọc |

---

## A. Sửa nội dung một bài (nhanh nhất, làm ngay trên GitHub)

1. Vào https://github.com/Ngocquyendang10/topik_vocabsys → thư mục `topics`
2. Bấm vào file bài muốn sửa (ví dụ `tu-vung-han-han.md`)
3. Bấm biểu tượng **cây bút chì** ✏️ ở góc phải
4. Sửa chữ như sửa văn bản bình thường
5. Kéo xuống cuối, bấm **Commit changes**

Đợi khoảng 1 phút rồi mở web bằng Cmd + Shift + R là thấy nội dung mới.
Làm được trên cả điện thoại. Muốn quay lại bản cũ: vào tab **History** của file đó.

## B. Thêm một bài mới

1. Vào thư mục `topics` trên GitHub → **Add file → Create new file**
2. Đặt tên file kiểu `tu-lay-tuong-thanh.md` (chữ thường, không dấu, không khoảng trắng)
3. Dán nội dung viết theo cú pháp ở mục C
4. Commit
5. Mở file `danh-muc.txt`, bấm ✏️, chép thêm một khối như mẫu có sẵn trong đó, sửa lại thông tin → Commit

Xong. Thẻ mới sẽ hiện ở trang tổng hợp.

---

## C. Cú pháp viết bài

Chỉ có 9 quy ước, tất cả đều là gõ chữ bình thường:

```
---
Dòng nhỏ: Tài liệu tham khảo · Tiếng Hàn cho người Việt
Số liệu: 152 gốc Hán tự | 482 từ phái sinh | 5 phần chủ đề
---

# Tiêu đề lớn của bài
Đoạn mở đầu, viết bình thường. Có thể **in đậm** hoặc *in nghiêng*.

## I — Tên phần lớn
*Câu giới thiệu ngắn cho phần này (viết trong dấu sao).*

### Tên nhóm nhỏ

[증] tăng
Câu giải nghĩa gốc chữ này.
증대 [tăng đại] = mở rộng quy mô, phạm vi
> 정부는 예산을 증대하기로 했다. // Chính phủ quyết định tăng ngân sách.
증진 [tăng tiến] {mở rộng} = được nâng cao, cải thiện thêm
! Đồng âm: 촉 và 축 đọc gần giống nhau nhưng khác chữ Hán.
```

Giải thích từng dòng:

| Bạn gõ | Web hiện ra |
| --- | --- |
| `# Chữ` | Tiêu đề lớn của bài (chỉ dùng 1 lần, ở đầu bài) |
| `## I — Tên phần` | Một phần lớn; chữ trước dấu — thành số La Mã to bên trái, và tự có chip điều hướng trên thanh đầu trang |
| `### Tên nhóm` | Tiêu đề nhóm nhỏ trong phần |
| `#### Tên mục` | Tiêu đề nhỏ hơn nữa (dùng trong bài đọc) |
| `[증] tăng` | Mở một mục từ gốc: con dấu chữ 증, bên dưới là nghĩa "tăng" |
| `증대 [tăng đại] = nghĩa` | Một dòng từ vựng. Phần `[...]` là âm Hán Việt, có thể bỏ trống |
| `증진 [tăng tiến] {mở rộng} = nghĩa` | Thêm `{...}` để gắn nhãn nhỏ (mở rộng, nâng cao…) |
| `> Câu Hàn // Nghĩa Việt` | Khung ví dụ song ngữ đặt ngay dưới từ vừa nêu |
| `! Nhãn: nội dung` | Khung ghi chú viền trái |
| `- Nội dung` | Gạch đầu dòng |
| `**đậm**` `*nghiêng*` | In đậm / in nghiêng |
| `\| a \| b \|` | Bảng (dòng đầu là tiêu đề cột) |
| `---` | Đường kẻ ngang |

Vài điều đáng nhớ:

- **Bài từ vựng** thì dùng `[gốc]`, dòng `= nghĩa`, `>` ví dụ. **Bài đọc chuyên môn** thì cứ viết đoạn văn, tiêu đề, gạch đầu dòng, bảng như Word. Trộn cả hai trong một bài cũng được.
- Số lượng mục và từ của mỗi phần **web tự đếm**, không cần ghi tay.
- Chữ Hàn trong dòng `từ = nghĩa` phải đứng một mình, không kèm dấu ngoặc hay dấu chấm — web dò chính xác chuỗi này với thư viện từ vựng để học viên bấm vào xem thẻ chi tiết.
- Dòng trống dùng để ngăn cách cho dễ đọc, thừa thiếu một dòng cũng không sao.

## C2. Cú pháp riêng cho BÀI ĐỌC (nghe – hiểu – dịch – chép)

Ngoài các dấu hiệu ở mục C, bài đọc có thêm 6 khối sau. Xem bài mẫu
`bai-doc-bao-ve-moi-truong.md` để hình dung.

| Bạn gõ | Web hiện ra |
| --- | --- |
| `@audio tts` | Trình phát đọc cả bài bằng giọng máy — chạy được ngay, không cần file |
| `@audio audio/ten-file.mp3` | Trình phát file thật: chạy/dừng, lùi–tiến 5 giây, kéo thanh thời gian, tốc độ 0.75×–1.5× |
| `~ 한국어 문장. // Bản dịch tiếng Việt` | Một câu của bài đọc: bấm vào câu hiện bản dịch, có nút ▶ nghe riêng câu đó |
| `& 최근 = gần đây` | Dữ liệu tra từ — KHÔNG hiện thành dòng, mà làm cho chữ 최근 trong bài được gạch chân, bấm vào hiện nghĩa |
| `? Câu hỏi` rồi `+ đáp án đúng` / `- đáp án sai`, kết bằng `! Giải thích: …` | Câu trắc nghiệm chấm ngay, tô xanh đáp án đúng và mở phần giải thích |
| `%dich 한국어 문장 // bản dịch mẫu` | Ô luyện dịch: học sinh gõ bản dịch rồi bấm xem bản mẫu |
| `%chep 한국어 문장 // 가까운 거리는 ___ 수 있다` | Nghe & chép chính tả: nút nghe, ô gõ, nút Kiểm tra chấm đúng/sai. Phần sau `//` là dòng gợi ý, bỏ trống cũng được |
| `%dien Câu có ___ // đáp án` | Ô điền từ nhanh, chấm tại chỗ |

Ghi nhớ:

- Đầu bài đọc nên có một dòng `@audio tts` để học sinh nghe được ngay.
- Dòng `&` đặt ở đâu cũng được (thường để ngay dưới đoạn vừa viết cho dễ quản lý);
  từ nào có trong bảng `&` mà xuất hiện y hệt trong câu `~` thì tự được gạch chân.
- Trong khối `?`, dấu `-` là đáp án sai chứ không phải gạch đầu dòng. Muốn dùng gạch
  đầu dòng bình thường thì để cách khối câu hỏi ra bằng một dòng chữ khác.
- Muốn dùng audio thật: tạo thư mục `topics/audio/` trên GitHub, tải file mp3 lên đó,
  rồi ghi `@audio audio/ten-file.mp3`. File nên dưới 20 MB.

## D. Mẹo: soạn bằng Google Sheet rồi dán vào

Với bài nhiều từ, cứ gõ vào Sheet như thường lệ (cột A từ Hàn, B âm Hán Việt, C nghĩa),
rồi ở cột D dùng công thức nối lại:

```
=A2&" ["&B2&"] = "&C2
```

Kéo công thức xuống hết bảng, copy cột D, dán thẳng vào file `.md`. Vậy là vẫn quản lý
bằng bảng tính cho tiện, mà bản đăng lên web vẫn là file gọn nhẹ, chạy nhanh.

## E. Nhờ AI viết bài mới

Copy TOÀN BỘ khung câu lệnh ở **mục G cuối file này**, chỉ điền các chỗ trong dấu 【 】 rồi
gửi cho bất kỳ AI nào (Claude, ChatGPT, Gemini…). AI trả về đủ 2 phần: nội dung file `.md`
và khối khai báo thẻ để dán vào `danh-muc.txt`. Không cần AI biết gì về code của web.

Nhưng nhớ là: **không có AI bạn vẫn tự viết được** — cú pháp ở mục C gõ tay hoàn toàn bình thường.

---

*Thư mục này chỉ cần 3 loại file: `danh-muc.txt`, các file bài `.md`, và chính bản hướng dẫn này.*

---

## F. Gặp lỗi "Chưa nạp được nội dung bài viết"?

**1. Repo phải có file `.nojekyll`.** Đây là lỗi hay gặp nhất. GitHub Pages mặc định tự "biên
dịch" các file `.md`, làm web không đọc được file gốc. Cách tắt: vào repo → **Add file →
Create new file** → gõ tên file là `.nojekyll` (có dấu chấm ở đầu, không có đuôi) → để trống
nội dung → **Commit**. Đặt ở **thư mục gốc** của repo, không phải trong `topics`.

**2. Tên file phải khớp tuyệt đối.** `Tu-Vung.md` khác `tu-vung.md`. Kiểm tra lại dòng
`=== ten-file.md` trong `danh-muc.txt`.

**3. Đừng đặt tên file bắt đầu bằng dấu gạch dưới** (`_ten-bai.md`) — GitHub Pages bỏ qua
những file như vậy.

**4. Mở web bằng đường link thật**, đừng nhấp đúp mở `index.html` trên máy — trình duyệt chặn
đọc file kèm theo khi mở kiểu đó.

Khung báo lỗi trên web sẽ nói rõ đang vướng trường hợp nào.

---

# G. KHUNG CÂU LỆNH NHỜ AI VIẾT BÀI MỚI

Copy từ dòng "Tôi cần bạn viết nội dung…" cho tới hết file, điền phần 【 】 rồi gửi cho AI.

---

Tôi cần bạn viết nội dung cho một bài trong web học tiếng Hàn của tôi. Bài này sẽ được lưu
thành một file .md và web tự dựng giao diện, nên bạn phải viết ĐÚNG cú pháp tôi mô tả ở dưới.

## Yêu cầu nội dung

- Chủ đề: 【 ví dụ: từ láy tượng thanh — tượng hình trong TOPIK cao cấp 】
- Đối tượng: học viên Việt Nam luyện TOPIK II, giải thích bằng tiếng Việt
- Quy mô: 【 ví dụ: khoảng 120 từ, chia 4 phần, mỗi phần 2–3 nhóm 】
- Kiểu bài: 【 chọn 1: bài từ vựng có mục từ / bài đọc chuyên môn dạng văn xuôi / trộn cả hai 】
- Mỗi từ 【 có / không 】 kèm một câu ví dụ tiếng Hàn và bản dịch tiếng Việt
- Tên file tôi sẽ đặt: 【 ví dụ: tu-lay-tuong-thanh.md 】

## Cú pháp bắt buộc

Bài mở đầu bằng khối thông tin giữa hai dòng `---`, chỉ gồm 2 dòng này:

```
---
Dòng nhỏ: 【 dòng chữ nhỏ in hoa phía trên tiêu đề, ví dụ: Tài liệu tham khảo · TOPIK cao cấp 】
Số liệu: 120 từ láy | 4 phần chủ đề | 30 phút đọc
---
```

Sau đó là nội dung, dùng các dấu hiệu sau (không dùng cú pháp Markdown nào khác):

| Gõ | Ý nghĩa |
| --- | --- |
| `# Tiêu đề bài` | Tiêu đề lớn, chỉ xuất hiện một lần, ngay sau khối `---` |
| đoạn văn ngay dưới `#` | Đoạn dẫn nhập của bài |
| `## I — Tên phần` | Mở một phần lớn. Ký hiệu trước dấu — là số La Mã hoặc số thường |
| `*Câu giới thiệu phần.*` | Đặt ngay dưới dòng `##`, viết trong dấu sao |
| `### Tên nhóm` | Tiêu đề nhóm nhỏ bên trong phần |
| `#### Tiêu đề phụ` | Tiêu đề nhỏ hơn, dùng trong bài văn xuôi |
| `[증] tăng` | Mở một mục từ gốc: chữ Hàn trong ngoặc vuông, sau đó là nghĩa tiếng Việt |
| đoạn văn ngay dưới `[증] tăng` | Câu giải nghĩa của mục từ đó |
| `증대 [tăng đại] = mở rộng quy mô` | Một dòng từ vựng: từ Hàn, âm Hán Việt trong ngoặc vuông, dấu `=`, rồi nghĩa |
| `증진 [tăng tiến] {mở rộng} = nghĩa` | Thêm `{...}` để gắn nhãn nhỏ cho từ |
| `> câu tiếng Hàn // nghĩa tiếng Việt` | Khung ví dụ song ngữ, đặt ngay dưới dòng từ vựng |
| `! Đồng âm: nội dung` | Khung ghi chú, chữ trước dấu hai chấm là nhãn |
| `- Nội dung` | Gạch đầu dòng |
| `**đậm**` · `*nghiêng*` | In đậm / in nghiêng |
| `\| cột 1 \| cột 2 \|` | Bảng, dòng đầu tiên là tiêu đề cột |
| `---` | Đường kẻ ngang ngăn đoạn |

## Quy tắc phải tuân thủ tuyệt đối

1. Trong dòng từ vựng, **phần đứng trước dấu `[` chỉ được là từ tiếng Hàn**, không kèm số
   thứ tự, dấu chấm, dấu gạch đầu dòng hay khoảng trắng thừa. Web dò chính xác chuỗi này với
   kho từ vựng để học viên bấm xem chi tiết, sai một ký tự là mất liên kết.
2. **Không dùng dấu `=` trong câu văn xuôi bình thường** — web sẽ tưởng đó là dòng từ vựng.
   Cần diễn đạt thì viết "là", "tức là", hoặc dấu gạch ngang.
3. **Không mở đầu một dòng văn xuôi bằng dấu `[`** vì đó là dấu hiệu mở mục từ mới.
4. Không viết `##` ở giữa câu, không dùng HTML, không chèn ảnh từ internet.
5. Không cần ghi số lượng mục/từ của từng phần — web tự đếm.
6. Câu ví dụ tiếng Hàn phải đúng ngữ pháp, tự nhiên, độ khó phù hợp TOPIK II, và bản dịch
   tiếng Việt phải sát nghĩa, thuần Việt.

## Bạn trả về cho tôi

**Phần 1 — nội dung file .md**, đặt trong một khối code, không giải thích lan man.

**Phần 2 — khối khai báo thẻ** để tôi dán vào file danh mục, theo đúng mẫu:

```
=== 【tên-file.md】
Tên: 【tên hiển thị trên thẻ】
Mô tả ngắn: 【một dòng ngắn dưới tên】
Chữ trên thẻ: 【một chữ Hán hoặc chữ Hàn tiêu biểu】
Nhãn: 【nhãn ngắn 1–2 chữ, ví dụ: Cao cấp】
Màu: 【chọn: tím / xanh dương / xanh lá / cam / đỏ / hồng / nâu / xám / vàng】
Giới thiệu: 【2–3 dòng mô tả bài, hiện trên thẻ ở trang tổng hợp】
Số liệu: 【ví dụ: 120 từ láy | 4 phần chủ đề】
```

Trước khi trả lời, hãy tự kiểm tra lại toàn bộ nội dung một lượt theo 6 quy tắc trên.

---

## Mẫu bài đúng chuẩn (đưa kèm cho AI nếu cần)

```
---
Dòng nhỏ: Tài liệu tham khảo · Tiếng Hàn cho người Việt
Số liệu: 12 từ láy | 2 phần chủ đề
---

# Từ láy tượng thanh và tượng hình trong TOPIK II

Nhóm từ mô phỏng âm thanh và hình dáng, xuất hiện nhiều trong bài đọc văn học.

## I — Từ mô phỏng âm thanh
*Nhóm từ tả tiếng động của sự vật và con người.*

### Nhóm 1 — Tiếng nước, tiếng gió

[졸] tiếng nước nhỏ
Mô phỏng tiếng nước chảy nhẹ, đều đặn.
졸졸 [chuốt chuốt] = tiếng nước chảy róc rách
> 시냇물이 졸졸 흐른다. // Nước suối chảy róc rách.
콸콸 [khoát khoát] {mở rộng} = tiếng nước chảy mạnh
! Phân biệt: 졸졸 tả dòng nhỏ, 콸콸 tả dòng mạnh và gấp.
```
