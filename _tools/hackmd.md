---
title: HackMD
category: "websites"
description: "HackMD là một trình soạn thảo Markdown cộng tác thời gian thực cho các nhóm."
icon: codimd.png
website: https://hackmd.io
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
    available: n
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
    available: y
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
  - name: Các tính năng của HackMD
    link: https://hackmd.io/s/features
---

[HackMD](https://hackmd.io) là một trình soạn thảo Markdown cộng tác đa nền tảng, thời gian thực. Bạn có thể sử dụng HackMD để viết ghi chú với những người khác trên máy tính, máy tính bảng hoặc điện thoại của mình. HackMD cung cấp nhiều mẫu tài liệu khác nhau và cho phép người dùng đẩy tài liệu lên GitHub. Bạn có thể nhập và xuất tài liệu từ Dropbox, Google Drive và GitHub gists.

{% include image.html file="{{ site.baseurl }}/assets/images/tools/hackmd.png" alt="Giao diện Markdown HackMD" %}

HackMD hỗ trợ CommonMark và các cú pháp đánh dấu khác, chẳng hạn như:

- MathJax cho các công thức
- Mermaid và Graphviz cho sơ đồ UML
- Vega-lite cho trực quan hóa dữ liệu

HackMD là phiên bản thương mại của [CodiMD](/tools/codimd/).

{% include tool-syntax-table.html %}

### Hỗ trợ cho các Phần tử Cú pháp Bổ sung

Như một phần thưởng thêm, HackMD cung cấp hỗ trợ cho một số phần tử ít người biết đến.

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
