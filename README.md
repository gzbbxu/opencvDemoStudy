### 环境搭建

1. 下载 https://blog.csdn.net/qq_26877377/article/details/79844947
2. 解压配置环境变量 E:\opencv\build\x64\vc14\bin
3. vs 视图->其他窗口->属性管理器  Microsoft.Cpp.x64.user 右键
   - vc++ 目录配置 包含目录  E:\opencv\build\include\opencv E:\opencv\build\include\opencv2   E:\opencv\build\include 
   - 库目录 	E:\opencv\build\x64\vc14\lib  
   - 链接器 ->输入 配置附件依赖项 opencv_world310d.lib  重启 vs

