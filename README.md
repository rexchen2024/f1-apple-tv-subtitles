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

## 使用前准备

1. 在 Surge 或 Stash 中开启 **MITM**。
2. 完成根证书安装与信任。
3. 如已启用其他会处理 F1 字幕的模块，请先停用，避免重复替换或显示异常。

---

## 安装与启用

### Surge

开启 Surge 的「模块」功能，在模块页面通过 URL 下载下方链接；下载完成后，启用「Apple TV F1 中文字幕」模块。

`https://raw.githubusercontent.com/rexchen2024/f1-apple-tv-subtitles/main/surge/f1-2026-british-gp-pretranslated.sgmodule`

### Stash

开启 Stash 的「覆写（Override）」功能，在覆写页面通过 URL 下载下方链接；下载完成后，启用「Apple TV F1 中文字幕」覆写。

`https://raw.githubusercontent.com/rexchen2024/f1-apple-tv-subtitles/main/stash/f1-2026-british-gp-pretranslated.stoverride`

---

## 观看方式

1. 打开当前支持赛事的 Apple TV 比赛回放。
2. 在字幕选项中选择英文解说对应的字幕轨。
3. 中文比赛解说字幕会自动生效，无需额外安装 DualSubs 模块。

---

## 说明

本项目仅供交流学习使用。
