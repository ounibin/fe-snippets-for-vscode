## 目录
snippets/ 代码片段






## 打包 vscode 插件
安装打包工具
```js
npm install -g vsce
```
  

打包到本地 vsix 文件
```js
vsce package
```


发布到vscode插件市场
```js
vsce login <your-publisher-name>
vsce publish
```