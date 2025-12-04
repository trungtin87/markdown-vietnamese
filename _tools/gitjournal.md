---
title: GitJournal
category: "notes"
description: "GitJournal là một trình soạn thảo Markdown ưu tiên thiết bị di động được tích hợp với Git."
icon: gitjournal.png
website: https://gitjournal.io
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
    available: n
  - id: footnotes
    available: n
  - id: heading-ids
    available: n
  - id: definition-lists
    available: n
  - id: strikethrough
    available: y
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
    available: n
  - id: auto-url-linking
    available: y
  - id: disabling-auto-url
    available: n
  - id: html
    available: n
see-also:
  - name: Kho lưu trữ GitJournal trên GitHub
    link: https://github.com/GitJournal/GitJournal
---

[GitJournal](https://gitjournal.io) là một trình soạn thảo Markdown ưu tiên thiết bị di động được tích hợp với Git.

Nó hỗ trợ đồng bộ hóa các ghi chú của bạn bằng cách sử dụng bất kỳ kho lưu trữ git nào có thể truy cập qua SSH, bao gồm GitHub, GitLab, Gitea hoặc máy chủ của riêng bạn. Toàn bộ cơ sở mã cũng hoàn toàn là mã nguồn mở. GitJournal tập trung vào việc cung cấp cho người dùng quyền kiểm soát dữ liệu của họ và cho phép họ truy cập nó bằng nhiều thiết bị bằng giao thức mở và nổi tiếng: git. Có nhiều nhà cung cấp dịch vụ lưu trữ git miễn phí và thương mại khác nhau, và việc thiết lập máy chủ git của riêng bạn có rào cản gia nhập thấp hơn bất kỳ giải pháp đồng bộ hóa nào khác.

GitJournal cũng cho phép bạn dễ dàng liên kết các ghi chú của mình với nhau bằng liên kết kiểu Wiki - ``[[TênFile]]``. Điều này cho phép bạn dễ dàng liên kết các ý tưởng khác nhau và thậm chí xây dựng cơ sở kiến thức của riêng bạn.

{% include tool-syntax-table.html %}

### Hỗ trợ cho các Phần tử Cú pháp Bổ sung

Như một phần thưởng thêm, GitJournal cung cấp hỗ trợ cho một số phần tử ít người biết đến.

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
      <td>WikiLinks</td>
      <td><code>[[TênTrang]]</code></td>
      <td>Liên kết đến file <code>TênTrang.md</code></td>
    </tr>
  </tbody>
</table>
