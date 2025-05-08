
# 🎓 BÁO CÁO DỰ ÁN CUỐI KỲ
## Xây Dựng Ứng Dụng Chỉnh Sửa Ảnh và Video Đa Nền Tảng

---

## 📑 MỤC LỤC

1. [Giới thiệu dự án](#1-giới-thiệu-dự-án)
2. [Mục tiêu và phạm vi](#2-mục-tiêu-và-phạm-vi)
3. [Phân tích yêu cầu](#3-phân-tích-yêu-cầu)
4. [Thiết kế hệ thống](#4-thiết-kế-hệ-thống)
5. [Thiết kế giao diện người dùng](#5-thiết-kế-giao-diện-người-dùng)
6. [Cài đặt và phát triển](#6-cài-đặt-và-phát-triển)
7. [Kiểm thử hệ thống](#7-kiểm-thử-hệ-thống)
8. [Đánh giá và cải tiến](#8-đánh-giá-và-cải-tiến)
9. [Kết luận](#9-kết-luận)
10. [Hướng dẫn sử dụng](#10-hướng-dẫn-sử-dụng)
11. [Phụ lục](#11-phụ-lục)

---

## 1. Giới thiệu dự án

- **Tên dự án**: Ứng dụng Chỉnh sửa Ảnh và Video Đa Nền Tảng  
- **Ngôn ngữ lập trình**: TypeScript, JavaScript  
- **Framework**: React Native (Expo)  
- **Mục tiêu**: Cung cấp công cụ chỉnh sửa ảnh và video cơ bản đến nâng cao cho người dùng trên cả Android và iOS.

## 2. Mục tiêu và phạm vi

### 2.1 Mục tiêu

- Chụp ảnh và quay video.
- Chọn ảnh/video từ thư viện.
- Chỉnh sửa ảnh: cắt, xoay, lật, xóa phông, thêm bộ lọc, chèn chữ.
- Chỉnh sửa video: cắt, thay đổi tốc độ, xoay.
- Lưu kết quả vào thiết bị.

### 2.2 Phạm vi

- Ứng dụng hoạt động trên Android và iOS.
- Không yêu cầu backend hoặc đăng nhập.
- Tập trung vào chỉnh sửa offline và trải nghiệm người dùng.

## 3. Phân tích yêu cầu

### 3.1 Yêu cầu chức năng

(Có bảng chi tiết như đã trình bày ở phần trước.)

### 3.2 Yêu cầu phi chức năng

- Giao diện thân thiện.
- Ứng dụng mượt và phản hồi nhanh.
- Tương thích thiết bị phổ biến.

## 4. Thiết kế hệ thống

- 5 module chính: Camera, Library, Photo Editor, Video Editor, Media Storage.
- DFD: Người dùng -> Chọn ảnh/video -> Chỉnh sửa -> Lưu.

## 5. Thiết kế giao diện người dùng

- Giao diện chính: Chọn ảnh/video, chỉnh sửa.
- Giao diện chỉnh sửa ảnh/video: Tương tác trực quan.
- Giao diện xem trước và lưu.

## 6. Cài đặt và phát triển

### 6.1 Thư viện sử dụng

- `expo-camera`, `react-native-vision-camera`
- `react-native-image-picker`
- `react-native-image-crop-picker`
- `expo-av`, `react-native-video`
- `remove.bg` API
- `expo-media-library`, `react-native-fs`

### 6.2 Quy trình phát triển

- Phát triển từng module riêng.
- Tích hợp, kiểm thử, tối ưu hóa hiệu năng.

## 7. Kiểm thử hệ thống

- Kiểm thử đơn vị và tích hợp trên Android/iOS.
- Kiểm tra tính ổn định và hiệu suất xử lý ảnh/video.

## 8. Đánh giá và cải tiến

- Ưu điểm: đầy đủ chức năng cơ bản và nâng cao.
- Nhược điểm: xử lý video lớn có thể chậm.
- Hướng phát triển: làm đẹp ảnh bằng AI, chia sẻ mạng xã hội.

## 9. Kết luận

Ứng dụng đáp ứng tốt yêu cầu đặt ra. Có thể thương mại hóa nếu phát triển thêm tính năng chuyên sâu.

## 10. Hướng dẫn sử dụng

### Bước 1: Cài đặt app

Clone repo:

```bash
git clone https://github.com/Duc-Viet123/Cross-Platform-Programming.git
cd Cross-Platform-Programming
npm install
npx expo start
```

Sau đó, quét mã QR bằng Expo Go trên điện thoại để chạy ứng dụng.

### Bước 2: Sử dụng tính năng

- **Chụp ảnh/quay video**: Bấm "Camera", sau đó chọn chụp/quay.
- **Chọn ảnh/video từ thư viện**: Bấm "Thư viện", chọn file muốn chỉnh sửa.
- **Chỉnh sửa ảnh**:
  - Cắt: Dùng khung chọn.
  - Xoay/Lật: Nút tùy chọn.
  - Xóa phông: Tự động dùng API remove.bg.
  - Bộ lọc: Chọn hiệu ứng mong muốn.
  - Chèn chữ: Nhập text và chọn vị trí.
- **Chỉnh sửa video**:
  - Cắt video: Chọn đoạn cần giữ.
  - Tăng/Giảm tốc độ: Chọn 0.5x, 1x, 2x.
  - Xoay: Nút xoay video.
- **Lưu ảnh/video**: Nhấn “Lưu” để lưu vào thư viện điện thoại.

## 11. Phụ lục

- **GitHub**: [https://github.com/Duc-Viet123/Cross-Platform-Programming](https://github.com/Duc-Viet123/Cross-Platform-Programming)
- **Video demo**: *(Bạn có thể quay video sử dụng app và đính kèm tại đây)*
- **Ảnh minh họa giao diện**: *(Chụp màn hình app các chức năng chính)*
