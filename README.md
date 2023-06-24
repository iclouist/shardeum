**Hướng Dẫn Chạy Shardeum**
Một số link hữu ích
1. Website :https://shardeum.org/
2. Twitter : https://twitter.com/shardeum
3. Discord : https://discord.gg/shardeum
4. Faucet Token SHM : https://faucet-sphinx.shardeum.org/
5. Tokenomics : https://shardeum.org/shm-tokenomics/Parameters

BẮT ĐẦU : 
1. ĐĂNG NHẬP VPS
2. TẠO SESSION BẰNG TMUX : `tmux new -s shardeum`
3. Cài đặt Curl: `sudo apt-get install curl`
4. Update package: `sudo apt update`
5. Cài đặt docker : `sudo apt install docker.io` =>  `docker --version`
6. Cài đặt docker-compose :
- `sudo curl -L "https://github.com/docker/compose/releases/download/1.29.2/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose`
- `sudo chmod +x /usr/local/bin/docker-compose`
- `docker-compose --version`
7. Download bộ cài Node
  `curl -O https://gitlab.com/shardeum/validator/dashboard/-/raw/main/installer.sh && chmod +x installer.sh && ./installer.sh`
8. Chọn yes hết , rồi nhập mật khẩu nhớ lưu mật khẩu lại
 ![image](https://github.com/iclouist/shardeum/assets/116245100/db38328c-7d0d-453c-8d5c-615f31da0b0b)
9. Sau khi cài đặt xong đăng nhập vào dashboard của node
**  <Your_VPS_IP>:8080**
  Sau đó nhập mật khẩu đã tạo
10. Quay lại terminal
-  `cd`
- `cd .shardeum`
- `./shell.sh`
- `operator-cli gui start`
- `operator-cli gui status`
11. Faucet token test SHM tại discord hoặc link faucet ở trên, sau khi đã có token test thì stake vào node
  Cần stake tối thiểu 10 SHM
  ![image](https://github.com/iclouist/shardeum/assets/116245100/3f855f83-2ad3-41c1-92aa-2608a9a70ff4)

  Link tham khảo : https://docs.shardeum.org/node/run/validator

