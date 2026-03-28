# jsDelivr 使用说明

- 当前分支: main
- 当前提交: 6085506e1fd425737b0b986ff4834e270369d427
- 图片数量: 177

## 链接类型

1. 跟随最新（方便维护，缓存可能延迟）
   - https://cdn.jsdelivr.net/gh/ayaairgear/my-ai-images@main/<path>
2. 固定提交（最稳定，不会漂移）
   - https://cdn.jsdelivr.net/gh/ayaairgear/my-ai-images@6085506e1fd425737b0b986ff4834e270369d427/<path>

## 已生成文件

- jsdelivr-links-main.txt: 全量 main 版图片链接
- jsdelivr-links-pinned.txt: 全量固定 commit 版图片链接
- jsdelivr-purge-links.txt: 全量缓存刷新链接

## 常用操作

1. 刷新单图缓存
   - https://purge.jsdelivr.net/gh/ayaairgear/my-ai-images@main/<path>
2. 刷新整个包缓存
   - https://purge.jsdelivr.net/gh/ayaairgear/my-ai-images@main
3. 检查目录（API）
   - https://data.jsdelivr.com/v1/package/gh/ayaairgear/my-ai-images@main/flat
