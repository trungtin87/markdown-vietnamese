---
title: Đoạn văn (Paragraphs)
syntax-id: paragraphs
description: "Để tạo các đoạn văn, sử dụng một dòng trống để tách một hoặc nhiều dòng văn bản. Bạn không nên thụt đầu dòng các đoạn văn bằng khoảng trắng hoặc tab."
examples:
  - markdown: |
      Tôi thực sự thích sử dụng Markdown.

      Tôi nghĩ tôi sẽ sử dụng nó để định dạng tất cả các tài liệu của mình từ bây giờ.
    html: "<p>Tôi thực sự thích sử dụng Markdown.</p><p>Tôi nghĩ tôi sẽ sử dụng nó để định dạng tất cả các tài liệu của mình từ bây giờ.</p>"
---

Để tạo các đoạn văn, sử dụng một dòng trống để tách một hoặc nhiều dòng văn bản.

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
      <td>
        <code class="highlighter-rouge">
          Tôi thực sự thích sử dụng Markdown.<br /><br />

          Tôi nghĩ tôi sẽ sử dụng nó để định dạng tất cả các tài liệu của mình từ bây giờ.
        </code>
      </td>
      <td>
        <code class="highlighter-rouge">&lt;p&gt;Tôi thực sự thích sử dụng Markdown.&lt;/p&gt;<br /><br />

        &lt;p&gt;Tôi nghĩ tôi sẽ sử dụng nó để định dạng tất cả các tài liệu của mình từ bây giờ.&lt;/p&gt;</code>
      </td>
      <td>
        <p>Tôi thực sự thích sử dụng Markdown.</p>

        <p>Tôi nghĩ tôi sẽ sử dụng nó để định dạng tất cả các tài liệu của mình từ bây giờ.</p>
      </td>
    </tr>
  </tbody>
</table>

### Thực tiễn tốt nhất cho Đoạn văn

Trừ khi [đoạn văn nằm trong một danh sách](/basic-syntax/#paragraphs), đừng thụt đầu dòng các đoạn văn bằng khoảng trắng hoặc tab.

<div class="alert alert-info">
  <i class="fas fa-info-circle"></i> <strong>Lưu ý:</strong> Nếu bạn cần thụt đầu dòng các đoạn văn trong đầu ra, xem phần về cách <a href="/hacks/#indent-tab">thụt đầu dòng (tab)</a>.
</div>

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
          Đừng đặt tab hoặc khoảng trắng trước các đoạn văn của bạn.<br><br>

          Giữ các dòng căn trái như thế này.<br><br>
        </code>
      </td>
      <td>
        <code class="highlighter-rouge">
        &nbsp;&nbsp;&nbsp;&nbsp;Điều này có thể dẫn đến các vấn đề
        định dạng không mong muốn.<br><br>

        &nbsp;&nbsp;Đừng thêm tab hoặc khoảng trắng trước các đoạn văn.
        </code>
      </td>
    </tr>
  </tbody>
</table>
