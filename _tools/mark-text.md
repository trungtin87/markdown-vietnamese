---
title: MarkText
category: documents
description: "MarkText là một trình soạn thảo miễn phí và mã nguồn mở phổ biến được thiết kế cho Markdown."
icon: mark-text.png
website: https://github.com/marktext/marktext
syntax:
  - id: headings
    available: y
  - id: paragraphs
    available: y
  - id: line-breaks
    available: y
    notes: "Có sự khác biệt giữa trình soạn thảo MarkText và đầu ra được hiển thị khi bạn nhấn phím Return một lần — điều đó *không* tạo ra ngắt dòng trong HTML và PDF đã xuất. Bạn phải sử dụng khoảng trắng ở cuối hoặc dấu gạch chéo ngược ở cuối (`\\`)."
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
    notes: "Vì một số lý do, [dấu ngoặc nhọn](/basic-syntax/#urls-and-email-addresses) cho URL và địa chỉ email được hiển thị theo nghĩa đen trong trình soạn thảo MarkText. Đó là một vấn đề nhỏ vì các liên kết được hiển thị chính xác trong HTML và PDF đã xuất."
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
    available: n
  - id: definition-lists
    available: n
  - id: strikethrough
    available: y
    notes: "Bạn có thể sử dụng hai dấu ngã (`~~từ~~`) hoặc một dấu ngã (`~từ~`) — cả hai đều hoạt động trong HTML và PDF đã xuất mặc dù trình soạn thảo MarkText chỉ hiển thị gạch ngang với hai dấu ngã."
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
  - name: Kho lưu trữ GitHub MarkText
    link: https://github.com/marktext/marktext
---

[MarkText](https://github.com/marktext/marktext) là một trình soạn thảo tài liệu miễn phí và mã nguồn mở phổ biến được thiết kế dành riêng cho việc viết bằng Markdown. Giống như [Typora](/tools/typora/), MarkText có giao diện bóng bẩy và trình soạn thảo trực tiếp ẩn định dạng Markdown sau khi bạn nhập. Các tùy chọn xuất PDF và HTML rất tiện dụng, cũng như tính năng cho phép bạn sao chép văn bản ra khỏi trình soạn thảo dưới dạng Markdown, HTML hoặc văn bản thuần túy.

Có một số phiền toái nhỏ. Trong một số trường hợp (được ghi chú bên dưới trong bảng), sự xuất hiện của văn bản trong ứng dụng không khớp với đầu ra được hiển thị của HTML và PDF đã xuất. Và cũng như với [Notion](/tools/notion/), có thể khó chỉnh sửa văn bản được định dạng Markdown sau khi trình soạn thảo trực tiếp đã chuyển đổi nó.

{% include tool-syntax-table.html %}
