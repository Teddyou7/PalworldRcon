这是一个专门为《Palworld》游戏适配的Rcon连接工具，基于mcrcon项目进行二次开发。本工具提供了一个简便的方式来发送Rcon命令到Minecraft服务器。

感谢[mcrcon](https://github.com/Tiiffi/mcrcon)项目，以及GPT-4.0。

## GCC
```
gcc -o PalworldRcon PalworldRcon.c -std=gnu99
```

## 使用方法
```
./PalworldRcon -H127.0.0.1 -P25575 -p"your_passwd" "ShowPlayers" ok
```

