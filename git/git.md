# 一、git简介

# 二、git安装

# 三、git常用命令

# ?、报错

1. **OpenSSL SSL_read: Connection was reset, errno 10054**

   在工程的.git文件夹下的config文件末尾添加：

   ```tex
   [http]
    
    sslverify = false
   
   [https]
   
    sslverify = false
   ```

2. **Failed to connect to github.com port 443 after 21084 ms: Timed out**

   连接到github超时了，原因可能是代理除了问题，删除全局配置就可以解决：

   ```git
   git config --global --unset http.proxy
    
   git config --global --unset https.proxy
   ```

3. 