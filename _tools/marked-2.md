---
title: Marked 2
category: "documents"
description: "Marked 2 cho phép bạn xem trước (không chỉnh sửa) các file Markdown trên máy Mac của bạn."
icon: marked2.png
website: https://marked2app.com/
syntax:
  - id: headings
    available: y
  - id: paragraphs
    available: y
  - id: line-breaks
    available: y
    notes: "MultiMarkdown không hỗ trợ dấu gạch chéo ngược ở cuối."
  - id: bold
    available: y
  - id: italic
    available: y
  - id: blockquotes
    available: y
  - id: ordered-lists
    available: y
  - id: unordered-lists
    available: p
    notes: "MultiMarkdown không hỗ trợ danh sách không có thứ tự lồng nhau. Hoạt động với Discount."
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
    available: n
  - id: footnotes
    available: y
  - id: heading-ids
    available: p
    notes: "Chỉ hoạt động với MultiMarkdown."
  - id: definition-lists
    available: p
    notes: "Discount không hỗ trợ tính năng này. Hoạt động với MultiMarkdown."
  - id: strikethrough
    available: p
    notes: "MultiMarkdown không hỗ trợ tính năng này. Hoạt động với Discount."
  - id: task-lists
    available: y
  - id: emoji-cp
    available: y
  - id: emoji-sc
    available: y
  - id: highlight
    available: n
  - id: subscript
    available: n
  - id: superscript
    available: y
  - id: auto-url-linking
    available: y
  - id: disabling-auto-url
    available: p
    notes: "Discount không hỗ trợ tính năng này."
  - id: html
    available: y
---

[Marked 2](https://marked2app.com/) là một ứng dụng Mac độc quyền giúp bạn xem trước (không chỉnh sửa) các file Markdown trên máy Mac của bạn. Công dụng rõ ràng của ứng dụng này là như một loại "trình hiển thị Markdown trên máy tính để bàn còn thiếu" — chỉ cần kéo và thả một file Markdown vào biểu tượng Marked 2 và bạn sẽ thấy nó được hiển thị. Ví dụ, người ta có thể tưởng tượng một giáo viên sử dụng ứng dụng này để đọc và chấm điểm các bài tập được nộp điện tử dưới dạng file Markdown. Nhưng có rất nhiều công dụng khác cho Marked 2.

Hãy xem xét rằng trong khi nhiều trình soạn thảo mới hơn như Atom và [VS Code](/tools/vscode/) có chức năng xem trước Markdown được tích hợp sẵn, nhiều trình soạn thảo cũ hơn thì không. Marked 2 được thiết kế cho những người sử dụng các trình soạn thảo như Vim. Bạn có thể sắp xếp cửa sổ Marked 2 bên cạnh Vim để xem trước trực tiếp file Markdown được hiển thị của bạn sẽ trông như thế nào.

Rõ ràng là tác giả của tiện ích này đã đầu tư rất nhiều thời gian và công sức để làm cho mọi thứ trở nên đúng đắn. Chính sự chú ý đến từng chi tiết làm cho ứng dụng này xứng đáng với mức giá yêu cầu. Ví dụ, khi bạn mở Marked 2, một trợ lý thiết lập sẽ hướng dẫn bạn cấu hình các tùy chọn hiển thị để hỗ trợ trường hợp sử dụng cụ thể của bạn (Marked 2 thực sự chứa hai bộ xử lý Markdown: MultiMarkdown và Discount). Rất khuyến khích cho người dùng Mac cần một cách đáng tin cậy để xem trước hoặc xuất các file Markdown (kiểm tra [các kiểu có sẵn](https://marked2app.com/styles/)).

{% include image.html file="/assets/images/tools/marked2-1.png" alt="Lựa chọn bộ xử lý Marked 2." %}

{% include tool-syntax-table.html %}

### Hỗ trợ cho các Phần tử Cú pháp Bổ sung

Như một phần thưởng thêm, Marked 2 cung cấp hỗ trợ cho một số phần tử ít người biết đến khi sử dụng MultiMarkdown.

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
      <td>Gạch chân</td>
      <td><code>_từ hoặc cụm từ_</code></td>
      <td><ins>từ hoặc cụm từ</ins></td>
    </tr>
  </tbody>
</table>
