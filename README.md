# 新闻杂志 · News Magazine

每天 09:00 自动更新的中文新闻杂志站点。单文件静态站，杂志版式，无框架痕迹。

- 在线访问：https://craeatZeven.github.io/news-magazine/
- 地图版：https://craeatZeven.github.io/news-magazine/map.html

## 内容

- 7 天新闻窗口，15 个领域（AI、国际形势、金融、国内民生、国防军工、能源材料、医疗健康等）
- 英文源标题/摘要自动翻译为中文，来源名保留原文
- 每日封面由 Gemini 生成，专家分析由 DeepSeek 生成
- 世界地图事件分布、冲突热点、全球行情

## 自动更新

本地管线每天 09:00（UTC+8）运行：

```
收集 → 翻译 → 分类 → 配图 → 分析 → 行情 → 构建 → 推送到 GitHub Pages
```

来源包括：人民日报、参考消息、新闻联播、央视、澎湃、财新、财联社、第一财经、南方周末、观察者网、BBC、卫报、纽约时报、路透、美联社、联合早报等 60+ 源。

## 本地运行

```bat
cd scripts
update_site.bat
```

构建产物在 `output/新闻可视化/`，推送后 GitHub Pages 自动生效。
