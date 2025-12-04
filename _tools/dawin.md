---
title: Dawin (محرر دوّن)
category: "online editor"
description: "Dawin là một trình soạn thảo Markdown RTL dựa trên web được thiết kế để sử dụng ở mọi nơi."
icon: dawin.png
website: https://dawin.io
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
    notes: "Không có khả năng tải lên hình ảnh — bạn sẽ cần lưu trữ hình ảnh trên một máy chủ khác."
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
    available: y
    notes: "Bạn không cần phải sử dụng dấu gạch ngang. Chỉ cần sử dụng dấu ngoặc vuông (ví dụ: `[ ]`)."
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
    available: y
  - id: disabling-auto-url
    available: y
  - id: html
    available: n
see-also:
  - name: Kho lưu trữ Dawin (trình soạn thảo Markdown RTL) trên GitHub
    link: https://github.com/dawin-editor
  - name: Hướng dẫn Markdown bằng tiếng Ả Rập
    link: https://guide.dawin.io/
---

[Dawin](https://www.dawin.io/) (còn gọi là *Writer in Arabic Language*) là một trình soạn thảo Markdown trực tuyến từ phải sang trái (RTL) (dành cho tiếng Ả Rập, tiếng Ba Tư, v.v.). Giống như [StackEdit](/tools/stackedit/), nó tải ngay trong trình duyệt web của bạn mà không cần phải cài đặt bất cứ thứ gì. Dawin có hai khung: Trình soạn thảo ở bên phải và bản xem trước trực tiếp ở bên trái. Các khung chia nhỏ giúp bạn dễ dàng xem văn bản được định dạng Markdown trông như thế nào.

Dawin cung cấp hỗ trợ Markdown tuyệt vời và có các tùy chọn xuất cho các file HTML và Markdown. Và vì Dawin tải trong trình duyệt web của bạn, bạn có thể xem trước nó trên trình duyệt hoặc điện thoại của mình và cài đặt nó ở bất cứ đâu bạn muốn — nó cũng hoạt động ngoại tuyến (PWA). Vì những lý do đó, Dawin được sử dụng tốt nhất để thử nghiệm và ghi chú nhanh.

Ứng dụng sử dụng bộ xử lý Markdown [markdown-it](https://github.com/markdown-it/markdown-it) và [simplemde-rtl](https://github.com/imAbdelhadi/simplemde-rtl).

{% include image.html file="{{ site.baseurl }}/assets/images/dawin.png" alt="Trình soạn thảo Markdown RTL Dawin" %}

{% include tool-syntax-table.html %}
