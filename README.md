# Spectrum

`Spectrum` là ứng dụng desktop dùng để biến file âm thanh thành hiệu ứng cột sóng nhạc và xuất ra video `WebM` có nền trong suốt.

## Tính năng chính

- Chọn file audio từ máy tính với các định dạng phổ biến như `mp3`, `wav`, `m4a`, `aac`, `ogg`, `flac`, `opus`.
- Xem trước trực tiếp trong app theo tiến trình phát nhạc.
- Tùy chỉnh giao diện cột sóng:
  - đổi màu thanh sóng
  - chỉnh bo góc thanh
  - chỉnh độ dãn ngang của cụm bar
- Xuất video `WebM` alpha để dễ chèn vào phần mềm dựng video hoặc overlay.
- Có tùy chọn xuất nhanh không kèm audio hoặc xuất kèm audio ngay trong file `webm`.

## Cách sử dụng

1. Bấm `Chọn Audio`.
2. App dùng `ffmpeg` để đọc audio và phân tích thành dữ liệu spectrum.
3. Bấm `Xem Trước` để nghe và xem thanh sóng chạy theo nhạc.
4. Tùy chỉnh màu, bo góc và độ dãn đến khi đạt kết quả mong muốn.
5. Bấm `Xuất Video` để lưu file `WebM`.
