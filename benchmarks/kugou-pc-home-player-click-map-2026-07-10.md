# Kugou PC Home And Player Click Map · 2026-07-10 Archive

## Source And Scope

- Source asset: `assets/数据基线/kugou-pc-home-player-click-map-2026-07-10.png`
- User confirmation: this is Kugou PC-side data.
- Visible surfaces: PC home page and PC player / lyrics page.
- Archive date: 2026-07-10. This is not necessarily the data collection date.
- Missing source metadata: statistical period, client version, metric name and denominator, sample size, and red/orange/blue color meaning.
- Data entry method: visually transcribed from the annotated screenshot. Ambiguous or unlabeled bubbles are preserved only in the source image, not force-mapped to a control.

## Direct Reading

This screenshot is useful as a PC placement map, not yet as a universal CTR benchmark. The reliable comparison is between clearly labeled controls on the same captured surface.

- PC home action is concentrated around search, core playback controls, favorites/recent history, and the primary recommendation blocks.
- Home recommendation cards differ sharply: `每日推荐 12.0%` and `猜你喜欢 10.6%` visibly outperform `排行榜 3.3%`, `歌手 1.0%`, and `歌单广场 0.9%`.
- PC player action remains concentrated in back navigation and playback controls: `返回 39.4%`, `播放/暂停 52.0%`, `下一首 31.1%`, `上一首 8.1%`.
- Auxiliary player controls mostly sit in the low single digits. A new commercial entry should not use the central playback numbers as its expected baseline.
- The PC home and PC player should be judged separately; identical-looking bottom controls have different visible percentages across the two surfaces.

## PC Home · Clearly Identifiable Labels

### Left Navigation

| Module | Visible Percentage |
|---|---:|
| 音乐 | 13.1% |
| 听书 | 1.6% |
| 直播 | 0.7% |
| 赚钱 | 0.8% |
| 我的收藏 | 17.9% |
| 最近播放 | 11.5% |
| 本地与下载 | 5.9% |
| 音乐云盘 | 1.1% |
| 我的听书 | 1.1% |
| 已购音乐 | 0.7% |
| 自建歌单 | 13.7% |
| 我喜欢 | 14.9% |

### Search And Main Navigation

| Module | Visible Percentage |
|---|---:|
| 搜索 | 29.8% |
| 推荐 | 4.3% |
| 乐库 | 5.5% |
| 歌单 | 5.3% |
| 频道 | 1.8% |
| 分类 | 2.7% |
| 长视频 | 0.7% |
| AI 帮唱 | 0.5% |
| 金币中心 | 0.1% |

### Recommendation Modules

| Module | Visible Percentage |
|---|---:|
| 猜你喜欢 | 10.6% |
| 每日推荐 | 12.0% |
| 排行榜 | 3.3% |
| 歌单广场 | 0.9% |
| 歌手 | 1.0% |
| 今日专属推荐区 | 11.4% |
| 今日专属推荐中的广告卡 | 0.7% |

### Bottom Playback Bar

| Module | Visible Percentage |
|---|---:|
| 当前歌曲封面/歌曲入口 | 23.8% |
| 上一首 | 4.7% |
| 播放/暂停 | 56.0% |
| 下一首 | 22.4% |
| 开会员畅听 | 6.4% |
| 音效 | 2.5% |
| 伴唱 | 1.4% |
| 词 | 5.9% |
| 播放列表 | 7.0% |

## PC Player / Lyrics · Clearly Identifiable Labels

### Page And Content Navigation

| Module | Visible Percentage |
|---|---:|
| 返回 | 39.4% |
| 歌词 tab | 4.9% |
| 相关 tab | 1.9% |
| 专辑封面区域入口 | 0.8% |

### Top / Auxiliary Actions

| Module | Visible Percentage |
|---|---:|
| 美鱼模式 | 1.0% |
| 方形封面 | 2.5% |
| 顶部工具入口（截图可辨识的一组） | 0.5% / 0.2% / 3.2% / 4.7% |

### Bottom Playback And Tools

| Module | Visible Percentage |
|---|---:|
| 收起/展开 | 22.3% |
| 收藏/喜欢 | 5.4% |
| VIP | 0.8% |
| 上一首 | 8.1% |
| 播放/暂停 | 52.0% |
| 下一首 | 31.1% |
| 开会员畅听 | 0.1% |
| 循环模式 | 4.3% |
| 音量 | 3.8% |
| 标准音质 | 1.9% |
| 音效 | 2.1% |
| 伴唱 | 2.4% |
| 词 | 3.3% |
| 播放列表 | 4.6% |

## How To Use In Review

Use this reference when the task explicitly involves Kugou PC home, PC player, PC lyrics, desktop-side membership entries, recommendation modules, or bottom playback-bar placements.

- Compare a proposal with the nearest same-surface control, not the highest number on the page.
- Home recommendation proposals should distinguish primary music intent (`10.6%-12.0%` in the two strongest recommendation cards) from secondary navigation (`0.9%-5.5%` among visible modules).
- Player commercial ideas should avoid treating `52.0%` play/pause or `31.1%` next-song behavior as attainable commercial-entry benchmarks.
- A low-single-digit auxiliary control can still be meaningful on PC; validate with exposure, downstream arrival, conversion, and interruption instead of entrance percentage alone.
- If raw data or a newer annotated map arrives, add the statistical period, metric formula, client version, and color legend before promoting this into a stricter baseline.

## Guardrails

- Do not call these values CTR until the metric definition is confirmed.
- Do not compare these percentages directly with Android home/player benchmarks.
- Do not infer that red means “good” or blue means “bad”; the screenshot does not provide the legend.
- Keep ambiguous bubbles in the source image rather than inventing a control mapping.
