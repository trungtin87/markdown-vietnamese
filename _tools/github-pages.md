---
title: GitHub Pages
category: "websites"
description: "GitHub Pages là một dịch vụ biến các file Markdown thành một trang web."
icon: github-pages.png
website: https://pages.github.com
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
  - name: Tài liệu Jekyll
    link: https://jekyllrb.com/
  - name: Tài liệu kramdown
    link: https://kramdown.gettalong.org/
---

[GitHub Pages](https://pages.github.com) là một dịch vụ biến các file Markdown thành một trang web và lưu trữ chúng miễn phí trên internet. Nếu bạn biết cách sử dụng GitHub và bạn cần tạo một trang web đơn giản, bạn không thể làm tốt hơn GitHub Pages. Chỉ cần tạo một kho lưu trữ mới trên GitHub, cam kết các file Markdown và bật tính năng GitHub Pages.

GitHub Pages sử dụng trình tạo trang web tĩnh [Jekyll](/tools/jekyll/) để tạo trang web của bạn và hỗ trợ Markdown rất tuyệt vời. Bạn có thể chọn một trong các chủ đề có sẵn của GitHub cho trang web của mình, sử dụng [chủ đề Jekyll](http://jekyllthemes.org/), hoặc sử dụng CSS tùy chỉnh của riêng bạn. Dưới đây là một trang web mẫu sử dụng một trong các chủ đề có sẵn của GitHub.

{% include image.html file="assets/images/tools/github-pages.png" alt="Ví dụ về các trang web GitHub Pages" width="90" %}

Thật khó hiểu, GitHub Pages hiển thị Markdown khác với GitHub. GitHub sử dụng bộ xử lý Markdown của riêng mình; GitHub Pages sử dụng [jekyll-commonmark](https://github.com/github/jekyll-commonmark-ghpages). Điều này có nghĩa là file `README.md` của bạn sẽ trông khác trên trang web của GitHub so với trên trang web GitHub Pages của bạn. Ví dụ, biểu tượng cảm xúc được hiển thị trên trang web của GitHub, nhưng không hiển thị trên các trang web được tạo bằng GitHub Pages.

{% include tool-syntax-table.html %}

### Hỗ trợ cho các Phần tử Cú pháp Bổ sung

Như một phần thưởng thêm, GitHub Pages cung cấp hỗ trợ cho một số phần tử ít người biết đến.

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
