---
title: Things
category: "tasks"
description: "Things là một trình quản lý tác vụ cho các thiết bị Apple cung cấp hỗ trợ Markdown."
icon: things.png
website: https://culturedcode.com/things/
syntax:
  - id: headings
    available: p
    notes: "[Cú pháp thay thế](/basic-syntax/#alternate-syntax) không được hỗ trợ."
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
    available: p
    notes: "Cú pháp được hỗ trợ, nhưng bản thân các quy tắc ngang không được hiển thị trong ứng dụng."
  - id: links
    available: y
  - id: images
    available: p
    notes: "Cú pháp được hỗ trợ, nhưng bản thân các hình ảnh không được hiển thị trong ứng dụng."
  - id: tables
    available: n
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
    available: n
  - id: highlight
    available: y
    notes: "Sử dụng hai dấu hai chấm thay vì dấu bằng (ví dụ: `::từ hoặc cụm từ::`)."
  - id: subscript
    available: n
  - id: superscript
    available: n
  - id: auto-url-linking
    available: y
  - id: disabling-auto-url
    available: y
  - id: html
    available: n
see-also:
  - name: Hướng dẫn Markdown Things
    link: https://culturedcode.com/things/support/articles/4651820/
---

[Things](https://culturedcode.com/things/) là một ứng dụng quản lý tác vụ độc quyền cho các thiết bị Apple. Có sẵn trong hơn một thập kỷ, Things có một lượng người theo dõi giống như giáo phái và nổi tiếng về thiết kế và tính dễ sử dụng. Vào tháng 8 năm 2021, Things đã thêm hỗ trợ Markdown trong phiên bản 3.14.

Things không hỗ trợ tất cả các phần tử cú pháp Markdown, nhưng các phần tử mà nó hỗ trợ có ý nghĩa trong bối cảnh của ứng dụng. Những người sử dụng Things không sử dụng nó để viết bài đăng trên blog — họ đang ghi chú ngắn.

{% include image.html file="assets/images/tools/things.png" alt="Markdown trong ứng dụng Things cho Mac" width="80" %}

Things ánh xạ định dạng Markdown với các phím tắt bàn phím để bạn không phải thực sự nhập các ký tự cần thiết để thêm định dạng Markdown. Ví dụ, bạn không phải nhập `**` để làm cho từ của bạn in đậm (mặc dù bạn có thể). Thay vào đó, bạn chỉ cần nhấn Command-B và Things sẽ bao bọc từ của bạn bằng dấu sao kép.

{% include tool-syntax-table.html %}
