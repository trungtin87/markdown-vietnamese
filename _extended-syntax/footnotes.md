---
title: Footnotes
syntax-id: footnotes
syntax-summary: |
  Here's a sentence with a footnote. [^1]

  [^1]: This is the footnote.
---

Chú thích cuối trang cho phép bạn thêm ghi chú và tham chiếu mà không làm lộn xộn nội dung tài liệu. Khi bạn tạo chú thích cuối trang, một số chỉ số trên với liên kết sẽ xuất hiện tại nơi bạn thêm tham chiếu chú thích cuối trang. Người đọc có thể nhấp vào liên kết để chuyển đến nội dung của chú thích cuối trang ở cuối trang.

Để tạo tham chiếu chú thích cuối trang, hãy thêm dấu mũ và mã định danh bên trong dấu ngoặc vuông (`[^1]`). Mã định danh có thể là số hoặc từ, nhưng chúng không thể chứa khoảng trắng hoặc tab. Mã định danh chỉ liên kết tham chiếu chú thích cuối trang với chính chú thích cuối trang — trong đầu ra, các chú thích cuối trang được đánh số tuần tự.

Thêm chú thích cuối trang bằng cách sử dụng dấu mũ và số khác bên trong dấu ngoặc vuông với dấu hai chấm và văn bản (`[^1]: My footnote.`). Bạn không cần đặt chú thích cuối trang ở cuối tài liệu. Bạn có thể đặt chúng ở bất kỳ đâu ngoại trừ bên trong các thành phần khác như danh sách, trích dẫn khối và bảng.

```
Here's a simple footnote,[^1] and here's a longer one.[^bignote]

[^1]: This is the first footnote.

[^bignote]: Here's one with multiple paragraphs and code.

    Indent paragraphs to include them in the footnote.

    `{ my code }`

    Add as many paragraphs as you like.
```

Kết quả hiển thị trông như thế này:

Here's a simple footnote,[^1] and here's a longer one.[^bignote]

[^1]: This is the first footnote.

[^bignote]: Here's one with multiple paragraphs and code.

    Indent paragraphs to include them in the footnote.

    `{ my code }`

    Add as many paragraphs as you like.
