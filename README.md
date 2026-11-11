# 波波储 · 公开试玩

四人同时出招的回合制博弈小游戏。这是学习项目的早期试玩版，欢迎反馈看不懂、操作不方便或规则异常的地方。

本仓库只提供试玩下载与反馈，不包含 Godot 项目源码。

## 下载

前往 [Releases 下载页](https://github.com/Reze1ove/bobochu-playtest/releases)，展开 **Assets**，选择对应系统的 ZIP。不要下载自动生成的 Source code，那不是游戏安装包。

| 系统与语言 | 文件 | 验证情况 |
| --- | --- | --- |
| macOS · 中文 | `Bobochu-v0.1-test2-macOS.zip` | Apple Silicon 已本机运行检查；Intel 待验证 |
| Windows 64 位 · 中文 | `Bobochu-v0.1-test2-windows-x86_64.zip` | 已跨平台导出，等待 Windows 实机试玩 |
| Windows 64 位 · 한국어 | `Bobochu-v0.1-test2-ko-windows-x86_64.zip` | 韩语画面与数据已在 Mac 检查；Windows 实机与母语校对待完成 |

### 한국어 체험판

Windows용 한국어 버전은 파일명에 `-ko-`가 있는 ZIP입니다. 게임 UI, 툴팁, 오른쪽 위의 ‘플레이 방법’ 세 페이지와 한국어 안내가 포함되어 있습니다. 전체를 압축 해제한 뒤 `Bobochu.exe`를 실행하세요. 같은 폴더의 `Bobochu.pck`를 이동하거나 삭제하지 마세요. Godot 설치는 필요 없습니다.

Windows 실제 실행과 한국어 원어민 교정은 아직 검증 전입니다. 실행 문제나 어색한 표현은 초대한 사람에게 알려 주시거나 Issues에 남겨 주세요.

无需安装 Godot。请先完整解压，再启动里面的应用。

- Mac：打开解压目录中的 `Bobochu.app`。应用未经过 Apple 公证，可能出现系统安全提示；请确认来源，不要关闭系统安全保护。
- Windows：打开解压目录中的游戏 `.exe`，保留同目录的 `.pck` 文件，不要只转发或移动 `.exe`。应用未进行商业代码签名，可能出现信誉提示。

## 怎么玩

1. 选择 Bot 难度和角色，点击“开始对局”。本版固定为一名玩家对三个 Bot；角色目前只有外观区别。
2. 从“储 / 进攻 / 防御 / 特殊”选择动作，需要目标时再选择对手，最后锁定。
3. 所有人锁定后统一结算；看完结果，点击“下一回合”继续。具体数值和例子请点游戏内“怎么玩”。

遇到打不开、崩溃或不懂的地方，都可以反馈；不必等到打完整局。

## 反馈

可以直接把下面信息发给邀请你试玩的人，也可以在本仓库的 [Issues](https://github.com/Reze1ove/bobochu-playtest/issues) 留言。公开留言前请遮住截图中的个人信息。

```text
系统与版本：
试玩包版本与语言：v0.1-test2 / v0.1-test2-ko
Bot 难度：
现象（哪里不懂 / 预期与实际有什么不同）：
出现时第几回合、各玩家动作（记得多少写多少）：
能否重复出现，以及操作步骤：
截图或短视频（可选）：
```

尤其想知道：能否顺利启动、第一局是否理解操作和结算、节奏是否合适、Bot 难度感觉如何。

## 文件校验与授权

试玩包中附有试玩说明、构建信息与第三方授权。当前 ZIP 的 SHA-256：

```text
01a0784e174828731ae153f780abfb9f9955ca8f6a6deef91235d3a9bd553c81  Bobochu-v0.1-test2-macOS.zip
f5292101649afd1957db5d238845e609e2da677b6f3c9af2ff2fa49314e24e2f  Bobochu-v0.1-test2-windows-x86_64.zip
7f1bc47f187528f8ff191ea088f4b76020042b90643f4001c0abe42d6184111d  Bobochu-v0.1-test2-ko-windows-x86_64.zip
```
