> Language select: [English](https://jcshan709.github.io/jetbrains-activating-tutorial) \| 中文  

# JetBrains全家桶激活教程
### Step 1 - 查找许可证服务器
1. 访问 [Censys Search](https://search.censys.io/)  
2. 搜索以下内容：
   ```plain
   services.http.response.headers.location: account.jetbrains.com/fls-auth
   ```  
3. 找一个开放了80端口的站点，且80端口的状态码为**302**
 
![looking up for license servers](https://github.com/user-attachments/assets/d273115b-887e-48ba-9367-376d43a042fe)
![checking whether status is 302](https://github.com/user-attachments/assets/a2cebd5e-0c71-4cca-80b7-84178bbd14cf)

### Step 2 - 激活IDE
1. 打开你的IDE，在激活界面选择许可证服务器  
2. 复制你刚刚找到的地址（带上`http://`前缀，不要带端口）
3. 用同样方法也可激活`Code With Me`等付费插件
4. 激活失败的话再重新找个服务器试试

![activating](https://github.com/user-attachments/assets/e36a4dd0-964a-4fd6-b993-443e05f42393)  
![activated](https://github.com/user-attachments/assets/0391245c-c324-40f6-981d-02b2d98f662b)
