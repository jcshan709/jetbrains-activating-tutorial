> Language select: English | [中文](https://github.com/jcshan709/jetbrains-activating-tutorial/tree/main/README_zh.md)  
# JetBrains Activating Tutorial
### Step 1 - Look up JetBrains License Server
1. Visit [Censys Search](https://search.censys.io/)  
2. Input the text below and search:
   ```plain
   services.http.response.headers.location: account.jetbrains.com/fls-auth
   ```  
3. Find a site open on port 80. Click and have a check whether the status code is **302**. If not, find another one.

![looking up for license servers](https://github.com/user-attachments/assets/d273115b-887e-48ba-9367-376d43a042fe)
![checking whether status is 302](https://github.com/user-attachments/assets/a2cebd5e-0c71-4cca-80b7-84178bbd14cf)

### Step 2 - Activate your IDE
1. Launch your IDE and select `License Server` in activating page.  
2. Copy the address, including protocol (`http://`) (do not include port) and click `Activate`
3. The same to JetBrains Plugins like `Code With Me`
4. If activating failed, find another server and have a try.

![activating](https://github.com/user-attachments/assets/e36a4dd0-964a-4fd6-b993-443e05f42393)  
![activated](https://github.com/user-attachments/assets/0391245c-c324-40f6-981d-02b2d98f662b)
