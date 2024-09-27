# 120FPS Maker
termux-setup-storage
pkg update && pkg upgrade -y
pkg install git -y
git clone https://github.com/coderduc/120Maker
cd 120Maker
chmod +x setup 120Maker
bash setup
./120Maker
