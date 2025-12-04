---
title: In đậm (Bold)
syntax-id: bold
syntax-summary: "**văn bản in đậm**"
description: "Để in đậm văn bản, thêm hai dấu sao hoặc dấu gạch dưới vào trước và sau một từ hoặc cụm từ. Để in đậm phần giữa của một từ nhằm nhấn mạnh, thêm hai dấu sao mà không có khoảng trắng xung quanh các chữ cái."
examples:
  - markdown: "Tôi rất thích **chữ in đậm**."
    html: "Tôi rất thích <strong>chữ in đậm</strong>."
  - markdown: "Tôi rất thích __chữ in đậm__."
    html: "Tôi rất thích <strong>chữ in đậm</strong>."
  - markdown: "Yêu**là**đậm"
    html: "Yêu<strong>là</strong>đậm"
---

Để in đậm văn bản, thêm hai dấu sao hoặc dấu gạch dưới vào trước và sau một từ hoặc cụm từ. Để in đậm phần giữa của một từ nhằm nhấn mạnh, thêm hai dấu sao mà không có khoảng trắng xung quanh các chữ cái.

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
      <td><code class="highlighter-rouge">Tôi rất thích **chữ in đậm**.</code></td>
      <td><code class="highlighter-rouge">Tôi rất thích &lt;strong&gt;chữ in đậm&lt;/strong&gt;.</code></td>
      <td>Tôi rất thích <strong>chữ in đậm</strong>.</td>
    </tr>
    <tr>
      <td><code class="highlighter-rouge">Tôi rất thích __chữ in đậm__.</code></td>
      <td><code class="highlighter-rouge">Tôi rất thích &lt;strong&gt;chữ in đậm&lt;/strong&gt;.</code></td>
      <td>Tôi rất thích <strong>chữ in đậm</strong>.</td>
    </tr>
    <tr>
      <td><code class="highlighter-rouge">Yêu**là**đậm</code></td> <td><code class="highlighter-rouge">Yêu&lt;strong&gt;là&lt;/strong&gt;đậm</code></td>
      <td>Yêu<strong>là</strong>đậm</td>
    </tr>
  </tbody>
</table>

#### Thực tiễn tốt nhất cho In đậm

Các ứng dụng Markdown không thống nhất về cách xử lý dấu gạch dưới ở giữa một từ. Để đảm bảo khả năng tương thích, hãy sử dụng dấu sao để in đậm phần giữa của một từ nhằm nhấn mạnh.

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
          Yêu**là**đậm
        </code>
      </td>
      <td>
        <code class="highlighter-rouge">
          Yêu__là__đậm
        </code>
      </td>
    </tr>
  </tbody>
</table>
