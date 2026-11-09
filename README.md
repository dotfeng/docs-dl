# docs-dl

本仓库只存放竞赛资料站（https://fengg.net）的**待下载文档**，不包含任何页面代码。

- 目录结构与主站一致：`public/download/<学科>/<赛事>/<文件名>`
- 通过 GitHub Pages 发布，访问前缀为 `fengg.net/docs-dl/`
- 主站页面里的下载链接由 `_config.yml` 的 `dl_base` 拼接而成
- 根目录的 `.nojekyll` 用于跳过 Jekyll，避免构建时逐个处理大文件

新增或更新文档后，主站的 `tools/check_downloads.py` 可用来核对引用与文件是否一一对应。
