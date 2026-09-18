# TA Studio Loop

Dây chuyền viết kịch bản và dựng video truyện cho kênh YouTube · Script-writing and video production pipeline for YouTube story channels.<br>
Developed by **YVN Studio**.

**Bản mới nhất · Latest: [v1.0.3](https://github.com/anhql77/TA-Studio-Loop/releases/tag/v1.0.3)** — [Tải bộ cài · Download installer](https://github.com/anhql77/TA-Studio-Loop/releases/download/v1.0.3/Setup_TA_Studio_Loop_v1.0.3.exe)

Phần mềm tự báo khi có bản mới (dòng chữ chạy trên cùng + nút **Cập nhật lên …**). The app announces new versions itself (a scrolling banner + an **Update to …** button).

Kho này chỉ chứa bộ cài và ghi chú phát hành · This repository only hosts installers and release notes.

## Lịch sử phiên bản · Version history

### [v1.0.3](https://github.com/anhql77/TA-Studio-Loop/releases/tag/v1.0.3) · 2026-09-18

| Tiếng Việt | English |
|---|---|
| **Báo và cài bản mới ngay trong phần mềm** — có bản mới là hiện dòng chữ chạy trên cùng và nút vàng “Cập nhật lên …”; cài xong hiện bảng Có gì mới. | **In-app update notice** — a scrolling banner and a yellow “Update to …” button appear when a new version is out; after updating, a What's New table opens. |
| **Dòng thông báo bản mới** — chữ chạy trên cùng phần mềm khi có bản mới; người dùng muốn thì cập nhật, không bị ép. | **New-version banner** — a scrolling line at the top of the app when an update is available; updating stays optional. |
| **Nút “Cập nhật lên …”** — nút vàng nhỏ ở cuối cột trái, bấm là xem thay đổi và tải bộ cài bản mới; dữ liệu và máy đã ghép giữ nguyên. | **“Update to …” button** — a small yellow button at the bottom of the sidebar shows the changes and downloads the new installer; data and paired machines are kept. |
| **Bảng Có gì mới** — lần đầu mở sau khi cập nhật, phần mềm liệt kê mọi thay đổi từ bản cũ lên bản mới. | **What's New table** — the first launch after an update lists every change since your previous version. |
| **Tên và phiên bản trên thanh tiêu đề** — cửa sổ ghi “TA Studio Loop 1.0.3 — Developed by YVN Studio”. | **Name and version in the title bar** — the window reads “TA Studio Loop 1.0.3 — Developed by YVN Studio”. |
| **Mỗi bản đều có trên GitHub** — bộ cài và bảng thay đổi hai thứ tiếng ở trang phát hành công khai; mã nguồn vẫn để riêng tư. | **Every version on GitHub** — installers and bilingual release notes live on a public releases page; the source code stays private. |
| **Bộ cài chứa mã đã biên dịch** — không kèm mã nguồn đọc được. | **Installer ships compiled code** — no readable source code inside. |

### [v1.0.2](https://github.com/anhql77/TA-Studio-Loop/releases/tag/v1.0.2) · 2026-09-18

| Tiếng Việt | English |
|---|---|
| **Mở trong cửa sổ riêng** — lối tắt mở TA Studio Loop như một phần mềm, không còn là một tab trình duyệt. | **Opens in its own window** — shortcuts open TA Studio Loop like an app instead of a browser tab. |
| **Cửa sổ ứng dụng riêng** — lối tắt ngoài màn hình và menu Start mở bằng chế độ ứng dụng của Microsoft Edge: không thanh địa chỉ, không tab. | **App window** — desktop and Start menu shortcuts use Microsoft Edge app mode: no address bar, no tabs. |
| **Tool viết chạy riêng trên máy cũng mở cửa sổ riêng.** | **The offline writing tool also opens in its own window.** |
| **Cài được như ứng dụng trên máy tính và điện thoại** — có biểu tượng riêng; dữ liệu luôn mới, không lưu đệm trang. | **Installable on desktop and phone** — own icon; data is always fresh, pages are never cached. |

### [v1.0.1](https://github.com/anhql77/TA-Studio-Loop/releases/tag/v1.0.1) · 2026-09-18

| Tiếng Việt | English |
|---|---|
| **Bản vá ổn định** — máy tự cắt Part dài và tự rút gọn không còn bị gãy. | **Stability patch** — automatic Part trimming and word-count trimming no longer break. |
| **Cắt Part / rút gọn chạy được** — lượt gọi thêm sau khi viết đủ bị hỏng ngay từ đầu nên Part dài vẫn giữ nguyên. Nay Part vượt độ dài đã chốt được cắt đúng. | **Part and word-count trimming work** — the extra pass after writing crashed at start, so over-long Parts were left untouched. They are now trimmed correctly. |
| **Ghi rõ lỗi của cổng AI** — cổng trả về rỗng thì máy ghi nguyên văn lý do, dễ tìm nguyên nhân. | **AI gateway errors are logged verbatim** — an empty gateway reply now records the exact reason. |
| **Đặt lại mật khẩu an toàn hơn** — lệnh máy chỉ mở được đặt lại mật khẩu cho Owner. | **Safer password reset** — the machine command can only reopen a password reset for the Owner. |
| **Sửa vặt** — đồng hồ đoạn vá không còn về 0; bỏ nháy thừa nhận cả nháy cong; màn “đang viết” không đứng im ở lượt gọi thêm. | **Small fixes** — patch timers no longer reset to 0; stray-quote cleanup handles curly quotes; the “writing” view no longer freezes during extra passes. |

### [v1.0.0](https://github.com/anhql77/TA-Studio-Loop/releases/tag/v1.0.0) · 2026-09-18

| Tiếng Việt | English |
|---|---|
| **Bản đầu tiên cho team** — bộ cài tự chạy, không cần quyền quản trị, mang sẵn Python. | **First team release** — a self-contained installer, no admin rights needed, Python included. |
| **Viết kịch bản 11 bước theo prompt người nắm kênh** — chia Part theo cảnh; vá song song 8 đoạn (bước 9 từ 35 phút xuống 4–11 phút). | **11-step scripts that follow the channel owner's prompt** — Parts split by scene; 8 patch passes run in parallel (step 9 from 35 min to 4–11 min). |
| **Nghiệm thu hai lớp, hai lăng kính** — đúng prompt + góc nhìn nhà sản xuất story cho khán giả Mỹ 60+: giữ chân, dễ nghe, cảm xúc, nhịp đọc, không bơm chữ, chất Mỹ. Máy tự sửa theo phiếu, tối đa 2 lần. | **Two-layer, two-lens acceptance check** — prompt compliance plus a producer's view for US 60+ story viewers: retention, listenability, emotion, pacing, no padding, authentic American voice. Auto-fix from the report, up to 2 attempts. |
| **Báo số từ so với prompt** — luôn hiện “N từ · prompt yêu cầu M từ”; lệch tối đa 200 từ; Part vượt độ dài đã chốt quá 5% thì máy tự cắt. | **Word count vs. prompt** — always shows “N words · prompt asks for M”; up to 200 words of tolerance; Parts more than 5% over their target are trimmed. |
| **Đồng hồ thời gian viết** — trần BKT 30 phút, Nuôi 20 phút. | **Writing-time clock** — caps of 30 min (BKT) and 20 min (Nuôi). |
| **Hai máy VIẾT và DỰNG chạy song song** — video đang dựng vẫn viết được kịch bản khác. | **VIẾT and DỰNG workers run side by side** — scripts keep being written while another video renders. |
| **Trang mở nhanh gấp 10 lần** — máy chủ dời về Singapore cạnh cơ sở dữ liệu (5–7 giây xuống 0,3–0,6 giây). | **Pages load 10× faster** — the server moved to Singapore next to the database (5–7 s down to 0.3–0.6 s). |
| **Việc treo tự về hàng chờ** — việc đứng im quá 25 phút được máy khác nhận lại. | **Stuck jobs recover on their own** — jobs idle for over 25 minutes go back to the queue. |
| **Vừa màn hình điện thoại** — dùng tốt ở khổ 375 px; nút bị chặn hiện trang báo dễ đọc. | **Phone-friendly** — works at 375 px wide; blocked actions show a readable notice. |
