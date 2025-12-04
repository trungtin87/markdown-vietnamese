---
title: Byword
category: "documents"
description: "Byword là một trình soạn thảo Markdown có năng lực dành cho macOS và iOS."
icon: byword.png
website: https://bywordapp.com
notes: Tôi chỉ mới thử nghiệm ứng dụng Mac, chưa thử ứng dụng iOS. Có lẽ nên thử nghiệm cả hai trong tương lai.
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
    available: p
    notes: "Danh sách lồng nhau không được hỗ trợ."
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
    available: n
  - id: definition-lists
    available: y
  - id: strikethrough
    available: n
  - id: task-lists
    available: n
  - id: emoji-cp
    available: y
  - id: emoji-sc
    available: n
  - id: highlight
    available: n
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

[Byword](https://bywordapp.com) là trình soạn thảo Markdown đơn giản dành cho macOS và iOS. Bạn gõ văn bản được định dạng Markdown, sử dụng tùy chọn menu để gọi bản xem trước và xuất sang một trong số các định dạng file có sẵn bao gồm HTML, PDF, Microsoft Word và LaTeX. Bạn có thể xuất bản lên một số dịch vụ viết blog và tính năng đồng bộ hóa iCloud cho phép bạn soạn thảo và truy cập các file từ tất cả các thiết bị Apple của mình. Byword không hào nhoáng chút nào — một số người thậm chí có thể cảm thấy khó chịu bởi giao diện và cảm giác không đáng kể của ứng dụng — nhưng nó hoàn thành công việc.

{% include tool-syntax-table.html %}

### Hỗ trợ cho các Phần tử Cú pháp Bổ sung

Như một phần thưởng thêm, Byword cung cấp hỗ trợ cho một số phần tử ít người biết đến.

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
  </tbody>
</table>
