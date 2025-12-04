---
title: Danh sách không có thứ tự (Unordered Lists)
syntax-id: unordered-lists
syntax-summary: |
  - Mục đầu tiên
  - Mục thứ hai
  - Mục thứ ba
description: "Để tạo danh sách không có thứ tự, thêm dấu gạch ngang (`-`), dấu sao (`*`), hoặc dấu cộng (`+`) vào trước các mục dòng. Thụt đầu dòng một hoặc nhiều mục để tạo danh sách lồng nhau."
examples:
  - markdown: |
      - Mục đầu tiên
      - Mục thứ hai
      - Mục thứ ba
      - Mục thứ tư
    html: <ul><li>Mục đầu tiên</li><li>Mục thứ hai</li><li>Mục thứ ba</li><li>Mục thứ tư</li></ul>
  - markdown: |
      * Mục đầu tiên
      * Mục thứ hai
      * Mục thứ ba
      * Mục thứ tư
    html: <ul><li>Mục đầu tiên</li><li>Mục thứ hai</li><li>Mục thứ ba</li><li>Mục thứ tư</li></ul>
  - markdown: |
      + Mục đầu tiên
      * Mục thứ hai
      - Mục thứ ba
      + Mục thứ tư
    html: <ul><li>Mục đầu tiên</li><li>Mục thứ hai</li><li>Mục thứ ba</li><li>Mục thứ tư</li></ul>
  - markdown: |
      - Mục đầu tiên
      - Mục thứ hai
      - Mục thứ ba
          - Mục được thụt đầu dòng
          - Mục được thụt đầu dòng
      - Mục thứ tư
    html: <ul><li>Mục đầu tiên</li><li>Mục thứ hai</li><li>Mục thứ ba<ul><li>Mục được thụt đầu dòng</li><li>Mục được thụt đầu dòng</li></ul></li><li>Mục thứ tư</li></ul>
---

Để tạo danh sách không có thứ tự, thêm dấu gạch ngang (`-`), dấu sao (`*`), hoặc dấu cộng (`+`) vào trước các mục dòng. Thụt đầu dòng một hoặc nhiều mục để tạo danh sách lồng nhau.

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
          - Mục đầu tiên<br/>
          - Mục thứ hai<br/>
          - Mục thứ ba<br/>
          - Mục thứ tư
        </code>
      </td>
      <td>
        <code class="highlighter-rouge">
          &lt;ul&gt;<br>
            &nbsp;&nbsp;&lt;li&gt;Mục đầu tiên&lt;/li&gt;<br/>
            &nbsp;&nbsp;&lt;li&gt;Mục thứ hai&lt;/li&gt;<br/>
            &nbsp;&nbsp;&lt;li&gt;Mục thứ ba&lt;/li&gt;<br/>
            &nbsp;&nbsp;&lt;li&gt;Mục thứ tư&lt;/li&gt;<br/>
          &lt;/ul&gt;
        </code>
      </td>
      <td>
        <ul>
          <li>Mục đầu tiên</li>
          <li>Mục thứ hai</li>
          <li>Mục thứ ba</li>
          <li>Mục thứ tư</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td>
        <code class="highlighter-rouge">
          * Mục đầu tiên<br/>
          * Mục thứ hai<br>
          * Mục thứ ba<br/>
          * Mục thứ tư
        </code>
      </td>
      <td>
        <code class="highlighter-rouge">
          &lt;ul&gt;<br>
            &nbsp;&nbsp;&lt;li&gt;Mục đầu tiên&lt;/li&gt;<br/>
            &nbsp;&nbsp;&lt;li&gt;Mục thứ hai&lt;/li&gt;<br/>
            &nbsp;&nbsp;&lt;li&gt;Mục thứ ba&lt;/li&gt;<br/>
            &nbsp;&nbsp;&lt;li&gt;Mục thứ tư&lt;/li&gt;<br/>
          &lt;/ul&gt;
        </code>
      </td>
      <td>
        <ul>
          <li>Mục đầu tiên</li>
          <li>Mục thứ hai</li>
          <li>Mục thứ ba</li>
          <li>Mục thứ tư</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td>
        <code class="highlighter-rouge">
          + Mục đầu tiên<br/>
          + Mục thứ hai<br/>
          + Mục thứ ba<br/>
          + Mục thứ tư
        </code>
      </td>
      <td>
        <code class="highlighter-rouge">
          &lt;ul&gt;<br>
            &nbsp;&nbsp;&lt;li&gt;Mục đầu tiên&lt;/li&gt;<br/>
            &nbsp;&nbsp;&lt;li&gt;Mục thứ hai&lt;/li&gt;<br/>
            &nbsp;&nbsp;&lt;li&gt;Mục thứ ba&lt;/li&gt;<br/>
            &nbsp;&nbsp;&lt;li&gt;Mục thứ tư&lt;/li&gt;<br/>
          &lt;/ul&gt;
        </code>
      </td>
      <td>
        <ul>
          <li>Mục đầu tiên</li>
          <li>Mục thứ hai</li>
          <li>Mục thứ ba</li>
          <li>Mục thứ tư</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td>
        <code class="highlighter-rouge">
          - Mục đầu tiên<br/>
          - Mục thứ hai<br/>
          - Mục thứ ba<br/>
          &nbsp;&nbsp;&nbsp;&nbsp;- Mục được thụt đầu dòng<br/>
          &nbsp;&nbsp;&nbsp;&nbsp;- Mục được thụt đầu dòng<br/>
          - Mục thứ tư
        </code>
      </td>
      <td>
        <code class="highlighter-rouge">
          &lt;ul&gt;<br/>
            &nbsp;&nbsp;&lt;li&gt;Mục đầu tiên&lt;/li&gt;<br/>
            &nbsp;&nbsp;&lt;li&gt;Mục thứ hai&lt;/li&gt;<br/>
            &nbsp;&nbsp;&lt;li&gt;Mục thứ ba<br/>
              &nbsp;&nbsp;&nbsp;&nbsp;&lt;ul&gt;<br/>
                &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&lt;li&gt;Mục được thụt đầu dòng&lt;/li&gt;<br/>
                &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&lt;li&gt;Mục được thụt đầu dòng&lt;/li&gt;<br/>
              &nbsp;&nbsp;&nbsp;&nbsp;&lt;/ul&gt;<br/>
            &nbsp;&nbsp;&lt;/li&gt;<br/>
            &nbsp;&nbsp;&lt;li&gt;Mục thứ tư&lt;/li&gt;<br/>
          &lt;/ul&gt;
        </code>
      </td>
      <td>
        <ul>
          <li>Mục đầu tiên</li>
          <li>Mục thứ hai</li>
          <li>Mục thứ ba
            <ul>
              <li>Mục được thụt đầu dòng</li>
              <li>Mục được thụt đầu dòng</li>
            </ul>
          </li>
          <li>Mục thứ tư</li>
        </ul>
      </td>
    </tr>
  </tbody>
