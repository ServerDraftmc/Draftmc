# Draftmc

```bash
./start.sh
```

Nếu bạn lỡ Ctrl + Z hãy làm như sau : 
- ghi trên terminal : ps aux | grep java - rồi tìm id của dòng java -Xmx16G -Xms4G -jar server.jar --nogui 
- Vd khi thực hiện lệnh trên : 
\n codespa+   *32776*  129 17.2 21132176 2826792 pts/0 Sl  01:33   2:05 java -Xmx16G -Xms4G -jar server.jar --nogui
\n codespa+   33920  0.0  0.0   8172  2304 pts/0    R+   01:35   0:00 grep --color=auto java
id sẽ là 32776
- rồi ghi kill -9 <ID>
- bật server lại thôi
