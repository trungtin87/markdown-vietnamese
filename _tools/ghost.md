---
title: Ghost
category: "websites"
description: "Ghost là một CMS mã nguồn mở nổi tiếng về tốc độ, sự đơn giản và dễ sử dụng."
icon: ghost.png
website: https://ghost.org/
syntax:
  - id: headings
    available: y
  - id: paragraphs
    available: y
  - id: line-breaks
    available: y
    notes: "Bạn có thể sử dụng dấu gạch chéo ngược ở cuối (`\\`) thay vì khoảng trắng ở cuối."
  - id: bold
    available: y
  - id: italic
    available: y
  - id: blockquotes
    available: p
    notes: Trích dẫn khối lồng nhau không được hỗ trợ.
  - id: ordered-lists
    available: p
    notes: Danh sách lồng nhau không được hỗ trợ.
  - id: unordered-lists
    available: p
    notes: Danh sách lồng nhau không được hỗ trợ.
  - id: code
    available: y
  - id: horizontal-rules
    available: y
  - id: links
    available: y
  - id: images
    available: y
  - id: tables
    available: n
  - id: fenced-code-blocks
    available: y
  - id: syntax-highlighting
    available: y
  - id: footnotes
    available: y
  - id: heading-ids
    available: p
    notes: "Được tạo tự động. Không có cách nào để đặt ID tiêu đề tùy chỉnh."
  - id: definition-lists
    available: n
  - id: strikethrough
    available: y
  - id: task-lists
    available: n
  - id: emoji-cp
    available: u
  - id: emoji-sc
    available: u
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
see-also:
  - name: Sử dụng Markdown trong Ghost
    link: https://ghost.org/faq/using-the-editor/#using-markdown
---

[Ghost](https://ghost.org/) là một hệ thống quản lý nội dung (CMS) tương đối mới để viết blog cạnh tranh với các sản phẩm CMS lâu đời hơn, đã được thiết lập như WordPress và Drupal. Ghost là một dự án mã nguồn mở nổi tiếng về tốc độ, sự đơn giản và dễ sử dụng. Hỗ trợ Markdown là tiêu chuẩn và có sẵn ngay lập tức.

{% include image.html file="{{ site.baseurl }}/assets/images/tools/ghost.png" alt="Trình soạn thảo blog Ghost" %}

Có một vài vấn đề tương thích nhỏ được ghi chú bên dưới nhưng, nói chung, Ghost có hỗ trợ Markdown vững chắc. Trình soạn thảo trực tiếp khá trực quan và có vẻ là một lựa chọn tốt cho các blogger. Sao chép và dán văn bản được định dạng Markdown vào trình soạn thảo hoạt động theo cách bạn mong đợi.

{% include tool-syntax-table.html %}
