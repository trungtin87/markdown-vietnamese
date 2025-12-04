---
title: HedgeDoc
category: "websites"
description: "HedgeDoc là một trình soạn thảo Markdown cộng tác thời gian thực mã nguồn mở."
icon: hedgedoc.png
website: https://hedgedoc.org/
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
    available: p
    notes: "Không phải tất cả các phần tử HTML đều được hỗ trợ."
see-also:
  - name: HedgeDoc Flavored Markdown
    link: https://docs.hedgedoc.org/references/hfm/
---

[HedgeDoc](https://hedgedoc.org/) là một trình soạn thảo Markdown cộng tác thời gian thực mã nguồn mở. Dự án này được tách ra từ — và tương tự như — [CodiMD](/tools/codimd/) (xem trang web HedgeDoc để biết tóm tắt về [lịch sử của dự án](https://hedgedoc.org/history/)). Tính đến tháng 11 năm 2021, HedgeDoc phiên bản 2 vẫn chưa được công khai — trang này ghi lại hỗ trợ Markdown trong HedgeDoc phiên bản 1.

{% include image.html file="{{ site.baseurl }}/assets/images/tools/hedgedoc.png" alt="Trình soạn thảo Markdown HedgeDoc." %}

{% include tool-syntax-table.html %}

### Hỗ trợ cho các Phần tử Cú pháp Bổ sung

Như một phần thưởng thêm, HedgeDoc cung cấp hỗ trợ cho một số phần tử ít người biết đến.

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
