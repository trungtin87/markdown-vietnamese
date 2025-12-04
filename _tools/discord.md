---
title: Discord
category: "collaboration"
description: "Discord là một ứng dụng nhắn tin và cộng tác nhóm miễn phí phổ biến."
icon: discord.png
website: https://discord.com/
syntax:
  - id: headings
    available: y
  - id: paragraphs
    available: n
  - id: line-breaks
    available: n
    notes: "Cú pháp Markdown không được hỗ trợ, nhưng bạn có thể nhấn phím Shift và Return để xuống dòng tiếp theo."
  - id: bold
    available: y
    notes: "Sử dụng dấu sao. Dấu gạch dưới không được hỗ trợ."
  - id: italic
    available: y
  - id: blockquotes
    available: y
    notes: "Bạn có thể sử dụng `>>>` để tạo một trích dẫn khối nhiều dòng. Tất cả văn bản từ `>>>` đến cuối tin nhắn sẽ được bao gồm trong trích dẫn."
  - id: ordered-lists
    available: y
  - id: unordered-lists
    available: y
  - id: code
    available: y
  - id: horizontal-rules
    available: n
  - id: links
    available: y
  - id: images
    available: n
  - id: tables
    available: n
  - id: fenced-code-blocks
    available: y
  - id: syntax-highlighting
    available: y
  - id: footnotes
    available: n
  - id: heading-ids
    available: n
  - id: definition-lists
    available: n
  - id: strikethrough
    available: y
  - id: task-lists
    available: n
  - id: emoji-cp
    available: y
  - id: emoji-sc
    available: y
  - id: highlight
    available: n
  - id: subscript
    available: n
  - id: superscript
    available: n
  - id: auto-url-linking
    available: y
  - id: disabling-auto-url
    available: y
  - id: html
    available: n
see-also:
  - name: Discord Markdown Text 101
    link: https://support.discord.com/hc/en-us/articles/210298617-Markdown-Text-101-Chat-Formatting-Bold-Italic-Underline-
---

[Discord](https://discord.com/) là một trong những ứng dụng nhắn tin và cộng tác phổ biến nhất hiện có. Phổ biến trong giới game thủ và thanh thiếu niên, Discord cung cấp một giao diện nhanh và được thiết kế tốt, hoạt động tốt để giao tiếp với bạn bè. Tương tự như [Slack](/tools/slack/), Discord cung cấp hỗ trợ Markdown hạn chế, có thể so sánh với các ứng dụng khác trong danh mục này.

{% include image.html file="/assets/images/tools/discord.png" alt="Ví dụ về Discord Markdown" %}

{% include tool-syntax-table.html %}

### Hỗ trợ cho các Phần tử Cú pháp Bổ sung

Như một phần thưởng thêm, Discord cung cấp hỗ trợ cho một số phần tử ít người biết đến.

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
      <td><code>Văn bản này sẽ bị ẩn: ||spoilers||</code></td>
      <td></td>
    </tr>
    <tr>
      <td>Gạch chân</td>
      <td><code>__Văn bản này sẽ được gạch chân.__</code></td>
      <td><ins>Văn bản này sẽ được gạch chân.</ins></td>
    </tr>
    <tr>
      <td>Văn bản phụ</td>
      <td><code>-# Dòng này sẽ được làm nhỏ hơn và mờ đi.</code></td>
      <td><small style="opacity: 0.6;">Dòng này sẽ được làm nhỏ hơn và mờ đi.</small></td>
    </tr>
  </tbody>
</table>
