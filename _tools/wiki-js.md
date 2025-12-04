---
title: Wiki.js
category: "wiki"
description: "Wiki.js là một wiki mã nguồn mở hỗ trợ Markdown."
icon: wikijs.png
website: https://js.wiki/
syntax:
  - id: headings
    available: y
  - id: paragraphs
    available: y
  - id: line-breaks
    available: y
    notes: "Bạn có thể sử dụng dấu gạch chéo ngược ở cuối (`\\`) thay vì khoảng trắng ở cuối."
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
    notes: "Bạn có thể liên kết đến các ghi chú khác bằng cách sử dụng cú pháp `[[Tên liên kết|tên file]]`."
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
    notes: "Được tạo tự động."
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
    available: n
  - id: html
    available: y
see-also:
  - name: Markdown Wiki.js
    link: https://docs.requarks.io/en/editors/markdown
  - name: Kho lưu trữ GitHub Wiki.js
    link: https://github.com/Requarks/wiki
---

[Wiki.js](https://js.wiki/) là một ứng dụng wiki mã nguồn mở cung cấp hỗ trợ Markdown tuyệt vời. Tôi đã ấn tượng với chất lượng của phần mềm miễn phí này và khuyên dùng nó cho bất kỳ ai quan tâm đến một wiki để sử dụng cá nhân hoặc nhóm. Wiki.js dễ sử dụng và cung cấp một số tùy chọn cấu hình mạnh mẽ, bao gồm khả năng bật Pandoc để chuyển đổi giữa các định dạng đánh dấu, như AsciiDoc, và các cài đặt để bật và tắt các tùy chọn định dạng Markdown khác nhau. Nó hoạt động tốt ngay lập tức và cạnh tranh với nhiều phần mềm độc quyền.

Đây là một ứng dụng dựa trên web yêu cầu cơ sở dữ liệu, vì vậy việc cài đặt có thể hơi đau đầu tùy thuộc vào sự quen thuộc của bạn với các tiện ích dòng lệnh. Điều đó nói rằng, đây là một dự án mã nguồn mở với tài liệu và hỗ trợ tuyệt vời. Nếu bạn gặp vấn đề, bạn có thể nộp một vấn đề GitHub hoặc ghé qua không gian làm việc Slack của Wiki.js.

{% include image.html file="/assets/images/tools/wikijs.png" alt="Ứng dụng Markdown Wiki.js" %}

{% include tool-syntax-table.html %}

### Hỗ trợ cho các Phần tử Cú pháp Bổ sung

Như một phần thưởng thêm, Wiki.js cung cấp hỗ trợ cho một số phần tử ít người biết đến.

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
