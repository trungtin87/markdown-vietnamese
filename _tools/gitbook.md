---
title: GitBook
category: "websites"
description: "GitBook là một giải pháp được lưu trữ cho các trang web tài liệu và cơ sở kiến thức."
icon: gitbook.png
website: https://www.gitbook.com
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
    available: n
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
    available: y
  - id: definition-lists
    available: n
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
    available: n
see-also:
  - name: Tài liệu Markdown GitBook
    link: https://docs.gitbook.com/content-creation/editor/markdown
---

[GitBook](https://www.gitbook.com) là một giải pháp được lưu trữ cho các trang web tài liệu và cơ sở kiến thức. Tóm lại, bạn đăng nhập vào trang web của GitBook và sử dụng trình soạn thảo dựa trên web của họ để viết tài liệu của bạn. Hoặc, nếu bạn muốn duy trì quyền kiểm soát nội dung của mình, bạn có thể giữ nó trong một kho lưu trữ git được [tích hợp với GitBook](https://docs.gitbook.com/product-tour/git-sync). Dù bằng cách nào, bạn có thể tạo các trang web khác nhau và sắp xếp chúng theo thứ tự hợp lý. Khi mọi thứ trông theo cách bạn muốn, bạn có thể xuất bản nó trên một tên miền tùy chỉnh.

Giống như rất nhiều dự án khác, GitBook bắt đầu như một chuỗi công cụ mã nguồn mở với một dịch vụ thương mại, nhưng cuối cùng đã từ bỏ dự án mã nguồn mở để ủng hộ một dịch vụ độc quyền và mã nguồn đóng mới được lưu trữ độc quyền trên trang web của họ. [Chuỗi công cụ mã nguồn mở vẫn có sẵn](https://github.com/GitbookIO/gitbook), nhưng vì tùy chọn đó hiện không được hỗ trợ, bài viết này chỉ ghi lại tùy chọn được lưu trữ mới.

Lợi thế của GitBook so với một công cụ như [Docusaurus](/tools/docusaurus/) là GitBook đảm nhận việc xây dựng và lưu trữ trang web, và các điều khiển WYSIWYG đủ trực quan để những người mới làm quen với Markdown sử dụng. Trên trang web GitBook, trình soạn thảo trực tiếp ẩn cú pháp định dạng Markdown sau khi bạn gõ nó. Trình soạn thảo hơi chập chờn, nhưng bỏ qua những lỗi nhỏ kỳ lạ, trang web nói chung hoạt động cho cả các chuyên gia Markdown và những người không có bất kỳ kinh nghiệm nào với Markdown. Bạn cũng có thể chỉ cần sao chép và dán văn bản được định dạng Markdown vào giao diện GitBook.

{% include tool-syntax-table.html %}
