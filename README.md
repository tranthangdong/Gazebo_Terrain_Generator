# Gazebo_Terrain_Generator
Hướng dẫn từng bước tạo địa hình 3D cho vọng lâu bằng cách sử dụng dữ liệu độ cao thực tế và dữ liệu vệ tinh.

> **Tip** ....

## 🚀 Thực thi Gazebo World Generator

1. Navigate to gazebo_terrian_generator and start the applciation.

```bash
export GAZEBO_MODEL_PATH="~/Desktop/gazebo_models"              # Option
export GAZEBO_WORLD_PATH="~/Desktop/gazebo_models/worlds"       # Optino
source terrain_generator/bin/activate
python scripts/server.py
```

2. Access the Web Interface: Open your web browser and navigate to http://localhost:8080

## ⚙️ Chức năng

Tạo địa hình thực tế: Tạo thế giới Gazebo 3D bằng cách sử dụng dữ liệu độ cao thực tế và hình ảnh vệ tinh của bất kỳ vị trí nào trên Trái đất. Các tòa nhà 3D: Thêm hoặc xóa các tòa nhà vào thế giới Gazebo bằng nút chuyển đổi. Vị trí xuất hiện có thể cấu hình: Thay đổi vị trí xuất hiện bằng cách sử dụng điểm đánh dấu giao diện người dùng tương tác trong khu vực quan tâm. Đầu ra có thể cấu hình: Đường dẫn đầu ra linh hoạt thông qua các biến môi trường cho các kịch bản triển khai khác nhau. Độ phân giải có thể tùy chỉnh: Độ phân giải ô có thể điều chỉnh. Tạo thế giới hoàn chỉnh: Tạo toàn bộ mã ì mà không gặp rắc rối ngay từ đầu.

## 🔑 Mapbox API Key
Đăng ký tài khoản tại MapBox (https://console.mapbox.com/). Lưu ý từ 2026, người dùng cần chuẩn bị thẻ Visa để cung cấp thông tin thanh toán cho trang web. Dĩ nhiên bạn sẽ không bị trừ tiền nếu tài nguyên bạn sử dụng không vượt quá plan miễn phí đã được cung cấp.

## 🔗 Ref
## Key Links

* [Documentation/Website](https://github.com/saiaravind19/gazebo_terrain_generator)
