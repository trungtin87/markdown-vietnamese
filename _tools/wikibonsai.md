---
title: WikiBonsai
category:
  - notes
  - websites
description: "WikiBonsai là bộ sưu tập các công cụ mã nguồn mở cho việc làm vườn kỹ thuật số dựa trên markdown."
icon: wikibonsai.png
website: https://github.com/wikibonsai/wikibonsai
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
    notes: "Hiển thị hình ảnh trong xem trước tuân theo chính sách bảo mật nội dung, có thể điều chỉnh từ menu thả xuống ở góc trên bên phải"
  - id: tables
    available: y
  - id: fenced-code-blocks
    available: y
  - id: syntax-highlighting
    available: y
  - id: footnotes
    available: p
    notes: "Chỉ trong trình soạn thảo mã. Hỗ trợ toàn diện yêu cầu [tiện ích mở rộng Markdown Preview Enhanced](https://github.com/shd101wyy/vscode-markdown-preview-enhanced)."
  - id: heading-ids
    available: p
    notes: "Không hỗ trợ ID tùy chỉnh. Hỗ trợ toàn diện yêu cầu [tiện ích mở rộng Markdown Preview Enhanced](https://github.com/shd101wyy/vscode-markdown-preview-enhanced)."
  - id: definition-lists
    available: p
    notes: "Yêu cầu [tiện ích mở rộng Markdown Preview Enhanced](https://github.com/shd101wyy/vscode-markdown-preview-enhanced)."
  - id: strikethrough
    available: p
    notes: "Chỉ hai dấu ngã (`~~từ~~`)."
  - id: task-lists
    available: p
    notes: "Một trong nhiều tiện ích mở rộng có sẵn có thể thêm tính năng này, ví dụ: [Markdown Preview Enhanced](https://github.com/shd101wyy/vscode-markdown-preview-enhanced)."
  - id: emoji-cp
    available: y
  - id: emoji-sc
    available: p
    notes: "Yêu cầu [tiện ích mở rộng Markdown Preview Enhanced](https://github.com/shd101wyy/vscode-markdown-preview-enhanced)."
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

[WikiBonsai](https://github.com/wikibonsai/wikibonsai) là một bộ sưu tập các công cụ mã nguồn mở để mang quy trình làm vườn kỹ thuật số đến markdown.

{% include image.html file="{{ site.baseurl }}/assets/images/tools/wikibonsai-demo.png" alt="vscode-wikibonsai" %}

Các quy trình làm việc chính:

- Cú pháp `[[wiki]]` mở rộng bao gồm thuộc tính, liên kết và nhúng.
- Cấu trúc "cây ngữ nghĩa" hoặc "bonsai kiến thức" để sắp xếp các tài liệu markdown của bạn.
- Trực quan hóa đồ họa để khám phá các ghi chú của bạn trong 2D, 3D, AR, VR hoặc ánh xạ đến nhúng (thường được sử dụng trong học sâu trong AI).
- CAML: Colon Attribute Markup Language một đánh dấu nhẹ, giống YAML cho các thuộc tính ngữ nghĩa (với hỗ trợ [[wiki]]!).

Các công cụ cấp cao nhất:

- [Tiện ích mở rộng VSCode](https://marketplace.visualstudio.com/items?itemName=manunamz.vscode-wikibonsai)
- [Công cụ CLI](https://github.com/wikibonsai/tendr-cli)

{% include tool-syntax-table.html %}
