这里是GPT-SoVITS的使用教程

[GPT-SoVITS项目地址](https://github.com/RVC-Boss/GPT-SoVITS)

[GPT-SoVITS官方教程地址-更加详细配图](https://www.yuque.com/baicaigongchang1145haoyuangong/ib3g1e)


使用教程-口述
 
  1.下载GPT-SoVITS的仓库代码
    [下载地址-github]([https://github.com/RVC-Boss/GPT-SoVITS](https://github.com/RVC-Boss/GPT-SoVITS/archive/refs/heads/main.zip))

  2.下载整合包
    [下载地址1-百度网盘-限速](https://pan.baidu.com/share/init?surl=OE5qL0KreO-ASHwm6Zl9gA&pwd=mqpi)
    [下载地址2-123云盘-不限速](https://www.123pan.com/s/5tIqVv-GVRcv.html)
  
  3.下载完整合包后 安装整合包内的 VisualStudioSetup.exe 安装的时候弹出的窗口 勾选 【使用C++的桌面开发】 然后点击右下角安装

  4.将整合包内的文件夹里面的文件 全选 拖拽解压到 GPT-SoVITS的仓库代码下进行覆盖  [我不知道什么是仓库代码?](https://github.com/haxyyx/haxyyx-smallitems/tree/2f070d22ea58af232d2cab44ea78e6c4efe25769/AI/%E5%A3%B0%E9%9F%B3%E5%85%8B%E9%9A%86/GPT-SoVITS#7)

  5.点击 更新后运行我更新依赖.bat

  6.点击go-webui.bat 等待网页自动出现 在不使用之前都不要关闭命令行窗口  [我报错了怎么办?-点击这里然后按下ctrl+F 然后输入报错查找](https://www.yuque.com/baicaigongchang1145haoyuangong/ib3g1e/pgah3gvetrdy8ryt)
  
  7.把 *.pth（ *.pth代表了任意名字的pth文件） 也就是模型文件放到 \GPT-SoVITS\SoVITS_weights 文件夹里面
  
  8.把 *.ckpt 也就是GPT文件放到 \GPT-SoVITS\GPT_weights 文件夹里面

  9.回到网页  [我不到它了-点击回到那个网页-前提是你打开了go-webui.bat](http://localhost:9874/)
  
  10.点击上面三个的 1-GPT-SoVITS-TTS

  11.点击下面的 1C-推理
  
  12.点击刷新模型路径

  13.修改GPT模型列表下面的窗口为自己想用的模型  SoVITS模型列表同理

  14.勾选 是否开启TTS推理WebUI 的方框

  15.等待页面出现  [我不小心关闭了它-点击此处回到-前提是你打开它了](http://localhost:9872/)

  16.确保上面的模型列表下面的列表选择的是你想用的模型
  
  17.放入参考音频-且大于3秒小于10秒 必填

  18.输入参考音频的文本 也就是 音频里面的人物说了什么话 翻译出来 如果听不懂人物说了什么 就勾选参考文本上面的开启无参考文本模式 让GPT来自己理解他说了什么

  19.把你想让模型说的话放到下面的 需要合成的切分前文本 按需求点击右边的按钮 切分

  20.在需要合成的文本里面输入你想生成的话或切分好的文本

  21.尽情合成
