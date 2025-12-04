---
title: Notion
category: "wiki"
description: "Notion là một giải pháp quản lý kiến thức tất cả trong một cho mọi người."
icon: notion.png
website: https://www.notion.so
syntax:
  - id: headings
    available: y
  - id: paragraphs
    available: y
  - id: line-breaks
    available: y
    notes: "Khi sao chép và dán văn bản được định dạng Markdown, bạn cũng có thể sử dụng dấu gạch chéo ngược ở cuối hoặc nhấn phím Return một lần để đạt được kết quả tương tự. Khi nhập trong Notion, nhấn Shift-Return."
  - id: bold
    available: y
  - id: italic
    available: y
  - id: blockquotes
    available: y
    notes: 'Notion sử dụng `|` hoặc `"` để biểu thị một trích dẫn khối, thay vì `>` tiêu chuẩn (tạo ra một Toggle).'
  - id: ordered-lists
    available: y
  - id: unordered-lists
    available: y
  - id: code
    available: y
  - id: horizontal-rules
    available: y
  - id: links
    available: p
    notes: "Sao chép và dán các liên kết được định dạng Markdown hoạt động, nhưng bạn không thể nhập chúng trong trình soạn thảo của Notion. Sử dụng lệnh gạch chéo `/link` thay thế (chỉ hoạt động cho các liên kết nội bộ đến các trang khác trong Notion)."
  - id: images
    available: p
    notes: "Sao chép và dán các hình ảnh được định dạng Markdown hoạt động, nhưng bạn không thể sử dụng định dạng đó trong trình soạn thảo của Notion. Sử dụng lệnh gạch chéo `/images` thay thế, hoặc dán hình ảnh trực tiếp."
  - id: tables
    available: p
    notes: "Sao chép và dán các bảng được định dạng Markdown hoạt động, nhưng bạn không thể nhập chúng trong trình soạn thảo của Notion. Sử dụng lệnh gạch chéo `/table` thay thế."
  - id: fenced-code-blocks
    available: y
  - id: syntax-highlighting
    available: p
    notes: "Phải chọn ngôn ngữ lập trình để tô sáng bằng GUI."
  - id: footnotes
    available: n
  - id: heading-ids
    available: n
  - id: definition-lists
    available: n
  - id: strikethrough
    available: p
    notes: "Chỉ sử dụng một ký hiệu dấu ngã trước và sau cụm từ khi nhập. Ngược lại, chỉ hoạt động cho nội dung đã dán với hai dấu ngã."
  - id: task-lists
    available: y
    notes: "Sao chép và dán danh sách tác vụ được định dạng Markdown hoạt động. Bạn có thể tạo các hộp việc cần làm bằng `[]` hoặc sử dụng lệnh gạch chéo `/todo` thay thế."
  - id: emoji-cp
    available: y
  - id: emoji-sc
    available: y
    notes: "Dấu hai chấm thứ hai không cần thiết. Nhập `:` theo sau là tên của biểu tượng cảm xúc, ví dụ: `:fire`. Không khả dụng khi sao chép-dán vào Notion."
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
    available: n
see-also:
  - name: Phím tắt Notion
    link: https://www.notion.so/help/keyboard-shortcuts
---

[Notion](https://www.notion.so) là một ứng dụng sáng tạo tự quảng cáo là giải pháp quản lý kiến thức tất cả trong một cho cá nhân và nhóm. Bạn có thể coi nó như một ứng dụng ghi chú hoặc một wiki, nhưng những mô tả đó thực sự không công bằng với nó. Bạn thực sự phải thử nó để có cảm nhận về những gì nó có khả năng - Notion cung cấp một bậc giá miễn phí cho người dùng đơn lẻ cho mục đích này. Một số tổ chức sử dụng Notion để quản lý dự án và theo dõi tác vụ, cùng những thứ khác. Ứng dụng cũng hỗ trợ "cơ sở dữ liệu": bộ sưu tập các tài liệu với các thuộc tính bổ sung tương tự như tiêu đề YAML, nhưng được xác định từ GUI ứng dụng.

Notion có sẵn các ứng dụng máy tính để bàn và di động, cũng như giao diện dựa trên web. Bạn tạo một tài khoản cho chính mình và tổ chức của mình — các tài khoản được sử dụng để đồng bộ hóa mọi thứ với máy chủ của Notion. Tài liệu được lưu trữ từ xa, yêu cầu kết nối internet để truy cập và cập nhật. Chỉnh sửa ngoại tuyến hạn chế có sẵn, nhưng chỉ cho các tài liệu bạn đã mở gần đây.

{% include image.html file="{{ site.baseurl }}/assets/images/tools/notion.png" alt="Ứng dụng Markdown Notion" %}

Hỗ trợ Markdown của Notion lúc được lúc không. Sao chép và dán văn bản được định dạng Markdown vào Notion thường hoạt động theo cách bạn mong đợi, nhưng sử dụng trình soạn thảo trực tiếp của Notion để viết bằng Markdown không phải lúc nào cũng hoạt động. Ví dụ, bạn có thể sử dụng dấu sao để làm đậm văn bản, nhưng cố gắng sử dụng dấu ngoặc vuông để tạo liên kết hoặc dấu gạch đứng để tạo bảng không hoạt động — điều này thật kỳ lạ khi xem xét rằng các phần tử cú pháp đó _có_ hoạt động khi bạn sao chép và dán chúng vào. Cũng rất khó để chỉnh sửa văn bản được định dạng Markdown mà bạn đã sao chép và dán vào Notion.

{% include tool-syntax-table.html %}
