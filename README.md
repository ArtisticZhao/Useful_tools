# 一些脚本工具, 主要是Python写的

## 1. 龙江数据库导出工具
将elasticsearch导出的json文件, 转换为xlsx文件  
#### 解决的问题:  
- 打开含有中文的文本文件
- 写入xlsx
- 将UTC时间戳转换为北京时间的格式化时间
- 将字符串化的bytes 还原成bytes
- bytes格式化 16进制输出 (e.g. b'\xaa\cc' AA CC)