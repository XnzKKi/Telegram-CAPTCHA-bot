# Telegram-CAPTCHA-bot

一个用于验证新加入群员是否为真人的 bot 。

原项目地址：https://github.com/lziad/Telegram-CAPTCHA-bot

本项目由 [@TH779](https://t.me/TH779) 修改并发布。

## 安装、配置及使用方法

1. 向 [@BotFather](https://t.me/BotFather) 申请一个 bot ，并将 bot api token 复制。
2. 在服务器上安装 python-telegram-bot ： `pip3 install --upgrade python-telegram-bot` 。
3. clone 并打开本项目： `git clone https://github.com:XnzKKi/Telegram-CAPTCHA-bot.git && cd Telegram-CAPTCHA-bot` 。
4. 将项目下 config.json 里的 token 字符串修改为第一步所获取到的 bot api token ，除此之外你也可以修改里面的配置选项。
5. 按照注释修改 Telegram-CAPTCHA-bot.service ，修改好后将其移动到 /etc/systemd/system 下(最好把文件“#”给去掉哦)
6. 输入 `systemctl start Telegram-CAPTCHA-bot` 即可运行 bot 。

## 开源协议

本项目使用 MIT 许可协议发布。
