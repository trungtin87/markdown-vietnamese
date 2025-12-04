---
title: Notable
category: "notes"
description: "Notable là một ứng dụng ghi chú đơn giản với hỗ trợ Markdown tuyệt vời."
icon: notable.png
website: https://notable.app
syntax:
  - id: headings
    available: y
  - id: paragraphs
    available: y
  - id: line-breaks
    available: y
    notes: "Ngoài khoảng trắng ở cuối, bạn cũng có thể sử dụng dấu gạch chéo ngược ở cuối hoặc nhấn phím Return một lần để đạt được kết quả tương tự."
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
    available: y
  - id: heading-ids
    available: p
    notes: "Được tạo tự động. Không có cách nào để đặt ID tiêu đề tùy chỉnh."
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
    available: n
  - id: subscript
    available: y
  - id: superscript
    available: y
  - id: auto-url-linking
    available: y
  - id: disabling-auto-url
    available: y
  - id: html
    available: y
see-also:
  - name: Bảng tra cứu Markdown Notable
    link: https://notable.app/static/pdfs/cheatsheet.pdf
---

[Notable](https://notable.app) là một ứng dụng ghi chú đơn giản với hỗ trợ Markdown tuyệt vời. Miễn phí cho máy tính để bàn, Notable được thiết kế cho những người thích xem văn bản được định dạng Markdown trong khi họ đang nhập. Không có trình soạn thảo trực tiếp ở đây. Chỉ có bạn và văn bản thô. Bạn có thể nhấp vào nút Chỉnh sửa (Edit) để chuyển đổi giữa trình soạn thảo và màn hình xem trước — một tính năng tiện dụng khi bạn đang đọc qua các ghi chú của mình.

{% include image.html file="{{ site.baseurl }}/assets/images/tools/notable.png" alt="Ứng dụng Markdown Notable" width="90" %}

Một trong những tính năng tốt nhất của Notable, nếu bạn có thể gọi nó như vậy, là sự thiếu các tính năng. Không cần tạo tài khoản và không có tính năng đồng bộ hóa. Một số người có thể coi đó là một hạn chế, nhưng nó loại bỏ khả năng các file của bạn bị xâm phạm trên máy chủ của bên thứ ba.

Nhưng chắc chắn, tính năng tốt nhất của Notable là nó không thao tác các file Markdown của bạn theo bất kỳ cách nào — chúng được lưu trữ trên máy tính của bạn ở cùng định dạng bạn thấy trong Notable. Nếu sau này bạn quyết định rằng bạn không thích Notable, bạn có thể lấy các file Markdown của mình và làm bất cứ điều gì với chúng.

Ứng dụng sử dụng bộ xử lý Markdown [markdown-it](https://github.com/markdown-it/markdown-it).

{% include tool-syntax-table.html %}
