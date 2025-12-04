# Hướng Dẫn Deploy lên GitHub Pages

## Các bước chuẩn bị

### 1. Kiểm tra cấu hình đã được cập nhật

Các file sau đã được cấu hình cho repository của bạn:

- ✅ `_config.yml` - Đã cập nhật:
  - `title`: "Hướng Dẫn Markdown"
  - `url`: https://trungtin87.github.io
  - `baseurl`: "/markdown-vietnamese"
  - `repo`: https://github.com/trungtin87/markdown-vietnamese
  - `og_locale`: "vi_VN"

- ✅ `.github/workflows/jekyll.yml` - Đã cập nhật:
  - Branch trigger: "main"

### 2. Push code lên GitHub

```bash
# Khởi tạo git (nếu chưa có)
git init

# Thêm tất cả files
git add .

# Commit
git commit -m "Initial commit - Vietnamese Markdown Guide"

# Thêm remote repository
git remote add origin https://github.com/trungtin87/markdown-vietnamese.git

# Push lên main branch
git push -u origin main
```

### 3. Cấu hình GitHub Pages

1. Vào repository trên GitHub: https://github.com/trungtin87/markdown-vietnamese
2. Click vào **Settings** (Cài đặt)
3. Trong menu bên trái, click **Pages**
4. Trong phần **Source**, chọn:
   - Source: **GitHub Actions**
5. Lưu lại

### 4. Kích hoạt GitHub Actions

Sau khi push code lên, GitHub Actions sẽ tự động chạy:

1. Vào tab **Actions** trong repository
2. Bạn sẽ thấy workflow "Deploy Jekyll site to Pages" đang chạy
3. Đợi workflow hoàn thành (thường mất 2-3 phút)

### 5. Truy cập website

Sau khi deployment thành công, website sẽ có tại:

**https://trungtin87.github.io/markdown-vietnamese/**

## Kiểm tra và Debug

### Nếu build thất bại:

1. Vào tab **Actions** để xem log lỗi
2. Kiểm tra các vấn đề thường gặp:
   - Thiếu dependencies trong Gemfile
   - Lỗi cú pháp trong file markdown
   - Lỗi cấu hình trong _config.yml

### Test local trước khi deploy:

```bash
# Cài đặt dependencies
bundle install

# Chạy Jekyll local
bundle exec jekyll serve --baseurl "/markdown-vietnamese"

# Truy cập tại: http://127.0.0.1:4000/markdown-vietnamese/
```

## Cập nhật sau này

Mỗi khi bạn push code mới lên branch `main`, GitHub Actions sẽ tự động build và deploy lại website.

```bash
# Sau khi sửa đổi files
git add .
git commit -m "Mô tả thay đổi"
git push origin main
```

## Lưu ý quan trọng

1. **Baseurl**: Website sẽ chạy tại `/markdown-vietnamese/` chứ không phải root domain
2. **Branch**: Đảm bảo bạn đang push lên branch `main`
3. **Permissions**: Đảm bảo GitHub Actions có quyền deploy (đã được cấu hình trong workflow)
4. **First deployment**: Lần deploy đầu tiên có thể mất 5-10 phút

## Troubleshooting

### Website không hiển thị đúng CSS/JS:
- Kiểm tra `baseurl` trong `_config.yml`
- Đảm bảo các link trong HTML sử dụng `{{ site.baseurl }}`

### 404 Error:
- Kiểm tra repository name khớp với baseurl
- Đảm bảo GitHub Pages đã được enable

### Build fails:
- Kiểm tra Ruby version (workflow dùng 3.1)
- Kiểm tra tất cả plugins trong Gemfile có tương thích

## Liên hệ

Nếu gặp vấn đề, tạo issue tại: https://github.com/trungtin87/markdown-vietnamese/issues
