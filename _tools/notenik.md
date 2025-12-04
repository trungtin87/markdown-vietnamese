---
title: Notenik
category: "notes"
description: "Notenik là một ứng dụng Mac để thu thập và sắp xếp các ghi chú."
icon: notenik.png
website: https://notenik.app/
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
    available: n
  - id: footnotes
    available: y
  - id: heading-ids
    available: n
  - id: definition-lists
    available: y
  - id: strikethrough
    available: n
  - id: task-lists
    available: y
  - id: emoji-cp
    available: n
  - id: emoji-sc
    available: n
  - id: highlight
    available: n
  - id: subscript
    available: n
  - id: superscript
    available: n
  - id: auto-url-linking
    available: n
  - id: disabling-auto-url
    available: n
  - id: html
    available: y
---

Notenik là một ứng dụng Mac miễn phí và mã nguồn mở để ghi chú và sắp xếp các ghi chú bằng Markdown. Nó có thể được tải xuống từ [Mac App Store](https://apps.apple.com/us/app/notenik/id1465997984).

Notenik có một vài tính năng khác biệt trong lĩnh vực ứng dụng ghi chú ngày càng đông đúc:

+ Nó là một ứng dụng Mac gốc được viết hoàn toàn bằng Swift và sử dụng AppKit
+ Nó có giao diện người dùng Mac rất truyền thống
+ Nó miễn phí và mã nguồn mở
+ Ghi chú được lưu trữ trong các file văn bản thuần túy
+ Ghi chú có thể được lưu trữ trong nhiều bộ sưu tập (còn gọi là thư mục)
+ Bộ sưu tập/thư mục có thể được lưu trữ ở bất cứ đâu người dùng thích
+ Notenik hỗ trợ nhiều trường cho mỗi ghi chú và nhiều loại trường khác nhau
+ Phần thân của ghi chú luôn được định dạng bằng Markdown, nhưng các trường khác (ví dụ: đoạn giới thiệu) cũng có thể được định dạng bằng Markdown
+ Notenik hỗ trợ lọc, sắp xếp và hợp nhất các ghi chú để tạo các trang web tĩnh
+ Hỗ trợ được cung cấp để nhập, xuất và chia sẻ ghi chú bằng nhiều định dạng khác nhau
+ Hỗ trợ cả siêu dữ liệu MultiMarkdown cũng như frontmatter YAML

Cửa sổ Bộ sưu tập hiển thị hai tab ở bên trái và hai tab khác ở bên phải. Ở bên trái, người dùng có thể chuyển đổi giữa danh sách được sắp xếp của tất cả các ghi chú trong bộ sưu tập và dàn ý của tất cả các ghi chú, được sắp xếp theo thẻ. Ở bên phải, người dùng có thể chuyển đổi giữa chế độ xem chỉnh sửa và chế độ xem hiển thị.

Tất cả tài liệu Notenik được lưu trữ trong Cơ sở kiến thức Notenik, bản thân nó là một Bộ sưu tập Notenik và luôn có thể truy cập được từ bên trong Notenik (cũng như từ [web](https://notenik.app/knowledge-base/EPUB/html/notenik-knowledge-base.html)).

{% include image.html file="assets/images/tools/notenik.png" alt="Cơ sở kiến thức Notenik được mở trong Notenik" %}

{% include tool-syntax-table.html %}
