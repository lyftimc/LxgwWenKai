> **注意事项**
> - 添字请在 [Issue #33](https://github.com/lxgw/LxgwWenKai/issues/33) 反馈，字形调整请在 [Issue #14](https://github.com/lxgw/LxgwWenKai/issues/14) 反馈，不要另开议题。
> - 若需要在网站上使用这款字体，请参阅 [Issue #24](https://github.com/lxgw/LxgwWenKai/issues/24)。
> - 以 Bold 字重为基础的 [霞鹜文楷屏幕阅读版 / LXGW WenKai Screen](https://github.com/lxgw/LxgwWenKai-Screen)，PC 和 Android 手机屏幕阅读更加舒适，无需特别切换到粗体模式。另有更粗且经过手工调整的 [霞鹜臻楷 / LXGW ZhenKai](https://github.com/lxgw/LxgwZhenKai)，加粗的同时减少笔画黏连。目前正处于测试阶段，最终将做完 GB 2312 及《通用规范汉字表》。
> - 为便于开发者将字体嵌入软件中，提供 [霞鹜文楷轻便版 / LXGW WenKai Lite](https://github.com/lxgw/LxgwWenKai-Lite)。与完整版的霞鹜文楷相比，剔除一些较不常用的汉字，且不包含谚文。


# LXGW WenKai / 霞鹜文楷
An open-source Chinese font derived from Fontworks' Klee One. 一款基于 FONTWORKS 的 Klee One 的开源中文字体。  

[![开源授权](https://img.shields.io/github/license/lxgw/LxgwWenKai)](https://github.com/lxgw/LxgwWenKai)
[![最新版](https://img.shields.io/github/release/lxgw/LxgwWenKai)](https://github.com/lxgw/LxgwWenKai/releases)

## 项目简介

2020 年 12 月，日本著名字体厂商 FONTWORKS 在 GitHub 上释出了 [7 款开源日文字体](https://github.com/fontworks-fonts)，分别为 **Train、Klee、Stick、Rock-n-Roll、Reggae、Rampart 和 DotGothic16。** 7 款开源日文字体各有各的特点，而这七款字体中，字符数量最多的是 [Klee](https://github.com/fontworks-fonts/Klee)。

这是一款有着日本教科书体风格的字体，兼有仿宋和楷体的特点，可读性高。一些 DIY 字体爱好者曾先后用仿宋等字体补全这款字体，作为手机系统的美化字体移植在 iOS、Android 等手机系统中，受到很多机友的欢迎。不过这样补全的字体有一些不足之处。 **第一**，原有字体和后补字体之间有着一定的差异，致使一些不同的文字（如 Klee 原有汉字与后补简体字）混排之后会有违和感。 **第二**，由于补字所用的字体为商业版权字体，补全之后不可用于商业用途，还会有侵权的风险。此外，目前现有的开源中文字库里，楷体类寥寥无几，仿宋类则几乎没有。

鉴于此，也为了丰富开源中文字体中的楷体门类，2021 年 1 月 20 日起，本人开始了为 Klee 这一高质量的日文字体补全简繁常用字的尝试。因该字体非常适合正文阅读，命名 **「霞鹜文楷」**。由于 Klee 字体的 Regular 字重太细不太适合阅读，选取原字体 SemiBold 字重作为 Regular 字重。经过长时间的积累，目前已发展成简繁日韩均支持的 3 字重字体家族（截至 v1.111 版本）。

有关补字过程的更多信息，请参阅本人 GitHub.io 博客里的文章：[《为 Klee 试制简化字》](https://lxgw.github.io/2021/01/28/Klee-Simpchin/)。

## 字体预览

![](https://raw.githubusercontent.com/lxgw/LxgwWenKai/main/image/wenkai-1.png)

![](https://raw.githubusercontent.com/lxgw/LxgwWenKai/main/image/wenkai-2.png)

![](https://raw.githubusercontent.com/lxgw/LxgwWenKai/main/image/wenkai-3.png)

![](https://raw.githubusercontent.com/lxgw/LxgwWenKai/main/image/wenkai-4.png)

![](https://raw.githubusercontent.com/lxgw/LxgwWenKai/main/image/wenkai-5.png)

![](https://raw.githubusercontent.com/lxgw/LxgwWenKai/main/image/wenkai-6.png)

![](https://raw.githubusercontent.com/lxgw/LxgwWenKai/main/image/wenkai-7.png)

![](https://raw.githubusercontent.com/lxgw/LxgwWenKai/main/image/wenkai-8.png)

![](https://raw.githubusercontent.com/lxgw/LxgwWenKai/main/image/wenkai-9.png)

## 简要更新记录

- **2021.01.20** 着手为 Klee 增补简体字。
- **2021.02.03** 完成原有字形繁转简工作。
- **2021.02.05** 增补完 3603 简中常用字。
- **2021.02.07** 增补完 4808 繁中常用字。
- **2021.02.14** 增补完 GB2312 共 6763 个字，版本号 0.2。
- **2021.02.21** 增补完通用规范汉字表二表汉字。
- **2021.04.25** 增补完通用规范汉字表 8105 个字、GB/T 12345-90 包含的繁体字、BIG5 常用字表。
- **2021.05.05** 增补通用规范汉字表内汉字对应的繁体字或港台异体字，以及部分香港粤字，版本号 0.3。
- **2021.05.08** 开始大范围调整字形。
- **2021.06.29** 增补部分粤字、闽南语字、客家语字。
- **2021.07.13** 1.0 版发布，此后继续调整字形，但更新速度有所放缓。
- **2021.10.01** 增补完 CJK 统一汉字基本区共 20992 个字，版本号 1.100。此后分为完整版（本项目）和 [轻便版](https://github.com/lxgw/LxgwWenKai-Lite)（适用于开发者嵌入 APP），新增 [屏幕阅读版](https://github.com/lxgw/LxgwWenKai-Screen)（适用于 PC 与 Android 设备屏幕阅读）。
- **2021.10.13** 完整版（本项目）增补 2367 个常用谚文音节，实现对韩语/朝鲜语的支持，版本号 1.110。
- **2022.02.15** 1.200 版本发布。
- **2022.02.16** 1.210 版本发布，修改等宽字符。

[查看详细更新记录。](https://github.com/lxgw/LxgwWenKai/blob/main/History.md)

历史版本的 Release，请在 [Release](https://github.com/lxgw/LxgwWenKai/releases) 页面查看。

## 补字计划

### 简体部分

- [x] 原字库所含繁体字对应的简化字（仅限 GBK 范围内）；
- [x] 简体中文 3603 常用汉字 <sup>①</sup>;
- [x] 「信息交换用汉字编码字符集（GB/T 2312-80）」 6763 个汉字；
- [x] 「通用规范汉字表」8105 个汉字；
- [x] 方正、汉仪简繁字库所含汉字；
- [x] 小鹤音形输入法表外字。

**<sup>①</sup>** 包括「现代汉语常用字表」（老 3500 字）及「义务教育语文课程常用字表」（新 3500 字，《通用规范汉字表》一级字表），新老 3500 加一起共 3603 字。

### 繁体部分 

- [x] 补完繁体中文 4808 常用汉字 *（台湾地区「常用国字标准字体表」）* ；
- [x] 补完「GB/T 12345-90」6866 个汉字；
- [x] 补完 BIG5 一级（常用）汉字 5401 个；
- [x] 补完「通用规范汉字表」内汉字对应的繁体字或港台异体字；
- 补完常用粤语、闽南语、客家语用字。*（基于 [「常用香港外字表」](https://github.com/ichitenfont/suppchara)）*
  - [x] 常用香港外字表 A-C 级
  - [x] 常用香港外字表 1-2 级
  - [x] 常用香港外字表 3-4 级
  - [x] 常用香港外字表 5 级
  - [x] 台湾闽客汉字（外字表ㄅ级）
- [x] 补完 IICore 范围内 9810 个简繁汉字。

*（以上字形补完后，将覆盖完整版中机器生成的字形，Lite 版也会加入这些字。）*

### 其他
- [x] 补完 CJK 统一汉字基本区 20992 个汉字 *（深度学习生成，字形较粗糙）* ；
- [x] 补全常用谚文（韩语/朝鲜语）音节 2367 个。 *（Lite 版不加入韩语谚文）*

[点击此处查看后续加字及调整计划。](https://github.com/lxgw/LxgwWenKai/projects)

## 下载字体

1. 进入 [Release](https://github.com/lxgw/LxgwWenKai/releases) 界面下载对应版本的 TTF 格式文件。以后 TTF 文件仅在 Release 页面更新。
2. 进入 [猫啃网](https://www.maoken.com/freefonts/9704.html) 进行下载。GitHub 项目更新后，会联系猫啃网站长进行同步更新。 **注意：** 其它收录免费商用字体的网站上可能也收录了本字体，但可能不是最新版。
3. [永硕个人网盘](http://lxgw.ys168.com/)、[蓝奏云（密码：8ppk）](https://lxgw.lanzoui.com/b0cqwpt3i) 会进行同步更新。
4. 本仓库 **FCP** 文件夹内为早期增补字的 Font Creator 工程文件，包含部分笔画分离的字形，可用 Font Creator 打开查看； **MonoLatin** 文件夹用于存放「霞鹜文楷等宽」的西文字体，字体名称为 LXGW WenKai Mono Latin； **Hangul** 文件夹存放笔画分离的谚文字体 LXGW MunHae。
5. 如果您使用 macOS, 已经安装过 [Homebrew](https://brew.sh/), 可以在终端输入命令：`brew tap homebrew/cask-fonts && brew install font-lxgw-wenkai` 来安装本字体。

## 注意事项

1. 截至 [1.100 版](https://github.com/lxgw/LxgwWenKai/releases/tag/v1.100)，本字体含有全部 CJK 基本区汉字，以及少量扩展 A~G 区汉字。 **如有补字需求，请在 [Issue #33](https://github.com/lxgw/LxgwWenKai/issues/33) 提出，不要另开 Issue。** 
2. 本人并不是专业的设计师，并未考虑设计美感，所以看起来可能略丑，补进去的字与原版可能略有违和感，且在 Bold 字重中部分字的轮廓曲线会有毛刺；此外由于时间仓促，并没有多余的时间细修，部分字的部件拼接会很生硬。**如有字形优化建议，请在 [Issue #14](https://github.com/lxgw/LxgwWenKai/issues/14) 提出，不要另开 Issue。**  
*（以上两个 issue 均已加上 long term 标签，且均已在 Issues 页面置顶。）*
3. 由于原版「霞鹜文楷」Regular 字重在 PC 和 Android 屏幕上显示较细，而 Bold 字重需要在粗体模式下才能调用，特制作以 Bold 字重为基础的 [霞鹜文楷屏幕阅读版 / LXGW WenKai Screen](https://github.com/lxgw/LxgwWenKai-Screen)，加粗后的「霞鹜文楷」与 Windows 默认英文字体 Segoe UI Regular 粗细相当，PC 和 Android 手机屏幕阅读更加舒适，无需特别切换到粗体模式。
4. 另有更粗且经过手工调整的 [霞鹜臻楷 / LXGW ZhenKai](https://github.com/lxgw/LxgwZhenKai)，加粗的同时减少笔画黏连。目前正处于测试阶段，最终将做完 GB 2312 及《通用规范汉字表》。
5. 为便于开发者将字体嵌入软件中，按照 [v1.008](https://github.com/lxgw/LxgwWenKai/releases/v1.008) 的字库大小提供 [霞鹜文楷轻便版 / LXGW WenKai Lite](https://github.com/lxgw/LxgwWenKai-Lite)。与 v1.100 版本的霞鹜文楷相比，剔除 v1.100 版本增补的一些较不常用的汉字，回到过往版本的体积。若完整版有字形优化或特性更新，精简版也将会跟进。精简版不包含谚文。
6. **若需要在网站上使用这款字体，请参阅 [Issue #24](https://github.com/lxgw/LxgwWenKai/issues/24)。**
7. 对于搭配的西文字体，推荐 [Ysabeau](https://github.com/CatharsisFonts/Ysabeau) 系列字体。另有 Ysabeau Office 与霞鹜文楷轻便版的合并字体 [LXGW Bright](https://github.com/lxgw/LxgwBright)，采用 [字体合并补全工具](https://github.com/nowar-fonts/Warcraft-Font-Merger) 将两款字体合并而成，提供 TTF 和 OTF 两种格式。
8. 另，本字体也有供繁体中文用户和旧字形爱好者使用的 [繁体中文版](https://github.com/lxgw/LxgwWenkaiTC)，基于轻便版制作，采用旧字形写法，主要采用 Klee One 的隐藏字形，部分部件手动修改 *（仍有部分字形不符合旧字形写法，将会参考[一点字坊《传承字形检校表》](https://github.com/ichitenfont/inheritedglyphs)，借助[「国学迷」汉字部件查字工具](http://www.guoxuemi.com/zidian/bujian/)作进一步调整，工程量较大，需要很长时间）* 。目前已有基于 Klee One 改造的繁体中文字体 [芫荽 / Iansui](https://github.com/ButTaiwan/iansui)，采用台湾地区的「国字标准字形」，有台标字形需求的可使用「芫荽」字体。

## 协助完善

欢迎更多志同道合的朋友在此基础上继续让这款字体更臻完善，您可以通过以下方式与本人联系。

- **Telegram：** @lxgwtg
- **微信公众号：** 霞鹜 *（ID: lxgwshare）*
- **酷安：** [@落霞孤鹜lxgw](https://www.coolapk.com/u/633884)
- **微博：** [@孤鹜先森](https://weibo.com/6624339726)
- **Email：** calxgw2018@gmail.com srtong2006@126.com lxgw1999@qq.com

## 授权信息

本字体是基于 SIL Open Font License 1.1 改造的 FONTWORKS 开发并发布的 [Klee](https://github.com/fontworks-fonts/Klee) 开源项目。Klee 是 FONTWORKS 的商标。

### 许可

- 这款字体无论是个人还是企业都可以自由商用，无需付费，也无需知会或者标明原作者。 *（但如果告知，我会很感激。）*
- 这款字体可以自由传播、分享，或者将字体安装于系统、软件或APP中也是允许的，可以与任何软件捆绑再分发以及／或一并销售。
- 这款字体可以自由修改、改造，制作衍生字体。修改或改造后的字体也必须同样以 [SIL OFL](https://scripts.sil.org/OFL) 公开。

### 限制

- 在制作衍生字体时，字体名称不可使用原有字体的「保留名称」。
- 这款字体不能用于违法行为，如因使用这款字体产生纠纷或法律诉讼，作者不承担任何责任。
- 根据 [SIL Open Font License 1.1](https://scripts.sil.org/OFL) 的规定， **禁止单独出售字体文件(OTF/TTF文件)的行为。**

## 鸣谢

- [FONTWORKS 株式会社](http://fontworks.co.jp) 提供原版开源字体； [开发者 GitHub 主页](https://github.com/fontworks-fonts/)
- [@CL-Jeremy](https://github.com/CL-Jeremy)、[@夜煞之乐](https://github.com/NightFurySL2001) 为字形设计提供指导；
- [@北辰極致卑微](https://weibo.com/u/5327681980?) 协助补全字体。
- [zi2zi_pytorch](https://github.com/EuphoriaYan/zi2zi-pytorch)

## 由本字体衍生的字体

- [澳声通拼音文楷](https://github.com/jeffreyxuan/toneoz-font-pinyin-wenkai) (需配合 [选音编辑器](http://toneoz.com/ime) 使用)

## 其它项目

- [霞鹜臻楷 / LXGW ZhenKai](https://github.com/lxgw/LxgwZhenKai)
- [霞鹜新晰黑 / Lxgw New Clear Gothic](https://github.com/lxgw/LxgwNewClearGothic)
- [霞鹜漫黑 / Lxgw Marker Gothic](https://github.com/lxgw/LxgwMarkerGothic)
- [小赖字体 / Xiaolai](https://github.com/lxgw/kose-font)
- [悠哉字体 / Yozai](https://github.com/lxgw/yozai-font)


## 打赏支持
[点击进入打赏页面。](https://github.com/lxgw/lxgw/blob/main/Donate.md)
