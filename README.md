## Rime 鼠须管（Squirrel）朙月拼音、小鹤双拼、自然码双拼配置详解

![](https://i.imgur.com/sw2IXL1.png)


[![](https://img.shields.io/badge/Rime鼠须管-TG群-red)](https://t.me/rimeim)
[![](https://img.shields.io/badge/V2EX-TG群-blue)](https://t.me/V2EXPro)
[![](https://img.shields.io/badge/Twitter-推特-1E9BF1)](https://twitter.com/muzhilau)

### 特点

* 朙月拼音（默认）、小鹤双拼、自然码双拼
* 词库不丢失，支持多平台同步
* 百万词库[（城市信息、自然科学、社会科学、工程应用、农林渔畜、医药医学、电子游戏、艺术设计、生活百科、运动休闲、人文科学、娱乐休闲）](https://pinyin.sogou.com/dict/cate/index/167)
* Emoji
* 动态输入时间、日期、星期
* 速度快、开源、保护隐私、自定义强

---
### 安装

下载 [鼠须管](https://github.com/rime/squirrel/releases/download/0.15.2/Squirrel-0.15.2.zip)，安装后菜单栏点选【ㄓ】开始使用输入法，默认繁体输出，通过快捷键 `Control+｀` 切换输入方式，例如选择【朙月拼音·简化字】简体输出。

---
### 定制

1. 下载 [配置](https://github.com/ssnhd/rime/archive/refs/heads/master.zip) 解压得到【配置文件】和【花园明朝字体】，将字体安装到字体册（Mac 缺少生僻字）。
2. 点击菜单栏【ㄓ】-【用户设定】，将【配置文件】里所有文件粘贴进去，并选择覆盖。
3. 点击菜单栏【ㄓ】-【重新部署】（快捷键 `Control+Option+｀`），至此完成定制配置，可以愉快的使用了。
- 定制详解：[点击这里。](https://ssnhd.com/2022/01/06/rime/)

---
### [👏 购买 Google Voice 点击这里 👏](https://ssnhd.com/2022/01/27/voice/)
[![](https://i.imgur.com/RELjhoN.png)](https://ssnhd.com/2022/01/27/voice/)

### 更新日志

#### 2022-6
- 【增加】皮肤支持浅色和深色自动切换

#### 2022-5
- 【删除】luna_pinyin.chat.dict.yaml
- 【增加】chat里少部分词库转移至搜狗词库


#### 2022-3
- 【修改】朙月拼音默认开启自动纠错
- 【增加】聊天词
- 【修改】搜狗词库增加词频，同时原12个分类合并在一起

#### 2022-1
* 【增加】聊天词、英文词、搜狗词库（城市、工程、农业、人文、社会、生活、艺术、医学、游戏、娱乐、运动、自然）
* 【删除】旧搜狗和日本 AV 女优词库（列入新搜狗词库）
* 【删除】朙月拼音符号`【 】`候选项里 ~「」、〔〕、[]~
* 【增加】皮肤
* 【增加】Emoji：`日 🌞 ☀️`、`圣诞 🎄`、`美利坚 🇺🇸`、`老美 🇺🇸`、`国旗 🇨🇳`
* 【修改】动态日期、时间、星期编码改为 `rq`、`sj`、`xq`

#### 2021-12
* 【调整】英文候选词位置 `initial_quality: -0.5`
* 【增加】Emoji：`对 ✓ ✅`，`正确 ✔️ ☑️`
* 【增加】聊天词库 `luna_pinyin.chat.dict.yaml`，日本AV女优词库 `luna_pinyin.av.dict.yaml`
* 【增加】皮肤
* 【增加】默认英文输入程序：腾讯柠檬、Xcode、App Cleaner & Uninstaller

#### 2021-09
* 【增加】增加第二三候选快捷键（默认关闭）

#### 2021-08
- 【增加】搜狗词库加入 `搜狗 sogou`

#### 2021-07
- 【增加】综合词库增加三角叠字、左右叠字、四方叠字。例如：输入 `tututu` 输出 `垚`

#### 2021-06
- 【增加】`Tab` 键：默认设为拼音分词功能
- 【修复】Emoji：日本 `🇯🇵` 不显示问题

#### 2021-05
- 【修复】无法使用超级简拼
- 【增加】macOS 11.3 Emoji
- 【增加】搜狗词库增加至约 172 万词条

#### 2021-04

- 【增加】小鹤双拼和自然码双拼（[双拼练习](https://api.ihint.me/shuang/) 和 [自然码词库](https://github.com/SleepyBag/rime-zrm)）
- 【增加】Emoji：更新中文编码和增加繁体编码
- 【修改】动态时间日期星期：编码 `sj → time`、`rq → date`、`xq → week`
- 【修改】搜狗词库：编码更改为 `汉字 + 拼音`和繁体
- 【增加】大写数字输入方案
- 【增加】皮肤
- 【删除】自定义短语和英文词典里的重复词条
- 【修复】候选词：无法更改个数
- 【增加】回车清码功能（默认关闭）

#### 2021-03

- 【删除】搜狗词库：12 个分类合并为一个 `luna_pinyin.sogou.dict.yaml`，并删除重复词条
- 【更改】~~`luna_pinyin.cn_en.dict.yaml`~~ 更改为 `luna_pinyin.zonghe.dict.yaml`

#### 2021-02

- 【删除】动态日期：美式格式 ~~`"%m-%d-%Y"`~~
- 【删除】动态时间：含日期格式 ~~`"%Y%m%d%H%M%S"`~~

