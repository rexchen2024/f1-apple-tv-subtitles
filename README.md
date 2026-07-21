# Apple TV F1 中文字幕（Public Beta）

为 Apple TV 中指定的 F1 比赛回放提供中文比赛解说字幕，重点适配中文 F1 赛车文化圈的常用表达。

**当前版本：Public Beta**

目前已支持 2026 奥地利站与英国站的全场比赛解说字幕，不含赛前、赛后采访。

项目仍处于公测阶段，可能出现翻译、时间轴或显示问题；欢迎通过 [Telegram @rexchen29](https://t.me/rexchen29) 反馈具体赛事、时间点和问题内容，帮助持续优化。

---

## 呈现效果

- 对应赛事的英文比赛解说可显示为中文。
- 字幕内容覆盖正赛解说；不包含赛前、赛后采访。

---

## 当前支持赛事

| 赛季 | 分站 | 范围 |
| --- | --- | --- |
| 2026 | 奥地利站 | 全场比赛解说 |
| 2026 | 英国站 | 全场比赛解说 |

---

## 安装方式

### Surge

在 Surge 的「模块」页面通过 URL 安装并启用：

`https://raw.githubusercontent.com/rexchen2024/f1-apple-tv-subtitles/main/surge/f1-2026-british-gp-pretranslated.sgmodule`

### Stash

在 Stash 的 Override 页面通过 URL 添加并启用：

`https://raw.githubusercontent.com/rexchen2024/f1-apple-tv-subtitles/main/stash/f1-2026-british-gp-pretranslated.stoverride`

---

## 使用方法

1. 先在 Surge 或 Stash 中开启 **MITM**，并完成根证书安装与信任。
2. 安装并启用本模块。
3. 打开支持赛事的 Apple TV 比赛回放。
4. 在字幕选项中选择英文解说对应的字幕轨。

如同时启用了其他会处理 F1 字幕的模块，请先停用它们，避免重复替换或显示异常。

---

## 说明

本项目仅供交流学习使用。
