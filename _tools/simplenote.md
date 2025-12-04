---
title: Simplenote
category: notes
description: "Simplenote là một ứng dụng ghi chú Markdown đa nền tảng."
icon: simplenote.png
website: https://simplenote.com
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
    available: p
    notes: "Dấu gạch dưới không được hỗ trợ — chúng được sử dụng để gạch chân văn bản."
  - id: blockquotes
    available: y
  - id: ordered-lists
    available: y
  - id: unordered-lists
    available: y
  - id: code
    available: p
    notes: "[Khối mã](/basic-syntax/#code-blocks) không được hỗ trợ — hãy sử dụng [khối mã có rào chắn](/extended-syntax/#fenced-code-blocks) thay thế."
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
    available: n
  - id: footnotes
    available: p
    notes: "Chỉ iOS và macOS"
  - id: heading-ids
    available: n
  - id: definition-lists
    available: n
  - id: strikethrough
    available: y
  - id: task-lists
    available: y
  - id: emoji-cp
    available: y
  - id: emoji-sc
    available: n
  - id: highlight
    available: y
  - id: subscript
    available: n
  - id: superscript
    available: y
  - id: auto-url-linking
    available: y
  - id: disabling-auto-url
    available: y
  - id: html
    available: n
see-also:
  - name: Tài liệu hỗ trợ Markdown Simplenote
    link: https://simplenote.com/help/#markdown
---

[Simplenote](https://simplenote.com) là một ứng dụng ghi chú cơ bản được phát triển bởi Automattic, cùng công ty đã tạo ra WordPress. Ứng dụng này miễn phí và có sẵn trên mọi nền tảng, bao gồm cả Linux. Nó cũng là [mã nguồn mở](https://simplenote.com/developers/). Bạn có thể sử dụng Simplenote trong trình duyệt web của mình.

Sau khi bạn tải xuống ứng dụng, bạn sẽ được nhắc tạo một tài khoản. Tài khoản đó được sử dụng để sao lưu các ghi chú của bạn vào máy chủ của Automattic và đồng bộ hóa các ghi chú của bạn trên tất cả các thiết bị khác của bạn. Lưu ý rằng Automattic [không mã hóa nội dung của bạn](https://simplenote.com/help/#encryption) trên máy chủ của họ. Bạn không thể tắt tính năng đồng bộ hóa.

Các tùy chọn xuất bị hạn chế, nhưng tính năng *Publish to Web* cho phép bạn chia sẻ các ghi chú của mình trên internet với một URL công khai.

### Bật Hỗ trợ Markdown

Để bật hỗ trợ Markdown trong Simplenote, hãy tạo một ghi chú, nhấp vào biểu tượng Thông tin (Info), và sau đó chọn **Markdown Formatted**.

{% include image.html file="{{ site.baseurl }}/assets/images/tools/simplenote-markdown.png" alt="Bật hỗ trợ Markdown trong Simplenote" width="30" %}

Ghi chú được chọn hiện tại và bất kỳ ghi chú mới nào bạn tạo trong tương lai sẽ tự động bật cài đặt này.

{% include tool-syntax-table.html %}

### Hỗ trợ cho các Phần tử Cú pháp Bổ sung

Như một phần thưởng thêm, Simplenote cung cấp hỗ trợ cho một số phần tử ít người biết đến.

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
      <td><code>_từ hoặc cụm từ_</code></td>
      <td><ins>từ hoặc cụm từ</ins></td>
    </tr>
  </tbody>
</table>

### Xem trước Tài liệu Markdown

Simplenote không sử dụng trình soạn thảo trực tiếp. Bạn sẽ tiếp tục thấy văn bản được định dạng Markdown sau khi bạn đã nhập nó. Để xem trước các tài liệu Markdown trong Simplenote, hãy nhấp vào biểu tượng Xem trước Markdown (Preview Markdown) — nó trông giống như một con mắt.
