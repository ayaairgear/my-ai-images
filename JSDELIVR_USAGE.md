# jsDelivr 使用说明

- 当前分支: main
- 固定提交(用于 pinned 链接): 09212a9eb102ddd33f4a496321758b2acf1909af
- 清单图片数量(仅 jpg/jpeg/png): 177

## 兼容策略

- `jsdelivr-links-main.txt` 与 `jsdelivr-links-pinned.txt` 现在只包含 `jpg/jpeg/png`，已排除 `webp`。
- 已新增 `webp-to-png-map.csv`，用于把旧 webp 链接替换为 png 链接。

## 已生成文件

- jsdelivr-links-main.txt: 全量 main 版（仅 jpg/jpeg/png）
- jsdelivr-links-pinned.txt: 全量固定 commit 版（仅 jpg/jpeg/png）
- jsdelivr-purge-links.txt: 全量缓存刷新链接（仅 jpg/jpeg/png）
- webp-to-png-map.csv: webp 到 png 的映射关系

## 常用操作

1. 刷新单图缓存
   - https://purge.jsdelivr.net/gh/ayaairgear/my-ai-images@main/<path>
2. 刷新整个包缓存
   - https://purge.jsdelivr.net/gh/ayaairgear/my-ai-images@main
