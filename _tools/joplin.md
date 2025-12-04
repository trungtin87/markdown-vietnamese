---
title: Joplin
category: "notes"
description: "Joplin là một ứng dụng ghi chú tôn trọng quyền riêng tư của bạn."
icon: joplin.png
website: https://joplinapp.org
syntax:
  - id: headings
    available: y
  - id: paragraphs
    available: y
  - id: line-breaks
    available: y
    notes: "Ngoài khoảng trắng ở cuối, bạn cũng có thể sử dụng dấu gạch chéo ngược ở cuối hoặc nhấn phím Return một lần để đạt được kết quả tương tự."
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
    available: p
    notes: "Được tạo tự động. Không có cách nào để đặt ID tiêu đề tùy chỉnh."
  - id: definition-lists
    available: y
    notes: "Không được bật theo mặc định, nhưng có thể được bật trong **Preferences** > **Plugins**."
  - id: strikethrough
    available: y
  - id: task-lists
    available: y
  - id: emoji-cp
    available: y
  - id: emoji-sc
    available: y
    notes: "Không được bật theo mặc định, nhưng có thể được bật trong **Preferences** > **Plugins**."
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
  - name: Tài liệu Markdown Joplin
    link: https://joplinapp.org
---

[Joplin](https://joplinapp.org) là một ứng dụng ghi chú mã nguồn mở và miễn phí hoạt động trên mọi nền tảng. Giao diện người dùng của Joplin không bóng bẩy như một số đối thủ cạnh tranh — nó có cảm giác lập dị hơn, nếu điều đó có ý nghĩa — nhưng ứng dụng này là một ứng dụng yêu thích của những người ủng hộ quyền riêng tư và được [Privacy Guides](https://www.privacyguides.org/en/notebooks/) khuyên dùng. Joplin lưu trữ các ghi chú trên hệ thống file cục bộ của bạn, cung cấp mã hóa đầu cuối và cho phép bạn đồng bộ hóa các file trên các thiết bị bằng cách lưu trữ chúng trên một dịch vụ như Dropbox hoặc Nextcloud. Hoặc, bạn có thể đăng ký [Joplin Cloud](https://joplinapp.org/plans/) để đồng bộ hóa.

{% include image.html file="assets/images/tools/joplin.png" alt="Ứng dụng Markdown Joplin" width="90" %}

{% include tool-syntax-table.html %}

### Hỗ trợ cho các Phần tử Cú pháp Bổ sung

Như một phần thưởng thêm, Joplin cung cấp hỗ trợ cho một số phần tử ít người biết đến.

<div class="alert alert-success">
  <i class="fas fa-lightbulb"></i> <strong>Mẹo:</strong> Hầu hết các phần tử này bị vô hiệu hóa theo mặc định. Bạn có thể bật chúng trong <strong>Preferences</strong> > <strong>Plugins</strong>.
</div>

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
