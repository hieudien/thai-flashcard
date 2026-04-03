# 🇹🇭 Thai Flashcard Pro - Audio Edition

Website: https://thai-flash-card.vercel.app/

![Thai Flashcard Banner](https://img.shields.io/badge/Language-Thai-blue)
![License](https://img.shields.io/badge/License-MIT-green)
![Status](https://img.shields.io/badge/Status-Stable-brightgreen)

**Thai Flashcard Pro** là một ứng dụng web nhẹ, mạnh mẽ giúp người mới bắt đầu học tiếng Thái làm chủ bảng chữ cái (44 phụ âm và hệ thống nguyên âm) thông qua phương pháp lặp lại ngắt quãng (Spaced Repetition) và âm thanh trực quan.

---

## ✨ Tính năng nổi bật

* **🗂️ Đầy đủ dữ liệu:** Bao gồm 44 phụ âm (Trung, Cao, Thấp) và hệ thống nguyên âm ngắn/dài kèm ký hiệu vị trí chính xác.
* **🔊 Âm thanh chất lượng cao:** Sử dụng dữ liệu âm thanh Base64 tích hợp sẵn, giúp phát âm chuẩn xác ngay lập tức mà không cần load file từ server ngoài.
* **🧠 Thuật toán Spaced Repetition:** Tự động sắp xếp lịch ôn tập dựa trên mức độ ghi nhớ của bạn (Chưa biết, Khó, Nhớ, Dễ).
* **📊 Thống kê tiến độ:** Theo dõi tỉ lệ chính xác và số lượng từ đã thuộc lòng theo thời gian thực.
* **💾 Lưu trữ cục bộ:** Toàn bộ tiến độ học tập được lưu tại `LocalStorage` trên trình duyệt của bạn, không cần đăng ký tài khoản.
* **📱 Giao diện Mobile-first:** Tối ưu hóa hoàn hảo cho trải nghiệm học tập trên điện thoại di động.

---

## 🛠️ Công nghệ sử dụng

* **Frontend:** HTML5, CSS3 (Flexbox/Grid), JavaScript (ES6+).
* **Data Management:** JSON & ES6 Modules.
* **Audio:** Base64 Encoded MPEG-3.
* **Storage:** Browser LocalStorage API.

---

## 🚀 Hướng dẫn cài đặt

Dự án này chạy hoàn toàn trên trình duyệt, không cần cài đặt backend phức tạp.

1.  **Clone dự án:**
    ```bash
    git clone [https://github.com/username/thai-flashcard-pro.git](https://github.com/username/thai-flashcard-pro.git)
    ```
2.  **Mở file:**
    Mở file `index.html` trực tiếp trên trình duyệt hoặc sử dụng Live Server (trong VS Code).

---

## 📖 Cách sử dụng

1.  **Học thẻ:** Nhìn chữ cái trên màn hình và cố gắng nhớ lại cách đọc/ý nghĩa.
2.  **Kiểm tra:** Nhấn vào thẻ hoặc nút **"Hiện đáp án"** để xem phiên âm và loại chữ cái.
3.  **Phát âm:** Nhấn nút **🔊 Phát âm** để nghe giọng đọc bản xứ.
4.  **Đánh giá:** Chọn mức độ ghi nhớ để thuật toán sắp xếp lần xuất hiện tiếp theo của thẻ đó.
5.  **Reset:** Nếu muốn bắt đầu lại từ đầu, nhấn nút **🔄 Xóa tiến độ**.

---

## 📂 Cấu trúc thư mục

```text
├── index.html          # Giao diện chính của ứng dụng
├── data.js             # Chứa danh sách mảng baseCards và dữ liệu âm thanh Base64
└── README.md           # Tài liệu hướng dẫn dự án