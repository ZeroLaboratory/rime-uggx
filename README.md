# rime-uggx
一个用于 RIME 的郑码输入方案

### 关于名字
什么？你要问这个方案为什么叫 uggx？因为「郑码」的郑码正是「uggx」。

### 特点
+ 不自动上屏
+ 4 码顶字上屏
+ 足 4 码无候选时下一码自动清动清除前 4 码
+ 出字优先级，其中用户词组为动态词频，其余为固定词频
    1. 预设单字
    2. 用户词组
    3. 预设词组
+ 自动根据上屏历史造词
+ 使用分词符 `'` 可自造词
+ `` ` `` 开头进入拼音反查模式
+ `aa` 开头可打出符号，详见 `uggx.symbols.dict.yaml`

### 用法
本方案可以用在任何基于 librime 的输入法平台上。

有关可用的程序列表及自定义配置，请查阅 https://rime.im/ 。

注意：本方案所用语法较新，目前我本人不确定其最低支持的 librime 版本号是多少，请尽可能使用最新版。

如果你发现问题，欢迎提 issuse 。

### 鸣谢
+ 不知路人（吧友） - 多年前制作了一个「不知郑码」的方案。本方案正是沿用了其使用的码表，依据 librime 的新特性重写而来。
