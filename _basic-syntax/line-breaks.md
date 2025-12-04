---
title: Ngắt dòng (Line Breaks)
syntax-id: line-breaks
description: "Để tạo ngắt dòng hoặc dòng mới (`<br>`), kết thúc một dòng bằng hai hoặc nhiều khoảng trắng, và sau đó gõ phím return."
examples:
  - markdown: |
      Đây là dòng đầu tiên.  
      Và đây là dòng thứ hai.
    html: "<p>Đây là dòng đầu tiên.  <br>Và đây là dòng thứ hai.</p>"
---

Để tạo ngắt dòng hoặc dòng mới (`<br>`), kết thúc một dòng bằng hai hoặc nhiều khoảng trắng, và sau đó gõ phím return.

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
          Đây là dòng đầu tiên. &nbsp;<br />
          Và đây là dòng thứ hai.
        </code>
      </td>
      <td>
        <code class="highlighter-rouge">&lt;p&gt;Đây là dòng đầu tiên.&lt;br&gt;<br />
        Và đây là dòng thứ hai.&lt;/p&gt;</code>
      </td>
      <td>
        <p>Đây là dòng đầu tiên.<br />
        Và đây là dòng thứ hai.</p>
      </td>
    </tr>
  </tbody>
</table>

### Thực tiễn tốt nhất cho Ngắt dòng

Bạn có thể sử dụng hai hoặc nhiều khoảng trắng (thường được gọi là "khoảng trắng ở cuối dòng") để ngắt dòng trong hầu hết các ứng dụng Markdown, nhưng điều này gây tranh cãi. Rất khó để nhìn thấy khoảng trắng ở cuối dòng trong trình soạn thảo, và nhiều người vô tình hoặc cố ý đặt hai khoảng trắng sau mỗi câu. Vì lý do này, bạn có thể muốn sử dụng một cái gì đó khác ngoài khoảng trắng ở cuối dòng để ngắt dòng. Nếu ứng dụng Markdown của bạn [hỗ trợ HTML](/basic-syntax/#html), bạn có thể sử dụng thẻ HTML `<br>`.

Để đảm bảo khả năng tương thích, hãy sử dụng khoảng trắng ở cuối dòng hoặc thẻ HTML `<br>` ở cuối dòng.

Có hai tùy chọn khác mà tôi không khuyến khích sử dụng. CommonMark và một số ngôn ngữ đánh dấu nhẹ khác cho phép bạn gõ dấu gạch chéo ngược (`\`) ở cuối dòng, nhưng không phải tất cả các ứng dụng Markdown đều hỗ trợ điều này, vì vậy nó không phải là một lựa chọn tuyệt vời từ góc độ tương thích. Và ít nhất một vài ngôn ngữ đánh dấu nhẹ không yêu cầu bất cứ điều gì ở cuối dòng — chỉ cần gõ phím return và chúng sẽ tạo ra một ngắt dòng.

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
          Dòng đầu tiên với hai khoảng trắng phía sau. &nbsp;<br>
          Và dòng tiếp theo.<br><br>

          Dòng đầu tiên với thẻ HTML phía sau.&lt;br&gt;<br>
          Và dòng tiếp theo.<br><br>
        </code>
      </td>
      <td>
        <code class="highlighter-rouge">
        Dòng đầu tiên với dấu gạch chéo ngược phía sau.\<br>
        Và dòng tiếp theo.<br><br>

        Dòng đầu tiên không có gì phía sau.<br>
        Và dòng tiếp theo.<br><br>
        </code>
      </td>
    </tr>
  </tbody>
</table>
