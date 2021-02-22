# NeteaseMusicUnlock
解锁网易云音乐vip及变灰歌曲
QuantumultX 设置

[server_remote]  
https://raw.githubusercontent.com/Corvus091/NeteaseMusicUnlock/main/unlock.txt, tag=NeteaseMusicUnlock, img-url=https://raw.githubusercontent.com/Orz-3/mini/master/Netease.png, update-interval=86400, opt-parser=true, enabled=true  

[filter_remote]  
#解锁网易云音乐  
https://raw.githubusercontent.com/Corvus091/NeteaseMusicUnlock/main/filter.list, tag=NeteaseMusicUnlock, enabled=true  

[policy]  
static=NeteaseMusicUnlock, direct, 网易云音乐解锁, img-url=https://raw.githubusercontent.com/Koolson/Qure/master/IconSet/Netease_Music.png  

[filter_local]  
host-suffix, music.126.net, direct  
