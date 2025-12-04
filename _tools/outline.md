---
title: Outline
category: "wiki"
description: "Outline là một cơ sở kiến thức và wiki hiện đại cho các nhóm."
icon: outline.png
website: https://www.getoutline.com
syntax:
  - id: headings
    available: y
  - id: paragraphs
    available: y
  - id: line-breaks
    available: y
    notes: "Trình soạn thảo Outline duy trì ngắt dòng theo mặc định mà không cần cú pháp bổ sung."
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
    available: p
    notes: "Bạn không thể nhập chúng trong trình soạn thảo của Outline. Sử dụng lệnh gạch chéo `/table` hoặc thanh công cụ chèn khối."
  - id: fenced-code-blocks
    available: y
  - id: syntax-highlighting
    available: y
  - id: footnotes
    available: n
  - id: heading-ids
    available: p
    notes: "Bạn không thể nhập chúng trong trình soạn thảo của Outline, nhưng tất cả các tiêu đề đều được cấp một ID duy nhất theo mặc định."
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
    available: n
  - id: subscript
    available: n
  - id: superscript
    available: n
  - id: auto-url-linking
    available: n
  - id: disabling-auto-url
    available: n
  - id: html
    available: n
see-also:
  - name: Trình soạn thảo mã nguồn mở
    link: https://github.com/outline/rich-markdown-editor
---

[Outline](https://www.getoutline.com) là một cơ sở kiến thức và wiki nhanh được thiết kế cho các nhóm. Trình soạn thảo trực tiếp của Outline hỗ trợ nhiều phím tắt Markdown. Các tài liệu được tạo trong ứng dụng được lưu trữ ở định dạng Markdown và cũng có thể được xuất dưới dạng Markdown, vì vậy bạn không bao giờ bị khóa.

Ngoài Markdown, Outline hỗ trợ một loạt các tính năng như tổ chức tài liệu có cấu trúc, tìm kiếm, quyền đọc/ghi, nhóm người dùng, backlinking, chia sẻ công khai và hơn thế nữa.

{% include image.html file="assets/images/tools/outline.png" alt="Ảnh chụp màn hình Outline" %}

Outline được cung cấp dưới dạng dịch vụ được lưu trữ và cũng có sẵn để tự lưu trữ dưới dạng vùng chứa docker. [Mã nguồn được công khai](https://github.com/outline/outline) trên GitHub.

{% include tool-syntax-table.html %}
