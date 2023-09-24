**Nodejs_Internet_Deployment**
Public

**Hướng dẫn deploy ứng dụng Node JS:**
- Deploy trên local: Mở VS Code ngay tại thư mục gốc của project, mở terminal và nhập `npm install` (Lưu ý: Phải cài đặt Node JS trên máy trước), chờ vài phút và nhập `npm start`, ứng dụng sẽ được chạy trên local với port 3000 (http://localhost:3000/).

  
- Deploy trên Internet: Clone 1 Node JS App Repository về, kết nối tài khoảng Render.com với Github, tạo Web Service trên Render.com và dùng Repository đã clone để build. Điền theo như thế này:
+ Name: URL muốn tạo.
+ Root Directory: .
+ Runtime: Node
+ Build Command: npm install
+ Start Command: node index.js
  Bấm tạo và chờ vài phút là có thể truy cập trang web.
