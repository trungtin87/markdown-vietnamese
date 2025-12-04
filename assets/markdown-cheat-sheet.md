# Markdown Cheat Sheet

Thanks for visiting [The Markdown Guide](https://www.markdownguide.org)!

Mã này cung cấp một cái nhìn nhanh về tất cả các thành phần cú pháp Markdown. Nó không thể bao phủ mọi trường hợp, vì vậy nếu bạn cần thêm thông tin về bất kỳ thành phần nào, hãy tham khảo các hướng dẫn tham khảo cho [cú pháp cơ bản](https://www.markdownguide.org/basic-syntax/) và [cú pháp mở rộng](https://www.markdownguide.org/extended-syntax/).

## Basic Syntax

Các thành phần này được nêu trong tài liệu thiết kế gốc của John Gruber. Tất cả các ứng dụng Markdown đều hỗ trợ các thành phần này.

### Heading

# H1
## H2
### H3

### Bold

**bold text**

### Italic

*italicized text*

### Blockquote

> blockquote

### Ordered List

1. First item
2. Second item
3. Third item

### Unordered List

- First item
- Second item
- Third item

### Code

`code`

### Horizontal Rule

---

### Link

[Markdown Guide](https://www.markdownguide.org)

### Image

![alt text](https://www.markdownguide.org/assets/images/tux.png)

## Extended Syntax

Các thành phần này mở rộng cú pháp cơ bản bằng cách thêm các tính năng bổ sung. Không phải tất cả các ứng dụng Markdown đều hỗ trợ các thành phần này.

### Table

| Syntax | Description |
| ----------- | ----------- |
| Header | Title |
| Paragraph | Text |

### Fenced Code Block

```
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```

### Footnote

Here's a sentence with a footnote. [^1]

[^1]: This is the footnote.

### Heading ID

### My Great Heading {#custom-id}

### Definition List

term
: definition

### Strikethrough

~~The world is flat.~~

### Task List

- [x] Write the press release
- [ ] Update the website
- [ ] Contact the media

### Emoji

That is so funny! :joy:

(See also [Copying and Pasting Emoji](https://www.markdownguide.org/extended-syntax/#copying-and-pasting-emoji))

### Highlight

Tôi cần nhấn mạnh những từ này ==như những từ quan trọng==.

### Subscript

H~2~O

### Superscript

X^2^