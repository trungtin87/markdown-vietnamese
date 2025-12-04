---
title: Typora
category: documents
description: "Typora là một trình soạn thảo đơn giản và có thể cấu hình được thiết kế cho ghi chú và tài liệu."
icon: typora.png
website: https://typora.io
syntax:
  - id: headings
    available: y
  - id: paragraphs
    available: y
    notes: "Theo mặc định, bạn chỉ cần nhấn phím Return một lần (không phải hai lần). Xem [tài liệu Typora](https://support.typora.io/Line-Break/) để biết thêm thông tin."
  - id: line-breaks
    available: y
    notes: "Theo mặc định, bạn cần nhấn Command-Shift-Return. Xem [tài liệu Typora](https://support.typora.io/Line-Break/) để biết thêm thông tin."
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
    notes: "Xem [tài liệu Typora](https://support.typora.io/Links/) để biết hướng dẫn về cách liên kết đến các file trên máy tính của bạn."
  - id: images
    available: y
    notes: "Để chèn hình ảnh từ máy tính của bạn, hãy sử dụng các tùy chọn trong **Format > Images**."
  - id: tables
    available: y
  - id: fenced-code-blocks
    available: y
  - id: syntax-highlighting
    available: y
    notes: "Xem [danh sách các ngôn ngữ được hỗ trợ](https://support.typora.io/Code-Fences-Language-Support/)."
  - id: footnotes
    available: y
  - id: heading-ids
    available: p
    notes: "Được tạo tự động. Ví dụ, nếu bạn có một tiêu đề có tên `Heading IDs`, bạn có thể liên kết đến nó bằng `[link](#heading-ids)`. Dường như không có cách nào để đặt ID tiêu đề tùy chỉnh. Không rõ điều gì xảy ra khi có hai tiêu đề giống hệt nhau."
  - id: definition-lists
    available: n
  - id: strikethrough
    available: y
  - id: task-lists
    available: y
  - id: emoji-cp
    available: y
  - id: emoji-sc
    available: y
  - id: highlight
    available: y
    notes: "Để sử dụng tính năng này, hãy mở Preferences và bật cài đặt trong **Markdown** > **Syntax Support**."
  - id: subscript
    available: y
    notes: "Để sử dụng tính năng này, hãy mở Preferences và bật cài đặt trong **Markdown** > **Syntax Support**."
  - id: superscript
    available: y
    notes: "Để sử dụng tính năng này, hãy mở Preferences và bật cài đặt trong **Markdown** > **Syntax Support**."
  - id: auto-url-linking
    available: y
  - id: disabling-auto-url
    available: y
  - id: html
    available: p
    notes: "Xem [tài liệu Typora](https://support.typora.io/HTML/) để biết thông tin về các phần tử HTML nào được hỗ trợ."
see-also:
  - name: Hỗ trợ Typora
    link: https://support.typora.io/
---

[Typora](https://typora.io) là một trình soạn thảo tài liệu đơn giản và có thể cấu hình cung cấp hỗ trợ Markdown tuyệt vời. Ứng dụng này lý tưởng cho sinh viên và chuyên gia cần viết bài luận và báo cáo. Có thể khó sử dụng Typora cho các dự án nhiều file hoặc để xuất bản trang web.

Typora nổi bật bằng cách cung cấp nhiều cài đặt khác nhau mà không hy sinh sự đơn giản của giao diện tối giản. Người mới làm quen với Markdown có thể đánh giá cao các phím tắt cho các tùy chọn định dạng cũng như trình soạn thảo trực tiếp trực quan ẩn cú pháp định dạng Markdown sau khi bạn nhập.

Xem [tài liệu tham khảo Markdown](https://support.typora.io/Markdown-Reference/) của Typora cho tài liệu chính thức. Tài liệu Typora chỉ ra rằng ứng dụng thường sử dụng [GitHub Flavored Markdown (GFM)](https://github.github.com/gfm/).

{% include image.html file="{{ site.baseurl }}/assets/images/tools/typora-editor.png" alt="Giao diện trình soạn thảo Typora" width="70" %}

{% include tool-syntax-table.html %}

### Chủ đề

Typora [cung cấp nhiều chủ đề khác nhau](https://theme.typora.io/) cho khi bạn xuất tài liệu của mình. Nếu bạn biết CSS, bạn có thể tùy chỉnh các chủ đề này. Mở cửa sổ Preferences và xem các cài đặt trong **Appearance** > **Themes**.

### Chế độ nghiêm ngặt

Typora cung cấp cài đặt *chế độ nghiêm ngặt* cho người dùng muốn thực thi các hạn chế cú pháp đối với tiêu đề, danh sách có thứ tự và danh sách không có thứ tự. Ví dụ, bạn có thể cấu hình danh sách không có thứ tự chỉ sử dụng dấu gạch ngang và không sử dụng dấu sao. Cấu hình các cài đặt này trong cửa sổ Preferences trong **Markdown** > **Syntax Preference**. Xem [tài liệu](https://support.typora.io/Strict-Mode/) Typora để biết thêm thông tin.

### Chế độ mã nguồn

Bạn có thể tắt trình soạn thảo trực tiếp của Typora bằng cách chọn **View** > **Source Code Mode**. Điều này sẽ hiển thị tất cả định dạng Markdown bị ẩn bởi trình soạn thảo trực tiếp.

### Tùy chọn xuất

Typora cung cấp nhiều tùy chọn xuất khác nhau trong **File** > **Export** cho khi bạn sẵn sàng xuất bản tài liệu Markdown của mình. Một số tùy chọn xuất, như định dạng Microsoft Word và LaTeX, yêu cầu [Pandoc](https://pandoc.org/).
