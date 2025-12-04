---
title: Reddit
category: "website"
description: "Reddit là một cộng đồng trực tuyến phổ biến hỗ trợ đăng bài bằng Markdown."
icon: reddit.png
website: https://www.reddit.com
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
    notes: "Danh sách phải bắt đầu bằng số 1. Bạn có thể sử dụng dấu ngoặc đơn làm dấu chấm câu kết thúc (tức là, `1)` thay vì `1.`)."
  - id: unordered-lists
    available: p
    notes: "Không thể sử dụng dấu cộng (`+`)."
  - id: code
    available: y
  - id: horizontal-rules
    available: y
  - id: links
    available: y
    notes: "Liên kết có thể chứa khoảng trắng."
  - id: images
    available: n
    notes: "Hình ảnh chỉ được hỗ trợ trong trình soạn thảo văn bản đa dạng thức."
  - id: tables
    available: y
  - id: fenced-code-blocks
    available: y
  - id: syntax-highlighting
    available: n
  - id: footnotes
    available: n
  - id: heading-ids
    available: p
    notes: "Được tạo tự động. Không có cách nào để đặt ID tiêu đề tùy chỉnh."
  - id: definition-lists
    available: n
  - id: strikethrough
    available: y
  - id: task-lists
    available: n
  - id: emoji-cp
    available: u
  - id: emoji-sc
    available: u
  - id: highlight
    available: n
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
  - name: Reddit-flavored Markdown
    link: https://www.reddit.com/wiki/markdown
---

Với Markdown, định dạng văn bản [Reddit](https://www.reddit.com) thật dễ dàng. Tất cả người dùng Reddit đều có tùy chọn viết bình luận và bài đăng bằng Markdown. Trang web tin tức phổ biến này đã phát triển bộ xử lý Markdown của riêng mình có tên là "snoomark" dựa trên GitHub-Flavored Markdown. Một số người đã bắt đầu gọi đây là "Reddit-flavored Markdown." Để tìm hiểu sâu về hỗ trợ Markdown của Reddit, hãy xem [bài viết wiki này](https://www.reddit.com/wiki/markdown).

### Bật Hỗ trợ Markdown

Theo mặc định, Reddit vô hiệu hóa hỗ trợ Markdown cho các bài đăng và bình luận mới. Bạn có thể chuyển từ trình soạn thảo văn bản đa dạng thức sang Markdown bằng cách nhấp vào liên kết **Switch to markdown**, như được hiển thị bên dưới.

{% include image.html file="{{ site.baseurl }}/assets/images/tools/reddit.png" alt="Chuyển sang Markdown trên Reddit.com" width="80" %}

Để lưu vĩnh viễn cài đặt này, bạn có thể bật cài đặt **Default to Markdown** trong **User Settings** > **Feed Settings**. Bật cài đặt đó sẽ tự động bật Markdown cho các bài đăng hoặc bình luận mới.

{% include tool-syntax-table.html %}

### Hỗ trợ cho các Phần tử Cú pháp Bổ sung

Như một phần thưởng thêm, Reddit cung cấp hỗ trợ cho một số phần tử ít người biết đến.

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
      <td>Spoilers</td>
      <td><code>Văn bản này sẽ bị ẩn: >!spoilers!<</code></td>
      <td></td>
    </tr>
  </tbody>
</table>
