---
title: Markdeep
category: "websites"
description: "Markdeep biến bất kỳ file Markdown nào thành một file HTML độc lập."
icon: markdeep.png
website: https://casual-effects.com/markdeep
notes: "đã thử nghiệm bằng cách sử dụng mẫu web Markdeep mặc định"
syntax:
  - id: headings
    available: y
  - id: paragraphs
    available: y
  - id: line-breaks
    available: n
  - id: bold
    available: p
    notes: "Dấu sao ở giữa một từ (tức là, `ở**giữa**đây`) được hiển thị theo nghĩa đen."
  - id: italic
    available: p
    notes: "Dấu sao ở giữa một từ (tức là, `ở*giữa*đây`) được hiển thị theo nghĩa đen."
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
    available: n
  - id: definition-lists
    available: y
  - id: strikethrough
    available: y
  - id: task-lists
    available: y
  - id: emoji-cp
    available: u
  - id: emoji-sc
    available: u
  - id: highlight
    available: n
  - id: subscript
    available: n
  - id: superscript
    available: n
  - id: auto-url-linking
    available: y
  - id: disabling-auto-url
    available: y
  - id: html
    available: y
---

[Markdeep](https://casual-effects.com/markdeep) là một công cụ miễn phí và đơn giản giúp biến bất kỳ file Markdown nào thành một file HTML độc lập có thể xem được trong trình duyệt web. Không có gì để cài đặt và không có dịch vụ nào để đăng ký — bạn chỉ cần thêm một dòng mã vào cuối file Markdown của mình. Đây là một lựa chọn tuyệt vời nếu bạn cần xem nhanh một file Markdown trong trình duyệt web hoặc chia sẻ một file Markdown với ai đó cần xem đầu ra được hiển thị.

Sử dụng Markdeep là một quy trình gồm ba phần:

1. Thêm thẻ sau cho Markdeep trên một dòng duy nhất ở cuối file Markdown.

    `<!-- Markdeep: --><style class="fallback">body{visibility:hidden;white-space:pre;font-family:monospace}</style><script src="markdeep.min.js" charset="utf-8"></script><script src="https://casual-effects.com/markdeep/latest/markdeep.min.js" charset="utf-8"></script><script>window.alreadyProcessedMarkdeep||(document.body.style.visibility="visible")</script>`

2. Đổi tên file Markdown để thêm phần mở rộng `.md.html` (tức là, `myfile.md.html`).
3. Mở file trong trình duyệt web để xem đầu ra được hiển thị.

Công cụ này có rất nhiều tính năng ngoài những gì được mô tả ở đây. Ví dụ, bạn có thể chọn từ nhiều mẫu khác nhau để tùy chỉnh giao diện trang của mình. Markdeep cũng hỗ trợ sơ đồ, sắp chữ LaTeX cho các phương trình, và nhiều hơn nữa. Kiểm tra [tài liệu](https://casual-effects.com/markdeep) tuyệt vời để biết chi tiết đầy đủ.

{% include tool-syntax-table.html %}
