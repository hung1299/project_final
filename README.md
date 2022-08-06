
# Hướng dẫn chạy


cd vào từng thư mục p3-server, p3-frontend, p3-admin rồi chạy

```bash
  npm install
```

thêm file .env vào thư mục p3-server
```bash
PORT = {cổng đầu ra của server}
NODE_ENV = development
JWT_SECRET = {secret key của jwt}
MONGO_URL =  {đường dẫn của mongodb}
PAYPAL_CLIENT_ID = {paypal client id}
```
# p3-server
chạy lệnh sau để chạy server
```bash
  npm run server
```
sau đó server sẽ chạy ở cổng 5000
```bash
  http://localhost:5000/
```
# p3-frontend
chạy lệnh sau để chạy giao diện cho client
```bash
  npm run start
```
client chạy ở cổng 3000
```bash
  http://localhost:3000/
```
tài khoản cho user đăng nhập vào client 
```bash
  user@example.com 
  123456
```
tài khoản cho user đăng nhập vào paypal sandbox để thanh toán 
```bash
  user1299@gmail.com
  user1299
```
# p3-admin
chạy lệnh sau để chạy giao diện cho admin
```bash
  npm run start
```
admin chạy ở cổng 4000
```bash
  http://localhost:4000/
```
tài khoản cho admin đăng nhập vào admin 
```bash
  admin@example.com
  123456
```