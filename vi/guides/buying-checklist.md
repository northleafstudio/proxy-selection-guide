# Danh sách ngắn trước khi mua gói proxy

Danh sách này do Northleaf Studio xuất bản. Northleaf Studio cũng vận hành [ProxyVendors](https://proxyvendors.com/vi/). Đây là tài liệu bổ trợ của cùng một bên, không phải khuyến nghị của bên thứ ba không liên quan. Hãy đối chiếu với trang giá hiện hành, điều khoản và một thử nghiệm nhỏ. Danh sách không bảo đảm một gói sẽ chạy được với đích của bạn.

## Ngôn ngữ

- [English](../../guides/buying-checklist.md)
- [简体中文](../../zh-cn/guides/buying-checklist.md)
- [Español](../../es/guides/buying-checklist.md)
- [Deutsch](../../de/guides/buying-checklist.md)
- [Français](../../fr/guides/buying-checklist.md)
- [日本語](../../ja/guides/buying-checklist.md)
- [Português](../../pt/guides/buying-checklist.md)
- [한국어](../../ko/guides/buying-checklist.md)
- [اردو](../../ur/guides/buying-checklist.md)
- [Bahasa Indonesia](../../id/guides/buying-checklist.md)
- [Türkçe](../../tr/guides/buying-checklist.md)
- [العربية](../../ar/guides/buying-checklist.md)
- [Polski](../../pl/guides/buying-checklist.md)
- [Italiano](../../it/guides/buying-checklist.md)
- [ไทย](../../th/guides/buying-checklist.md)
- [Українська](../../uk/guides/buying-checklist.md)
- **Tiếng Việt**
- [Русский](../../ru/guides/buying-checklist.md)

## 1. Nêu việc cần làm, rồi chọn mạng

Viết ra lối ra cần làm gì: đăng nhập kéo dài, dữ liệu công khai theo vùng, số lượng yêu cầu lớn, hoặc thử một nhà mạng di động. Khớp việc đó với một loại mạng, như trong [hướng dẫn loại proxy](./proxy-types.md): dân cư, trung tâm dữ liệu, ISP hoặc di động. Nếu trang chủ và trang giá quảng cáo giá khởi điểm hoặc số quốc gia khác nhau, ghi cả hai và hỏi con số nào áp dụng cho đúng bậc bạn sẽ mua.

## 2. Kiểm tra cách phiên hoạt động

Quyết định bạn cần cùng một lối ra trong vài phút, vài giờ hoặc suốt thời hạn thuê, hay một lối ra mới cho mỗi yêu cầu. Xác nhận thời lượng dính hoặc tĩnh, điều gì làm đứt thời lượng đó, và IP rơi có được thay hay không. Tài liệu chính thức đôi khi đưa hai thời gian giữ; hãy coi điểm đó là chưa chốt cho tới khi nhà cung cấp xác nhận.

## 3. Xác nhận giao thức và xác thực

HTTP, gồm [HTTP CONNECT](https://proxyvendors.com/vi/glossary/http-connect) cho trang HTTPS, không giống [SOCKS5](https://proxyvendors.com/vi/glossary/socks5). Một số sản phẩm dân cư chỉ hỗ trợ HTTP và HTTPS. Nếu cần SOCKS5, hoặc UDP qua SOCKS5, hãy kiểm tra cả sản phẩm và máy khách đều hỗ trợ. Xác nhận máy chủ vào, cổng và cách xác thực: tên người dùng và mật khẩu, danh sách IP được phép, hoặc cả hai. Phản hồi 407 trong lúc CONNECT đến từ proxy. Trạng thái này có nghĩa Proxy Authentication Required: proxy đang yêu cầu xác thực, hoặc không chấp nhận xác thực đã nhận. Đường hầm chưa được dựng, và trang đích không thấy yêu cầu.

## 4. Cộng chi phí thật

Nhìn xa hơn đơn giá trên tiêu đề. Ghi lượng mua tối thiểu, thời hạn hoặc ngày hết hạn của gói, phí vượt mức, lượng hao vì thử lại, phụ phí chọn đích chi tiết, thuế, cùng nạp hoặc gia hạn tự động. Giá được nêu nổi bật có thể thuộc bậc khối lượng lớn, không phải gói bạn sẽ bắt đầu. Nếu bản thử yêu cầu thẻ và bật nạp tự động, hãy quyết định có tắt mục đó trước khi bắt đầu hay không.

## 5. Đọc quy tắc dùng thử, hoàn tiền và truy cập

Kiểm tra quy mô và thời gian dùng thử, khoảng hoàn tiền, trần sử dụng, và hoàn tiền có đòi một sự cố mạng đã được ghi nhận hay không. Chú ý kiểm tra danh tính hoặc KYC, các nhóm bị chặn như trang ngân hàng hoặc cơ quan nhà nước, và giới hạn sử dụng hợp lý với sản phẩm tĩnh hoặc dành riêng. Nếu nguồn gốc hoặc tuân thủ quan trọng với bạn, hãy xin tài liệu từ nhà cung cấp thay vì chỉ dựa vào lời quảng cáo.

## 6. Tra mạng, rồi thử

Nếu cần một nhà mạng cụ thể, hãy xác nhận [chọn theo ASN](https://proxyvendors.com/vi/glossary/asn) được hỗ trợ và điều gì xảy ra khi không có lối ra. Sau đó chạy một việc thật và nhỏ: phản hồi hợp lệ từ đích, phiên bị rớt, độ đúng của vị trí và lưu lượng thực sự tiêu thụ. Sau khi kết nối, dùng [kiểm tra IP](https://proxyvendors.com/vi/ip-check) để đối chiếu IP công cộng, tổ chức và ASN với sản phẩm đã mua, rồi chạy kiểm tra DNS và WebRTC nếu các đường đó quan trọng.

Chỉ sau đó hãy quyết định mua bao nhiêu.

— Northleaf Studio
