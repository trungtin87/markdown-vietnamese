---
title: Tables
syntax-id: tables
syntax-summary: |
  | Syntax | Description |
  | ----------- | ----------- |
  | Header | Title |
  | Paragraph | Text |
---

Để thêm bảng, hãy sử dụng ba hoặc nhiều dấu gạch ngang (`---`) để tạo tiêu đề của mỗi cột và sử dụng dấu gạch đứng (`|`) để phân tách các cột. Để tương thích, bạn cũng nên thêm dấu gạch đứng ở hai đầu của hàng.

```
| Syntax      | Description |
| ----------- | ----------- |
| Header      | Title       |
| Paragraph   | Text        |
```

Kết quả hiển thị trông như thế này:

<table class="table table-bordered">
  <thead>
    <tr>
      <th>Syntax</th>
      <th>Description</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Header</td>
      <td>Title</td>
    </tr>
    <tr>
      <td>Paragraph</td>
      <td>Text</td>
    </tr>
  </tbody>
</table>

Độ rộng ô có thể khác nhau, như được hiển thị bên dưới. Kết quả hiển thị sẽ giống nhau.

```
| Syntax | Description |
| --- | ----------- |
| Header | Title |
| Paragraph | Text |
```

<div class="alert alert-success">
  <i class="fas fa-lightbulb"></i> <strong>Mẹo:</strong> Tạo bảng bằng dấu gạch ngang và dấu gạch đứng có thể tẻ nhạt. Để tăng tốc quá trình, hãy thử sử dụng <a href="https://www.tablesgenerator.com/markdown_tables">Markdown Tables Generator</a> hoặc <a href="https://anywaydata.com">AnyWayData Markdown Export</a>. Xây dựng bảng bằng giao diện đồ họa, sau đó sao chép văn bản định dạng Markdown được tạo vào tệp của bạn.
</div>

### Căn Chỉnh

Bạn có thể căn chỉnh văn bản trong các cột sang trái, phải hoặc giữa bằng cách thêm dấu hai chấm (`:`) vào bên trái, bên phải hoặc cả hai bên của dấu gạch ngang trong hàng tiêu đề.

```
| Syntax      | Description | Test Text     |
| :---        |    :----:   |          ---: |
| Header      | Title       | Here's this   |
| Paragraph   | Text        | And more      |
```

Kết quả hiển thị trông như thế này:

<table class="table table-bordered">
  <thead>
    <tr>
      <th style="text-align: left">Syntax</th>
      <th style="text-align: center">Description</th>
      <th style="text-align: right">Test Text</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align: left">Header</td>
      <td style="text-align: center">Title</td>
      <td style="text-align: right">Here's this</td>
    </tr>
    <tr>
      <td style="text-align: left">Paragraph</td>
      <td style="text-align: center">Text</td>
      <td style="text-align: right">And more</td>
    </tr>
  </tbody>
</table>

### Định Dạng Văn Bản Trong Bảng

Bạn có thể định dạng văn bản trong bảng. Ví dụ: bạn có thể thêm [liên kết](/basic-syntax/#links), [mã](/basic-syntax/#code-1) (chỉ các từ hoặc cụm từ trong dấu backtick (`` ` ``), không phải [khối mã](/basic-syntax/#code-blocks)) và [nhấn mạnh](/basic-syntax/#emphasis).

Bạn không thể sử dụng tiêu đề, trích dẫn khối, danh sách, đường kẻ ngang, hình ảnh hoặc hầu hết các thẻ HTML.

<div class="alert alert-success">
  <i class="fas fa-lightbulb"></i> <strong>Mẹo:</strong> Bạn có thể sử dụng HTML để tạo <a href="/hacks/#line-breaks-within-table-cells">ngắt dòng</a> và thêm <a href="/hacks/#lists-within-table-cells">danh sách</a> trong các ô bảng.
</div>

### Thoát Ký Tự Gạch Đứng Trong Bảng

Bạn có thể hiển thị ký tự gạch đứng (`|`) trong bảng bằng cách sử dụng mã ký tự HTML của nó (`&#124;`).
