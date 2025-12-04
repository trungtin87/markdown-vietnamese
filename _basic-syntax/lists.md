---
title: Danh sách (Lists)
syntax-id: lists
api: "no"
---

Bạn có thể tổ chức các mục thành danh sách có thứ tự và không có thứ tự.

{% include syntax.html type="basic-sub" syntax-id="ordered-lists" %}

{% include syntax.html type="basic-sub" syntax-id="unordered-lists" %}

### Thêm Phần tử vào Danh sách

Để thêm một phần tử khác vào danh sách trong khi vẫn giữ tính liên tục của danh sách, hãy thụt đầu dòng phần tử đó bốn khoảng trắng hoặc một tab, như được hiển thị trong các ví dụ sau.

<div class="alert alert-success">
  <i class="fas fa-lightbulb"></i> <strong>Mẹo:</strong> Nếu mọi thứ không xuất hiện theo cách bạn mong đợi, hãy kiểm tra kỹ xem bạn đã thụt đầu dòng các phần tử trong danh sách bốn khoảng trắng hoặc một tab chưa.
</div>

#### Đoạn văn

```
* Đây là mục danh sách đầu tiên.
* Đây là mục danh sách thứ hai.

    Tôi cần thêm một đoạn văn khác bên dưới mục danh sách thứ hai.

* Và đây là mục danh sách thứ ba.
```

Kết quả hiển thị sẽ trông như thế này:

* Đây là mục danh sách đầu tiên.
* Đây là mục danh sách thứ hai.

    Tôi cần thêm một đoạn văn khác bên dưới mục danh sách thứ hai.

* Và đây là mục danh sách thứ ba.

#### Trích dẫn khối

```
* Đây là mục danh sách đầu tiên.
* Đây là mục danh sách thứ hai.

    > Một trích dẫn khối sẽ trông rất tuyệt bên dưới mục danh sách thứ hai.

* Và đây là mục danh sách thứ ba.
```

Kết quả hiển thị sẽ trông như thế này:

* Đây là mục danh sách đầu tiên.
* Đây là mục danh sách thứ hai.

    > Một trích dẫn khối sẽ trông rất tuyệt bên dưới mục danh sách thứ hai.

* Và đây là mục danh sách thứ ba.

#### Khối mã {#code-blocks-1}

[Khối mã](#code-blocks) thường được thụt đầu dòng bốn khoảng trắng hoặc một tab. Khi chúng ở trong một danh sách, hãy thụt đầu dòng chúng tám khoảng trắng hoặc hai tab.

```text
1. Mở file.
2. Tìm khối mã sau ở dòng 21:

        <html>
          <head>
            <title>Test</title>
          </head>

3. Cập nhật tiêu đề để khớp với tên trang web của bạn.
```

Kết quả hiển thị sẽ trông như thế này:

1. Mở file.
2. Tìm khối mã sau ở dòng 21:

    ```text
    <html>
      <head>
        <title>Test</title>
      </head>
    ```

3. Cập nhật tiêu đề để khớp với tên trang web của bạn.

#### Hình ảnh

```
1. Mở file chứa linh vật Linux.
2. Chiêm ngưỡng vẻ đẹp của nó.

    ![Tux, linh vật Linux](/assets/images/tux.png)

3. Đóng file.
```

Kết quả hiển thị sẽ trông như thế này:

1. Mở file chứa linh vật Linux.
2. Chiêm ngưỡng vẻ đẹp của nó.

    <picture>
      <source srcset="/assets/images/generated/assets/images/tux-480.webp 480w,
                      /assets/images/generated/assets/images/tux-1080.webp 1080w"
              type="image/webp"
              sizes="100vw">
      <img srcset="/assets/images/generated/assets/images/tux-480.png 480w,
                  /assets/images/generated/assets/images/tux.png-1080.png 1080w"
                  src="/assets/images/generated/assets/images/tux-1080.png" width="20%"  alt="Tux, linh vật Linux" loading="lazy" sizes="100vw">
    </picture>

3. Đóng file.

#### Danh sách

Bạn có thể lồng một danh sách không có thứ tự vào một danh sách có thứ tự, hoặc ngược lại.

```
1. Mục đầu tiên
2. Mục thứ hai
3. Mục thứ ba
    - Mục được thụt đầu dòng
    - Mục được thụt đầu dòng
4. Mục thứ tư
```

Kết quả hiển thị sẽ trông như thế này:

1. Mục đầu tiên
2. Mục thứ hai
3. Mục thứ ba
    * Mục được thụt đầu dòng
    * Mục được thụt đầu dòng
4. Mục thứ tư
