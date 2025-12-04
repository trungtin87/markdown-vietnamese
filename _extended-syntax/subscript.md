---
title: Chỉ số dưới (Subscript)
syntax-id: subscript
---

Điều này không phổ biến, nhưng một số bộ xử lý Markdown cho phép bạn sử dụng *chỉ số dưới* để đặt một hoặc nhiều ký tự hơi thấp hơn dòng văn bản thông thường. Để tạo chỉ số dưới, hãy sử dụng một ký hiệu dấu ngã (`~`) trước và sau các ký tự.

```text
H~2~O
```

Kết quả hiển thị trông như thế này:

H<sub>2</sub>O

<div class="alert alert-success">
  <i class="fas fa-lightbulb"></i> <strong>Mẹo:</strong> Hãy chắc chắn kiểm tra điều này trong ứng dụng Markdown của bạn trước khi sử dụng. Một số ứng dụng Markdown sử dụng một ký hiệu dấu ngã trước và sau các từ không phải cho chỉ số dưới, mà cho <a href="/extended-syntax/#strikethrough">gạch ngang</a>. 
</div>

Ngoài ra, nếu ứng dụng Markdown của bạn hỗ trợ [HTML](/basic-syntax/#html), bạn có thể sử dụng thẻ HTML `sub`.

```html
H<sub>2</sub>O
```