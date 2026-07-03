# How to Block Website
---
Open with notepad as admin 
```cmd
C:\Windows\System32\drivers\etc\hosts
```
Add
```cmd
127.0.0.1   example.com
127.0.0.1   www.example.com
```
This will redirect to localhost  
Or add
```cmd
0.0.0.0   example.com
0.0.0.0   www.example.com
```
This will redirect to nothing.
