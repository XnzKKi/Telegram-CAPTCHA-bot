# Telegram-CAPTCHA-bot

一个用于验证新加入群员是否为真人的 bot 。

原项目地址：https://github.com/lziad/Telegram-CAPTCHA-bot

本项目由 [@TH779](https://t.me/TH779) 修改并发布。

## 安装、配置及使用方法

⒈向 [@BotFather](https://t.me/BotFather) 申请一个 bot ，并将 bot api token 复制。
</br>⒉在服务器上安装 python-telegram-bot ： `pip3 install --upgrade python-telegram-bot` 。
</br>⒊clone 并打开本项目： `git clone https://github.com/XnzKKi/Telegram-CAPTCHA-bot.git && cd Telegram-CAPTCHA-bot` 。
</br>⒋将项目下 config.json 里的 token 字符串修改为第一步所获取到的 bot api token ，除此之外你也可以修改里面的配置选项。
</br>⒌按照注③修改 Telegram-CAPTCHA-bot.service ，修改好后将其移动到 `/etc/systemd/system`
</br>⒍输入 `systemctl start Telegram-CAPTCHA-bot` 即可运行 bot 。

注:
   </br>① 请在你的server中增加<b>中文语言包</b>
   </br>② 查看Bot运行日志:`systemctl status Telegram-CAPTCHA-bot`
   </br>③ `WorkingDirectory` 设置为机器人源码目录 `ExecStart `为pythone3库(一般默认就行)
   
## 开源协议

本项目使用 MIT 许可协议发布。
