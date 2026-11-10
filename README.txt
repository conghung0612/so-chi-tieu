SO THU CHI - ANDROID

Dự án Android Studio, ứng dụng offline.

CÁCH TẠO APK:
1. Cài Android Studio bản mới trên máy tính.
2. Giải nén SoThuChiAndroid.zip.
3. Android Studio > Open > chọn thư mục SoThuChiAndroid.
4. Chờ Gradle Sync hoàn tất. Nếu được hỏi, cài Android SDK Platform 35 và dùng JDK 17.
5. Chọn Build > Build Bundle(s) / APK(s) > Build APK(s).
6. APK debug được tạo tại:
   app/build/outputs/apk/debug/app-debug.apk
7. Chép APK sang điện thoại Android và mở để cài. Có thể cần cho phép cài ứng dụng từ nguồn này.

TÍNH NĂNG:
- Lưu từng tháng tự động bằng localStorage trên thiết bị.
- Thêm/xóa/sửa khoản chi; tính tổng và số dư.
- Quy đổi số dư sang VND theo tỷ giá nhập thủ công.
- Sao lưu tất cả tháng ra file JSON và khôi phục từ file.
- Hoạt động offline, không yêu cầu quyền Internet.

LƯU Ý:
- Dữ liệu nằm trên điện thoại. Hãy dùng Sao lưu file định kỳ và giữ file JSON ở nơi an toàn.
- Đây là mã nguồn dự án để build APK bằng Android Studio; môi trường hiện tại không có Android SDK/Gradle nên chưa thể biên dịch APK trực tiếp tại đây.
