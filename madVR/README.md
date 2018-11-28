# madVR 汉化插件

版本号：2

首发于VCB-S<br>
http://bbs.vcb-s.com/thread-3892-1-1.html<br>
<br>
by revar<br>
<br>
## 重大更新于2018年11月29日 06:55:11，几乎完全重新汉化了一遍，请之前下载使用过的务必进行此次更新<br>
<br>

<br>
该汉化补丁对应madVR目前最新版本V0.92.17<br>
内有【原文件】，【硬汉化】，【软汉化】三个文件夹<br>
近完全汉化，保留了部分术语，汉化率高于90%<br>
如果仍遇到汉化文本错误或不合理的地方，欢迎大家进行反馈，[点我进入翻译记忆文件](https://github.com/revaraver/Soft-CHS/blob/master/madVR/madVR.CHS/EN%20to%20CH.txt "点我进入翻译记忆文件")，可以结合该文件进行勘误。本插件的汉化均是建立在这份文件上
<br>
<br>
[直接点击此处进行下载madVR.CHS for V0.92.17](https://github.com/revaraver/Soft-CHS/raw/master/madVR/madVR.CHS/release/V0.92.17/madVR.CHS%20for%20V0.92.17.7z "madVR.CHS for V.92.17")<br>
于2018年11月29日 06:55:11更新<br>
<br>
<br>
有两种汉化操作方法：<br>
<br>
<br>
方法一：<br>
将【软汉化】文件夹中的全部文件拷贝至madVR的安装目录下<br>
<br>
推荐该方法，没有修改原文件<br>
<br>
<br>
若方法一没有实现汉化，则使用方法二:<br>
方法二：<br>
1.删除madVR目录下对应的三个后缀为【CH】的文件（若有的话）<br>
2.将【硬汉化】文件夹中的全部文件拷贝至madVR的安装目录下覆盖即可（可自行备份）<br>
<br>
<br>
恢复英文：<br>
1.删除madVR目录下对应【软汉化】中的三个后缀为【CH】的文件（若有的话）<br>
2.将【原文件】文件夹中的全部文件拷贝至madVR的安装目录下覆盖即可<br>
<br>
<br>
### 汉化补丁已更新，于2018年11月29日 06:55:11前安装插件的，可按照上述方法进行完全更新或按下述方法进行简洁更新（需配合往期任一版本汉化补丁），效果相同  
<br>
简洁更新方法：<br>

[直接点击此处进行下载更新后的madHcCtrl.CH文件](https://github.com/revaraver/Soft-CHS/raw/master/madVR/madVR.CHS/all%20files/V0.92.17/%E8%BD%AF%E6%B1%89%E5%8C%96/madHcCtrl.CH "madHcCtrl.CH")（对应软汉化），或者[直接点击此处进行下载更新后的madHcCtrl.exe文件](https://github.com/revaraver/Soft-CHS/raw/master/madVR/madVR.CHS/all%20files/V0.92.17/%E7%A1%AC%E6%B1%89%E5%8C%96/madHcCtrl.exe "2")（对应硬汉化），并与汉化方法结合使用<br>
<br>

更新历史
--
#####第二次重大更新
#####2018年11月29日 06:55:11
###喜讯
#####在插件更新过程中收到了madVR作者madshi的允许汉化的邮件，版权问题解决啦

------------

[![汉化许可](https://github.com/revaraver/Soft-CHS/raw/master/madVR/license.jpg "汉化许可")](https://github.com/revaraver/Soft-CHS/raw/master/madVR/license.jpg "汉化许可")

------------
本次更新版本：1→2<br>
old文件夹中文件命名为：<br>
\*.1.*<br>
做了好多工作，此次更新结果较为满意，可能是这个版本最后一次更新了~~还为了解释某个名词甚至去翻了GTX 1080的英文白皮书~~下面为部分修正：

1. 确定了“ringing”的翻译为“振铃”
2. 改正“default debanding strength:”的翻译由“默认debanding强度：”到“默认去色阶断层强度：”
3. 改正“activate only if it comes for free (as part of NGU sharp)”由“只在空闲时激活（作为NGU sharp的一部分）”到“只在空闲时激活（作为NGU 锐化的一部分）”
4. 改正“activate anti-bloating filter”由“激活anti-bloating过滤器”到“激活强化高频阻断低频过滤器”
5. 改正“only look at pixels in the frame center  (good for broadcasts, bad for Anime)”由“只看帧中心的像素（适合广播，不适合动漫）”到“不侦测画面四角的像素（适合画面四角有台标的TV广播，不适合动漫）”
6. 改正“processing done by GPU texture units:”由“GPU纹理单元完成的处理：”到“GPU纹理映射映射单元的工作算法：”
7. 改正“activate SuperRes filter, strength:”由“激活SuperRes过滤器, 强度:”到“激活超级锐化过滤器, 强度:”
8. 改正“present a frame for every VSync”由“为每个VSync提供框架”到“为垂直同步建立一个框架”
9. 改正“use a separate device for DXVA processing (Vista and newer)”由“使用单独的设备进行DXVA处理（Vista或更高版本）”到“分离一个设备用于硬件加速（Vista或更高版本）”
10. 改正“use a separate device for presentation (Vista and newer)”由“使用单独的设备进行演示（Vista或更高版本）”到“分离一个设备用于显示（Vista或更高版本）”
11. 改正“... after D3D presentation”由“D3D演示之后”到“Direct3D演示之后”
12. 改正“when and how shall the GPU be flushed:”由“何时以及如何刷新GPU：”到“何时刷新GPU：”
13. 改正“only if there would be motion judder without it...”由“除非没有它就会有抖动”到“选这个会有抖动时”
14. 改正“... or if the display refresh rate is an exact multiple of the movie frame rate”由“显示器刷新率是视频帧率的倍数”到“显示器刷新率是视频帧率的倍数时”
15. 改正“Error Diffusion - option 1”由“误差扩散 - 选项1”到“降低底噪 - 模式1”
16. 改正“low noise level, mild dither patterns”由“低噪音，温和的抖动痕迹”到“低噪音，有少部分抖动痕迹”
17. 改正“enable stereo 3d playback”由“启用立体声3D播放”到“启用3D播放功能”
18. 改正“disable os stereo 3d support for all displays”由“所有显示器禁用os立体声3d支持”到“禁用所有显示器的3d功能”
19. 改正“restore os stereo 3d settings when media player is closed”由“媒体播放器关闭时恢复os立体声3d设置”到“媒体播放器关闭时恢复3d设置”
20. 改正“reduce banding artifacts”由“减少条带伪影”到“减少条带”
21. 改正“reduce random noise”由“减少随机噪音”到“减少随机噪点”
22. 改正“use DXVA chroma upscaling when doing native DXVA decoding”由“在进行本机DXVA解码时使用DXVA色度增强”到“在进行硬解时使用硬件加速的色度增强技术”
23. 改正“use DXVA chroma upscaling when doing DXVA deinterlacing”由“在进行DXVA去隔行扫描时使用DXVA色度增强”到“在进行硬件去隔行扫描时使用硬件加速的色度增强技术”
24. 改正“trust DXVA color && levels conversion”由“相信DXVA的颜色和水平转换”到“相信硬件加速的色彩和码率的转换能力”
25. 改正“disable GPU gamma ramps”由“禁用 GPU gamma ramps”到“禁用 GPU gamma raps屏幕校色技术”
26. 追加翻译“LumaSharpen”到“整体锐化”
27. 追加翻译“Nearest Neighbor”到“邻近算法”
28. 追加翻译“Bilinear”到“双线算法”
29. 追加翻译“don't flush”到“不刷新”
30. 追加翻译“side-by-side”到“左右屏”
31. 追加翻译“top-and-bottom”到“上下屏”
32. 追加翻译“line alternative”到“左右交错”
33. 追加翻译“column alternative”到“上下交错”
34. 追加翻译“flush & wait (loop)”到“刷新和等待（循环）”
35. 追加翻译“strength: 25%”到“强度：25％”
36. 追加翻译“strength: 50%”到“强度：50％”
37. 追加翻译“strength: 75%”到“强度：75％”
38. 追加翻译“SuperRes”到“超分辨率”
39. 追加翻译“anti-bloating”到“强频高阻低频”
40. 追加翻译“anti-ringing”到“抗振铃”
41. 追加翻译“double again”到“加倍两次”
42. 追加翻译“DXVA2”到“硬件加速”
43. 追加翻译“DXVA”到“硬件加速”
44. 追加翻译“Bicubic60 AR Linear Ligh”到“Bicubic60 AR 线性光”
45. 追加翻译“(requires DX11 GPU)”到“（需要支持DX11的 GPU）”
46. 改正翻译“抖动模式”到“抖动痕迹”
47. 改正翻译“有色噪音”到“有色噪点”
48. 改正翻译“播放2d内容时：”到“播放2D内容时：”
49. 改正翻译“PC levels (0-255)”到“PC(0-255)”
50. 改正翻译“TV levels (16-235)”到“TV(16-235)”
......
......


------------


##### 第一次更新：
##### 2018年11月27日 14:59:08
本次更新版本：0→1<br>
old文件夹中文件命名为：<br>
\*.0.*<br>
改正优化了三处翻译错误：<br>
1. 去掉了多余的“..”翻译<br>
2. 改正“crop black bars”翻译由“黑边”至“滋养黑边（视频处理前先切除黑边）”<br>
3. 修正“zoom small black bars away”翻译为“裁剪黑边”<br>
<br>
