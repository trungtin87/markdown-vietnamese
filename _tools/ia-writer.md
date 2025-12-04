---
title: iA Writer
category: "documents"
description: "iA Writer là một trong những trình soạn thảo Markdown lâu đời và được đánh giá cao nhất."
icon: ia-writer.png
website: https://ia.net/writer
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
    notes: "Được tạo tự động. Sử dụng `[custom-id]` cho các ID tiêu đề tùy chỉnh."
  - id: definition-lists
    available: y
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
    available: y
  - id: superscript
    available: y
  - id: auto-url-linking
    available: n
  - id: disabling-auto-url
    available: y
    notes: "Bạn không cần sử dụng cái này vì các URL không được liên kết tự động."
  - id: html
    available: y
see-also:
  - name: Hướng dẫn Markdown iA Writer
    link: https://ia.net/writer/support/general/markdown-guide
---

[iA Writer](https://ia.net/writer) là một trong những trình soạn thảo Markdown lâu đời và được đánh giá cao nhất. Được coi là trình soạn thảo Markdown "tiêu chuẩn vàng", iA Writer có sẵn cho các thiết bị chạy hệ điều hành macOS, Windows, iOS và Android. Ứng dụng cho phép bạn xuất các file Markdown sang định dạng file HTML, PDF và Microsoft Word bằng cách sử dụng [các mẫu tùy chỉnh](https://ia.net/writer/templates).

Một trong những đặc điểm nổi bật của ứng dụng là *chế độ tập trung* (focus mode). Khi được bật, tính năng đó giữ cho câu bạn đang làm việc được căn giữa theo chiều ngang, như được hiển thị trong ảnh chụp màn hình bên dưới. Cảm giác hơi giống như sử dụng máy đánh chữ.

{% include image.html file="/assets/images/tools/ia-writer.png" alt="iA Writer ở chế độ tập trung" %}

Có một vài điều kỳ quặc bạn nên biết. iA Writer không lưu các file mới với phần mở rộng Markdown (`.md`) theo mặc định. Nếu bạn định tạo độc quyền các file Markdown bằng iA Writer, bạn nên thay đổi phần mở rộng mặc định thành `.md` trong **Preferences** > **Files**.

Nút Xem trước (Preview) là nút hình tam giác nhỏ ở góc trên bên phải của cửa sổ. Bạn có thể nhấp vào đó để xem trước đầu ra, và sau đó nhấp lại vào nó để quay lại nguồn.

{% include tool-syntax-table.html %}

### Hỗ trợ cho các Phần tử Cú pháp Bổ sung

Như một phần thưởng thêm, iA Writer cung cấp hỗ trợ cho một số phần tử ít người biết đến.

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
