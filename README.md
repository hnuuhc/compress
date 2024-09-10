文件压缩工具
=========

### 说明:

一个简单的压缩工具封装

1.支持密码  
2.支持单文件添加删除

### 简单示例:

```
ZipUtil.origin(file).passwd("123456").compress(file); // 文件压缩  

ZipUtil.origin(file).charset("GBK").deCompress(folder); // 文件解压
```

## 鸣谢

感谢[**JetBrains**](https://www.jetbrains.com/zh-cn/community/opensource/#support)提供的开源开发许可证，JetBrains 通过为核心项目贡献者免费提供一套一流的开发者工具来支持非商业开源项目。

[<img src="https://www.jetbrains.com/icon.svg" width="200"/>](https://www.jetbrains.com/zh-cn/community/opensource/#support)
