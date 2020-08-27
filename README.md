# 血小板以及pio（随机换装）模型

### 模型下载

自行整理的，修改了血小板的事件触发范围，以及pio的随机换装。有需要的朋友可以下载使用。

演示地址： [www.litblc.com/archives/722][1]

### 使用方式

 - 参考demo.html,将需要的文件引入
 - 注意引入路径，按照实际情况修改（注意waifu.js中的message.json路径也要修改）
 - 如果出现进入新页面canvas错乱的问题，查看是否使用了pjax，不支持
 - 自行修改message.json

### 注意事项
 - 很多朋友反馈 按照demo的来最后只显示血小板3个字，文本框里也空空的，注意当屏幕小于860px宽度时候会自动隐藏模型，具体修改在 `live2d/css/waifu.css`的`71`行

  [1]: https://www.litblc.com/archives/772.html
