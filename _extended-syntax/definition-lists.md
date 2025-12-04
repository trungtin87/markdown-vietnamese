---
title: Definition Lists
syntax-id: definition-lists
syntax-summary: |
  term
  : definition
---

Một số bộ xử lý Markdown cho phép bạn tạo *danh sách định nghĩa* của các thuật ngữ và định nghĩa tương ứng của chúng. Để tạo danh sách định nghĩa, hãy nhập thuật ngữ trên dòng đầu tiên. Trên dòng tiếp theo, nhập dấu hai chấm theo sau là khoảng trắng và định nghĩa.  

```
First Term
: This is the definition of the first term.

Second Term
: This is one definition of the second term.
: This is another definition of the second term.
```

HTML trông như thế này:

```html
<dl>
  <dt>First Term</dt>
  <dd>This is the definition of the first term.</dd>
  <dt>Second Term</dt>
  <dd>This is one definition of the second term. </dd>
  <dd>This is another definition of the second term.</dd>
</dl>
```

Kết quả hiển thị trông như thế này:

First Term
: This is the definition of the first term.

Second Term
: This is one definition of the second term.
: This is another definition of the second term.
