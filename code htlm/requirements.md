# Nguyên tắc làm việc và yêu cầu dự án

## Giới thiệu về dự án

- Đây là trang web cho phép điều khiển robot trên một bản đồ (map.png và robot.png)
- Map có kích thước chuẩn 120cm x 120cm, robot khoảng 16cm x 12cm
- Trang web được chia làm 3 phân khu chính

## Cấu trúc trang web

1. **Phân khu 1-2 (bên trái)**:

   - Điều khiển robot
   - Hiển thị tỉ lệ, tọa độ
   - Điều chỉnh kích thước robot và map
   - Lưu vị trí, kích thước và chương trình

2. **Phân khu 2 (dưới phân khu 1)**:

   - Lập trình robot bằng cách kéo thả các khối lệnh
   - Có thể lưu chương trình khối để sử dụng sau này

3. **Phân khu 3 (bên phải)**:
   - Hiển thị map và robot
   - Có thể điều chỉnh kích thước và vị trí

## Các tính năng hiện có

- Thanh header có các nút: hiện/ẩn lưới, đánh dấu điểm, cài đặt, chế độ tối
- Có thể chỉnh kích thước robot bằng cách kéo chuột
- Kích đúp chuột vào robot để kích hoạt chế độ kéo robot đến vị trí khác
- Robot chỉ di chuyển trong khu vực map, không thể ra ngoài
- Có ô hiển thị mini-map và ô hiển thị tọa độ chuột

## Nguyên tắc làm việc

1. **Không xóa code**: Không xóa bất kỳ dòng nào khi chưa chắc chắn
2. **Thêm cẩn thận**: Chỉ thêm những tính năng đã được yêu cầu rõ ràng
3. **Sửa cẩn thận**: Suy nghĩ kỹ trước khi sửa đổi code
4. **Truyền thông rõ ràng**: Thông báo rõ phần sẽ sửa, ở dòng nào, code hiện tại là gì
5. **Hỏi khi không chắc chắn**: Nếu có điều gì không hiểu, hỏi lại ngay

## Yêu cầu cụ thể (sẽ cập nhật theo thời gian)

- Cần làm cẩn thận, đọc kỹ yêu cầu trước khi thực hiện
- Trước khi sửa code, phải xác định rõ dòng nào sẽ sửa và giải thích
- Không được thêm/sửa/xóa bất cứ thứ gì khi chưa chắc chắn
- Luôn tuân theo hướng dẫn của người dùng
- Với mỗi yêu cầu mới, thêm vào file requirements.md và nói rõ yêu cầu đó
- Mỗi khi cập nhật code, thêm chú thích vào file requirements.md về những gì đã sửa (chỉ ý chính, không cần code đầy đủ)
- File requirements.md đóng vai trò như "bộ nhớ" trong đoạn chat này, lưu trữ tất cả yêu cầu và lịch sử làm việc
- Cần thận trọng khi cập nhật file này vì đây là nơi lưu trữ bộ nhớ của toàn bộ dự án

## Thông tin về các file trong dự án

- **backup.html**: File chính chứa code cho trang web Robot Map Interface (khoảng 3500+ dòng). Đây là file chính mà chúng ta sẽ làm việc và sửa đổi.
- **requirements.md**: File lưu trữ yêu cầu và bộ nhớ của dự án (file hiện tại). Đóng vai trò như "bộ nhớ" của cuộc trò chuyện.
- **map.png**: Hình ảnh bản đồ (120cm x 120cm)
- **robot.png**: Hình ảnh robot (16cm x 12cm)
- **Các file khác**: 1backup.html, index.html, indexCopilot.html, luulai.html, test.html (các phiên bản khác hoặc file test). Nếu làm việc với các file này, sẽ có chú thích rõ hơn.

## Lịch sử cuộc trò chuyện và cập nhật

### 17/04/2025

1. Tạo file requirements.md để lưu trữ tất cả các yêu cầu và nguyên tắc làm việc
2. Thêm phần lịch sử cập nhật để theo dõi các thay đổi: Từ không có mục lịch sử -> Thêm mục "Lịch sử cập nhật"
3. Thảo luận về cấu trúc và mục đích của trang web: Làm rõ 3 phân khu chính và chức năng của từng phân khu
4. Thống nhất về cách làm việc: không xóa code khi chưa chắc chắn, cẩn thận khi thêm/sửa code
5. Đồng ý sử dụng file requirements.md làm "bộ nhớ" cho toàn bộ dự án: Thêm mục "Yêu cầu cụ thể" với các nguyên tắc
6. Thêm thông tin về các file trong dự án và mục đích của chúng: Từ không có mục thông tin file -> Thêm mục "Thông tin về các file trong dự án"
7. Ghi chú: Khi cần đổi tên file, tạo file mới với tên mới thay vì xóa file cũ
8. Làm rõ backup.html là file chính để làm việc, requirements.md là file bộ nhớ: Cập nhật mô tả của các file trong mục "Thông tin về các file trong dự án"
9. Cập nhật định dạng phần lịch sử cuộc trò chuyện để thêm thời gian cụ thể và mô tả chi tiết hơn về các thay đổi: Từ chỉ ghi nội dung -> Thêm thời gian và chi tiết thay đổi
10. Xóa múi giờ không chính xác trong lịch sử cập nhật: Loại bỏ các thời gian không chính xác, thống nhất chỉ thêm thời gian mới khi được xác nhận
11. [16:14] Xác nhận múi giờ Việt Nam và thêm thời gian chính xác cho các cập nhật
12. [16:40] Thêm tính năng điều chỉnh độ rộng giữa phân khu 1-2 và phân khu 3:

- Thêm một thanh điều chỉnh (sidebar-resizer) vào giữa sidebar và display-area
- Thêm JavaScript để xử lý tính năng kéo thả điều chỉnh kích thước:
  - Hàm `initSidebarResizer()` để khởi tạo sự kiện
  - Hàm `startResizingSidebar()` để bắt đầu quá trình kéo
  - Hàm `stopResizingSidebar()` để dừng quá trình kéo
  - Hàm `resizeSidebar()` để xử lý việc điều chỉnh kích thước
  - Hàm `updateSidebarResizerPosition()` để cập nhật vị trí
- Giới hạn kích thước sidebar từ 250px đến 500px
- Sử dụng localStorage để lưu trữ kích thước đã điều chỉnh giữa các phiên làm việc
- Thay đổi: Từ không có tính năng điều chỉnh -> Có thanh điều chỉnh đầy đủ chức năng

13. [17:10] Sửa lỗi hiển thị của các khối lệnh trong phân khu 2:

- Vấn đề: Ô nhập chữ (input) trong các khối lệnh bị lòi ra ngoài khối và khi kéo một khối sang khung bên phải, các phần tử (dấu x, dấu tích, ô nhập liệu) bị lòi ra khỏi khối
- Giải pháp: Chỉnh sửa CSS cho `.command-block` và `.command-block input`:
  - Thêm `width: calc(100% - 16px)` để đảm bảo độ rộng phù hợp
  - Thêm `box-sizing: border-box` để padding không làm tăng kích thước
  - Thêm `overflow: hidden` để ẩn nội dung bị lòi
  - Thêm `flex-wrap: wrap` để các phần tử bên trong xuống dòng khi cần
  - Giới hạn độ rộng của input với `max-width: 60px`
- Kết quả: Tất cả các phần tử trong khối lệnh giờ đều nằm gọn trong khối, không còn bị lòi ra ngoài và hiển thị đúng khi kéo từ thư viện sang vùng chương trình
