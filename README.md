# gift-to-lover

程序猿(媛)/极客/理工男(女)们，献给爱人的DIY礼物。

## 功能

全屏以幻灯片模式显示一系列图片，并循环播放背景音乐。

目前默认的图片是来自电影的男女主角说“我爱你”的截图。默认的背景音乐是一些经典的中文情歌。

当然，此项目不仅仅可以用于表白，还可以用作生日礼物、圣诞礼物等等——只需要更换合适的图片和背景音乐，定制合适的字幕。

各位同学若对此项目有任何意见或建议，请在 issue 中和我讨论。

另，征集电影截图，以及背景音乐。有推荐的电影或音乐也请提在 issue 中，谢谢！

## 演示

参见[演示页面](http://haixing-hu.github.io/gift-to-lover/demo/index.html)

## 使用方法

- check out 这个代码库；如果不会用git，也可以直接下载整个代码库的压缩包然后解压；
- 按需要，修改 `src/config.js` 文件中的配置；文件中有中文注释，很容易看懂；
- 打开 `src/index.html` 网页可以看到效果

## 支持的浏览器

支持Firefox，Chrome，Safari的最新版，以及其移动版本；IE暂不支持全屏。

建议使用最新版的Chrome以获得最佳的浏览效果。

## 计划

- [x] 加入背景音乐播放功能；
- [x] 加入全屏显示功能（是指将整个浏览器页面全屏，隐藏浏览器窗口）；
- [ ] 电影截图不够清晰，需要重新选择高清的、无水印的电影截图；
- [ ] 需要调整电影截图的播放顺序；
- [ ] 开头增加一些字幕，描述一下礼物献给的对象以及其他一些要对她/他说的话；
- [ ] 定制第一张幻灯片和最后一张幻灯片中的字幕，打算最后一张显示大话西游的那段经典台词，并且播放那首《一生所爱》；
- [ ] 最后增加一个可选的致谢字幕，向项目的资源提供者表示感谢；
- [ ] 制作脚本一键发布项目到某些常见的个人网站（比如发布到自己的github page上）；
- [ ] 制作脚本将项目打包为成苹果、安卓的手机应用；
- [ ] 支持i18n，让歪果的程序猿也能用得上；

## 致谢

此项目，使用了下述朋友们提供的资源和代码，在此一并表示感谢！

- 项目的灵感以及最初的电影截图来自于 @陈弈飘 同学在知乎上的下面这个答案：
  http://www.zhihu.com/question/21682442/answer/36924153?group_id=636890926812016640
- 幻灯片播放代码来自于 Jay Salvat 的 vegas 项目：
  https://github.com/jaysalvat/vegas
- 音乐播放代码来自于 Jay Salvat 的 buzz 项目：
  https://github.com/jaysalvat/buzz
- 整体的设计思路来自于这篇 Jay Salvat 的这篇博文：
  http://tympanus.net/codrops/2011/07/05/fullscreen-slideshow-with-html5-audio/
- 全屏显示的代码来自于下面的博文：
  http://johndyer.name/native-fullscreen-javascript-api-plus-jquery-plugin/

## 协议

本项目的代码遵循 [GNU General Public License v3.0](http://www.gnu.org/licenses/gpl.html)

本项目用到的各类图片，音乐资源收集自网络，仅供个人使用。若无意中侵犯了您的版权，请与项目作者联系，我会立即将其删除。
