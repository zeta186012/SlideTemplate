# 合肥工业大学在线幻灯片模板

本模板参考了 [TonyCrane 的幻灯片模板仓库](https://github.com/TonyCrane/slide-template)，在此基础上进行了定制化改进：

- 融合了蒋炎岩老师的设计风格
- 增添了与合工大相关的图标
- 调整了 CSS 中的字体与配色方案使其适配合工大的主色调


## 使用方法

使用Makefile来进行操作，具体的Makefile可参考src/文件夹中的内容，你可以自己进行定制。

1. 首先你需要安装`reveal-md`
```
npm install -g reveal-md
```

2. 然后开启本地实时预览
```
make live
```

3. 构建静态文件，输出到site文件夹中
```
make build
```

4. 生成pdf文件，需要在浏览器的地址栏后面加入`?print-pdf`然后使用浏览器打印即可。


