---
title: Jekyll
category: "websites"
description: "Jekyll là một trình tạo trang web tĩnh giúp chuyển đổi các file Markdown thành một trang web."
icon: jekyll.png
website: https://jekyllrb.com
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
    notes: "Đảm bảo rằng `syntax_highlighter: rouge` nằm trong phần `kramdown` của file `_config.yml`."
  - id: footnotes
    available: y
  - id: heading-ids
    available: y
  - id: definition-lists
    available: y
  - id: strikethrough
    available: y
    notes: "Bạn có thể sử dụng hai dấu ngã (`~~từ~~`) hoặc một dấu ngã (`~từ~`) — cả hai đều hoạt động."
  - id: task-lists
    available: y
  - id: emoji-cp
    available: y
  - id: emoji-sc
    available: n
    notes: "Không được hỗ trợ theo mặc định, nhưng bạn có thể sử dụng plugin [jemoji](https://github.com/jekyll/jemoji) để bật hỗ trợ."
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
  - name: Các tùy chọn cấu hình Markdown Jekyll
    link: https://jekyllrb.com/docs/configuration/markdown/
  - name: Tài liệu kramdown
    link: https://kramdown.gettalong.org/
---

[Jekyll](https://jekyllrb.com) là một trình tạo trang web tĩnh lấy các file Markdown và chuyển đổi chúng thành một trang web. Jekyll là một ứng dụng mã nguồn mở và miễn phí được viết bằng ngôn ngữ lập trình Ruby. Hàng ngàn trang web, bao gồm cả *Markdown Guide*, dựa vào Jekyll để chuyển đổi các file nguồn Markdown sang đầu ra HTML. [GitHub Pages](/tools/github-pages/) sử dụng Jekyll làm backend cho dịch vụ tạo trang web miễn phí của mình.

Theo mặc định, Jekyll sử dụng bộ xử lý Markdown [kramdown](https://kramdown.gettalong.org/) với các cài đặt gốc, nhưng bạn có thể bật các tùy chọn kramdown khác hoặc thậm chí chuyển Jekyll sang bộ xử lý Markdown khác. Xem tài liệu [Các tùy chọn cấu hình Markdown Jekyll](https://jekyllrb.com/docs/configuration/markdown/) để biết thêm thông tin. Bạn có thể thay đổi cài đặt kramdown của Jekyll trong file `_config.yml`. Các cài đặt cho *Markdown Guide* được hiển thị bên dưới.

```yaml
kramdown:
  syntax_highlighter: rouge
  input: GFM
  auto_ids:       true
  toc_levels:     1..3
```

{% include tool-syntax-table.html %}

### Hỗ trợ cho các Phần tử Cú pháp Bổ sung

Như một phần thưởng thêm, Jekyll cung cấp hỗ trợ cho một số phần tử ít người biết đến.

<table class="table table-bordered" style="font-size: 14px">
  <thead class="thead-light">
    <tr>
      <th>Phần tử</th>
      <th>Markdown</th>
      <th>Kết quả hiển thị</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Viết tắt</td>
      <td><code>*[HTML]: Hyper Text Markup Language</code><br>
      <code>Đặc tả HTML được duy trì bởi W3C.</code></td>
      <td>Đặc tả <abbr title="Hyper Text Markup Language">HTML</abbr> được duy trì bởi W3C.</td>
    </tr>
  </tbody>
</table>
