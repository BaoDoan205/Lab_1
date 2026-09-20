# 📱 Campus Club Event Booking App

> **Mini-Project 1 — Cross-Platform Mobile App Development (VKU)**
>
> Ứng dụng cho phép các câu lạc bộ sinh viên đặt phòng/thiết bị, và nhà trường (Admin) duyệt hoặc từ chối yêu cầu.

[![Course](https://img.shields.io/badge/Course-VKU-blue)](https://vku.udn.vn/)
[![Status](https://img.shields.io/badge/Status-In%20Progress-yellow)](https://github.com/BaoDoan205/Lab_1)
[![Team](https://img.shields.io/badge/Team-Mr.BlueSky-green)](https://github.com/BaoDoan205/Lab_1)

---

## 📖 Table of Contents

- [About the Project](#-about-the-project)
- [Features](#-features)
- [Tech Stack](#-tech-stack)
- [Project Structure](#-project-structure)
- [Getting Started](#-getting-started)
- [Documentation](#-documentation)
- [Team Members](#-team-members)

---

## 🎯 About the Project

**Campus Club Event Booking App** là một ứng dụng di động đa nền tảng (cross-platform) giúp:

- 🏫 **Sinh viên / Câu lạc bộ:** Xem lịch trống phòng/thiết bị, gửi yêu cầu đặt chỗ, theo dõi trạng thái yêu cầu.
- ✅ **Admin (Nhà trường):** Xem danh sách yêu cầu, phê duyệt hoặc từ chối, gửi thông báo cho sinh viên.

Dự án được thực hiện trong khuôn khổ môn học **Cross-Platform Mobile App Development** tại **Trường Đại học Công nghệ Thông tin và Truyền thông Việt - Hàn (VKU)**.

---

## ✨ Features

### 1. Booking Request Module
- [ ] Lịch trống phòng/thiết bị (Availability Calendar)
- [ ] Form gửi yêu cầu đặt chỗ (Booking Request Form)
- [ ] Trình theo dõi trạng thái yêu cầu (Status Tracker)

### 2. Approval Workflow
- [ ] Bảng điều khiển phê duyệt của Admin (Admin Approval Dashboard)
- [ ] Thông báo khi duyệt/từ chối (Notification on Approve/Reject)

### 3. User Management
- [ ] Xác thực người dùng (Authentication)
- [ ] Phân quyền người dùng (Roles & Permissions)

> 📌 **Trạng thái:** Các tính năng đang trong giai đoạn lập kế hoạch (Planning). Sẽ được cập nhật khi bắt đầu code.

---

## 🛠 Tech Stack

| Layer | Technology |
|-------|------------|
| **Framework** | React Native (Expo) |
| **Language** | TypeScript |
| **State Management** | Zustand / React Query |
| **Navigation** | React Navigation |
| **Local Storage** | AsyncStorage |
| **Backend (dự kiến)** | Firebase / Supabase |
| **Deployment** | Vercel / Expo Snack |

---

## 📁 Project Structure

```
/campus-booking-app
├── README.md
├── docs/
│   ├── wbs-decomposition.md
│   └── images/
│       └── wbs-diagram.png
└── src/
    ├── modules/
    │   ├── booking/      # Calendar, Form, Tracker
    │   ├── approval/     # Admin Dashboard, Notification
    │   └── user/         # Auth, Roles
    └── shared/
        ├── components/   # UI components dùng chung
        └── utils/        # Helper functions
```

---

## 🚀 Getting Started

### Prerequisites
- Node.js >= 18.x
- npm hoặc yarn
- Expo CLI (`npm install -g expo-cli`)

### Installation

```bash
# 1. Clone repository
git clone https://github.com/BaoDoan205/Lab_1.git
cd Lab_1

# 2. Cài đặt dependencies
npm install

# 3. Chạy ứng dụng
npm start
# hoặc
expo start
```

> ⚠️ **Lưu ý:** Phần hướng dẫn này sẽ được cập nhật đầy đủ khi nhóm bắt đầu code.

---

## 📚 Documentation

- 📄 [WBS Decomposition](https://github.com/BaoDoan205/Lab_1/blob/main/wbs-decomposition.md) — Phân rã công việc dự án.
- 🖼 [WBS Diagram](https://github.com/BaoDoan205/Lab_1/raw/main/docs/images/wbs-diagram.png) — Sơ đồ WBS trên Miro.
- 📊 [Mini-Project 1 Report](https://github.com/BaoDoan205/Lab_1/blob/main/docs/Mr.BlueSky_MiniProject1_Report.pdf) — Báo cáo kỹ thuật (sẽ cập nhật).

---

## 👥 Team Members

| # | Họ và Tên | MSSV | Role | Contribution |
|:-:|-----------|------|------|:------------:|
| 1 | Đoàn Nguyên Bảo | 23IT.B009 | Team Lead / Frontend Architecture | 40% |
| 2 | Hồ Tấn Phát | 23IT.B162 | Member / Logic & State Management | 30% |
| 3 | Hồ Văn Anh Vũ | 23IT.B248 | Member / Logic & State Management | 30% |

---

## 📝 License

Dự án này được thực hiện cho mục đích học tập tại VKU. © 2026 Mr.BlueSky Team.

---

<p align="center">
  Made with ❤️ by <strong>Mr.BlueSky Team</strong> — VKU
</p>
