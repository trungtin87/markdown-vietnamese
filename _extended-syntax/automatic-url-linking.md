---
title: Automatic URL Linking
syntax-id: automatic-url-linking
---

Nhiều bộ xử lý Markdown tự động chuyển URL thành liên kết. Điều đó có nghĩa là nếu bạn nhập http://www.example.com, bộ xử lý Markdown của bạn sẽ tự động chuyển nó thành liên kết mặc dù bạn chưa [sử dụng dấu ngoặc vuông](/basic-syntax/#links).

```
http://www.example.com
```

Kết quả hiển thị trông như thế này:

[http://www.example.com](http://www.example.com)

## Vô Hiệu Hóa Tự Động Liên Kết URL

Nếu bạn không muốn URL được tự động liên kết, bạn có thể xóa liên kết bằng cách [biểu thị URL dưới dạng mã](/basic-syntax/#code) với dấu backtick.

```
`http://www.example.com`
```

Kết quả hiển thị trông như thế này:

`http://www.example.com`
