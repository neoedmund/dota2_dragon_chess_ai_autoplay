# dota2_dragon_chess_ai_autoplay
Dota2 minigame dragon chess AI autoplay helper (刀塔倾天之战第三幕小游戏神龙象棋AI自动辅助)

## How to use it
* open dota2 in windows mode with 1600x900, put window on left top.
* unpack zip file download from release section and unpack and run the `run_win.cmd` in it
* start the minigame and make sure the dota2 window is not covered by other window
* AI will play it.

### troubleshooting
* Align your Dota2 window with the red-cross, just like the picture below.
* If you use desktop scaling of Windows usually on some large screen, reset it to 100% for this tool to function.
* If you use multi-screen, put Dota2 window on the first screen.
* dota2 render quality setting to max
  
## How to use it (chinese 中文)

用法:
* 打开 dota2，设置用窗口模式，1600x900分辨率, 把dota2窗口放在左上角。
* 下载 安装包 zip文件，解压到任意目录,运行其中的 `run_win.cmd` 
* 开始小游戏。注意不要让dota2窗口被遮挡。
* AI 自动开始表演。
* 如有问题请截图告知详情。

常见问题:
* 现在实时显示截图，如果框子没对准，可以微调dota的窗口位置
* 大屏的话注意缩放比改成100%
* 双屏的话dota放在第一个屏幕
* 设置dota2画质最高

按图校准:

[![c](https://github.com/neoedmund/dota2_dragon_chess_ai_autoplay/raw/main/mark1.webp)]

[![Watch the video](https://img.youtube.com/vi/-MnfqQkg9HA/0.jpg)](https://youtu.be/-MnfqQkg9HA)
录像是早期版本，目前实力已增强。


## 故事(The story)

首先游戏必须好玩才有必要。

AI在这方面有优势，看清楚图案只需要0.001秒，然后向前推算4步，找出最优解，也只是1秒内的事情。。

所以我写了AI但是看不懂它的意图，只是肉眼可见的强大，常态是3-5-3-5，然后5的多了，导致全屏连锁爆炸。

3的时候就是有意识的创造出5。而且看4步的话，能让5个次数更多。
