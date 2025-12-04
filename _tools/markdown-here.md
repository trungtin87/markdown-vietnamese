---
title: Markdown Here
category: "browser extension"
description: "Markdown Here là một tiện ích mở rộng trình duyệt chuyển đổi văn bản Markdown trong các biểu mẫu web."
icon: markdown-here.png
website: https://markdown-here.com
notes: "đã thử nghiệm trong gmail"
syntax:
  - id: headings
    available: y
  - id: paragraphs
    available: y
  - id: line-breaks
    available: y
    notes: "Bạn cũng có thể nhấn phím Return một lần để đạt được kết quả tương tự."
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
    available: y
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
  - name: Danh sách tương thích Markdown Here
    link: https://github.com/adam-p/markdown-here/wiki/Compatibility
  - name: Kho lưu trữ Markdown Here trên GitHub
    link: https://github.com/adam-p/markdown-here
---

[Markdown Here](https://markdown-here.com) là một tiện ích mở rộng trình duyệt miễn phí và mã nguồn mở giúp chuyển đổi văn bản Markdown trong các biểu mẫu trang web thành văn bản đa dạng thức được định dạng đúng. Đây là một cách tốt để bắt đầu sử dụng Markdown ở mọi nơi bạn nhập, cho dù bạn đang soạn thảo tin nhắn email trong Gmail hay viết bài đăng trên blog trong WordPress. Tài liệu tiếp thị định vị Markdown Here như một giải pháp cho email, nhưng tiện ích mở rộng này có thể được sử dụng với hầu như bất kỳ trang web nào hỗ trợ văn bản đa dạng thức, bao gồm Evernote. Xem danh sách [các trang web và dịch vụ tương thích](https://github.com/adam-p/markdown-here/wiki/Compatibility) để biết thêm thông tin.

Để sử dụng Markdown Here sau khi cài đặt nó, hãy bắt đầu nhập văn bản được định dạng Markdown vào một biểu mẫu, chẳng hạn như một tin nhắn email mới trong Gmail. Khi bạn viết xong tin nhắn, hãy nhấp chuột phải vào biểu mẫu và chọn **Markdown Toggle**, như được hiển thị trong ảnh chụp màn hình bên dưới. Markdown Here sẽ chuyển đổi văn bản được định dạng Markdown của bạn thành văn bản đa dạng thức được định dạng đúng.

{% include image.html file="{{ site.baseurl }}/assets/images/tools/markdown-here.png" alt="Markdown Here trong Gmail" width="60" %}

Một nguồn gây thất vọng là sự không nhất quán trong đầu ra được hiển thị. Vì Markdown Here dựa vào các tính năng được cung cấp bởi bất kỳ trình soạn thảo văn bản đa dạng thức nào mà bạn tình cờ đang làm việc, đầu ra được hiển thị sẽ khác nhau giữa các trang web. Điều này có lẽ không cần phải nói, nhưng bạn nên cẩn thận kiểm tra đầu ra trước khi gửi tin nhắn email hoặc lưu file của mình.

{% include tool-syntax-table.html %}
