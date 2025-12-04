---
title: MkDocs
category: "websites"
description: "MkDocs là một trình tạo trang web tĩnh để xây dựng các trang web tài liệu."
icon: mkdocs.png
website: https://www.mkdocs.org
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
    available: y
  - id: footnotes
    available: n
  - id: heading-ids
    available: n
  - id: definition-lists
    available: n
  - id: strikethrough
    available: n
  - id: task-lists
    available: n
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
see-also:
  - name: Viết bằng Markdown với MkDocs
    link: https://www.mkdocs.org/user-guide/writing-your-docs/#writing-with-markdown
  - name: Kho lưu trữ MkDocs trên GitHub
    link: https://github.com/mkdocs/mkdocs/
---

[MkDocs](https://www.mkdocs.org) là một trình tạo trang web tĩnh được thiết kế để xây dựng các trang web tài liệu. Được viết bằng ngôn ngữ lập trình Python, MkDocs là một dự án mã nguồn mở với rất nhiều sự hỗ trợ từ cộng đồng. Có nhiều [chủ đề](https://github.com/mkdocs/mkdocs/wiki/MkDocs-Themes) khác nhau. Về hỗ trợ Markdown, MkDocs thực hiện công việc tuyệt vời trong việc hỗ trợ các phần tử cú pháp cơ bản, nhưng nó thiếu hỗ trợ cho một số phần tử cú pháp mở rộng.

Ứng dụng sử dụng bộ xử lý Markdown [Python-Markdown](https://python-markdown.github.io/). Bạn có thể bật thêm [các tiện ích mở rộng](https://www.mkdocs.org/user-guide/configuration/#markdown_extensions).

{% include image.html file="assets/images/tools/mkdocs.png" alt="Một trang web MkDocs mới được triển khai." width="70" %}

{% include tool-syntax-table.html %}

### Sử dụng Lời khuyên răn (Admonitions)

Đây là một tính năng tiện dụng: Bạn có thể bật một tiện ích mở rộng để sử dụng [lời khuyên răn](https://python-markdown.github.io/extensions/admonition/) trong MkDocs. Đây là một cách nhanh chóng và dễ dàng để bắt đầu sử dụng ghi chú, cảnh báo và mẹo trên trang web MkDocs của bạn. Xem [vấn đề GitHub này](https://github.com/mkdocs/mkdocs/issues/1659) để biết thêm thông tin và ví dụ.
