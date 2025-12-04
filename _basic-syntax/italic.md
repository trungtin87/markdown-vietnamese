---
title: In nghiêng (Italic)
syntax-id: italic
syntax-summary: "*văn bản in nghiêng*"
description: "Để in nghiêng văn bản, thêm một dấu sao hoặc dấu gạch dưới vào trước và sau một từ hoặc cụm từ. Để in nghiêng phần giữa của một từ nhằm nhấn mạnh, thêm một dấu sao mà không có khoảng trắng xung quanh các chữ cái."
examples:
  - markdown: "Văn bản in nghiêng là *cat's meow*."
    html: "Văn bản in nghiêng là <em>cat's meow</em>."
  - markdown: "Văn bản in nghiêng là _cat's meow_."
    html: "Văn bản in nghiêng là <em>cat's meow</em>."
  - markdown: "Một*con*mèo"
    html: "Một<em>con</em>mèo"
---

Để in nghiêng văn bản, thêm một dấu sao hoặc dấu gạch dưới vào trước và sau một từ hoặc cụm từ. Để in nghiêng phần giữa của một từ nhằm nhấn mạnh, thêm một dấu sao mà không có khoảng trắng xung quanh các chữ cái.

<table class="table table-bordered">
  <thead class="thead-light">
    <tr>
      <th>Markdown</th>
      <th>HTML</th>
      <th>Kết quả hiển thị</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><code class="highlighter-rouge">Văn bản in nghiêng là *cat's meow*.</code></td>
      <td><code class="highlighter-rouge">Văn bản in nghiêng là &lt;em&gt;cat's meow&lt;/em&gt;.</code></td>
      <td>Văn bản in nghiêng là <em>cat’s meow</em>.</td>
    </tr>
    <tr>
      <td><code class="highlighter-rouge">Văn bản in nghiêng là _cat's meow_.</code></td>
      <td><code class="highlighter-rouge">Văn bản in nghiêng là &lt;em&gt;cat's meow&lt;/em&gt;.</code></td>
      <td>Văn bản in nghiêng là <em>cat’s meow</em>.</td>
    </tr>
    <tr>
      <td><code class="highlighter-rouge">Một*con*mèo</code></td>
      <td><code class="highlighter-rouge">Một&lt;em&gt;con&lt;/em&gt;mèo</code></td>
      <td>Một<em>con</em>mèo</td>
    </tr>
  </tbody>
</table>

#### Thực tiễn tốt nhất cho In nghiêng

Các ứng dụng Markdown không thống nhất về cách xử lý dấu gạch dưới ở giữa một từ. Để đảm bảo khả năng tương thích, hãy sử dụng dấu sao để in nghiêng phần giữa của một từ nhằm nhấn mạnh.

<table class="table table-bordered">
  <thead class="thead-light">
    <tr>
      <th>✅&nbsp; Nên làm</th>
      <th>❌&nbsp; Không nên làm</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>
        <code class="highlighter-rouge">
          Một*con*mèo
        </code>
      </td>
      <td>
        <code class="highlighter-rouge">
          Một_con_mèo
        </code>
      </td>
    </tr>
  </tbody>
</table>
