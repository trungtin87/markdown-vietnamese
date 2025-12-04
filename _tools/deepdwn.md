---
title: Deepdwn
category: notes
description: "Deepdwn là một bộ công cụ chỉnh sửa Markdown cho Windows, Mac và Linux."
icon: deepdwn.png
website: https://www.deepdwn.com
syntax:
  - id: headings
    available: y
  - id: paragraphs
    available: y
  - id: line-breaks
    available: y
  - id: bold
    available: y
  - id: italic
    available: y
  - id: blockquotes
    available: y
  - id: ordered-lists
    available: y
  - id: unordered-lists
    available: y
  - id: code
    available: y
  - id: horizontal-rules
    available: y
  - id: links
    available: y
  - id: images
    available: y
  - id: tables
    available: y
  - id: fenced-code-blocks
    available: y
  - id: syntax-highlighting
    available: y
  - id: footnotes
    available: y
  - id: heading-ids
    available: p
    notes: ID tiêu đề được tạo tự động và liên kết đến các tiêu đề thông qua tự động hoàn thành.
  - id: definition-lists
    available: y
  - id: strikethrough
    available: y
  - id: task-lists
    available: y
  - id: emoji-cp
    available: y
  - id: emoji-sc
    available: n
  - id: highlight
    available: y
  - id: subscript
    available: y
  - id: superscript
    available: y
  - id: auto-url-linking
    available: y
  - id: disabling-auto-url
    available: y
  - id: html
    available: y
---

[Deepdwn](https://billiam.itch.io/deepdwn) là một trình soạn thảo Markdown ngoại tuyến, giàu tính năng dành cho Windows, Mac và Linux.

{% include image.html file="assets/images/tools/deepdwn.png" alt="Cửa sổ ứng dụng Deepdwn với các bảng cho bộ lọc, danh sách file, dàn ý tài liệu và trình soạn thảo." %}

Deepdwn hỗ trợ tổ chức tài liệu theo cả thẻ và danh mục được lưu trữ trong front matter YAML của tài liệu của bạn, và hỗ trợ backlinks để kết nối các tài liệu với nhau.

Deepdwn có một số tính năng chỉnh sửa, như dàn ý tài liệu, chế độ không xao nhãng, tự động định dạng và chỉnh sửa bảng, phím tắt Vim và Emacs, tiếp tục danh sách tự động, gập phần liên tục, kéo và thả hình ảnh và xem trước hình ảnh trong trình soạn thảo, lịch sử đếm từ theo file và toàn cầu, và các hiệu ứng đặc biệt cho chuỗi viết.

Deepdwn cũng hỗ trợ một số phần tử khối bổ sung:

* Sơ đồ Mermaid
* AsciiMath, Katex, và mhchem để hiển thị toán học và hóa học
* Bản nhạc, tab guitar và sách bài hát

{% include tool-syntax-table.html %}

### Hỗ trợ cho các Phần tử Cú pháp Bổ sung

Như một phần thưởng thêm, Deepdwn cung cấp hỗ trợ cho một số phần tử ít người biết đến.

<table class="table table-bordered" style="font-size: 14px">
  <thead class="thead-light">
    <tr>
      <th>Phần tử</th>
      <th>Markdown</th>
      <th>Kết quả hiển thị</th>
    </tr>
  </thead>
  <tbody>
      <tr>
      <td>Viết tắt</td>
      <td><code>*[HTML]: Hyper Text Markup Language</code><br>
      <code>Đặc tả HTML được duy trì bởi W3C.</code></td>
      <td>Đặc tả <abbr title="Hyper Text Markup Language">HTML</abbr> được duy trì bởi W3C.</td>
    </tr>
    <tr>
      <td>Căn giữa</td>
      <td><code>-&gt;Văn bản này đã được căn giữa&lt;-</code></td>
      <td><center>Văn bản này đã được căn giữa</center></td>
    </tr>
  </tbody>
</table>
