# Google Ads Page

Trang web Google Ads với HTML, CSS và JavaScript đã được tách riêng.

## Cấu trúc file

- `google-ads.html` - File HTML chính
- `styles.css` - Tất cả CSS styles
- `script.js` - JavaScript (nếu có)

## Deploy lên GitHub Pages

1. Push code lên GitHub repository
2. Vào Settings → Pages
3. Chọn branch `main` và folder `/ (root)`
4. URL sẽ là: `https://[username].github.io/[repo-name]/google-ads.html`

## Embed vào Google Sites

Sử dụng iframe code:
```html
<iframe 
    src="https://[username].github.io/[repo-name]/google-ads.html" 
    width="100%" 
    height="900px" 
    frameborder="0"
    style="border: none;">
</iframe>
```

## Lưu ý

- File `google-ads.html` có các scripts với nonce attribute
- Các external resources từ Google sẽ được load tự động
- Đảm bảo CSS file (`styles.css`) cùng thư mục với HTML

