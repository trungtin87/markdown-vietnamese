---
title: Buttondown
category: "email"
description: "Buttondown là một nền tảng email để chạy bản tin của bạn."
icon: buttondown.png
website: https://buttondown.com/
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
    available: n
  - id: html
    available: p
    notes: "Một số HTML được làm sạch."
---

[Buttondown](https://buttondown.com) là một nền tảng email, tương tự như [TinyLetter](https://buttondown.com/comparisons/tinyletter) hiện đã ngừng hoạt động, cho phép bạn gửi email cho người đăng ký. Nó cũng tích hợp với nhiều nền tảng khác để tự động xuất bản hoặc thêm người đăng ký, cùng với các khả năng khác.

Trình soạn thảo email [hỗ trợ Markdown](https://buttondown.com/features/markdown), với khả năng chuyển sang trình soạn thảo WYSIWYG cho những người thích nó hơn.

{% include image.html file="{{ site.baseurl }}/assets/images/tools/buttondown.png" alt="Trình soạn thảo email Buttondown" %}

Có một vài vấn đề tương thích nhỏ được ghi chú bên dưới nhưng, nói chung, Buttondown có hỗ trợ Markdown vững chắc. Theo [tài liệu của họ](https://docs.buttondown.com/using-markdown), nó sử dụng Python-Markdown để phân tích cú pháp và hiển thị cùng với một vài tiện ích mở rộng. Trình soạn thảo trực tiếp khá trực quan và cung cấp cho bạn bản xem trước về cách email sẽ trông như thế nào trong cả kho lưu trữ và trong các ứng dụng email như Gmail. Sao chép và dán văn bản được định dạng Markdown vào trình soạn thảo hoạt động theo cách bạn mong đợi.

{% include tool-syntax-table.html %}
