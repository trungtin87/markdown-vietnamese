---
title: Writerside
category: "websites"
description: "Writerside là một môi trường viết và xuất bản kỹ thuật mới từ JetBrains."
icon: writerside.png
website: https://www.jetbrains.com/writerside/
syntax:
  - id: headings
    available: y
  - id: paragraphs
    available: y
  - id: line-breaks
    available: n
  - id: bold
    available: y
  - id: italic
    available: y
  - id: blockquotes
    available: y
    notes: "Theo mặc định, đánh dấu trích dẫn khối sẽ chuyển thành một khối lời khuyên răn được gọi là mẹo. Người ta có thể thay đổi loại khối thành ghi chú hoặc cảnh báo. Đọc thêm tại đây: <https://www.jetbrains.com/help/writerside/admonition-blocks.html>."
  - id: ordered-lists
    available: y
  - id: unordered-lists
    available: y
  - id: code
    available: y
  - id: horizontal-rules
    available: n
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
    available: n
  - id: heading-ids
    available: y
  - id: definition-lists
    available: y
  - id: strikethrough
    available: y
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
    available: n
---

[Writerside](https://www.jetbrains.com/writerside/) là một môi trường viết và xuất bản kỹ thuật mới từ JetBrains. Nó bao gồm một trình soạn thảo, một trình tạo trang web tĩnh và một giao diện người dùng có thể tùy chỉnh được thiết kế riêng cho tài liệu kỹ thuật.
Được tạo bởi JetBrains, Writerside dựa trên nền tảng IntelliJ.

Writerside sử dụng bộ xử lý Markdown [flexmark](https://github.com/vsch/flexmark-java).

{% include tool-syntax-table.html %}
