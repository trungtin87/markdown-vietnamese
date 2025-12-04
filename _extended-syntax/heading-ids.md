---
title: Heading IDs
syntax-id: heading-ids
syntax-summary: "### My Great Heading {#custom-id}"
---

Nhiều bộ xử lý Markdown hỗ trợ ID tùy chỉnh cho [tiêu đề](/basic-syntax/#headings) — một số bộ xử lý Markdown tự động thêm chúng. Thêm ID tùy chỉnh cho phép bạn liên kết trực tiếp đến tiêu đề và sửa đổi chúng bằng CSS. Để thêm ID tiêu đề tùy chỉnh, hãy đặt ID tùy chỉnh trong dấu ngoặc nhọn trên cùng một dòng với tiêu đề.

```text
### My Great Heading {#custom-id}
```

HTML trông như thế này:

```html
<h3 id="custom-id">My Great Heading</h3>
```

### Liên Kết Đến ID Tiêu Đề

Bạn có thể liên kết đến tiêu đề với ID tùy chỉnh trong tệp bằng cách tạo [liên kết tiêu chuẩn](/basic-syntax/#links) với dấu thăng (`#`) theo sau là ID tiêu đề tùy chỉnh. Chúng thường được gọi là *liên kết neo*.

<table class="table table-bordered">
  <thead class="thead-light">
    <tr>
      <th>Markdown</th>
      <th>HTML</th>
      <th>Rendered Output</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><code class="highlighter-rouge">[Heading IDs](#heading-ids)</code></td>
      <td><code class="highlighter-rouge"> &lt;a href="#heading-ids"&gt;Heading IDs&lt;/a&gt;</code></td>
      <td><a href="#heading-ids">Heading IDs</a></td>
    </tr>
  </tbody>
</table>

Các trang web khác có thể liên kết đến tiêu đề bằng cách thêm ID tiêu đề tùy chỉnh vào URL đầy đủ của trang web (ví dụ: `[Heading IDs](https://www.markdownguide.org/extended-syntax#heading-ids)`).
