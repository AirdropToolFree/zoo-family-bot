# Tool Auto ZOO FAMILY sử dụng Node.js (Hỗ trợ cả Không có Proxy và Proxy)

## Mô tả
Auto ZOO FAMILY là một tập lệnh được phát triển bằng Node.js để tự động hóa các tác vụ trong trò chơi BIRDS. Công cụ này cung cấp các tính năng chính sau:

- ✔️ Auto cho thú ăn
- ✔️ Auto task
- ✔️ Auto mua animal
- ✔️ Auto điểm danh

## Yêu cầu

- Node.js phải được cài đặt trên hệ thống của bạn.

## Hướng dẫn cài đặt

1. **Cài đặt các mô-đun cần thiết**
Chạy lệnh sau để cài đặt các mô-đun Node.js cần thiết:
   ```bash
   npm install
2. **Tạo tệp dữ liệu**
Tạo hai tệp có tên data.txt và proxy.txt:

- data.txt:
   - Tệp này phải bao gồm định dạng query_id=xxx hoặc user=xxxx
- proxy.txt (Chỉ tạo nếu sử dụng nhiều tài khoản):
   - Định dạng proxy phải là: http://user:pass@ip:port
   - Nếu bạn chỉ sử dụng một tài khoản, không cần tạo tệp này.
## Chạy tool

- Nếu không sử dụng proxy, hãy chạy lệnh sau:
   ```bash
   node zoo.js
- Nếu sử dụng proxy, hãy chạy lệnh:
   ```bash
   node zoo-proxy.js
## Lưu ý
- [Đăng ký ZOO FAMILY](http://t.me/zoo_story_bot/game?startapp=ref1288479303)

## Định dạng tệp
- Định dạng tệp data.txt:

   ```bash
   query_id=xxx
- hoặc

   ```bash
   user=xxxx
- Định dạng tệp proxy.txt (nếu sử dụng proxy):

   ```text
   http://user:pass@ip:port
