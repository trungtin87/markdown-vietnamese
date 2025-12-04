---
title: teedoc
category: "websites"
description: "Trình tạo trang web tài liệu tĩnh từ Markdown và jupyter, được viết bằng Python."
icon: teedoc.png
website: https://teedoc.github.io
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
    available: n
  - id: highlight
    available: n
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
  - name: Các tính năng Markdown của teedoc
    link: https://teedoc.github.io/get_started/en/syntax/syntax_markdown.html
---

[teedoc](https://teedoc.github.io) là một trình tạo trang web tĩnh mã nguồn mở chuyển đổi các file Markdown và jupyter notebooks thành một trang web tài liệu. teedoc được viết bằng ngôn ngữ lập trình Python, dễ sử dụng và mở rộng. teedoc đặc biệt phù hợp cho nhiều trang web tài liệu, wiki hoặc cơ sở kiến thức.

teedoc sử dụng trình phân tích cú pháp Markdown [mistune](https://github.com/lepture/mistune).

{% include image.html file="assets/images/tools/teedoc.png" alt="Ví dụ về trang web teedoc" %}

{% include tool-syntax-table.html %}

### Hỗ trợ cho các Phần tử Cú pháp Bổ sung

teedoc hỗ trợ nhiều cú pháp bổ sung hữu ích như:

* [mermaid](https://mermaid-js.github.io/mermaid/): Một ngôn ngữ kịch bản đơn giản giống markdown để tạo biểu đồ từ văn bản thông qua javascript.
* math: Hỗ trợ cú pháp toán học Latex, tex và thẻ MathML.
* tabset: Một cú pháp tabset dễ sử dụng. Ví dụ, nó hiển thị các ví dụ mã khác nhau cho các ngôn ngữ lập trình khác nhau.

  ```markdown
    .. tabset::
        :id: tabset1

        ## Kotlin

        Nội dung 1, hỗ trợ đầy đủ cú pháp Markdown

        ## Java

        Nội dung 2, hỗ trợ đầy đủ cú pháp Markdown
  ```

  sẽ được hiển thị thành:

  ```html
  <div class="tabset tabset-id-tabset1">
    <div class="tabset-title">Tiêu đề(tùy chọn)</div>
    <div class="tabset-content">
      <div class="tabset-tab">
        <span class="tabset-tab-label tabset-tab-active" idx="0">Kotlin</span>
        <span class="tabset-tab-label " idx="1">Java</span>
      </div>
      <div class="tabset-text-container">
          <div class="tabset-text tabset-text-active" idx="0">
            <p>Nội dung 1, hỗ trợ đầy đủ cú pháp Markdown</p>
          </div>
          <div class="tabset-text" idx="1">
            <p>Nội dung 2, hỗ trợ đầy đủ cú pháp Markdown</p>
          </div>
      </div>
    </div>
  </div>
  ```

* details: Một cú pháp để tạo thẻ details HTML5.

  ```markdown
    .. details::Tiêu đề, nhấp để mở rộng

        Nội dung, hỗ trợ đầy đủ cú pháp Markdown
  ```

  sẽ được hiển thị thành:

  ```html
    <details>
      <summary>Tiêu đề, nhấp để mở rộng</summary>
      <div class="details-content">
        <p>Nội dung, hỗ trợ đầy đủ cú pháp Markdown</p>
      </div>
    </details>
  ```

Để biết thêm thông tin về cú pháp, hãy truy cập [cú pháp markdown teedoc](https://teedoc.github.io/get_started/en/syntax/syntax_markdown.html).
