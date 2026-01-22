# 📝 Todo & Habit Tracker App

> **Hệ thống quản lý công việc và thói quen cá nhân, tập trung vào tính bền vững của dữ liệu và trải nghiệm người dùng mượt mà trên di động.**

![React Native](https://img.shields.io/badge/react_native-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)
![Zustand](https://img.shields.io/badge/Zustand-orange?style=for-the-badge)

---

## 📖 Giới thiệu (Overview)

Dự án này là một ứng dụng di động mô phỏng các tính năng cốt lõi của một hệ thống quản lý tác vụ chuyên nghiệp. Thay vì chỉ là một danh sách tạm thời, ứng dụng tập trung vào việc **Xử lý dữ liệu bền vững (Persistence)** và quy trình **Validation** chặt chẽ để đảm bảo tính toàn vẹn của dữ liệu người dùng.

---

## 🛠 Tech Stack (Công nghệ sử dụng)

| Category | Technology | Description |
| :--- | :--- | :--- |
| **Mobile Core** | React Native | Framework xây dựng ứng dụng native đa nền tảng. |
| **Language** | TypeScript | Đảm bảo kiểu dữ liệu chặt chẽ và giảm thiểu lỗi runtime. |
| **Navigation** | React Navigation | Xử lý điều hướng đa màn hình (Stack & Tab Navigation). |
| **State Management**| Zustand | Quản lý trạng thái ứng dụng nhẹ nhàng và hiệu quả. |
| **Storage** | MMKV / Async Storage | Lưu trữ dữ liệu cục bộ với tốc độ truy xuất cao. |
| **Form Handling** | React Hook Form | Xử lý nhập liệu và validation chuyên nghiệp. |

---

## ✨ Tính năng nổi bật (Key Features)

### 1. 📋 Quản lý Task Toàn diện
* **Cấu trúc dữ liệu**: Mỗi đầu việc bao gồm *Title*, *Description* (tùy chọn) và trạng thái *Status* (Done/Not Done).
* **Hành động nhanh**: Hỗ trợ chuyển đổi trạng thái (Toggle) và xóa task chỉ với một thao tác chạm.

### 2. 🛡 Validation & UX chuyên nghiệp
* **Input Protection**: Hệ thống chặn việc tạo task trống thông qua logic kiểm tra phía client, đảm bảo không có dữ liệu rác.
* **Giao diện tối giản**: Tập trung tối đa vào nội dung và sự tiện lợi cho người dùng.

### 3. 💾 Data Persistence (Tính bền vững)
* **Auto-Save**: Tự động đồng bộ mọi thay đổi xuống bộ nhớ thiết bị ngay lập tức.
* **Rehydration**: Khi khởi động lại ứng dụng, toàn bộ danh sách công việc được khôi phục chính xác trạng thái trước đó.

---

## 🚀 Hướng dẫn cài đặt (Installation)

### Yêu cầu tiên quyết (Prerequisites)
* Node.js (v18+)
* Android Studio (cho máy ảo Android) hoặc Xcode (cho iOS)

### Các bước thực hiện
1. **Clone dự án**:
   ```bash
   git clone [https://github.com/XuanQuang1301/Todo-Habit-Tracker.git](https://github.com/XuanQuang1301/Todo-Habit-Tracker.git)
   cd Todo-Habit-Tracker
2. **Cài đặt thư viện:**
   npm install
3. **Chạy ứng dụng:**
   npx react-native run-android  # Cho Android
   npx react-native run-ios      # Cho iOS
🧪 Kiểm thử & Chất lượng (Quality Control)
✅ Persistence Test: Đảm bảo dữ liệu không bị mất sau khi đóng ứng dụng hoàn toàn và mở lại.
✅ Validation Test: Thử nghiệm bỏ trống trường Title để xác nhận hệ thống chặn tạo task lỗi thành công.
✅ Navigation Test: Đảm bảo luồng chuyển đổi giữa Home Screen và Add Task Screen mượt mà.

👤 **Author**
**Xuan Quang**
* GitHub: @XuanQuang1301
* Project: Todo & Habit Tracker App
