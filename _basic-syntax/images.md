---
title: Hình ảnh (Images)
syntax-id: images
syntax-summary: "![văn bản thay thế](image.jpg)"
description: "Để thêm hình ảnh, thêm dấu chấm than (`!`), theo sau là văn bản thay thế trong dấu ngoặc vuông, và đường dẫn hoặc URL đến tài sản hình ảnh trong dấu ngoặc đơn. Bạn có thể tùy chọn thêm tiêu đề sau URL trong dấu ngoặc đơn."
examples:
  - markdown: |
      ![Dãy núi San Juan thật đẹp](/assets/images/san-juan-mountains.jpg "Dãy núi San Juan")
    html: <img src=\"/assets/images/san-juan-mountains.jpg\" class=\"img-responsive\" alt=\"Dãy núi San Juan thật đẹp\" title=\"Dãy núi San Juan\">
additional-examples:
  - name: "Liên kết Hình ảnh"
    description: "Để thêm liên kết vào hình ảnh, hãy bao quanh Markdown cho hình ảnh bằng dấu ngoặc vuông, và sau đó thêm liên kết trong dấu ngoặc đơn."
    markdown: |
      [![Một tảng đá cũ trên sa mạc](/assets/images/shiprock.jpg "Shiprock, New Mexico bởi Beau Rogers")](https://www.flickr.com/photos/beaurogers/31833779864/in/photolist-Qv3rFw-34mt9F-a9Cmfy-5Ha3Zi-9msKdv-o3hgjr-hWpUte-4WMsJ1-KUQ8N-deshUb-vssBD-6CQci6-8AFCiD-zsJWT-nNfsgB-dPDwZJ-bn9JGn-5HtSXY-6CUhAL-a4UTXB-ugPum-KUPSo-fBLNm-6CUmpy-4WMsc9-8a7D3T-83KJev-6CQ2bK-nNusHJ-a78rQH-nw3NvT-7aq2qf-8wwBso-3nNceh-ugSKP-4mh4kh-bbeeqH-a7biME-q3PtTf-brFpgb-cg38zw-bXMZc-nJPELD-f58Lmo-bXMYG-bz8AAi-bxNtNT-bXMYi-bXMY6-bXMYv)
    html: <a href=\"https://www.flickr.com/photos/beaurogers/31833779864/in/photolist-Qv3rFw-34mt9F-a9Cmfy-5Ha3Zi-9msKdv-o3hgjr-hWpUte-4WMsJ1-KUQ8N-deshUb-vssBD-6CQci6-8AFCiD-zsJWT-nNfsgB-dPDwZJ-bn9JGn-5HtSXY-6CUhAL-a4UTXB-ugPum-KUPSo-fBLNm-6CUmpy-4WMsc9-8a7D3T-83KJev-6CQ2bK-nNusHJ-a78rQH-nw3NvT-7aq2qf-8wwBso-3nNceh-ugSKP-4mh4kh-bbeeqH-a7biME-q3PtTf-brFpgb-cg38zw-bXMZc-nJPELD-f58Lmo-bXMYG-bz8AAi-bxNtNT-bXMYi-bXMY6-bXMYv\"><img src=\"/assets/images/shiprock.jpg\" alt=\"Một tảng đá cũ trên sa mạc\" title=\"Shiprock, New Mexico bởi Beau Rogers\"></a>
---

Để thêm hình ảnh, thêm dấu chấm than (`!`), theo sau là văn bản thay thế trong dấu ngoặc vuông, và đường dẫn hoặc URL đến tài sản hình ảnh trong dấu ngoặc đơn. Bạn có thể tùy chọn thêm tiêu đề trong dấu ngoặc kép sau đường dẫn hoặc URL.

```
![Dãy núi San Juan thật đẹp](/assets/images/san-juan-mountains.jpg "Dãy núi San Juan")
```

Kết quả hiển thị sẽ trông như thế này:

{% include image.html file="/assets/images/san-juan-mountains.jpg" alt="Dãy núi San Juan thật đẹp" title="Dãy núi San Juan" lazy="yes" %}

<div class="alert alert-info">
  <i class="fas fa-info-circle"></i> <strong>Lưu ý:</strong> Để thay đổi kích thước hình ảnh, xem phần về <a href="/hacks/#image-size">kích thước hình ảnh</a>. Để thêm chú thích, xem phần về <a href="/hacks/#image-captions">chú thích hình ảnh</a>.
</div>

### Liên kết Hình ảnh

Để thêm liên kết vào hình ảnh, hãy bao quanh Markdown cho hình ảnh bằng dấu ngoặc vuông, và sau đó thêm liên kết trong dấu ngoặc đơn.

```
[![Một tảng đá cũ trên sa mạc](/assets/images/shiprock.jpg "Shiprock, New Mexico bởi Beau Rogers")](https://www.flickr.com/photos/beaurogers/31833779864/in/photolist-Qv3rFw-34mt9F-a9Cmfy-5Ha3Zi-9msKdv-o3hgjr-hWpUte-4WMsJ1-KUQ8N-deshUb-vssBD-6CQci6-8AFCiD-zsJWT-nNfsgB-dPDwZJ-bn9JGn-5HtSXY-6CUhAL-a4UTXB-ugPum-KUPSo-fBLNm-6CUmpy-4WMsc9-8a7D3T-83KJev-6CQ2bK-nNusHJ-a78rQH-nw3NvT-7aq2qf-8wwBso-3nNceh-ugSKP-4mh4kh-bbeeqH-a7biME-q3PtTf-brFpgb-cg38zw-bXMZc-nJPELD-f58Lmo-bXMYG-bz8AAi-bxNtNT-bXMYi-bXMY6-bXMYv)
```

Kết quả hiển thị sẽ trông như thế này:

<div>
  <a href="https://www.flickr.com/photos/beaurogers/31833779864/in/photolist-Qv3rFw-34mt9F-a9Cmfy-5Ha3Zi-9msKdv-o3hgjr-hWpUte-4WMsJ1-KUQ8N-deshUb-vssBD-6CQci6-8AFCiD-zsJWT-nNfsgB-dPDwZJ-bn9JGn-5HtSXY-6CUhAL-a4UTXB-ugPum-KUPSo-fBLNm-6CUmpy-4WMsc9-8a7D3T-83KJev-6CQ2bK-nNusHJ-a78rQH-nw3NvT-7aq2qf-8wwBso-3nNceh-ugSKP-4mh4kh-bbeeqH-a7biME-q3PtTf-brFpgb-cg38zw-bXMZc-nJPELD-f58Lmo-bXMYG-bz8AAi-bxNtNT-bXMYi-bXMY6-bXMYv" class="no-underline">
  {% include image.html file="/assets/images/shiprock.jpg" alt="Một tảng đá cũ trên sa mạc" title="Shiprock, New Mexico bởi Beau Rogers" lazy="yes" %}
  </a>
</div>
