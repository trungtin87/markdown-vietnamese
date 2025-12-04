---
title: Slack
category: collaboration
description: "Slack là một ứng dụng nhắn tin và cộng tác nhóm."
icon: slack.png
website: https://slack.com
---

[Slack](https://slack.com) là một ứng dụng nhắn tin và cộng tác nhóm phổ biến hỗ trợ một tập hợp con của cú pháp Markdown. Các phần khác nhau của giao diện cung cấp các mức hỗ trợ Markdown khác nhau.

### Tin nhắn

Giao diện tin nhắn của Slack là giao diện mọi người sử dụng nhiều nhất. Hỗ trợ cho một số [cú pháp cơ bản](/basic-syntax/) được cung cấp, mặc dù hỗ trợ cho nhiều phần tử vắng mặt đáng kể.

Vào tháng 11 năm 2019, Slack đã giới thiệu một giao diện WYSIWYG mới, như được hiển thị bên dưới. Tính năng này được bật cho tất cả người dùng theo mặc định. Thay đổi rõ ràng nhất là việc bổ sung các nút định dạng trong các điều khiển giao diện, nhưng cũng có một trình soạn thảo trực tiếp ẩn định dạng Markdown sau khi bạn nhập. Bạn không cần phải sử dụng các điều khiển giao diện để định dạng văn bản của mình — bạn vẫn có thể sử dụng các phần tử cú pháp Markdown được mô tả trong phần tiếp theo.

{% include image.html file="/assets/images/tools/slack-messages.png" alt="Slack markdown trong giao diện tin nhắn" width="70" %}

Bạn có thể tắt giao diện WYSIWYG trong **Preferences** > **Advanced**. Chọn cài đặt **Format messages with markup**, như được hiển thị bên dưới. Bật cài đặt này sẽ ẩn các nút định dạng WYSIWYG và tắt trình soạn thảo trực tiếp để bạn có thể thấy định dạng Markdown khi bạn nhập.

<div class="alert alert-success">
  <i class="fas fa-lightbulb"></i> <strong>Mẹo:</strong> Nếu bạn mở nhiều không gian làm việc trong Slack, bạn sẽ cần bật cài đặt này cho từng không gian làm việc.
</div>

{% include image.html file="/assets/images/tools/slack-enable-markdown.png" alt="Bật Markdown trong giao diện tin nhắn Slack" width="80" %}

#### Hỗ trợ Markdown của Slack trong Tin nhắn

Giao diện tin nhắn Slack cung cấp hỗ trợ cho các phần tử Markdown sau.

<table class="table table-bordered" style="font-size: 14px">
  <thead class="thead-light">
    <tr>
      <th>Phần tử</th>
      <th>Hỗ trợ</th>
      <th>Ghi chú</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><a href="/basic-syntax/#headings">Tiêu đề</a></td>
      <td class="table-danger">Không</td>
      <td></td>
    </tr>
    <tr>
      <td><a href="/basic-syntax/#paragraphs-1">Đoạn văn</a></td>
      <td class="table-danger">Không</td>
      <td></td>
    </tr>
    <tr>
      <td><a href="/basic-syntax/#line-breaks">Ngắt dòng</a></td>
      <td class="table-danger">Không</td>
      <td>Cú pháp Markdown không được hỗ trợ, nhưng bạn có thể nhấn phím Shift và Return để xuống dòng tiếp theo.</td>
    </tr>
    <tr>
      <td><a href="/basic-syntax/#bold">In đậm</a></td>
      <td class="table-danger">Không</td>
      <td>Cú pháp Markdown không được hỗ trợ, nhưng bạn có thể thêm kiểu in đậm bằng dấu sao đơn, đây là cú pháp Markdown tiêu chuẩn cho in nghiêng. Rất khó hiểu!</td>
    </tr>
    <tr>
      <td><a href="/basic-syntax/#italic">In nghiêng</a></td>
      <td class="table-warning">Một phần</td>
      <td>Chỉ dấu gạch dưới được hỗ trợ.</td>
    </tr>
    <tr>
      <td><a href="/basic-syntax/#blockquotes-1">Trích dẫn khối</a></td>
      <td class="table-success">Có</td>
      <td></td>
    </tr>
    <tr>
      <td><a href="/basic-syntax/#ordered-lists">Danh sách có thứ tự</a></td>
      <td class="table-danger">Một phần</td>
      <td>Cú pháp Markdown tiêu chuẩn *chỉ* được hỗ trợ nếu trình soạn thảo WYSIWIG bị tắt.</td>
    </tr>
    <tr>
      <td><a href="/basic-syntax/#unordered-lists">Danh sách không có thứ tự</a></td>
      <td class="table-danger">Một phần</td>
      <td>Cú pháp Markdown tiêu chuẩn *chỉ* được hỗ trợ nếu trình soạn thảo WYSIWIG bị tắt. Chỉ hỗ trợ dấu gạch ngang và dấu sao cho danh sách không có thứ tự.</td>
    </tr>
    <tr>
      <td><a href="/basic-syntax/#code">Mã</a></td>
      <td class="table-warning">Một phần</td>
      <td><a href="/basic-syntax/#code-blocks">Khối mã</a> không được hỗ trợ.</td>
    </tr>
    <tr>
      <td><a href="/basic-syntax/#horizontal-rules">Quy tắc ngang</a></td>
      <td class="table-danger">Không</td>
      <td></td>
    </tr>
    <tr>
      <td><a href="/basic-syntax/#links">Liên kết</a></td>
      <td class="table-danger">Một phần</td>
      <td>Cú pháp Markdown tiêu chuẩn *chỉ* được hỗ trợ nếu trình soạn thảo WYSIWIG bị tắt.</td>
    </tr>
    <tr>
      <td><a href="/basic-syntax/#images-1">Hình ảnh</a></td>
      <td class="table-danger">Không</td>
      <td>Cú pháp Markdown không được hỗ trợ, nhưng bạn có thể kéo và thả hình ảnh để chia sẻ chúng.</td>
    </tr>
    <tr>
      <td><a href="/extended-syntax/#tables">Bảng</a></td>
      <td class="table-danger">Không</td>
      <td></td>
    </tr>
    <tr>
      <td><a href="/extended-syntax/#fenced-code-blocks">Khối mã có rào chắn</a></td>
      <td class="table-success">Có</td>
      <td></td>
    </tr>
    <tr>
      <td><a href="/extended-syntax/#syntax-highlighting">Tô sáng cú pháp</a></td>
      <td class="table-danger">Không</td>
      <td></td>
    </tr>
    <tr>
      <td><a href="/extended-syntax/#footnotes">Chú thích cuối trang</a></td>
      <td class="table-danger">Không</td>
      <td></td>
    </tr>
    <tr>
      <td><a href="/extended-syntax/#heading-ids">ID tiêu đề</a></td>
      <td class="table-danger">Không</td>
      <td></td>
    </tr>
    <tr>
      <td><a href="/extended-syntax/#definition-lists">Danh sách định nghĩa</a></td>
      <td class="table-danger">Không</td>
      <td></td>
    </tr>
    <tr>
      <td><a href="/extended-syntax/#strikethrough">Gạch ngang</a></td>
      <td class="table-warning">Một phần</td>
      <td>Chỉ sử dụng một ký hiệu dấu ngã trước và sau cụm từ.</td>
    </tr>
    <tr>
      <td><a href="/extended-syntax/#task-lists">Danh sách tác vụ</a></td>
      <td class="table-danger">Không</td>
      <td>Được hiểu là một danh sách không có thứ tự</td>
    </tr>
    <tr>
      <td><a href="/extended-syntax/#copying-and-pasting-emoji">Biểu tượng cảm xúc (sao chép và dán)</a></td>
      <td class="table-success">Có</td>
      <td></td>
    </tr>
    <tr>
      <td><a href="/extended-syntax/#using-emoji-shortcodes">Biểu tượng cảm xúc (mã ngắn)</a></td>
      <td class="table-success">Có</td>
      <td></td>
    </tr>
    <tr>
      <td><a href="/extended-syntax/#highlight">Tô sáng</a></td>
      <td class="table-danger">Không</td>
      <td></td>
    </tr>
    <tr>
      <td><a href="/extended-syntax/#subscript">Chỉ số dưới</a></td>
      <td class="table-danger">Không</td>
      <td></td>
    </tr>
    <tr>
      <td><a href="/extended-syntax/#superscript">Chỉ số trên</a></td>
      <td class="table-danger">Không</td>
      <td></td>
    </tr>
    <tr>
      <td><a href="/extended-syntax/#automatic-url-linking">Liên kết URL tự động</a></td>
      <td class="table-success">Có</td>
      <td></td>
    </tr>
    <tr>
      <td><a href="/extended-syntax/#disabling-automatic-url-linking">Vô hiệu hóa liên kết URL tự động</a></td>
      <td class="table-danger">Có</td>
      <td></td>
    </tr>
    <tr>
      <td><a href="/basic-syntax/#html">HTML</a></td>
      <td class="table-danger">Không</td>
      <td></td>
    </tr>
  </tbody>
</table>

<div class="alert alert-success">
  <i class="fas fa-lightbulb"></i> <strong>Mẹo:</strong> Thông tin này liên quan đến giao diện tin nhắn trong giao diện người dùng của Slack. API Slack cho tin nhắn hỗ trợ các phần tử cú pháp bổ sung không được hỗ trợ trong giao diện người dùng của Slack. Xem <a href="https://api.slack.com/messaging/composing/formatting">tài liệu API của Slack</a> để biết thêm thông tin.
</div>

### Bài đăng

Giao diện bài đăng của Slack là trình soạn thảo cho phép bạn tạo tài liệu để chia sẻ trong Slack. Đây là một trình soạn thảo trực tiếp, có nghĩa là bạn sẽ thấy định dạng thực tế ngay sau khi bạn nhập văn bản được định dạng Markdown. Ví dụ, nếu bạn nhập `_test_`, các dấu gạch dưới sẽ biến mất và bạn sẽ thấy từ "test" được in nghiêng.

Để tạo một bài đăng, hãy nhấp vào biểu tượng phím tắt và chọn **Create a Post** như được hiển thị bên dưới.

<img src="{{ site.baseurl }}/assets/images/tools/slack-posts.png" class="img-fluid" style="width:50%" alt="Slack markdown trong giao diện bài đăng">

#### Hỗ trợ Markdown của Slack trong Bài đăng

Giao diện bài đăng Slack cung cấp hỗ trợ cho các phần tử Markdown sau.

<table class="table table-bordered" style="font-size: 14px">
  <thead class="thead-light">
    <tr>
      <th>Phần tử</th>
      <th>Hỗ trợ</th>
      <th>Ghi chú</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><a href="/basic-syntax/#headings">Tiêu đề</a></td>
      <td class="table-warning">Một phần</td>
      <td>Chỉ các mức tiêu đề một và hai được hỗ trợ. Chỉ hỗ trợ dấu thăng.</td>
    </tr>
    <tr>
      <td><a href="/basic-syntax/#paragraphs-1">Đoạn văn</a></td>
      <td class="table-success">Có</td>
      <td></td>
    </tr>
    <tr>
      <td><a href="/basic-syntax/#line-breaks">Ngắt dòng</a></td>
      <td class="table-danger">Không</td>
      <td></td>
    </tr>
    <tr>
      <td><a href="/basic-syntax/#bold">In đậm</a></td>
      <td class="table-danger">Không</td>
      <td>Cú pháp Markdown không được hỗ trợ, nhưng bạn có thể thêm kiểu in đậm bằng dấu sao đơn, đây là cú pháp Markdown tiêu chuẩn cho in nghiêng. Rất khó hiểu!</td>
    </tr>
    <tr>
      <td><a href="/basic-syntax/#italic">In nghiêng</a></td>
      <td class="table-warning">Một phần</td>
      <td>Chỉ dấu gạch dưới được hỗ trợ.</td>
    </tr>
    <tr>
      <td><a href="/basic-syntax/#blockquotes-1">Trích dẫn khối</a></td>
      <td class="table-success">Có</td>
      <td></td>
    </tr>
    <tr>
      <td><a href="/basic-syntax/#ordered-lists">Danh sách có thứ tự</a></td>
      <td class="table-success">Có</td>
      <td></td>
    </tr>
    <tr>
      <td><a href="/basic-syntax/#unordered-lists">Danh sách không có thứ tự</a></td>
      <td class="table-success">Có</td>
      <td></td>
    </tr>
    <tr>
      <td><a href="/basic-syntax/#code">Mã</a></td>
      <td class="table-success">Có</td>
      <td></td>
    </tr>
    <tr>
      <td><a href="/basic-syntax/#horizontal-rules">Quy tắc ngang</a></td>
      <td class="table-danger">Không</td>
      <td></td>
    </tr>
    <tr>
      <td><a href="/basic-syntax/#links">Liên kết</a></td>
      <td class="table-danger">Không</td>
      <td></td>
    </tr>
    <tr>
      <td><a href="/basic-syntax/#images-1">Hình ảnh</a></td>
      <td class="table-danger">Không</td>
      <td></td>
    </tr>
    <tr>
      <td><a href="/extended-syntax/#tables">Bảng</a></td>
      <td class="table-danger">Không</td>
      <td></td>
    </tr>
    <tr>
      <td><a href="/extended-syntax/#fenced-code-blocks">Khối mã có rào chắn</a></td>
      <td class="table-success">Có</td>
      <td></td>
    </tr>
    <tr>
      <td><a href="/extended-syntax/#syntax-highlighting">Tô sáng cú pháp</a></td>
      <td class="table-danger">Không</td>
      <td></td>
    </tr>
    <tr>
      <td><a href="/extended-syntax/#footnotes">Chú thích cuối trang</a></td>
      <td class="table-danger">Không</td>
      <td></td>
    </tr>
    <tr>
      <td><a href="/extended-syntax/#heading-ids">ID tiêu đề</a></td>
      <td class="table-danger">Không</td>
      <td></td>
    </tr>
    <tr>
      <td><a href="/extended-syntax/#definition-lists">Danh sách định nghĩa</a></td>
      <td class="table-danger">Không</td>
      <td></td>
    </tr>
    <tr>
      <td><a href="/extended-syntax/#strikethrough">Gạch ngang</a></td>
      <td class="table-warning">Một phần</td>
      <td>Chỉ sử dụng một ký hiệu dấu ngã trước và sau cụm từ.</td>
    </tr>
    <tr>
      <td><a href="/extended-syntax/#task-lists">Danh sách tác vụ</a></td>
      <td class="table-danger">Không</td>
      <td></td>
    </tr>
    <tr>
      <td><a href="/extended-syntax/#copying-and-pasting-emoji">Biểu tượng cảm xúc (sao chép và dán)</a></td>
      <td class="table-success">Có</td>
      <td></td>
    </tr>
    <tr>
      <td><a href="/extended-syntax/#using-emoji-shortcodes">Biểu tượng cảm xúc (mã ngắn)</a></td>
      <td class="table-success">Có</td>
      <td></td>
    </tr>
    <tr>
      <td><a href="/extended-syntax/#highlight">Tô sáng</a></td>
      <td class="table-danger">Không</td>
      <td></td>
    </tr>
    <tr>
      <td><a href="/extended-syntax/#subscript">Chỉ số dưới</a></td>
      <td class="table-danger">Không</td>
      <td></td>
    </tr>
    <tr>
      <td><a href="/extended-syntax/#superscript">Chỉ số trên</a></td>
      <td class="table-danger">Không</td>
      <td></td>
    </tr>
    <tr>
      <td><a href="/extended-syntax/#automatic-url-linking">Liên kết URL tự động</a></td>
      <td class="table-success">Có</td>
      <td></td>
    </tr>
    <tr>
      <td><a href="/extended-syntax/#disabling-automatic-url-linking">Vô hiệu hóa liên kết URL tự động</a></td>
      <td class="table-success">Có</td>
      <td></td>
    </tr>
    <tr>
      <td><a href="/basic-syntax/#html">HTML</a></td>
      <td class="table-danger">Không</td>
      <td></td>
    </tr>
  </tbody>
</table>

### Xem thêm

- [Định dạng tin nhắn Slack trong giao diện](https://get.slack.help/hc/en-us/articles/202288908-Format-your-messages)
- [Định dạng bài đăng Slack trong giao diện](https://get.slack.help/hc/en-us/articles/203950418-Composing-a-Post#-formatting-options)
- [Tài liệu API để định dạng tin nhắn Slack](https://api.slack.com/messaging/composing/formatting)
- [slack_markdown ruby gem](https://github.com/rutan/slack_markdown)
