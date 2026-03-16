# Meow
- misconfiguration 造成 telnet 可以匿名登入且為root權限(靶機為刻意設計)
現在都使用OpenSSH
- ls -l 允許read
# Cap
- nmap -sC -sV ip 找TCP port
- browser 打ip，snapshot後URL改變
- 修改URL參數發現其他user packet
- download PCAP file
- 用Wireshark發現用FTP傳輸敏感資料
- nmap 顯示22port為Openssh
- ssh username@pw 遠端連線target host
- home 找到 nathan folder 裡面有user.txt
- getcap -r /usr/bin 發現python3.8可以root privilege
- 進入python3.8 修改uid 執行/bin/bash
