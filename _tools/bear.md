---
title: Bear
category: notes
description: "Bear là một ứng dụng ghi chú Markdown cho các thiết bị macOS và iOS."
icon: bear.png
website: https://bear.app
syntax:
  - id: headings
    available: p
    notes: "[Cú pháp thay thế](/basic-syntax/#alternate-syntax) không được hỗ trợ."
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
    available: p
    notes: "[Trích dẫn khối lồng nhau](/basic-syntax/#nested-blockquotes) không được hỗ trợ."
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
    notes: "Bạn có thể liên kết đến các ghi chú khác bằng cách bao quanh tên ghi chú trong dấu ngoặc vuông kép (tức là, `[[tên-ghi-chú]]`)."
  - id: images
    available: n
    notes: "Cú pháp Markdown không được hỗ trợ, nhưng bạn có thể kéo và thả hình ảnh vào ghi chú."
  - id: tables
    available: n
  - id: fenced-code-blocks
    available: y
  - id: syntax-highlighting
    available: y
  - id: footnotes
    available: n
  - id: heading-ids
    available: p
    notes: "Được tạo tự động. Không có cách nào để đặt ID tiêu đề tùy chỉnh. Bạn có thể sao chép liên kết đến tiêu đề bằng cách nhấp vào biểu tượng **H#** bên cạnh tiêu đề ở lề và chọn **Copy Link to Here**. Xem [tài liệu](https://bear.app/faq/how-to-link-notes-together/) để biết thêm thông tin."
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
    available: y
    notes: "Sử dụng hai dấu hai chấm thay vì dấu bằng (ví dụ: `::từ hoặc cụm từ::`)."
  - id: subscript
    available: n
  - id: superscript
    available: n
  - id: auto-url-linking
    available: y
  - id: disabling-auto-url
    available: y
  - id: html
    available: p
    notes: "HTML không được hiển thị trong ghi chú Bear, nhưng dường như nó được hiển thị trong đầu ra HTML từ các ghi chú đã xuất."
see-also:
  - name: Cách sử dụng Markdown trong Bear
    link: https://bear.app/faq/how-to-use-markdown-in-bear/
---

[Bear](https://bear.app) là một ứng dụng macOS và iOS được thiết kế cho một việc: ghi chú. Nó giống như [Evernote](https://evernote.com/), nhưng không cồng kềnh.

Không có nhiều tính năng hào nhoáng trong Bear. Thay vào đó, Bear luôn thực hiện đúng tất cả các lời hứa của mình. Thẻ, tìm kiếm và đồng bộ hóa đều hoạt động hoàn hảo. Ứng dụng này trực quan, và đó chính xác là những gì bạn muốn khi ghi chú.

{% include image.html file="assets/images/tools/bear.png" alt="Markdown trong ứng dụng Markdown Bear" %}

Bear không tự động bật hỗ trợ Markdown theo mặc định, nhưng bạn có thể [bật nó trong tùy chọn](#enabling-markdown-support). Ứng dụng có trình soạn thảo trực tiếp và trình soạn thảo văn bản lai — bạn có thể thấy cả cú pháp Markdown và cách định dạng thay đổi văn bản. Phải mất một lúc để làm quen, nhưng nó hữu ích nếu bạn mới bắt đầu với Markdown.

### Bật Hỗ trợ Markdown

Để bật hỗ trợ Markdown trong Bear, hãy mở cửa sổ Tùy chọn (Preferences). Trên tab **General**, bật cài đặt cho **Markdown compatibility mode**.

<div class="alert alert-success">
  <i class="fas fa-lightbulb"></i> <strong>Mẹo:</strong> Nếu bạn đang sử dụng Bear trên nhiều thiết bị, bạn sẽ cần bật cài đặt chế độ tương thích Markdown trên tất cả các thiết bị của mình.
</div>

{% include tool-syntax-table.html %}

### Hỗ trợ cho các Phần tử Cú pháp Bổ sung

Như một phần thưởng thêm, Bear cung cấp hỗ trợ cho một số phần tử ít người biết đến.

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
      <td>Gạch chân</td>
      <td><code>~từ hoặc cụm từ~</code></td>
      <td><ins>từ hoặc cụm từ</ins></td>
    </tr>
  </tbody>
</table>
