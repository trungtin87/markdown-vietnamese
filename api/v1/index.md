---
layout: default
title: API
description: Truy cập tài liệu Markdown theo chương trình.
last_modified_at: 2018-10-18
---

## Giới Thiệu

API Hướng Dẫn Markdown cung cấp một tập hợp con tài liệu từ *Hướng Dẫn Markdown* ở định dạng JSON. Chúng tôi hy vọng rằng các nhà phát triển phần mềm và tổ chức sử dụng API này để truy cập tài liệu của chúng tôi theo chương trình và hiển thị nó trong các ứng dụng và trên các trang web.

### Tại Sao?

Tại sao tạo API cho tài liệu Markdown? Bởi vì có quá nhiều tài liệu Markdown trùng lặp trên web! Có vẻ như mọi người đều có phiên bản tài liệu Markdown riêng cho ứng dụng hoặc trang web của họ. Thật đáng tiếc vì hầu hết chúng đều giống hệt nhau.

Rồi đến khoảnh khắc sáng tạo. 💡 Chúng tôi nhận ra rằng chúng tôi có thể tạo một API JSON sử dụng tài liệu từ *Hướng Dẫn Markdown*. Bằng cách đó, các nhà phát triển phần mềm có thể bắt đầu sử dụng API để đưa tài liệu của chúng tôi vào ứng dụng của họ, và các tổ chức như trường đại học và thư viện có thể sử dụng API để đưa tài liệu của chúng tôi vào trang web của họ.

Chúng tôi rất muốn thấy *Hướng Dẫn Markdown* trở thành kho tài liệu trung tâm cho hàng nghìn hướng dẫn Markdown rải rác trên internet. Nó có hoạt động không? Ai biết được! Nhưng một điều chắc chắn: Chúng tôi không thể chờ đợi để xem bạn làm gì với nó. 🤘

### Hạn Chế

API Hướng Dẫn Markdown được thiết kế để chỉ cung cấp tài liệu Markdown thiết yếu. Do đó, API không bao gồm tất cả tài liệu có sẵn trên trang web *Hướng Dẫn Markdown*. Ví dụ: phần [Thêm Thành Phần Trong Danh Sách](/basic-syntax/#adding-elements-in-lists) không có sẵn thông qua endpoint cú pháp cơ bản.

## Endpoint Cú Pháp Cơ Bản

Endpoint cú pháp cơ bản chứa tài liệu về các thành phần Markdown được nêu trong tài liệu thiết kế của John Gruber và được mô tả trên [trang Cú Pháp Cơ Bản](/basic-syntax/).

<div class="card">
  <h6 class="card-header no-anchor" data-toc-skip>API Endpoint</h6>
  <div class="card-body"><a href="/api/v1/basic-syntax.json">/api/v1/basic-syntax.json</a></div>
</div>

### Yêu Cầu

`curl https://www.markdownguide.org/api/v1/basic-syntax.json`

### Phản Hồi

<script src="https://gist.github.com/mattcone/a0103c47bdac8bf81a54b29f650e5cb2.js"></script>

## Endpoint Bảng Tra Cứu Nhanh

Endpoint bảng tra cứu nhanh cung cấp tổng quan về các thành phần cú pháp Markdown cơ bản và mở rộng phổ biến nhất, như được mô tả trên [trang Bảng Tra Cứu Nhanh](/cheat-sheet/).

<div class="card">
  <h6 class="card-header no-anchor" data-toc-skip>API Endpoint</h6>
  <div class="card-body"><a href="/api/v1/cheat-sheet.json">/api/v1/cheat-sheet.json</a></div>
</div>

### Yêu Cầu

`curl https://www.markdownguide.org/api/v1/cheat-sheet.json`

### Phản Hồi

<script src="https://gist.github.com/mattcone/ec8057127a0ff2e0b45d2cde14355b2a.js"></script>

## Nhật Ký Thay Đổi

Đây là danh sách tất cả các thay đổi chúng tôi đã thực hiện đối với API Hướng Dẫn Markdown.

```
2018-10-18
- Cập nhật endpoint bảng tra cứu nhanh để bao gồm thông tin về danh sách định nghĩa

2018-07-12
- Cập nhật mô tả liên kết để bao gồm thông tin về việc thêm tiêu đề

2017-11-10
- Thêm endpoint bảng tra cứu nhanh

2017-11-04
- Thêm phần về thoát dấu backtick trong mã

2017-10-24
- Phát hành API v1
- Xuất bản tài liệu
```
