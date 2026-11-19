# Loại proxy: mạng, cách gán và giao thức

Hướng dẫn này do Northleaf Studio xuất bản. Northleaf Studio cũng vận hành [ProxyVendors](https://proxyvendors.com/vi/), thư mục để so sánh nhà cung cấp theo việc cần làm, phiên, vị trí và chi phí. Đây là tài liệu nền của cùng một bên, không phải bài đánh giá độc lập về trang đó hoặc về một nhà cung cấp do bên thứ ba không liên quan viết. Nhãn sản phẩm thay đổi, và hai trang chính thức của cùng một nhà cung cấp có thể khác nhau. Hãy dùng bài này như bản đồ thuật ngữ, rồi đối chiếu chi tiết trên tài liệu hiện hành của nhà cung cấp.

## Ngôn ngữ

- [English](../../guides/proxy-types.md)
- [简体中文](../../zh-cn/guides/proxy-types.md)
- [Español](../../es/guides/proxy-types.md)
- [Deutsch](../../de/guides/proxy-types.md)
- [Français](../../fr/guides/proxy-types.md)
- [日本語](../../ja/guides/proxy-types.md)
- [Português](../../pt/guides/proxy-types.md)
- [한국어](../../ko/guides/proxy-types.md)
- [اردو](../../ur/guides/proxy-types.md)
- [Bahasa Indonesia](../../id/guides/proxy-types.md)
- [Türkçe](../../tr/guides/proxy-types.md)
- [العربية](../../ar/guides/proxy-types.md)
- [Polski](../../pl/guides/proxy-types.md)
- [Italiano](../../it/guides/proxy-types.md)
- [ไทย](../../th/guides/proxy-types.md)
- [Українська](../../uk/guides/proxy-types.md)
- **Tiếng Việt**
- [Русский](../../ru/guides/proxy-types.md)

## Ba câu hỏi khác nhau

Người ta thường gộp ba câu hỏi vào một từ, “proxy”:

1. **IP lối ra đến từ loại mạng nào?** Đây là nghĩa thường gặp của dân cư, trung tâm dữ liệu, ISP và di động.
2. **Cùng một lối ra được giữ bao lâu?** Đây là khác biệt giữa tĩnh và xoay, đôi khi gọi là phiên dính.
3. **Máy khách kết nối bằng cách nào?** Đây là HTTP, gồm đường hầm [HTTP CONNECT](https://proxyvendors.com/vi/glossary/http-connect) dùng cho HTTPS, hoặc [SOCKS5](https://proxyvendors.com/vi/glossary/socks5).

Một IP tĩnh vẫn có thể dùng chung với khách hàng khác. Điểm cuối SOCKS5 là cách kết nối, không phải một loại IP. Cùng một lối ra dân cư hoặc trung tâm dữ liệu thường tới được bằng nhiều hơn một giao thức, và một số sản phẩm chỉ hỗ trợ HTTP hoặc HTTPS.

## Loại mạng

**Dân cư.** Lối ra gắn với mạng tiêu dùng hoặc băng rộng. Đây là lựa chọn thường gặp khi đích nhạy với dải địa chỉ máy chủ, hoặc khi cần một vị trí trông như kết nối hộ gia đình thông thường. Lưu lượng dân cư thường tính theo gigabyte. Nhóm địa chỉ được dùng chung và xoay, trừ khi mua lựa chọn dính hoặc dành riêng. Nhãn là cách phân loại của nhà cung cấp hoặc của cơ sở dữ liệu bên thứ ba; đó không phải trường do chính IP mang theo.

**Trung tâm dữ liệu.** Lối ra đến từ mạng lưu trữ hoặc đám mây. Các sản phẩm này thường rẻ hơn theo đơn vị lưu lượng hoặc theo IP, và có thể cho thông lượng cao hơn khi số yêu cầu lớn. Nhiều trang xử lý dải trung tâm dữ liệu nghiêm ngặt hơn. Trước khi mua gói lớn, hãy kiểm tra đích có trả nội dung hợp lệ qua loại lối ra đó hay không.

**ISP, đôi khi được bán như dân cư tĩnh.** Địa chỉ thường được đăng ký dưới tên nhà cung cấp truy cập hộ gia đình, trong khi máy chủ proxy thường đặt ở trung tâm dữ liệu. ISP gọi tên việc đăng ký đó; riêng điều này không có nghĩa lối ra giữ nguyên. Bên bán thường ghép nhãn này với thời gian gán dài hơn, phù hợp cho đăng nhập, danh sách IP được phép và một vị trí cố định. Hãy xác nhận IP dành riêng hay dùng chung, điều gì xảy ra khi mất kết nối hoặc gia hạn, và có kiểm tra danh tính hay không.

**Di động.** Lối ra đến từ mạng nhà mạng di động, thường là 4G hoặc 5G. Nó được dùng cho quảng cáo di động, trang riêng của nhà mạng và nội dung theo vùng khác nhau trên mạng di động. Cách tính phí có thể theo gigabyte, theo ngày hoặc theo cổng. Hãy kiểm tra tồn kho theo nhà mạng và quốc gia, quy tắc xoay và giới hạn dùng, vì kho di động thường mỏng hơn nhóm dân cư.

Không nhãn nào trong số này là điểm chất lượng. Đích có chấp nhận yêu cầu hay không phụ thuộc vào lối ra, cách gửi yêu cầu và chính sách của đích.

## Cách gán: tĩnh, xoay và dính

Xoay thường có nghĩa một lối ra mới được chọn theo từng yêu cầu, hoặc theo khoảng ngắn. Dính hoặc tĩnh thường có nghĩa cùng một lối ra được giữ trong một phiên hoặc suốt thời hạn thuê. Nhà cung cấp không dùng các từ này theo cùng một cách, và trang chính thức đôi khi đưa hai thời lượng phiên. Nếu việc cần cùng một IP, hãy lấy đúng thời gian giữ, điều kiện làm đứt thời gian đó, và IP thay thế có được bảo đảm hay không.

## ASN không phải loại thứ tư

[ASN](https://proxyvendors.com/vi/glossary/asn) xác định nhà khai thác định tuyến đang quảng bá một khối địa chỉ. Nó có thể chính xác hơn quốc gia khi cần mạng của một nhà mạng. Đó không phải quốc gia, và nó không cho biết IP là dân cư hay trung tâm dữ liệu. Yêu cầu một ASN cũng thu hẹp nhóm địa chỉ; nếu không có lối ra, yêu cầu có thể thất bại.

## Sau khi chọn loại, hãy kiểm tra lối ra

Trang gói mô tả sản phẩm định mua. [Kiểm tra IP](https://proxyvendors.com/vi/ip-check) cho thấy IP công cộng, tổ chức và ASN thực sự nhận được, cùng kiểm tra DNS và WebRTC tùy chọn. Nếu kết quả không khớp sản phẩm đã mua, hãy dừng và giải quyết trước khi tăng lượng dùng.

Khi so một gói cụ thể, hãy dùng [danh sách trước khi mua](./buying-checklist.md).

— Northleaf Studio
