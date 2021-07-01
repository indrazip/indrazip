- 👋 Hi, I’m @indrazip
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
indrazip/indrazip is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
sudo apt-get update
sudo apt-get install xrdp
sudo systemctl enable xrdp
sudo apt-get install xfce4 xfce4-terminal
sudo sed -i.bak '/fi/a #xrdp multiple users configuration n xfce-session n' /etc/xrdp/startwm.sh
sudo ufw allow 3389/tcp
sudo /etc/init.d/xrdp restart
wget https://bin.equinox.io/c/4VmDzA7iaHb/ngrok-stable-linux-amd64.zip
unzip ngrok-stable-linux-amd64.zip
./ngrok authtoken 1ujauNt1F6lUE1ACoGN90s2smOZ_5r7NqLG9FXNAGhmJvdkQk
passd
./ngrok tcp 3389
