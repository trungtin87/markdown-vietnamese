---
title: Danh sách có thứ tự (Ordered Lists)
syntax-id: ordered-lists
syntax-summary: |
  1. Mục đầu tiên
  2. Mục thứ hai
  3. Mục thứ ba
description: "Để tạo danh sách có thứ tự, thêm các mục dòng với các số theo sau là dấu chấm. Các số không nhất thiết phải theo thứ tự số học, nhưng danh sách nên bắt đầu bằng số một."
examples:
  - markdown: |
      1. Mục đầu tiên
      2. Mục thứ hai
      3. Mục thứ ba
      4. Mục thứ tư
    html: <ol><li>Mục đầu tiên</li><li>Mục thứ hai</li><li>Mục thứ ba</li><li>Mục thứ tư</li></ol>
  - markdown: |
      1. Mục đầu tiên
      1. Mục thứ hai
      1. Mục thứ ba
      1. Mục thứ tư
    html: <ol><li>Mục đầu tiên</li><li>Mục thứ hai</li><li>Mục thứ ba</li><li>Mục thứ tư</li></ol>
  - markdown: |
      1. Mục đầu tiên
      8. Mục thứ hai
      3. Mục thứ ba
      5. Mục thứ tư
    html: <ol><li>Mục đầu tiên</li><li>Mục thứ hai</li><li>Mục thứ ba</li><li>Mục thứ tư</li></ol>
  - markdown: |
      1. Mục đầu tiên
      2. Mục thứ hai
      3. Mục thứ ba
        1. Mục được thụt đầu dòng
        2. Mục được thụt đầu dòng
      4. Mục thứ tư
    html: <ol><li>Mục đầu tiên</li><li>Mục thứ hai</li><li>Mục thứ ba<ol><li>Mục được thụt đầu dòng</li><li>Mục được thụt đầu dòng</li></ol></li><li>Mục thứ tư</li></ol>
---

