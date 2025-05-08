 # App 

> Ứng dụng di động đa nền tảng cho phép người dùng chụp ảnh, chỉnh sửa ảnh (cắt, xoay, lật), thay đổi nền và lưu ảnh về thư viện.

---

## 👨‍💻 Giới thiệu dự án

Đây là đồ án môn **Lập trình đa nền tảng**, được phát triển bằng **React Native (Expo)** với các tính năng xử lý ảnh cơ bản. Ứng dụng cho phép:

- Chụp ảnh bằng camera.
- Chọn ảnh từ thư viện.
- Cắt, xoay, lật ảnh.
- Xóa nền ảnh và thay bằng màu tùy chọn.
- Lưu ảnh đã chỉnh sửa về thư viện điện thoại.

---

## 🧑‍🤝‍🧑 Thành viên nhóm

| Họ tên        | Vai trò                        |
|---------------|-------------------------------|
| Bảo           | Thiết kế giao diện (Figma)     |
| Dân           | Thiết kế giao diện (Figma)     |
| Việt          | Lập trình frontend             |
| Quốc Vũ       | Lập trình frontend             |

---

## 🛠️ Công nghệ sử dụng

| Công nghệ                  | Mô tả                                |
|---------------------------|--------------------------------------|
| React Native + Expo       | Nền tảng phát triển ứng dụng         |
| react-native-vision-camera | Chụp ảnh với camera                  |
| react-native-image-picker | Chọn ảnh từ thư viện                 |
| react-native-image-crop-picker | Cắt, xoay, lật ảnh                |
| remove.bg API             | Xóa nền ảnh sử dụng AI               |
| Axios                     | Gửi HTTP request đến API             |

---

## 📂 Cấu trúc thư mục

```
Cross-Platform-Programming/
├── assets/              # Hình ảnh, icon
├── components/          # Các thành phần giao diện tái sử dụng
├── screens/             # Các màn hình chính (Home, Camera, Editor, etc.)
├── services/            # Gọi API remove.bg
├── utils/               # Hàm tiện ích hỗ trợ
├── App.js               # File khởi chạy chính
├── app.json             # Cấu hình cho Expo
└── README.md            # Báo cáo dự án (file này)
```

---

## 🚀 Hướng dẫn cài đặt và chạy dự án

### 1. Clone dự án

```bash
git clone https://github.com/Duc-Viet123/Cross-Platform-Programming.git
cd Cross-Platform-Programming
```

### 2. Cài đặt dependencies

```bash
npm install
```

### 3. Chạy dự án với Expo

```bash
npx expo start
```

📱 Sử dụng ứng dụng **Expo Go** trên điện thoại để quét mã QR và chạy ứng dụng.

---

## 🧠 Tính năng chi tiết

| Tính năng                | Mô tả                                                                 |
|--------------------------|----------------------------------------------------------------------|
| 📸 Chụp ảnh              | Mở camera để chụp ảnh bằng `react-native-vision-camera`              |
| 🖼️ Chọn ảnh             | Chọn ảnh có sẵn từ thư viện thiết bị                                 |
| ✂️ Chỉnh sửa ảnh         | Cắt, xoay, lật ảnh bằng thư viện `image-crop-picker`                |
| 🪄 Xóa nền               | Sử dụng `remove.bg API` để xóa nền ảnh                               |
| 🎨 Đổi nền                | Thay nền bằng màu tuỳ chọn sau khi xoá nền                           |
| 💾 Lưu ảnh               | Lưu ảnh đã chỉnh sửa về thư viện máy                                 |

---

## 🖼️ Minh hoạ giao diện

> *(Chèn hình ảnh giao diện nếu có)*

```
assets/
├── screenshot-home.png
├── screenshot-editor.png
```

---

## 📈 Đánh giá và kết quả

- ✅ Ứng dụng chạy mượt trên Android và iOS (Expo Go).
- ✅ UI đơn giản, dễ sử dụng.
- ✅ Xử lý ảnh mượt, thời gian phản hồi nhanh (nhờ API remove.bg).
- ⚠️ Ứng dụng cần kết nối Internet để thực hiện xóa nền.

---

## 📚 Tài liệu tham khảo

- [React Native Documentation](https://reactnative.dev/)
- [Expo Documentation](https://docs.expo.dev/)
- [remove.bg API](https://www.remove.bg/api)
- [React Native Image Picker](https://github.com/react-native-image-picker/react-native-image-picker)

---

## ✅ Ghi chú

- Bạn cần đăng ký API Key từ [remove.bg](https://www.remove.bg/) để gọi API xóa nền ảnh.
- Hạn chế: Gói miễn phí có giới hạn số lượt gọi API mỗi tháng.

---

## ❤️ Cảm ơn thầy cô đã hướng dẫn!

> Mọi góp ý xin gửi qua GitHub Issues hoặc liên hệ trực tiếp với nhóm.
