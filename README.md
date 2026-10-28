# h2-rapid-reset-labtainer
Bài thực hành Labtainer: Tấn công HTTP/2 Rapid Reset và cạn kiệt tài nguyên stream (CVE-2023-44487)
## Cài đặt và thực hành:
cd ~/labtainer/labtainer-student
imodule https://raw.githubusercontent.com/ngdung-0405/h2-rapid-reset-labtainer/main/h2-rapid-reset.tar.gz
labtainer h2-rapid-reset
Các lệnh trong bài lab:
target-web: ./run_target.sh
sec-gateway: ./run_gateway.sh (chế độ lỗi) hoặc ./run_gateway_secure.sh (chế độ bảo mật)
victim: python3 victim_client.py
attacker-web: python3 attack_rapid_reset.py
Đánh giá tự động: checkwork 
