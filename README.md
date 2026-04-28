# LAN Network Simulation

Dự án mô phỏng hệ thống mạng LAN sử dụng Cisco Packet Tracer.

## 📖 Giới thiệu

Dự án này mô phỏng một hệ thống mạng doanh nghiệp nhỏ với:
- Định tuyến động OSPF
- Firewall ASA
- Mô hình DMZ
- Phân chia vùng mạng (inside, outside, DMZ)

Mục tiêu: hiểu và triển khai các cơ chế bảo mật và định tuyến trong mạng thực tế.

## 🛠️ Công nghệ

- Cisco Packet Tracer
- OSPF Routing Protocol
- ASA Firewall
- ACL

## 📂 Cấu trúc

- `LAN-System.pkt`: File mô phỏng mạng

## ⚙️ Cách sử dụng

1. Mở file `LAN-System.pkt` bằng Cisco Packet Tracer
2. Kiểm tra cấu hình các thiết bị:
   - Router
   - ASA Firewall
3. Test kết nối:
   - Ping giữa các mạng
   - Kiểm tra NAT và ACL

## 📸 Demo

![Topology](images/topology.png)

## 📌 Kiến thức đạt được

- Hiểu cách hoạt động của OSPF
- Cấu hình ASA Firewall cơ bản
- Thiết kế mạng có DMZ
- Áp dụng ACL trong thực tế

## 🧠 Hướng phát triển

- Thêm VPN site-to-site
- Triển khai IDS/IPS
- Mô phỏng mạng lớn hơn
