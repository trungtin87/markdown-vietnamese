---
title: Logseq
category: "notes"
description: "Logseq là một ứng dụng ghi chú mã nguồn mở hỗ trợ cú pháp Markdown và Orgmode."
icon: logseq.png
website: https://logseq.com
syntax:
  - id: headings
    available: y
  - id: paragraphs
    available: y
    notes: "Mỗi đoạn văn bắt đầu bằng một ký tự gạch nối (`-`)"
  - id: line-breaks
    available: y
    notes: "Sử dụng ký tự CR (`\\r`)"
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
    available: n
    notes: "Chưa được hỗ trợ, nhưng nó nằm trong lộ trình"
  - id: heading-ids
    available: n
  - id: definition-lists
    available: n
  - id: strikethrough
    available: y
  - id: task-lists
    available: n
    notes: "Logseq có các lệnh được xác định trước cho việc này: TODO/DOING/DONE hoặc LATER/NOW"
  - id: emoji-cp
    available: y
  - id: emoji-sc
    available: n
  - id: highlight
    available: y
  - id: subscript
    available: n
    notes: "Sử dụng `X_{sub}`"
  - id: superscript
    available: n
    notes: "Sử dụng `X^{super}`"
  - id: auto-url-linking
    available: y
  - id: disabling-auto-url
    available: n
  - id: html
    available: y
    notes: "Yêu cầu thẻ XHTML: thẻ phải được đóng hoặc tự đóng (ví dụ: `<p/>`)"
see-also:
  - name: Tài liệu Logseq
    link: https://docs.logseq.com/
---

[Logseq](https://logseq.com) là một ứng dụng ghi chú mã nguồn mở hỗ trợ cú pháp Markdown và Orgmode. Vì nó ưu tiên quyền riêng tư, mọi thứ được lưu trữ cục bộ trên máy của bạn cho các ứng dụng máy tính để bàn và web. Có [các ứng dụng di động](https://logseq.com/downloads) có sẵn cho các thiết bị iOS và Android.

Logseq cung cấp một bộ tính năng rất hứa hẹn: Back links, biểu đồ ghi chú (lấy cảm hứng từ Roam Research), tạo thẻ tự động (để học tập), mẫu, và nhiều hơn nữa.

{% include image.html file="{{ site.baseurl }}/assets/images/tools/logseq.png" alt="Ứng dụng Logseq" %}

{% include tool-syntax-table.html %}
