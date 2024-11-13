# my ss

懂得的都懂


封装docker运行,更方便


```
docker run 
-p 1080:1080
-e SERVER_ADDR=地址
-e SERVER_PORT=端口
-e PASSWORD=密码 
-e METHOD=加密方式
msl
```

密码和加密方式都有默认值，在运行容器的时候显示