---
title: Supernotes
category: "notes"
description: "Supernotes là một ứng dụng ghi chú đa nền tảng nhanh chóng sử dụng thẻ ghi chú Markdown."
icon: supernotes.png
website: https://supernotes.app
syntax:
  - id: headings
    available: y
  - id: paragraphs
    available: y
  - id: line-breaks
    available: y
  - id: bold
    available: y
  - id: italic
    available: y
  - id: blockquotes
    available: y
  - id: ordered-lists
    available: y
  - id: unordered-lists
    available: y
  - id: code
    available: y
  - id: horizontal-rules
    available: y
  - id: links
    available: y
  - id: images
    available: y
  - id: tables
    available: y
  - id: fenced-code-blocks
    available: y
  - id: syntax-highlighting
    available: y
  - id: footnotes
    available: y
  - id: heading-ids
    available: n
  - id: definition-lists
    available: n
  - id: strikethrough
    available: y
  - id: task-lists
    available: y
  - id: emoji-cp
    available: y
  - id: emoji-sc
    available: y
  - id: highlight
    available: y
  - id: subscript
    available: y
  - id: superscript
    available: y
  - id: auto-url-linking
    available: y
  - id: disabling-auto-url
    available: y
  - id: html
    available: p
    notes: "Một số thẻ, chẳng hạn như `<script>`, không được hỗ trợ."
    
see-also:
  - name: Tài liệu Supernotes
    link: https://docs.supernotes.app/
---

[Supernotes](https://supernotes.app) là một ứng dụng ghi chú nhanh có sẵn trên Mac, Windows, Linux, Android, iOS và web. Ứng dụng khuyến khích bạn chia nhỏ thông tin của mình thành các thẻ ghi chú dạng ngắn. Điều này giúp bạn kết nối kiến thức của mình với nhau theo cách linh hoạt hơn – mỗi thẻ ghi chú đều có thể gắn thẻ, lồng nhau, liên kết và chia sẻ. Bạn có thể xem các thẻ của mình theo một số cách khác nhau: dưới dạng Danh sách, dưới dạng lưới trong chế độ xem Broadsheet hoặc dưới dạng các nút trong chế độ xem Đồ thị.

Cùng với hỗ trợ Markdown mở rộng, Supernotes hỗ trợ các phương trình LaTeX và [các tính năng chỉnh sửa nâng cao](https://docs.supernotes.app/en/articles/6048775-advanced-editing-techniques) chẳng hạn như hỗ trợ nhiều con trỏ và một loạt các phím tắt tiện dụng. Supernotes là một ứng dụng ưu tiên web, chú trọng vào việc đồng bộ hóa nhanh giữa các thiết bị và chia sẻ dễ dàng giữa những người dùng. Trên Supernotes, dữ liệu của bạn luôn được mã hóa khi truyền (bắt buộc TLS) và được mã hóa khi nghỉ (AES-256).

Một trong những lợi ích lớn nhất của Supernotes là cộng đồng. Những người đồng sáng lập rất tích cực trên [Diễn đàn cộng đồng](https://community.supernotes.app), nơi người dùng đề xuất các ý tưởng tính năng mới, báo cáo lỗi và chia sẻ quy trình làm việc. Những người đồng sáng lập cũng tổ chức [các phiên giới thiệu miễn phí](https://supernotes.app/welcome) để giúp người dùng mới bắt đầu với Supernotes.

[Tất cả các tính năng của Supernotes](https://supernotes.app/features/) đều được bao gồm trong gói Starter miễn phí. Trên gói Starter, bạn bắt đầu với 40 thẻ, nhưng bạn có thể giới thiệu bạn bè hoặc nâng cấp lên gói Unlimited để có nhiều tính năng hơn. Supernotes là một công ty khởi nghiệp độc lập nhỏ, được xây dựng bởi một nhóm hai người và việc đăng ký sẽ hỗ trợ họ và sự phát triển của nền tảng.

{% include image.html file="{{ site.baseurl }}/assets/images/tools/supernotes.png" alt="Ứng dụng Markdown Supernotes" width="90" %}

{% include tool-syntax-table.html %}

### Hỗ trợ cho các Phần tử Cú pháp Bổ sung

Như một phần thưởng thêm, Supernotes cung cấp hỗ trợ cho một số phần tử ít người biết đến.

<table class="table table-bordered" style="font-size: 14px">
  <thead class="thead-light">
    <tr>
      <th>Phần tử</th>
      <th>Markdown</th>
      <th>Kết quả hiển thị</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Spoilers</td>
      <td><code>!!Văn bản này bị mờ khi hiển thị!!</code></td>
      <td><span class="spoiler" style="filter: blur(4px);">Văn bản này bị mờ khi hiển thị</span></td>
    </tr>
     <tr>
      <td>Video có thể nhúng</td>
      <td><code>@[youtube](F7puJIw0k-w)</code><br/><code>@[vimeo](106365480)</code></td>
      <td>Video Youtube được nhúng trong iframe.<br/>Video Vimeo được nhúng trong iframe.</td>
    </tr>
  </tbody>
</table>
