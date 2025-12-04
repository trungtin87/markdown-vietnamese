---
title: Nhấn mạnh (Emphasis)
syntax-id: emphasis
api: "no"
---

Bạn có thể thêm nhấn mạnh bằng cách làm cho văn bản in đậm hoặc in nghiêng.

{% include syntax.html type="basic-sub" syntax-id="bold" %}

{% include syntax.html type="basic-sub" syntax-id="italic" %}

### In đậm và In nghiêng

Để nhấn mạnh văn bản bằng cả in đậm và in nghiêng cùng một lúc, thêm ba dấu sao hoặc dấu gạch dưới vào trước và sau một từ hoặc cụm từ. Để in đậm và in nghiêng phần giữa của một từ nhằm nhấn mạnh, thêm ba dấu sao mà không có khoảng trắng xung quanh các chữ cái.

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
      <td><code class="highlighter-rouge">Văn bản này ***thực sự quan trọng***.</code></td>
      <td><code class="highlighter-rouge">Văn bản này &lt;em&gt;&lt;strong&gt;thực sự quan trọng&lt;/strong&gt;&lt;/em&gt;.</code></td>
      <td>Văn bản này <em><strong>thực sự quan trọng</strong></em>.</td>
    </tr>
    <tr>
      <td><code class="highlighter-rouge">Văn bản này ___thực sự quan trọng___.</code></td>
      <td><code class="highlighter-rouge">Văn bản này &lt;em&gt;&lt;strong&gt;thực sự quan trọng&lt;/strong&gt;&lt;/em&gt;.</code></td>
      <td>Văn bản này <em><strong>thực sự quan trọng</strong></em>.</td>
    </tr>
    <tr>
      <td><code class="highlighter-rouge">Văn bản này __*thực sự quan trọng*__.</code></td>
      <td><code class="highlighter-rouge">Văn bản này &lt;em&gt;&lt;strong&gt;thực sự quan trọng&lt;/strong&gt;&lt;/em&gt;.</code></td>
      <td>Văn bản này <em><strong>thực sự quan trọng</strong></em>.</td>
    </tr>
    <tr>
      <td><code class="highlighter-rouge">Văn bản này **_thực sự quan trọng_**.</code></td>
      <td><code class="highlighter-rouge">Văn bản này &lt;em&gt;&lt;strong&gt;thực sự quan trọng&lt;/strong&gt;&lt;/em&gt;.</code></td>
      <td>Văn bản này <em><strong>thực sự quan trọng</strong></em>.</td>
    </tr>
    <tr>
      <td><code class="highlighter-rouge">Đây là văn bản thực sự***rất***quan trọng.</code></td>
      <td><code class="highlighter-rouge">Đây là văn bản thực sự&lt;em&gt;&lt;strong&gt;rất&lt;/strong&gt;&lt;/em&gt;quan trọng.</code></td>
      <td>Đây là văn bản thực sự<em><strong>rất</strong></em>quan trọng.</td>
    </tr>
  </tbody>
</table>

<div class="alert alert-info">
  <i class="fas fa-info-circle"></i> <strong>Lưu ý:</strong> Thứ tự của các thẻ <code>em</code> và <code>strong</code> có thể bị đảo ngược tùy thuộc vào bộ xử lý Markdown bạn đang sử dụng.
</div>

#### Thực tiễn tốt nhất cho In đậm và In nghiêng

Các ứng dụng Markdown không thống nhất về cách xử lý dấu gạch dưới ở giữa một từ. Để đảm bảo khả năng tương thích, hãy sử dụng dấu sao để in đậm và in nghiêng phần giữa của một từ nhằm nhấn mạnh.

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
          Đây là văn bản thực sự***rất***quan trọng.
        </code>
      </td>
      <td>
        <code class="highlighter-rouge">
          Đây là văn bản thực sự___rất___quan trọng.
        </code>
      </td>
    </tr>
  </tbody>
</table>
