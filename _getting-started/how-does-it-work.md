## Nó hoạt động như thế nào?

Dillinger giúp việc viết bằng Markdown trở nên dễ dàng vì nó ẩn đi những thứ đang diễn ra ở hậu trường, nhưng cũng đáng để tìm hiểu xem quy trình này hoạt động như thế nào nói chung.

Khi bạn viết bằng Markdown, văn bản được lưu trữ trong một file văn bản thuần túy có phần mở rộng `.md` hoặc `.markdown`. Nhưng sau đó thì sao? Làm thế nào để file được định dạng Markdown của bạn được chuyển đổi thành HTML hoặc một tài liệu sẵn sàng để in?

Câu trả lời ngắn gọn là bạn cần một *ứng dụng Markdown* có khả năng xử lý file Markdown. Có rất nhiều ứng dụng có sẵn — mọi thứ từ các tập lệnh đơn giản đến các ứng dụng máy tính để bàn trông giống như Microsoft Word. Mặc dù có sự khác biệt về hình ảnh, tất cả các ứng dụng đều làm điều tương tự. Giống như Dillinger, tất cả chúng đều chuyển đổi văn bản được định dạng Markdown sang HTML để nó có thể được hiển thị trong các trình duyệt web.

Các ứng dụng Markdown sử dụng một thứ gọi là *bộ xử lý Markdown* (cũng thường được gọi là "trình phân tích cú pháp" hoặc "triển khai") để lấy văn bản được định dạng Markdown và xuất nó sang định dạng HTML. Tại thời điểm đó, tài liệu của bạn có thể được xem trong trình duyệt web hoặc kết hợp với một bảng định kiểu và in ra. Bạn có thể thấy một hình ảnh đại diện cho quy trình này bên dưới.

<div class="alert alert-info">
  <i class="fas fa-info-circle"></i> <strong>Lưu ý:</strong> Ứng dụng Markdown và bộ xử lý là hai thành phần riêng biệt. Để ngắn gọn, tôi đã kết hợp chúng thành một phần tử ("Ứng dụng Markdown") trong hình bên dưới.
</div>

{% include image.html file="{{ site.baseurl }}/assets/images/markdown-flowchart.png" alt="Quy trình Markdown" lazy="yes" %}

Tóm lại, đây là một quy trình gồm bốn phần:

1. Tạo một file Markdown bằng trình soạn thảo văn bản hoặc một ứng dụng Markdown chuyên dụng. File nên có phần mở rộng `.md` hoặc `.markdown`.
2. Mở file Markdown trong một ứng dụng Markdown.
3. Sử dụng ứng dụng Markdown để chuyển đổi file Markdown thành tài liệu HTML.
4. Xem file HTML trong trình duyệt web hoặc sử dụng ứng dụng Markdown để chuyển đổi nó sang định dạng file khác, như PDF.

Từ góc độ của bạn, quy trình sẽ thay đổi đôi chút tùy thuộc vào ứng dụng bạn sử dụng. Ví dụ, Dillinger về cơ bản kết hợp các bước 1-3 thành một giao diện liền mạch duy nhất — tất cả những gì bạn phải làm là gõ vào khung bên trái và kết quả hiển thị sẽ xuất hiện một cách kỳ diệu trong khung bên phải. Nhưng nếu bạn sử dụng các công cụ khác, như trình soạn thảo văn bản với trình tạo trang web tĩnh, bạn sẽ thấy rằng quy trình này rõ ràng hơn nhiều.
