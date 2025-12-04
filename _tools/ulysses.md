---
title: Ulysses
category: "documents"
description: "Ulysses là một ứng dụng viết phổ biến cho các thiết bị macOS và iOS."
icon: ulysses.png
website: https://ulysses.app
syntax:
  - id: headings
    available: y
    notes: "[Cú pháp thay thế](/basic-syntax/#alternate-syntax) không được hỗ trợ."
  - id: paragraphs
    available: y
  - id: line-breaks
    available: y
    notes: "Ngoài khoảng trắng ở cuối, bạn cũng có thể nhấn phím Return một lần để đạt được kết quả tương tự."
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
    available: p
    notes: "[Khối mã](/basic-syntax/#code-blocks) không được hỗ trợ."
  - id: horizontal-rules
    available: p
    notes: "Phải sử dụng bốn dấu gạch ngang (`----`)."
  - id: links
    available: n
    notes: "Cú pháp Markdown không được hỗ trợ, nhưng bạn có thể thêm liên kết bằng cách sử dụng menu Markup."
  - id: images
    available: n
    notes: "Cú pháp Markdown không được hỗ trợ, nhưng bạn có thể thêm hình ảnh bằng cách sử dụng menu Markup."
  - id: tables
    available: n
  - id: fenced-code-blocks
    available: n
    notes: "Cú pháp Markdown không được hỗ trợ, nhưng bạn có thể thêm khối mã bằng cách sử dụng menu Markup."
  - id: syntax-highlighting
    available: n
    notes: "Cú pháp Markdown không được hỗ trợ, nhưng bạn có thể chỉ định ngôn ngữ bằng cách sử dụng giao diện."
  - id: footnotes
    available: n
    notes: "Cú pháp Markdown không được hỗ trợ, nhưng bạn có thể thêm chú thích cuối trang bằng cách sử dụng menu Markup."
  - id: heading-ids
    available: n
  - id: definition-lists
    available: n
  - id: strikethrough
    available: p
    notes: "Cú pháp Markdown không được hỗ trợ, nhưng bạn có thể sử dụng hai dấu gạch đứng ở hai đầu của một từ hoặc cụm từ (`||gạch bỏ cái này||`)."
  - id: task-lists
    available: y
    notes: "Bạn không cần phải sử dụng dấu gạch ngang. Chỉ cần sử dụng dấu ngoặc vuông (ví dụ: `[ ]`)."
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
    available: n
  - id: disabling-auto-url
    available: y
    notes: "Bạn không cần sử dụng cái này vì các URL không được liên kết tự động."
  - id: html
    available: n
---

[Ulysses](https://ulysses.app) là một ứng dụng viết phổ biến cho các thiết bị macOS và iOS. Được ca ngợi bởi các nhà báo và người đánh giá, Ulysses cung cấp rất nhiều tính năng hữu ích và những điểm nhấn tuyệt vời cho những người viết chuyên nghiệp. Các tùy chọn chủ đề và xuất là không ai sánh kịp.

Thật không may, sử dụng Ulysses để viết bằng Markdown là một bài tập gây thất vọng. Ứng dụng hỗ trợ một tập hợp con của cú pháp Markdown, nhưng hỗ trợ cho nhiều phần tử cú pháp vắng mặt đáng kể. Thậm chí tệ hơn, hỗ trợ cho một số phần tử được cung cấp bằng cách sử dụng ký hiệu không chuẩn. Ulysses có thể không phải là lựa chọn đầu tiên của bạn nếu bạn muốn viết độc quyền bằng Markdown.

{% include image.html file="assets/images/tools/ulysses.png" alt="Ứng dụng Ulysses với một file Markdown" %}

{% include tool-syntax-table.html %}
