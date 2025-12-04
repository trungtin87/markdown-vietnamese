---
title: Dendron
category: "notes"
description: "Dendron là một công cụ ghi chú Markdown được xây dựng trên VS Code."
icon: dendron.png
website: https://www.dendron.so/
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
    notes: "Bạn có thể liên kết đến các ghi chú khác trong Dendron bằng cách sử dụng cú pháp `[[Tên liên kết|tên file]]`."
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
    available: y
  - id: definition-lists
    available: y
  - id: strikethrough
    available: y
  - id: task-lists
    available: y
  - id: emoji-cp
    available: y
  - id: emoji-sc
    available: y
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
see-also:
  - name: Định dạng phong phú
    link: https://wiki.dendron.so/notes/8DCgctK-RMD4EeHjC5_hI/
  - name: Dendron Markdown
    link: https://wiki.dendron.so/notes/ba97866b-889f-4ac6-86e7-bb2d97f6e376/
  - name: Tự lưu trữ xuất bản bằng Netlify
    link: https://wiki.dendron.so/notes/yetuum6o9wZi6eVJQBbQb/
---

[Dendron](https://www.dendron.so) là một công cụ ghi chú Markdown mã nguồn mở được xây dựng trên [VS Code](/tools/vscode/). Nếu bạn đã cài đặt VS Code trên máy tính của mình, bạn có thể cài đặt [tiện ích mở rộng Dendron](https://link.dendron.so/vscode) để bắt đầu. Tiện ích mở rộng Dendron miễn phí sử dụng. [Các tùy chọn trả phí](https://accounts.dendron.so/account/subscribe) có sẵn cho những người cần các tùy chọn xuất bản được lưu trữ và hỗ trợ ưu tiên.

Dendron rõ ràng dành cho đối tượng nhà phát triển. Công cụ này yêu cầu kiến thức tiên quyết về VS Code, và hầu hết mọi người có thể sẽ cần dành chút thời gian đọc [tài liệu](https://wiki.dendron.so/), khám phá các tính năng và nắm vững các phím tắt. Điểm bán hàng lớn nhất đối với người dùng Dendron có thể là công cụ này nằm trong VS Code. Các công cụ tương tự như [Obsidian](/tools/obsidian/) nằm trong các ứng dụng độc lập, riêng biệt — chúng có thể có ít tính năng hơn, nhưng chúng cũng có rào cản gia nhập thấp hơn.

{% include image.html file="/assets/images/tools/dendron.png" alt="Ứng dụng Markdown Dendron" %}

{% include tool-syntax-table.html %}

### Hỗ trợ cho các Phần tử Cú pháp Bổ sung

Như một phần thưởng thêm, Dendron cung cấp hỗ trợ cho một số phần tử ít người biết đến.

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
