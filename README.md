# VPN Remote Access – RRAS | thatccna.isa

## 🎯 Mục tiêu
Triển khai VPN Server cho user domain truy cập tài nguyên nội bộ từ ngoài mạng.

## 🧱 Mô hình
- Domain: thatccna.isa
- DC: 192.168.189.10
- VPN + File Server: 192.168.189.20
- VPN Client: External network (VMnet8)

## ⚙️ Các bước triển khai

### 1️⃣ Cài đặt RRAS
![RRAS Install](images/rras-install.png)

### 2️⃣ Enable VPN
![RRAS Enabled](images/rras-enabled.png)

### 3️⃣ Cấu hình IP Pool
![IP Pool](images/ip-pool.png)

### 4️⃣ Allow user Dial-in
![Dial-in](images/dial-in.png)

### 5️⃣ Tạo VPN Client
![VPN Client](images/vpn-client.png)

### 6️⃣ VPN Connected
![VPN Connected](images/vpn-connected.png)

### 7️⃣ Truy cập LAN qua VPN
![Access LAN](images/access-lan-over-vpn.png)

## ✅ Kết quả
User domain kết nối VPN thành công và truy cập được tài nguyên nội bộ.
