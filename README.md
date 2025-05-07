<div align="center">

<img src="https://img.shields.io/badge/version-1.20.1-blue.svg" alt="version">
<img src="https://img.shields.io/badge/platform-Paper-2ea44f.svg" alt="platform">
<img src="https://img.shields.io/github/license/your-username/HaoyiProGuard" alt="license">
<img src="https://img.shields.io/github/issues/your-username/HaoyiProGuard" alt="issues">

<br><br>

<h1>🛡️ HaoyiProGuard</h1>
<p><strong>Malware Scanner & Backdoor Remediator for Minecraft Paper Servers</strong></p>

</div>

---

## ✨ Tổng quan

**HaoyiProGuard** là plugin được thiết kế đặc biệt cho máy chủ Minecraft sử dụng nền tảng **Paper**, nhằm **phát hiện và loại bỏ mã độc (malware)**, đồng thời **vá các method backdoor nguy hiểm** trong các plugin bên thứ ba.

> 🔒 Giải pháp tự động bảo vệ máy chủ Minecraft khỏi các plugin độc hại và mã khai thác nguy hiểm.

---

## 🚀 Tính năng nổi bật

| 🔍 Tính năng                    | 🧩 Mô tả ngắn gọn |
|-------------------------------|------------------|
| 🧠 Quét thông minh            | Phân tích hành vi của các plugin khi khởi động hoặc theo lệnh |
| ⚔️ Phát hiện backdoor         | Nhận diện method nguy hiểm như `Runtime.exec`, `ClassLoader`, `Reflection`... |
| 🛠️ Tự động sửa chữa           | Vô hiệu hóa hoặc xóa các method độc hại được phát hiện |
| 📊 Báo cáo chi tiết            | Ghi log đầy đủ và minh bạch các hành động thực hiện |
| ⚙️ Tùy biến cao               | Cấu hình thông qua `config.yml`, dễ dùng và mở rộng |

---

## 🧩 Yêu cầu hệ thống

| Thành phần  | Yêu cầu                     |
|-------------|-----------------------------|
| Minecraft   | `1.20.1`                    |
| Máy chủ     | Nền tảng **Paper** (latest) |
| Java        | **Java 21+** (ưu tiên hiệu năng và bảo mật) |

---

## 🛠️ Cài đặt nhanh

1. 📥 Tải plugin tại [Releases](#).
2. 📂 Thả file `HaoyiProGuard-1.20.1.jar` vào thư mục `plugins/` của máy chủ.
3. 🔄 Khởi động lại server hoặc dùng lệnh `/hpgreload`.

> ✅ Ngay khi được nạp, plugin sẽ bắt đầu hoạt động và quét toàn bộ plugin trong máy chủ.

---

## ⚙️ Sử dụng

### 🔎 Quét thủ công
Bạn có thể kích hoạt quét plugin thủ công bằng lệnh sau:

