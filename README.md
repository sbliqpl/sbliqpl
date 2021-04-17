- 👋 Hi, I’m @sbliqpl
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
sbliqpl/sbliqpl is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
### 1.  安装

`sudo apt install ssh`

### 2.  创建目录权限

`mkdir ~/.ssh && chmod 700 .ssh`

### 3. 生成RSA秘钥

`ssh-keygen -t rsa -C "your_email@example.com"`

### 4. 将key添加到ssh-agent中

`eval "$(ssh-agent -s)"`
`ssh-add ~/.ssh/id_rsa`
