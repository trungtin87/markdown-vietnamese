---
title: VS Code
category: documents
description: "Một trình soạn thảo mã nguồn đa nền tảng, mã nguồn mở, có thể mở rộng."
icon: vscode.png
website: https://code.visualstudio.com
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
see-also:
  - name: Kho lưu trữ Visual Studio Code trên GitHub
    link: https://github.com/microsoft/vscode
---

[Visual Studio Code](https://code.visualstudio.com) là một trình soạn thảo mã nguồn. Nó có thể mở rộng, miễn phí, mã nguồn mở và đa nền tảng. Nó nợ phần lớn thành công của mình cho cộng đồng các nhà phát triển tiện ích mở rộng tích cực. Bất cứ khi nào nó thiếu một tính năng nhất định, thường có một tiện ích mở rộng để khắc phục thiếu sót đó. Hỗ trợ Markdown ngay lập tức của nó bao gồm:

* Hỗ trợ CommonMark
* Tô sáng cú pháp
* Xem trước
* Tự động hoàn thành
* Chủ đề
* Kiểu mã

Nó không hỗ trợ chỉnh sửa WYSIWIG. Mặc dù Visual Studio Code không đi kèm với khả năng xuất Markdown sang bất kỳ định dạng nào khác ngay lập tức, nhưng nó có thể sao chép mã Markdown với màu cú pháp còn nguyên vẹn.

{% include image.html file="assets/images/tools/vscode.png" alt="Visual Studio Code" %}

Các tiện ích mở rộng Markdown có sẵn trong thị trường Visual Studio mở rộng nó với các tính năng sau:

* Cú pháp mở rộng (ví dụ: "Markdown Extended")
* Định dạng mã Markdown (ví dụ: "Prettier - Code formatter")
* Xuất sang các định dạng khác (ví dụ: "Markdown Preview Enhanced")
* Các phần tử UI (ví dụ: "Markdown Shortcuts")
* Tô sáng cú pháp markdown mở rộng (ví dụ: "One Dark Pro")
* Linting (ví dụ: "markdownlint") – Đây là một tính năng cho nhà phát triển nhưng là một phiền toái lớn cho các nhà văn bình thường
* Bộ công cụ tuân thủ kiểu cho các dịch vụ khác nhau (ví dụ: "Docs Authoring Pack" cho Microsoft Docs)
* Kiểm tra chính tả (ví dụ: "Code Spell Checker")

{% include image.html file="assets/images/tools/vscode-extended.png" alt="Visual Studio Code, với Markdown Preview Enhanced, Markdownlint, và One Dark Pro" lazy="yes" %}

{% include tool-syntax-table.html %}
