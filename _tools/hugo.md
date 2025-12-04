---
title: Hugo
category: "websites"
description: "Hugo là một trình tạo trang web tĩnh giúp chuyển đổi các file Markdown thành một trang web."
icon: hugo.png
website: https://gohugo.io
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
    available: y
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
    notes: "Bị vô hiệu hóa theo mặc định nếu bạn đang sử dụng Goldmark. Để bật, hãy đặt tùy chọn `unsafe` thành `true` trong [cấu hình Goldmark](https://gohugo.io/getting-started/configuration-markup#goldmark)."
see-also:
  - name: Các định dạng nội dung được Hugo hỗ trợ
    link: https://gohugo.io/content-management/formats/
  - name: Kho lưu trữ GitHub Goldmark
    link: https://github.com/yuin/goldmark/
---

[Hugo](https://gohugo.io) là một trình tạo trang web tĩnh phổ biến được viết bằng ngôn ngữ lập trình Go. Hugo có rất nhiều tính năng, nhưng một trong những điểm bán hàng chính của nó là tốc độ — Hugo chỉ mất vài giây để tạo một trang web với hàng nghìn trang. [Smashing Magazine](https://www.smashingmagazine.com/2017/03/a-little-surprise-is-waiting-for-you-here/) gần đây đã chuyển sang Hugo từ WordPress.

Hugo có hỗ trợ Markdown tuyệt vời ngay lập tức. Theo mặc định, Hugo sử dụng bộ xử lý Markdown [Goldmark](https://github.com/yuin/goldmark/) hoàn toàn tuân thủ CommonMark. Xem [hướng dẫn cấu hình](https://gohugo.io/getting-started/configuration-markup/) để tìm hiểu thêm về các tiện ích mở rộng mà bạn có thể cấu hình. Bạn có thể thay đổi cài đặt Goldmark của Hugo trong file `config.toml`, như được hiển thị bên dưới.

```toml
baseURL = "http://mysite.org/"
languageCode = "en-us"
title = "My Site"
theme = "ananke"

[markup]
taskLists = false
```

{% include tool-syntax-table.html %}
