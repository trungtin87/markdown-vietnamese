---
title: Typemill
category: "websites"
description: "Typemill là một CMS mã nguồn mở cho các trang web và sách điện tử ở định dạng pdf và epub."
icon: typemill.png
website: https://typemill.net
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
    available: p
    notes: "Tô sáng cú pháp có sẵn trong trình soạn thảo markdown thô và trong frontend với một plugin có thể."    
  - id: footnotes
    available: y
  - id: heading-ids
    available: y
    notes: "Có thể được kích hoạt trong cài đặt."
  - id: definition-lists
    available: y
  - id: strikethrough
    available: n
  - id: task-lists
    available: n
  - id: emoji-cp
    available: n
  - id: emoji-sc
    available: n
  - id: highlight
    available: n
  - id: subscript
    available: n
  - id: superscript
    available: y
  - id: auto-url-linking
    available: y
  - id: disabling-auto-url
    available: n
  - id: html
    available: p
    notes: "HTML bị tắt theo mặc định vì lý do bảo mật nhưng bạn có thể sử dụng nhiều thẻ html khác nhau với một plugin sử dụng tính năng shortcode."
---
[Typemill](https://typemill.net) là một hệ thống quản lý nội dung (CMS) nhẹ để tạo các trang web và sách điện tử ở định dạng PDF và ePub. Typemill đặc biệt phổ biến trong các công ty vừa và nhỏ để tạo tài liệu và hướng dẫn sử dụng cho phần mềm, sản phẩm vật lý và dịch vụ.

{% include image.html file="/assets/images/tools/typemill.gif" alt="Trình soạn thảo markdown Typemill" %}

Typemill được xây dựng bằng Vue.js và PHP. Nó sử dụng thư viện Parsedown được áp dụng rộng rãi để chuyển đổi Markdown.

{% include tool-syntax-table.html %}
