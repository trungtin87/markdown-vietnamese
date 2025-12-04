---
title: Madoko
category: documents
description: "Madoko là một ứng dụng để viết các bài báo chuyên nghiệp và hơn thế nữa."
icon: madoko.png
website: https://github.com/koka-lang/madoko
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
    available: p
    notes: "Hình ảnh có thể được thả vào tài liệu để được tự động tải lên và liên kết đến một thư mục con của thư mục tài liệu. Chỉ cần chú ý kích thước file vì hình ảnh lớn hơn khoảng 1Mb sẽ bị máy chủ Madoko từ chối."
  - id: tables
    available: y
    notes: "Madoko mở rộng đáng kể cú pháp bảng của Markdown cơ bản."
  - id: fenced-code-blocks
    available: y
  - id: syntax-highlighting
    available: y
    notes: "Bên trong, Madoko sử dụng thư viện Monarch để thực hiện tô sáng cú pháp."
  - id: footnotes
    available: y
  - id: heading-ids
    available: y
  - id: definition-lists
    available: y
  - id: strikethrough
    available: y
  - id: task-lists
    available: y
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
    available: n
  - id: html
    available: p
    notes: "Xem Tài liệu tham khảo Madoko để biết thêm thông tin về các khối tùy chỉnh."
---

[Madoko](https://github.com/koka-lang/madoko) là một bộ xử lý Markdown nhanh để viết các bài báo chuyên nghiệp, sách, hướng dẫn sử dụng, trang web và bài thuyết trình, tập trung vào sự đơn giản và khả năng đọc văn bản thuần túy. Bạn có thể sử dụng Madoko để viết các tài liệu phức tạp bằng Markdown và nhận được đầu ra PDF và HTML đẹp mắt. Madoko là một bộ xử lý Markdown Javascript được viết bằng Koka. Nó bắt đầu như một chương trình demo cho ngôn ngữ Koka mới, được định kiểu mạnh và tên gọi này xuất phát từ "Markdown in Koka."

Madoko có thể được chạy cục bộ như một chương trình dòng lệnh hoặc trên Madoko.net để tận dụng các tính năng lưu trữ và cộng tác. Madoko tích hợp liền mạch với Dropbox, Github và OneDrive. Nó tự động đồng bộ hóa tất cả các thay đổi trên đám mây. Bằng cách này, tài liệu của bạn luôn có sẵn từ mọi thiết bị. Trình soạn thảo trực tuyến cũng có thể chỉnh sửa các file trên đĩa cục bộ hoặc chạy LaTeX cục bộ, sử dụng chương trình cục bộ Madoko.

{% include image.html file="{{ site.baseurl }}/assets/images/tools/madoko-editor.png" alt="Giao diện trình soạn thảo Madoko" width="90" %}

Madoko triển khai các tiện ích mở rộng như Github Flavored Markdown, [pandoc](https://pandoc.org/), [Markdown Extra](https://michelf.ca/projects/php-markdown/extra/), và [multi-markdown](https://fletcherpenney.net/multimarkdown/), và nó thêm các tính năng hữu ích khác để viết các tài liệu học thuật và công nghiệp.

Trong Madoko, các tab được coi là tương đương với 4 khoảng trắng. Tốt nhất là định cấu hình trình soạn thảo của bạn để xem các tab rộng 4 khoảng trắng nếu không tài liệu có thể trông lệch lạc.

{% include tool-syntax-table.html %}
