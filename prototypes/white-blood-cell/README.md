# PROTOTYPE - NOT FOR PRODUCTION — Bạch cầu tiêu diệt mầm bệnh (3D)

**Giả thuyết:** Mô phỏng 3D tự động cảnh bạch cầu (đại thực bào/bạch cầu trung tính)
truy đuổi và thực bào vi khuẩn, virus trong mạch máu đủ trực quan và hấp dẫn để
làm nền cho một game/ứng dụng giáo dục.

**Cách chạy:** mở `index.html` bằng trình duyệt (cần internet để tải Three.js từ CDN jsdelivr).
Kéo chuột để xoay camera, cuộn để zoom.

**Cơ chế mô phỏng:**
- Bạch cầu tìm mầm bệnh gần nhất chưa bị bạch cầu khác nhắm (hoá ứng động).
- Khi tới gần, màng tế bào vươn chân giả về phía mục tiêu.
- Chạm tới → nuốt (thực bào): mầm bệnh bị kéo vào trong, co lại, đổi màu và biến mất (tiêu hoá).
- Mầm bệnh mới xuất hiện định kỳ; hồng cầu trôi theo dòng máu làm nền.
- Thông số chỉnh trong object `CFG` đầu script.

**Trạng thái:** in-progress

**Kết quả:** chưa có — cập nhật sau khi xem thử.
