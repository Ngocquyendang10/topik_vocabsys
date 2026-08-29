# Hướng dẫn viết & sửa bài "Từ vựng theo chủ đề"

Thư mục này chứa toàn bộ bài viết của tab **Từ vựng theo chủ đề**.
Bạn chỉ cần đụng tới 2 loại file, **không bao giờ phải mở `index.html` nữa**:

| File | Việc của nó |
| --- | --- |
| `danh-muc.txt` | Quyết định có những thẻ nào ở trang tổng hợp (tên, màu, mô tả, thứ tự) |
| `ten-bai.md` | Nội dung của một bài viết |

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

## D. Mẹo: soạn bằng Google Sheet rồi dán vào

Với bài nhiều từ, cứ gõ vào Sheet như thường lệ (cột A từ Hàn, B âm Hán Việt, C nghĩa),
rồi ở cột D dùng công thức nối lại:

```
=A2&" ["&B2&"] = "&C2
```

Kéo công thức xuống hết bảng, copy cột D, dán thẳng vào file `.md`. Vậy là vẫn quản lý
bằng bảng tính cho tiện, mà bản đăng lên web vẫn là file gọn nhẹ, chạy nhanh.

## E. Nếu muốn nhờ AI viết bài mới

Gửi cho AI: nội dung bạn muốn + nguyên mục C ở trên (cú pháp), và dặn "trả về đúng một
file .md theo cú pháp này". Không cần AI biết gì về code của web.

Nhưng nhớ là: **không có AI bạn vẫn tự viết được** — cú pháp trên gõ tay hoàn toàn bình thường.

---

*Ghi chú kỹ thuật: file `tu-vung-han-han.html` là bản HTML cũ của bài Hán Hàn, giữ lại để
đối chiếu và để in ấn. Web hiện đang dùng bản `.md`. Xoá file html đó cũng không ảnh hưởng gì.*
