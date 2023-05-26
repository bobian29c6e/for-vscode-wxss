# vscode-wxss
关于用vscode打开微信小程序项目时无法识别和使用wxss文件

需要“ctrl + shift + p”搜索“setting.json”，选择“首选项：打开工作区设置(JSON)”会创建一个空白json文件，将一下代码添加进即可

```
{
    "files.associations": {
        "*.wxml": "html",
        "*.wxss": "css",
    }    
}
```
