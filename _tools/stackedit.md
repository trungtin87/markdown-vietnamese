---
title: StackEdit
category: "online editor"
description: "StackEdit là một trình soạn thảo Markdown trực tuyến mạnh mẽ mà bạn có thể sử dụng ở bất cứ đâu."
icon: stackedit.png
website: https://stackedit.io
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
  - name: Kho lưu trữ StackEdit trên GitHub
    link: https://github.com/benweet/stackedit/
---

[StackEdit](https://stackedit.io) là một trình soạn thảo Markdown trực tuyến mạnh mẽ. Giống như [Dillinger](/tools/dillinger/), nó tải ngay trong trình duyệt web của bạn, vì vậy không cần tải xuống và cài đặt ứng dụng trên máy tính của bạn. StackEdit có nhiều tính năng và tùy chọn cấu hình cho người dùng chuyên nghiệp, khiến nó trở thành một lựa chọn toàn diện tốt hơn so với các ứng dụng máy tính để bàn tương đương theo nhiều cách.

{% include image.html file="assets/images/tools/stackedit.png" alt="Trình soạn thảo Markdown StackEdit" %}

Hỗ trợ Markdown của StackEdit rất tuyệt vời. Các tính năng bao gồm khả năng đồng bộ hóa và lưu file vào các dịch vụ của bên thứ ba, xuất sang các định dạng file khác nhau bằng cách sử dụng các mẫu tùy chỉnh và định cấu hình các thuộc tính siêu dữ liệu cho các file. (Lưu ý rằng bạn phải đăng ký StackEdit để xuất sang một số định dạng file, như PDF.) LaTeX và sơ đồ UML cũng được hỗ trợ. Bạn dường như có thể sử dụng StackEdit mà không cần kết nối internet.

StackEdit bị hạn chế bởi sự thiếu tài liệu. Người dùng phải tự khám phá và tìm hiểu nhiều tính năng của ứng dụng. Thật đáng tiếc, vì các tính năng không có tài liệu về cơ bản là không thể sử dụng được bởi tất cả mọi người trừ những người dùng cao cấp nhất. Ví dụ, bạn có thể tạo các mẫu của riêng mình cho các file đã xuất, nhưng không có thông tin về ngôn ngữ tạo mẫu nào được sử dụng và không có hướng dẫn về cách tạo các mẫu của riêng bạn. Có một [diễn đàn hỗ trợ cộng đồng](https://community.stackedit.io/), nhưng người dùng không nên phải đọc qua các câu hỏi và câu trả lời để tìm ra cách làm một việc đơn giản.

{% include tool-syntax-table.html %}

### Hỗ trợ cho các Phần tử Cú pháp Bổ sung

Như một phần thưởng thêm, StackEdit cung cấp hỗ trợ cho một số phần tử ít người biết đến.

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
