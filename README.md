

## 新增
- 对返回路径正则匹配
- 增加自定义前缀

## 建议使用方式
打开 vscode 

通过vsix[文件](https://github.com/zxsos/vscode-img-fast/releases/download/vscode-img-fast-1.0.4/vscode-img-fast-1.0.4.vsix)安装

配置如  
![image](https://github.com/user-attachments/assets/b87857c9-d83f-4e56-840c-5d02084d90ed)


Ctrl+Shift+P 进入 keybindings.json  

![快捷方式](https://zxsos.pages.dev/file/pic/1747486818389_20250517210011244.webp)  
添加如下命令到 [ ] 中
```json 
  {
    "key": "ctrl+v",
    "command": "img-fast.upload",
    "when": "editorTextFocus && editorLangId == 'markdown'"
  }
```

