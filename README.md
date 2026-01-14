# AIxC_Hub_AutoDaily

# 🤖 AIxCrypto Automated Bot V11 - Full Guide

Mô tả: Công cụ tự động hóa hoàn toàn dự án AIxCrypto với công nghệ bảo mật Session, đa luồng và hệ thống License HWID.

---

## 🛠 1. YÊU CẦU HỆ THỐNG

Gruop Aidrop Free : https://t.me/HVchannelss

Tham Gia Discor ( Vip ) : https://discord.gg/gKxvTNu5

Tham gia NHóm VIp Với Chi Phí 8u/1thang Lợi ích tham gia nhóm ViP Sẽ được cấp keey sử dụng các tool vip trong discor hỗ trợ Và tham khao Code các tool dự án mà các bạn đề xuất

Gửi Phí tháng vào đây và chụp hình gửi trực tiếp cho tôi tại discor để xác nhận Role VIp ☕ https://huynhviet933.github.io/donate_viet_mmo/ Có thể tặng tôi ít cafe tại đây

<img width="1920" height="1080" alt="Screenshot (31)" src="https://github.com/user-attachments/assets/53267bdb-95a2-434a-a817-9d49a15a30fc" />

- Đã cài đặt **Node.js** (Phiên bản mới nhất hoặc v16 trở lên).
- Máy tính hoặc VPS có kết nối Internet ổn định.
- Tài khoản **2Captcha** (để vượt mã bảo vệ Cloudflare).

---

## 📥 2. CÀI ĐẶT THƯ VIỆN (DEPENDENCIES)
Mở Terminal/CMD tại thư mục chứa Tool và copy-paste lệnh sau để cài đặt toàn bộ thư viện cần thiết:

npm install ethers axios https-proxy-agent readline-sync chalk@4 ora@5 os crypto

---

## ⚙️ 3. CẤU HÌNH CÁC FILE DỮ LIỆU (.txt)
Bạn cần tạo các file sau trong cùng thư mục với file `Main.js`:

1.  **pk.txt (hoặc keys.txt):** Chứa danh sách Private Key của các ví.
    *   *Định dạng:* Mỗi dòng 1 Private Key.
2.  **proxy.txt:** Chứa danh sách Proxy để đổi IP cho từng ví.
    *   *Định dạng:* `http://user:pass@ip:port`
3.  **user_agents.txt:** Chứa danh sách User-Agent trình duyệt.
    *   *Lưu ý:* Càng nhiều càng tốt để tránh bị sàn quét dấu vân tay trình duyệt.
    *   * Dùng Tool https://github.com/huynhviet933/Reg_User_Agents
4.  **ref.txt:** Chứa danh sách mã mời (Invite Code) của bạn.
    *   *Lưu ý:* Tool sẽ tự động xoay vòng mã mời để Join Team cho các tài khoản clone.
5.  **2captcha.txt:** Chứa duy nhất 1 dòng là **API Key** của tài khoản 2Captcha của bạn.

---

## 🚀 4. HƯỚNG DẪN CHẠY TOOL

1. Mở Terminal/CMD và gõ lệnh:
   node bot.js

2. Nhập **License Key** (Nếu chạy lần đầu). Key sẽ được gắn với HWID máy của bạn.
3. Nhập **Thread Count** (Số luồng): Ví dụ nhập `5` để chạy 5 ví cùng lúc.

---

## 💡 5. CƠ CHẾ HOẠT ĐỘNG CỦA BOT V11

- **Tự động lưu Session:** Sau khi giải Captcha và Login thành công, Token sẽ được lưu vào `profiles.json`. Trong vòng 24h tiếp theo, Tool sẽ dùng lại Token này mà KHÔNG cần giải lại Captcha (Tiết kiệm 100% chi phí 2Captcha cho bạn).
- **Auto Battery & Betting:** Bot tự động kiểm tra năng lượng. Nếu hết, nó tự tìm Task để hồi Pin. Nó sẽ đánh đúng tiến trình Server (ví dụ 50/100) cho đến khi hoàn thành 100 ván/ngày.
- **Stealth Logging (Ẩn lỗi rác):** Các lỗi do Proxy yếu hoặc Server quá tải (429) sẽ được Bot tự động xử lý ngầm và ẩn đi, giúp màn hình Log cực kỳ sạch đẹp.
- **Color Coding (Hệ thống màu):**
    *   [Xanh lá]: Login thành công / Thắng cược (WIN).
    *   [Đỏ]: Thua cược (LOSE) / Lỗi nghiêm trọng.
    *   [Tím]: Tổng số điểm (PTS) thực tế của ví.
    *   [Vàng]: Thông tin IP, Mã mời, và thời gian chờ.

---

## ⚠️ 6. LƯU Ý QUAN TRỌNG
- **Tiết kiệm:** Nên chạy Bot theo chu kỳ 24h để tận dụng 1 lần giải Captcha cho 2 ngày cày (Bú Captcha).
- **Bảo mật:** Không chia sẻ file `profiles.json` và `license.key` cho người khác.
- **HWID:** Nếu bạn muốn chuyển Tool sang máy khác, hãy liên hệ Admin để reset License Key.

---
© Developed by [Huỳnh Việt /1 Thành Viên]
Telegram: https://t.me/Viet_Huynh_993
