Language select: English | [中文](https://github.com/jcshan709/jetbrains-activating-tutorial/tree/main/README_zh.md)  
# JetBrains Activating Tutorial
### Step 1 - Look up JetBrains License Server
1. Visit [Censys Search](https://search.censys.io/)  
2. Input the text below and search:
   ```plain
   services.http.response.headers.location: account.jetbrains.com/fls-auth
   ```  
3. Find a site open on port 80. Click and have a check whether the status code is `302`. If not, find another one.
4. Launch your IDE and select `License Server` in activating page.  
5. Copy the address, including protocol (`http://`) (do not include port) and click `Activate`
6. The same to JetBrains Plugins like `Code With Me`
7. If activating failed, back to step 3.  
![image](https://github.com/user-attachments/assets/e36a4dd0-964a-4fd6-b993-443e05f42393)