</table>

#### Bắt đầu Mục Danh sách không có thứ tự bằng Số

Nếu bạn cần bắt đầu một mục danh sách không có thứ tự bằng một số theo sau là dấu chấm, bạn có thể sử dụng dấu gạch chéo ngược (`\`) để [thoát](#escaping-characters) dấu chấm.

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
          - 1968\. Một năm tuyệt vời!<br/>
          - Tôi nghĩ năm 1969 là năm tuyệt vời thứ hai.
        </code>
      </td>
      <td>
        <code class="highlighter-rouge">
          &lt;ul&gt;<br>
            &nbsp;&nbsp;&lt;li&gt;1968. Một năm tuyệt vời!&lt;/li&gt;<br/>
            &nbsp;&nbsp;&lt;li&gt;Tôi nghĩ năm 1969 là năm tuyệt vời thứ hai.&lt;/li&gt;<br/>
          &lt;/ul&gt;
        </code>
      </td>
      <td>
        <ul>
          <li>1968. Một năm tuyệt vời!</li>
          <li>Tôi nghĩ năm 1969 là năm tuyệt vời thứ hai.</li>
        </ul>
      </td>
    </tr>
  </tbody>
</table>

#### Thực tiễn tốt nhất cho Danh sách không có thứ tự

Các ứng dụng Markdown không thống nhất về cách xử lý các dấu phân cách khác nhau trong cùng một danh sách. Để đảm bảo khả năng tương thích, đừng trộn lẫn và kết hợp các dấu phân cách trong cùng một danh sách — hãy chọn một và gắn bó với nó.

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
          - Mục đầu tiên<br>
          - Mục thứ hai<br>
          - Mục thứ ba<br>
          - Mục thứ tư
        </code>
      </td>
      <td>
        <code class="highlighter-rouge">
          + Mục đầu tiên<br>
          * Mục thứ hai<br>
          - Mục thứ ba<br>
          + Mục thứ tư
        </code>
      </td>
    </tr>
  </tbody>
</table>
