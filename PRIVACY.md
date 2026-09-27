# Chính sách quyền riêng tư — Quán Cà Phê Nhỏ

*Cập nhật lần cuối: 27/09/2026*

Chính sách này giải thích game Quán Cà Phê Nhỏ (https://happycoffeeshop.vercel.app) thu thập dữ liệu gì, dùng để làm gì và bạn kiểm soát nó ra sao. Game không có quảng cáo, không dùng công cụ phân tích hay theo dõi hành vi, và không bán dữ liệu của bạn.

## 1. Chơi với tư cách khách

Nếu bạn chơi với tư cách khách, **không có dữ liệu nào của bạn được gửi lên máy chủ của game**. Mọi thứ nằm trong bộ nhớ trình duyệt (localStorage) trên máy bạn:

- Tiến trình chơi và tối đa 3 bản tự lưu dự phòng.
- Tuỳ chọn âm thanh, rung và lựa chọn cách chơi (khách hay Discord).

## 2. Đăng nhập bằng Discord

Khi bạn chọn đăng nhập bằng Discord, game chỉ xin quyền `identify` và nhận được:

| Dữ liệu | Dùng để |
|---|---|
| Mã tài khoản Discord | Gắn tiến trình lưu trên máy chủ với đúng tài khoản của bạn |
| Tên hiển thị | Hiện trong phần Cài đặt để bạn biết đang đăng nhập bằng tài khoản nào |
| Ảnh đại diện | Hiện cạnh tên trong phần Cài đặt |

Game **không** nhận email, số điện thoại, danh sách máy chủ, tin nhắn hay bạn bè của bạn, và không bao giờ đăng gì thay bạn. Mã truy cập Discord chỉ dùng một lần để đọc ba thông tin trên rồi bỏ đi, không được lưu lại.

## 3. Dữ liệu lưu trên máy chủ

Chỉ khi bạn đăng nhập Discord, máy chủ lưu một bản ghi gắn với mã tài khoản Discord của bạn, gồm:

- **Tiến trình chơi:** tên quán bạn tự đặt, chi nhánh, cấp máy pha, nâng cấp, nhiệm vụ, tiền vàng, kim cương và các vật phẩm trong game.
- **Thời điểm lưu gần nhất.**
- **Mã thiết bị ngẫu nhiên:** một chuỗi ngẫu nhiên do game tự tạo trong trình duyệt để nhận ra bản lưu nào do máy nào ghi, tránh hỏi bạn chọn tiến trình mỗi lần vào. Mã này không lấy từ phần cứng và không dùng để nhận dạng bạn.

Bản ghi được giữ cho tới khi bạn yêu cầu xoá (mục 6).

## 4. Cookie và bộ nhớ trình duyệt

| Tên | Loại | Thời hạn | Dùng để |
|---|---|---|---|
| `cs_sess` | Cookie HttpOnly, đã ký | 30 ngày, hoặc tới khi đăng xuất | Giữ trạng thái đăng nhập Discord |
| `cs_state` | Cookie | 10 phút | Chống giả mạo trong lúc đăng nhập Discord |
| `cafe3d_v2`, `cafe3d_v2_bak1..3` | localStorage | Tới khi bạn xoá | Tiến trình chơi và bản dự phòng |
| `cafe3d_opts` | localStorage | Tới khi bạn xoá | Tuỳ chọn âm thanh, rung, cách chơi |
| `cafe3d_dev`, `cafe3d_cloudat` | localStorage | Tới khi đăng xuất | Mã thiết bị và mốc lưu lên mây gần nhất (mục 3) |
| `cafe3d_rescue` | localStorage | Tới khi bạn xoá | Cất riêng bản lưu bị hỏng để không mất hẳn |

Game không dùng cookie quảng cáo hay cookie theo dõi của bên thứ ba.

## 5. Dịch vụ bên thứ ba

Để chạy được, game dùng các dịch vụ sau. Mỗi dịch vụ có thể nhận địa chỉ IP và thông tin trình duyệt của bạn khi trình duyệt kết nối tới họ, theo chính sách riêng của họ:

- **Vercel:** lưu trữ và phục vụ game.
- **Upstash:** lưu tiến trình của người chơi đã đăng nhập Discord.
- **Discord:** đăng nhập và hiện ảnh đại diện (cdn.discordapp.com).
- **Google Fonts:** phông chữ của game.
- **jsDelivr:** thư viện đồ hoạ 3D (Three.js).

## 6. Quyền của bạn

- **Xem và mang đi:** tiến trình của bạn luôn nằm trong trình duyệt; bạn có thể xem nó trong công cụ nhà phát triển của trình duyệt.
- **Ngừng đồng bộ:** đăng xuất Discord trong Cài đặt. Game xoá cookie phiên, mã thiết bị và mốc lưu trên máy này.
- **Xoá trên trình duyệt:** bấm "Chơi lại từ đầu" trong Cài đặt, hoặc xoá dữ liệu trang web của trình duyệt.
- **Xoá trên máy chủ:** mở một issue tại https://github.com/zenkifeed/coffeeshop-legal/issues, ghi mã tài khoản Discord (User ID, bật Chế độ nhà phát triển trong Discord rồi chuột phải vào tên mình → Sao chép ID; mã này vốn ai cũng xem được, không phải mật khẩu). Để chắc chắn bạn là chủ tài khoản, nhà phát triển sẽ trả lời trong issue một mã ngắn; bạn đổi tên quán trong game thành mã đó khi đang đăng nhập Discord, tiến trình tự lưu lên mây, rồi dữ liệu được xoá và issue được đóng.

## 7. Trẻ em

Game phù hợp mọi lứa tuổi và không cố ý thu thập thông tin cá nhân của trẻ em. Đăng nhập Discord tuân theo độ tuổi tối thiểu của Discord tại nơi bạn sống; người chơi nhỏ tuổi hơn có thể chơi với tư cách khách mà không gửi dữ liệu nào lên máy chủ.

## 8. Thay đổi chính sách

Chính sách có thể được cập nhật khi game thay đổi cách xử lý dữ liệu. Ngày cập nhật ở đầu trang cho biết phiên bản mới nhất. Lịch sử thay đổi xem được trong repo này.

## 9. Liên hệ

Câu hỏi về quyền riêng tư: mở issue tại https://github.com/zenkifeed/coffeeshop-legal/issues. Xem thêm [Điều khoản sử dụng](TERMS.md).

---

# Privacy Policy — Quán Cà Phê Nhỏ (English)

*Last updated: September 27, 2026*

This policy explains what data Quán Cà Phê Nhỏ ("Little Coffee Shop", https://happycoffeeshop.vercel.app) collects, why, and how you control it. The game has no ads, no analytics or behavioural tracking, and never sells your data.

1. **Guest play.** As a guest, **nothing about you is sent to the game's server**. Your progress, up to 3 automatic backups and your sound, haptics and sign-in preferences stay in your browser's localStorage.
2. **Discord sign-in.** The game requests only the `identify` scope and receives your **Discord user ID** (to link your saved progress to your account), **display name** and **avatar** (shown in Settings so you know which account is signed in). It does not receive your email, phone number, servers, messages or friends, and never posts on your behalf. The Discord access token is used once to read that information and is not stored.
3. **Server-side data.** Only when you sign in with Discord, the server stores one record keyed by your Discord user ID: your game progress (the shop name you chose, branch, machine levels, upgrades, tasks, in-game coins, gems and items), the time of the last save, and a random device code generated in your browser so the game can tell which device wrote a save. The device code is not derived from your hardware and is not used to identify you. The record is kept until you ask for it to be deleted.
4. **Cookies and browser storage.** `cs_sess` (signed, HttpOnly session cookie, 30 days or until sign-out), `cs_state` (10-minute cookie that protects the Discord sign-in against forgery), and localStorage keys for progress and backups (`cafe3d_v2`, `cafe3d_v2_bak1..3`), preferences (`cafe3d_opts`), sync state (`cafe3d_dev`, `cafe3d_cloudat`, cleared on sign-out) and a corrupted-save rescue copy (`cafe3d_rescue`). No advertising or third-party tracking cookies are used.
5. **Third-party services.** Vercel (hosting), Upstash (storage of signed-in players' progress), Discord (sign-in and avatar images), Google Fonts (fonts) and jsDelivr (the Three.js 3D library). Each may receive your IP address and browser information when your browser connects to it, under its own privacy policy.
6. **Your choices.** Stop syncing by signing out in Settings (this clears the session cookie, device code and sync marker on that device). Clear browser-side data with "Chơi lại từ đầu" (Start over) in Settings or by clearing the site's data. To delete server-side data, open an issue at https://github.com/zenkifeed/coffeeshop-legal/issues with your Discord User ID (enable Developer Mode in Discord, right-click your name → Copy ID; the ID is public, not a password). To confirm you own the account, the developer replies in the issue with a short code; rename your shop in the game to that code while signed in with Discord so it syncs, then the data is deleted and the issue closed.
7. **Children.** The game is suitable for all ages and does not knowingly collect children's personal information. Discord sign-in follows Discord's minimum age in your country; younger players can play as guests without sending any data to the server.
8. **Changes.** This policy may be updated when the game changes how it handles data. The date at the top shows the current version, and the change history is visible in this repository.
9. **Contact.** Privacy questions: https://github.com/zenkifeed/coffeeshop-legal/issues. See also the [Terms of Service](TERMS.md).
