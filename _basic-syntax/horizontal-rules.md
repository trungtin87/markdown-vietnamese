---
title: Quy tắc ngang (Horizontal Rules)
syntax-id: horizontal-rules
syntax-summary: "---"
description: "Để tạo một quy tắc ngang, sử dụng ba hoặc nhiều dấu sao (`***`), dấu gạch ngang (`---`), hoặc dấu gạch dưới (`___`) trên một dòng riêng biệt."
examples:
  - markdown: "***"
    html: "<hr>"
  - markdown: "---"
    html: "<hr>"
  - markdown: "_________________"
    html: "<hr>"
---

Để tạo một quy tắc ngang, sử dụng ba hoặc nhiều dấu sao (`***`), dấu gạch ngang (`---`), hoặc dấu gạch dưới (`___`) trên một dòng riêng biệt.

```
***

---

_________________
```

Kết quả hiển thị của cả ba đều giống hệt nhau:

---

### Thực tiễn tốt nhất cho Quy tắc ngang

Để đảm bảo khả năng tương thích, hãy đặt các dòng trống trước và sau quy tắc ngang.

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
        Cố gắng đặt một dòng trống trước...<br><br>

        ---<br><br>

        ...và sau một quy tắc ngang.
        </code>
      </td>
      <td>
        <code class="highlighter-rouge">
        Nếu không có dòng trống, đây sẽ là một tiêu đề.<br>
        ---<br>
        Đừng làm điều này!
        </code>
      </td>
    </tr>
  </tbody>
</table>
