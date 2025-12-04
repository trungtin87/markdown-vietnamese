---
title: Dillinger
category: "online editor"
description: "Dillinger là một trình soạn thảo Markdown trực tuyến được thiết kế để viết khi đang di chuyển."
icon: dillinger.png
website: https://dillinger.io
syntax:
  - id: headings
    available: y
  - id: paragraphs
    available: y
  - id: line-breaks
    available: p
    notes: "Cú pháp Markdown (khoảng trắng ở cuối dòng) không được hỗ trợ, nhưng bạn có thể nhấn phím Return một lần để đạt được kết quả tương tự."
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
    notes: "Không có khả năng tải lên hình ảnh — bạn sẽ cần lưu trữ hình ảnh trên một máy chủ khác."
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
    available: y
  - id: strikethrough
    available: y
  - id: task-lists
    available: y
    notes: "Bạn không cần phải sử dụng dấu gạch ngang. Chỉ cần sử dụng dấu ngoặc vuông (ví dụ: `[ ]`)."
  - id: emoji-cp
    available: y
  - id: emoji-sc
    available: n
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
    available: n
see-also:
  - name: Kho lưu trữ Dillinger trên GitHub
    link: https://github.com/joemccann/dillinger
---

[Dillinger](https://dillinger.io) là một trình soạn thảo Markdown trực tuyến. Giống như [StackEdit](/tools/stackedit/), nó tải ngay trong trình duyệt web của bạn, vì vậy không cần phải tải xuống và cài đặt ứng dụng trên máy tính của bạn. Dillinger có hai khung: trình soạn thảo ở bên trái và bản xem trước trực tiếp ở bên phải. Các khung chia nhỏ giúp bạn dễ dàng xem văn bản được định dạng Markdown trông như thế nào.

Dillinger cung cấp hỗ trợ Markdown tuyệt vời. Thật không may, các tùy chọn xuất không thể tùy chỉnh và các tính năng lưu file hơi chập chờn. Và vì Dillinger tải trong trình duyệt web của bạn, nó hoàn toàn phụ thuộc vào kết nối internet ổn định. Nếu kết nối internet của bạn bị ngắt hoặc trình duyệt web của bạn bị treo, bạn có thể mất công việc của mình. Vì những lý do đó, Dillinger được sử dụng tốt nhất để thử nghiệm và ghi chú nhanh.

Ứng dụng sử dụng bộ xử lý Markdown [markdown-it](https://github.com/markdown-it/markdown-it).

{% include image.html file="/assets/images/dillinger.png" alt="Trình soạn thảo Markdown Dillinger" %}

{% include tool-syntax-table.html %}

### Hỗ trợ cho các Phần tử Cú pháp Bổ sung

Như một phần thưởng thêm, Dillinger cung cấp hỗ trợ cho một số phần tử ít người biết đến.

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
    <tr>
      <td>Chèn</td>
      <td><code>++Văn bản này đã được chèn++</code></td>
      <td><ins>Văn bản này đã được chèn</ins></td>
    </tr>
  </tbody>
</table>