Để tạo danh sách có thứ tự, thêm các mục dòng với các số theo sau là dấu chấm. Các số không nhất thiết phải theo thứ tự số học, nhưng danh sách nên bắt đầu bằng số một.

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
        1. Mục đầu tiên<br/>
        2. Mục thứ hai<br/>
        3. Mục thứ ba<br/>
        4. Mục thứ tư
      </code>
    </td>
    <td>
      <code class="highlighter-rouge">
        &lt;ol&gt;<br>
          &nbsp;&nbsp;&lt;li&gt;Mục đầu tiên&lt;/li&gt;<br/>
          &nbsp;&nbsp;&lt;li&gt;Mục thứ hai&lt;/li&gt;<br/>
          &nbsp;&nbsp;&lt;li&gt;Mục thứ ba&lt;/li&gt;<br/>
          &nbsp;&nbsp;&lt;li&gt;Mục thứ tư&lt;/li&gt;<br/>
        &lt;/ol&gt;
      </code>
    </td>
    <td>
      <ol>
        <li>Mục đầu tiên</li>
        <li>Mục thứ hai</li>
        <li>Mục thứ ba</li>
        <li>Mục thứ tư</li>
      </ol>
    </td>
    </tr>
    <tr>
      <td>
        <code class="highlighter-rouge">
          1. Mục đầu tiên<br/>
          1. Mục thứ hai<br/>
          1. Mục thứ ba<br/>
          1. Mục thứ tư
        </code>
      </td>
      <td>
        <code class="highlighter-rouge">
          &lt;ol&gt;<br>
            &nbsp;&nbsp;&lt;li&gt;Mục đầu tiên&lt;/li&gt;<br/>
            &nbsp;&nbsp;&lt;li&gt;Mục thứ hai&lt;/li&gt;<br/>
            &nbsp;&nbsp;&lt;li&gt;Mục thứ ba&lt;/li&gt;<br/>
            &nbsp;&nbsp;&lt;li&gt;Mục thứ tư&lt;/li&gt;<br/>
          &lt;/ol&gt;
        </code>
      </td>
      <td>
        <ol>
          <li>Mục đầu tiên</li>
          <li>Mục thứ hai</li>
          <li>Mục thứ ba</li>
          <li>Mục thứ tư</li>
        </ol>
      </td>
    </tr>
    <tr>
      <td>
        <code class="highlighter-rouge">
          1. Mục đầu tiên<br/>
          8. Mục thứ hai<br/>
          3. Mục thứ ba<br/>
          5. Mục thứ tư
        </code>
      </td>
      <td>
        <code class="highlighter-rouge">
          &lt;ol&gt;<br>
            &nbsp;&nbsp;&lt;li&gt;Mục đầu tiên&lt;/li&gt;<br/>
            &nbsp;&nbsp;&lt;li&gt;Mục thứ hai&lt;/li&gt;<br/>
            &nbsp;&nbsp;&lt;li&gt;Mục thứ ba&lt;/li&gt;<br/>
            &nbsp;&nbsp;&lt;li&gt;Mục thứ tư&lt;/li&gt;<br/>
          &lt;/ol&gt;
        </code>
      </td>
      <td>
        <ol>
          <li>Mục đầu tiên</li>
          <li>Mục thứ hai</li>
          <li>Mục thứ ba</li>
          <li>Mục thứ tư</li>
        </ol>
      </td>
    </tr>
    <tr>
      <td>
        <code class="highlighter-rouge">
          1. Mục đầu tiên<br/>
          2. Mục thứ hai<br/>
          3. Mục thứ ba<br/>
          &nbsp;&nbsp;&nbsp;&nbsp;1. Mục được thụt đầu dòng<br/>
          &nbsp;&nbsp;&nbsp;&nbsp;2. Mục được thụt đầu dòng<br/>
          4. Mục thứ tư
        </code>
      </td>
      <td>
        <code class="highlighter-rouge">
          &lt;ol&gt;<br>
            &nbsp;&nbsp;&lt;li&gt;Mục đầu tiên&lt;/li&gt;<br/>
            &nbsp;&nbsp;&lt;li&gt;Mục thứ hai&lt;/li&gt;<br/>
            &nbsp;&nbsp;&lt;li&gt;Mục thứ ba<br/>
              &nbsp;&nbsp;&nbsp;&nbsp;&lt;ol&gt;<br>
                &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&lt;li&gt;Mục được thụt đầu dòng&lt;/li&gt;<br/>
                &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&lt;li&gt;Mục được thụt đầu dòng&lt;/li&gt;<br/>
              &nbsp;&nbsp;&nbsp;&nbsp;&lt;/ol&gt;<br/>
            &nbsp;&nbsp;&lt;/li&gt;<br/>
            &nbsp;&nbsp;&lt;li&gt;Mục thứ tư&lt;/li&gt;<br/>
          &lt;/ol&gt;
        </code>
      </td>
      <td>
        <ol>
          <li>Mục đầu tiên</li>
          <li>Mục thứ hai</li>
          <li>Mục thứ ba
            <ol>
              <li>Mục được thụt đầu dòng</li>
              <li>Mục được thụt đầu dòng</li>
            </ol>
          </li>
          <li>Mục thứ tư</li>
        </ol>
      </td>
    </tr>
  </tbody>
</table>

#### Thực tiễn tốt nhất cho Danh sách có thứ tự

CommonMark và một số ngôn ngữ đánh dấu nhẹ khác cho phép bạn sử dụng dấu ngoặc đơn (`)`) làm dấu phân cách (ví dụ: `1) Mục đầu tiên`), nhưng không phải tất cả các ứng dụng Markdown đều hỗ trợ điều này, vì vậy nó không phải là một lựa chọn tuyệt vời từ góc độ tương thích. Để đảm bảo khả năng tương thích, chỉ sử dụng dấu chấm.

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
          1. Mục đầu tiên<br>
          2. Mục thứ hai
        </code>
      </td>
      <td>
        <code class="highlighter-rouge">
          1) Mục đầu tiên<br>
          2) Mục thứ hai
        </code>
      </td>
    </tr>
  </tbody>
</table>
