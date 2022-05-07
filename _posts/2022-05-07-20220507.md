## GitHub Desktop之clone时报错处理

#### 1. 报错Failed to connect to github.com port 443:connection timed out

打开Git Bash，输入以下

```
git config --global http.proxy http://127.0.0.1:1080
git config --global https.proxy http://127.0.0.1:1080
```

取消代理

```
git config --global --unset http.proxy
git config --global --unset https.proxy
```

小结：切换到全局，然后取消全局代理



#### 2. 报错OpenSSL ssL_read:Connection was aborted,errno 10053

原因1：网络不稳定，或者更改网络认证设置

```
git config http.sslVerify "false"
```

原因2：Git默认限制推送的大小，更改限制大小

```
git config --global http.postBuffer 524288000
```



