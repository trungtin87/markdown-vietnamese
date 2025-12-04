---
layout: default
title: Hacks
description: Workarounds for things not officially supported by Markdown.
last_modified_at: 2022-04-15
---

## Tổng Quan

Phần lớn những người sử dụng Markdown sẽ thấy rằng các thành phần [cú pháp cơ bản](/basic-syntax/) và [cú pháp mở rộng](/extended-syntax/) đáp ứng nhu cầu của họ. Nhưng rất có thể nếu bạn sử dụng Markdown đủ lâu, bạn sẽ không thể tránh khỏi việc phát hiện ra rằng nó không hỗ trợ thứ gì đó bạn cần. Trang này cung cấp các mẹo và thủ thuật để giải quyết các hạn chế của Markdown.

<div class="alert alert-success">
  <i class="fas fa-lightbulb"></i> <strong>Mẹo:</strong> Các thủ thuật này không được đảm bảo hoạt động trong ứng dụng Markdown của bạn. Nếu bạn cần sử dụng các thủ thuật này thường xuyên, bạn nên cân nhắc viết bằng thứ gì đó khác ngoài Markdown.
</div>

## Gạch Chân

Văn bản gạch chân không phải là thứ bạn thường thấy trong viết web, có lẽ vì văn bản gạch chân gần như đồng nghĩa với liên kết. Tuy nhiên, nếu bạn đang viết một bài báo hoặc báo cáo, bạn có thể cần khả năng gạch chân các từ và cụm từ. Một số ứng dụng như [Bear](/tools/bear/) và [Simplenote](/tools/simplenote/) cung cấp hỗ trợ gạch chân văn bản, nhưng Markdown không hỗ trợ gạch chân nguyên bản. Nếu bộ xử lý Markdown của bạn hỗ trợ [HTML](/basic-syntax/#html), bạn có thể sử dụng thẻ HTML `<ins>` để gạch chân văn bản trong tài liệu của mình.

```html
Some of these words <ins>will be underlined</ins>.
```

Kết quả hiển thị trông như thế này:

Some of these words <ins>will be underlined</ins>.

## Thụt Lề (Tab)

Tab và khoảng trắng có ý nghĩa đặc biệt trong Markdown. Bạn có thể sử dụng khoảng trắng ở cuối để tạo [ngắt dòng](/basic-syntax/#line-breaks), và bạn có thể sử dụng tab để tạo [khối mã](/basic-syntax/#code-blocks). Nhưng nếu bạn cần thụt lề một đoạn văn theo cách truyền thống, sử dụng phím tab thì sao? Markdown không cung cấp cách dễ dàng để làm điều đó.

Lựa chọn tốt nhất của bạn có thể là sử dụng trình soạn thảo Markdown hỗ trợ thụt lề. Điều này phổ biến trong các ứng dụng hướng nhiều hơn đến xuất bản máy tính để bàn. Ví dụ: [iA Writer](/tools/ia-writer/) cho phép bạn tùy chỉnh cài đặt thụt lề cho trình soạn thảo trong tùy chọn ứng dụng. Nó cũng cung cấp các tùy chọn tùy chỉnh mẫu để bạn có thể làm cho tài liệu được hiển thị trông như bạn mong đợi, bao gồm cả thụt lề.

Một tùy chọn khác, nếu bộ xử lý Markdown của bạn hỗ trợ [HTML](/basic-syntax/#html), là sử dụng thực thể HTML cho khoảng trắng không ngắt (`&nbsp;`). Đây có lẽ nên là lựa chọn cuối cùng của bạn vì nó có thể trở nên khó xử. Về cơ bản, mỗi `&nbsp;` trong nguồn Markdown của bạn sẽ được thay thế bằng một khoảng trắng trong đầu ra được hiển thị. Vì vậy, nếu bạn đặt bốn phiên bản `&nbsp;` trước một đoạn văn, đoạn văn sẽ trông như thể nó được thụt lề bốn khoảng trắng.

```html
&nbsp;&nbsp;&nbsp;&nbsp;This is the first sentence of my indented paragraph.
```

Kết quả hiển thị trông như thế này:

&nbsp;&nbsp;&nbsp;&nbsp;This is the first sentence of my indented paragraph.

## Căn Giữa

Khả năng căn giữa văn bản là điều cần thiết khi viết một bài báo hoặc báo cáo. Thật không may, Markdown không có bất kỳ khái niệm nào về căn chỉnh văn bản (một ngoại lệ có thể có là khi sử dụng [bảng](/extended-syntax/#alignment)). Tin tốt là có một thẻ HTML bạn có thể sử dụng: `<center>`. Nếu bộ xử lý Markdown của bạn hỗ trợ [HTML](/basic-syntax/#html), bạn có thể đặt các thẻ này xung quanh bất kỳ văn bản nào bạn muốn căn giữa.

```html
<center>This text is centered.</center>
```

Kết quả hiển thị trông như thế này:

<p style="text-align:center">This text is centered.</p>

Thẻ HTML `<center>` về mặt kỹ thuật được hỗ trợ nhưng chính thức <a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/center">không được khuyến khích</a>, có nghĩa là nó hoạt động hiện tại nhưng bạn không nên sử dụng nó. Thật không may, không có một giải pháp HTML thuần túy khác. Bạn có thể thử sử dụng một trong các giải pháp CSS. Không phải tất cả các ứng dụng Markdown đều cung cấp hỗ trợ CSS, nhưng nếu ứng dụng bạn đang sử dụng có, đây là một giải pháp thay thế cho thẻ `<center>`:

```html
<p style="text-align:center">Center this text</p>
```

Nếu điều này được ứng dụng Markdown của bạn hỗ trợ, đầu ra trông như thế này:

<p style="text-align:center">Center this text</p>

## Màu Sắc

Markdown không cho phép bạn thay đổi màu của văn bản, nhưng nếu bộ xử lý Markdown của bạn hỗ trợ [HTML](/basic-syntax/#html), bạn có thể sử dụng thẻ HTML `<font>`. Thuộc tính `color` cho phép bạn chỉ định màu phông chữ bằng tên màu hoặc mã thập lục phân `#RRGGBB`.

```html
<font color="red">This text is red!</font>
```

Kết quả hiển thị trông như thế này:

<p style="color:red">This text is red!</p>

Thẻ HTML `<font>` về mặt kỹ thuật được hỗ trợ nhưng chính thức <a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/font">không được khuyến khích</a>, có nghĩa là nó hoạt động hiện tại nhưng bạn không nên sử dụng nó. Thật không may, không có một giải pháp HTML thuần túy khác. Bạn có thể thử sử dụng một trong các giải pháp CSS. Không phải tất cả các ứng dụng Markdown đều cung cấp hỗ trợ CSS, nhưng nếu ứng dụng bạn đang sử dụng có, đây là một giải pháp thay thế cho thẻ `<font>`:

```html
<p style="color:blue">Make this text blue.</p>
```

Nếu điều này được ứng dụng Markdown của bạn hỗ trợ, đầu ra trông như thế này:

<p style="color:blue">Make this text blue.</p>

## Chú Thích

Một số người cần khả năng viết các câu trong tệp Markdown của họ mà *sẽ không* xuất hiện trong đầu ra được hiển thị. Các chú thích này về cơ bản là văn bản ẩn. Văn bản có thể xem được bởi tác giả của tài liệu, nhưng nó không được in trên trang web hoặc PDF. Markdown không hỗ trợ chú thích nguyên bản, nhưng một số cá nhân sáng tạo đã nghĩ ra giải pháp.

Để thêm chú thích, hãy đặt văn bản bên trong dấu ngoặc vuông theo sau là dấu hai chấm, một khoảng trắng và dấu thăng (ví dụ: `[comment]: #`). Bạn nên đặt các dòng trống trước và sau chú thích.

```text
Here's a paragraph that will be visible.

[This is a comment that will be hidden.]: # 

And here's another paragraph that's visible.
```

Kết quả hiển thị trông như thế này:

Here's a paragraph that will be visible.


And here's another paragraph that's visible.

<div class="alert alert-success">
  <i class="fas fa-lightbulb"></i> <strong>Mẹo:</strong> Mẹo này đến từ <a href="https://stackoverflow.com/questions/4823468/comments-in-markdown" rel="nofollow">Stack Overflow</a>. Nó đã được đánh giá ngang hàng và sử dụng bởi hàng nghìn người!
</div>

## Cảnh Báo

Cảnh báo thường được sử dụng trong tài liệu để thu hút sự chú ý đến cảnh báo, ghi chú và mẹo. Markdown không cung cấp cú pháp đặc biệt cho cảnh báo, và hầu hết các ứng dụng Markdown không cung cấp hỗ trợ cho cảnh báo (một ngoại lệ là [MkDocs](/tools/mkdocs/)).

Tuy nhiên, nếu bạn cần thêm cảnh báo, bạn có thể sử dụng [trích dẫn khối](/basic-syntax/#blockquotes-1) với [emoji](/extended-syntax/#emoji) và [nhấn mạnh](/basic-syntax/#emphasis) để tạo thứ gì đó trông tương tự như cảnh báo bạn thấy trên các trang web khác.

```text
> :warning: **Warning:** Do not push the big red button.

> :memo: **Note:** Sunrises are beautiful.

> :bulb: **Tip:** Remember to appreciate the little things in life.
```

Kết quả hiển thị trông như thế này:

> ⚠️ **Warning:** Do not push the big red button.

> 📝 **Note:** Sunrises are beautiful.

> 💡 **Tip:** Remember to appreciate the little things in life.

## Kích Thước Hình Ảnh

Cú pháp Markdown cho [hình ảnh](/basic-syntax/#images-1) không cho phép bạn chỉ định chiều rộng và chiều cao của hình ảnh. Nếu bạn cần thay đổi kích thước hình ảnh và bộ xử lý Markdown của bạn hỗ trợ [HTML](/basic-syntax/#html), bạn có thể sử dụng thẻ HTML `img` với các thuộc tính `width` và `height` để đặt kích thước của hình ảnh theo pixel.

```html
<img src="image.png" width="200" height="100">
```

Đầu ra được hiển thị sẽ chứa hình ảnh được thay đổi kích thước theo kích thước bạn chỉ định.

## Chú Thích Hình Ảnh

Markdown không hỗ trợ chú thích hình ảnh nguyên bản, nhưng có hai giải pháp thay thế có thể có. Nếu ứng dụng Markdown của bạn hỗ trợ [HTML](/basic-syntax/#html), bạn có thể sử dụng các thẻ HTML `figure` và `figcaption` để thêm chú thích cho hình ảnh của bạn.

```html
<figure>
    <img src="{{ site.baseurl }}/assets/images/albuquerque.jpg"
         alt="Albuquerque, New Mexico">
    <figcaption>A single track trail outside of Albuquerque, New Mexico.</figcaption>
</figure>
```

Kết quả hiển thị trông như thế này:

<figure>
    {% include image.html file="/assets/images/albuquerque.jpg" alt="Albuquerque, New Mexico" lazy="yes" %}
    <figcaption>A single track trail outside of Albuquerque, New Mexico.</figcaption>
</figure>

<div class="alert alert-success">
  <i class="fas fa-lightbulb"></i> <strong>Mẹo:</strong> Nếu ứng dụng Markdown của bạn hỗ trợ CSS, bạn có thể sử dụng CSS để tạo kiểu cho giao diện của chú thích.
</div>

Nếu ứng dụng Markdown của bạn không hỗ trợ HTML, bạn có thể thử đặt chú thích ngay bên dưới hình ảnh và sử dụng [nhấn mạnh](/basic-syntax/#emphasis).

```text
![Albuquerque, New Mexico](/assets/images/albuquerque.jpg)
*A single track trail outside of Albuquerque, New Mexico.*
```

Kết quả hiển thị trông như thế này:

{% include image.html file="/assets/images/albuquerque.jpg" alt="Albuquerque, New Mexico" lazy="yes" %}
*A single track trail outside of Albuquerque, New Mexico.*

## Mục Tiêu Liên Kết

Một số người thích tạo liên kết mở trong tab hoặc cửa sổ mới. Cú pháp Markdown cho [liên kết](/basic-syntax/#links) không cho phép bạn chỉ định thuộc tính `target`, nhưng nếu bộ xử lý Markdown của bạn hỗ trợ [HTML](/basic-syntax/#html), bạn có thể sử dụng HTML để tạo các liên kết này.

```html
<a href="https://www.markdownguide.org" target="_blank">Learn Markdown!</a>

Bạn có thể phân tách các đoạn văn trong một ô bảng bằng cách sử dụng một hoặc nhiều thẻ HTML `<br>`.

```

| Syntax      | Description |
| ----------- | ----------- |
| Header      | Title |
| Paragraph   | First paragraph. <br><br> Second paragraph. |

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
      <td>First paragraph. <br><br> Second paragraph.</td>
    </tr>
  </tbody>
</table>

### Danh Sách Trong Ô Bảng

Bạn có thể thêm danh sách trong một ô bảng bằng cách sử dụng thẻ HTML.

```

| Syntax      | Description |
| ----------- | ----------- |
| Header      | Title |
| List        | Here's a list! <ul><li>Item one.</li><li>Item two.</li></ul> |

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
      <td>List</td>
      <td>Here's a list! <ul><li>Item one.</li><li>Item two.</li></ul></td>
    </tr>
  </tbody>
</table>

## Mục Lục

Một số ứng dụng Markdown như [Markdeep](/tools/markdeep/) có thể tự động tạo mục lục (còn được gọi là *toc*) từ [tiêu đề](/basic-syntax/#headings) của bạn, nhưng đây không phải là tính năng được cung cấp bởi tất cả các ứng dụng Markdown. Tuy nhiên, nếu ứng dụng Markdown của bạn hỗ trợ [ID tiêu đề](/extended-syntax/#heading-ids), bạn có thể tạo mục lục cho tệp Markdown của mình bằng cách sử dụng [danh sách](/basic-syntax/#lists-1) và một số [liên kết](/basic-syntax/#links).

```html
#### Table of Contents

- [Underline](#underline)
- [Indent](#indent)
- [Center](#center)
- [Color](#color)
```

Kết quả hiển thị trông như thế này:

<h4 class="no-anchor" data-toc-skip>Table of Contents</h4>

- [Underline](#underline)
- [Indent](#indent)
- [Center](#center)
- [Color](#color)

## Video

Nếu ứng dụng Markdown của bạn hỗ trợ [HTML](/basic-syntax/#html), bạn có thể nhúng video vào tệp Markdown của mình bằng cách sao chép và dán mã HTML được cung cấp bởi trang web video như YouTube hoặc Vimeo. Nếu ứng dụng Markdown của bạn không hỗ trợ HTML, bạn không thể nhúng video, nhưng bạn có thể gần như vậy bằng cách thêm [hình ảnh](/basic-syntax/#images-1) và liên kết đến video. Bạn có thể làm điều này với hầu như bất kỳ video nào trên bất kỳ dịch vụ video nào.

Vì YouTube làm cho điều này dễ dàng, chúng tôi sẽ sử dụng họ làm ví dụ. Lấy video này làm ví dụ: `https://www.youtube.com/watch?v=8q2IjQOzVpE`. Phần cuối cùng của URL (`8q2IjQOzVpE`) là ID của video. Chúng ta có thể lấy ID đó và đặt nó vào mẫu sau:

```test
[![Image alt text](https://img.youtube.com/vi/YOUTUBE-ID/0.jpg)](https://www.youtube.com/watch?v=YOUTUBE-ID)
```

YouTube tự động tạo hình ảnh cho mọi video (`https://img.youtube.com/vi/YOUTUBE-ID/0.jpg`), vì vậy chúng ta có thể sử dụng nó và [liên kết hình ảnh](/basic-syntax/#linking-images) đến video trên YouTube. Sau khi chúng ta thay thế văn bản thay thế hình ảnh và thêm ID của video, ví dụ của chúng ta trông như thế này:

```test
[![Less Than Jake — Scott Farcas Takes It On The Chin](https://img.youtube.com/vi/PYCxct2e0zI/0.jpg)](https://www.youtube.com/watch?v=PYCxct2e0zI)
```

Kết quả hiển thị trông như thế này:

<a href="https://www.youtube.com/watch?v=PYCxct2e0zI" rel="nofollow"><img src="https://img.youtube.com/vi/PYCxct2e0zI/0.jpg" width="480" height="360" alt="Less Than Jake — Scott Farcas Takes It On The Chin"></a>
