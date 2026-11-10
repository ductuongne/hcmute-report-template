# Mẫu báo cáo Word

Mẫu báo cáo `.docx` này được mình tinh chỉnh và hoàn thiện trong suốt quá trình học tập tại Trường Đại học Công nghệ Kỹ thuật TP.HCM (HCMUTE), áp dụng linh hoạt cho các bài tập lớn, tiểu luận và đồ án môn học. Mình chia sẻ lại để các bạn có thể tham khảo và phần nào đó giúp các bạn tiết kiệm thời gian căn chỉnh.

> **Lưu ý:** Đây **không phải tài liệu chính thức** của Trường hay của Khoa. Mẫu chỉ là sản phẩm cá nhân, được đúc kết từ kinh nghiệm học tập của tác giả và chia sẻ với mục đích tham khảo. Mỗi môn học, giảng viên hoặc khoa có thể có quy định trình bày riêng. Vui lòng đối chiếu với yêu cầu của giảng viên trước khi sử dụng và chỉnh lại mẫu nếu cần.

Mẫu có sẵn hệ thống style, đánh số tự động cho Chương, Mục, Hình, Bảng, Phụ lục và Mục lục tự cập nhật. Bạn chỉ cần điền nội dung, không phải định dạng lại từ đầu cho mỗi môn.

## Giới thiệu nhanh

- Mẫu sử dụng khổ A4, Font Times New Roman 14pt, theo quy cách thường gặp ở các báo cáo môn học
- Tự đánh số `CHƯƠNG X:`, `1.1.`, `1.1.1.`, `Hình X.Y:`, `Bảng X.Y:`, `PHỤ LỤC A.`
- Số Hình và Bảng tự reset khi sang Chương mới (Hình 2.1, Bảng 2.1...)
- Mục lục, Danh mục hình ảnh, Danh mục bảng biểu cập nhật chỉ với một thao tác
- Có sẵn ví dụ minh họa cho từng loại style: danh sách, bảng, hình, code block, phụ lục

## Nội dung repo

| File | Mô tả |
|------|-------|
| `mau-bao-cao.docx` | File mẫu báo cáo |
| `huong-dan-su-dung.docx` | Hướng dẫn áp dụng bộ style, cập nhật mục lục... |

## Bắt đầu nhanh

1. Tải `mau-bao-cao.docx`, dùng **Save As** để lưu thành tên báo cáo của bạn.
2. Khi mở file, nếu Word hỏi *"có cập nhật các trường trong tài liệu không"* thì chọn **Có**.
3. Điền các chỗ trong ngoặc vuông ở bìa: `[TÊN KHOA]`, `[TÊN MÔN HỌC]`, `[TÊN BÁO CÁO]`, `[TÊN ĐỀ TÀI]`...., cùng thông tin giảng viên, mã lớp và danh sách thành viên.
4. Xóa các phần ghi `[Xóa nếu môn học không yêu cầu]` mà môn của bạn không cần (kể cả dòng ghi nguồn mẫu trong phần Lời cam kết).
5. Viết nội dung bằng cách **gắn style**. Không gõ tay số thứ tự như `CHƯƠNG 1:`, `1.1.`, `Hình 1.1:`, `Bảng 1.1:`, `PHỤ LỤC A`.
6. Trước khi nộp: nhấn `Ctrl + A`, rồi `F9`, chọn **Update entire table** để cập nhật Mục lục, Danh mục hình ảnh và Danh mục bảng biểu.

> **Lưu ý:** Chỉ nên dùng Microsoft Word để mở và chỉnh sửa. Mẫu được tạo dựa vào danh sách nhiều cấp và field tự động trong Word, các phần mềm khác có thể hiển thị số thứ tự và số trang lệch.

## Bộ style chính

| Style | Dùng cho |
|-------|----------|
| Tiêu đề bìa / Tiêu đề giữa | Tiêu đề trang bìa và các mục đầu bài (Lời cam kết, Mục lục...) |
| Heading 1 | Cấp Phần lớn (Phần nội dung, Danh mục tài liệu tham khảo, Phụ lục), không đánh số |
| Heading 2 | Tên Chương, tự sinh `CHƯƠNG X:` |
| Heading 3 / 4 / 5 | Mục con, tự sinh `1.1.`, `1.1.1.`, `1.1.1.1.` |
| Nội dung / Nội dung không thụt lề | Văn bản chính (thụt đầu dòng 1 cm) và đoạn dẫn nhập (không thụt) |
| Nội dung bảng + Table Grid | Mọi ô dữ liệu trong bảng |
| Hình ảnh / Tên hình ảnh | Ảnh (In Line with Text) và chú thích `Hình X.Y:` đặt dưới ảnh |
| Tên bảng | Chú thích `Bảng X.Y:` đặt phía trên bảng |
| Danh sách | Liệt kê gạch đầu dòng |
| Code Block | Mã nguồn, đặt trong bảng 1 dòng 1 cột |
| Phụ lục - Tiêu đề / Phụ lục - Mục | Tự sinh `PHỤ LỤC A.`, `A.1.`, sau đó `B`, `B.1`... |

Chi tiết từng style xem trong `huong-dan-su-dung.docx`.

## Xoay ngang trang cho bảng hoặc sơ đồ rộng

1. Chèn **Section Break (Next Page)** trước và sau phần cần xoay: **Layout → Breaks → Section Breaks → Next Page**.
2. Đặt con trỏ vào trang đó, chọn **Layout → Orientation → Landscape**. Lề gợi ý: Top 3.0 cm, Bottom 2.0 cm, Left 2.5 cm, Right 2.5 cm.
3. Ở Footer của trang ngang và trang dọc phía sau, bật **Link to Previous**, rồi vào **Format Page Numbers** và chọn **Continue from previous section** để số trang liên tục.

## Quy cách trang trong mẫu

| Thông số | Giá trị |
|----------|---------|
| Khổ giấy | A4 |
| Lề | Trên 2.5 cm, dưới 2.5 cm, trái 3 cm, phải 2 cm |
| Phông chữ | Times New Roman 14pt |
| Giãn dòng | 1.5 cho nội dung, 1.0 cho bảng |
| Đánh số trang | Trang bìa và phần đầu không đánh số, bắt đầu từ 1 tại Phần nội dung |


## Tác giả

Mẫu được tạo bởi [@ductuongug](https://github.com/ductuongne).