---
title: Khối mã có rào chắn (Fenced Code Blocks)
syntax-id: fenced-code-blocks
syntax-summary: |
  ```
  {
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
  }
  ```
---

Cú pháp Markdown cơ bản cho phép bạn tạo [khối mã](/basic-syntax/#code-blocks) bằng cách thụt lề các dòng bốn khoảng trắng hoặc một tab. Nếu bạn thấy điều đó bất tiện, hãy thử sử dụng khối mã có rào chắn. Tùy thuộc vào bộ xử lý hoặc trình soạn thảo Markdown của bạn, bạn sẽ sử dụng ba dấu backtick (<code>```</code>) hoặc ba dấu ngã (`~~~`) trên các dòng trước và sau khối mã. Phần tốt nhất? Bạn không cần thụt lề bất kỳ dòng nào!

~~~~~~~~~
```
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```
~~~~~~~~~

Kết quả hiển thị trông như thế này:

```text
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```

<div class="alert alert-success">
  <i class="fas fa-lightbulb"></i> <strong>Mẹo:</strong> Cần hiển thị dấu backtick bên trong khối mã? Xem <a href="/basic-syntax/#escaping-backticks">phần này</a> để tìm hiểu cách thoát chúng.
</div>

### Làm Nổi Bật Cú Pháp

Nhiều bộ xử lý Markdown hỗ trợ làm nổi bật cú pháp cho các khối mã có rào chắn. Tính năng này cho phép bạn thêm màu nổi bật cho bất kỳ ngôn ngữ nào mà mã của bạn được viết. Để thêm làm nổi bật cú pháp, hãy chỉ định ngôn ngữ bên cạnh dấu backtick trước khối mã có rào chắn.

~~~~~~~~~
```json
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```
~~~~~~~~~

Kết quả hiển thị trông như thế này:

```json
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```
