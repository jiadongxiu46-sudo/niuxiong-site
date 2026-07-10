# 每日快讯 · 穿越牛熊

`liugc.xyz` 的 GitHub Pages 静态站点仓库。

## 内容

- `index.html`：历史期刊导航，并在首页原样嵌入最新一期。
- `issues/`：从每日快讯发布成品目录同步的原始 HTML，不修改内容或样式。
- `issues.json`：期刊清单与复制校验哈希。
- `CNAME`：GitHub Pages 自定义域名 `liugc.xyz`。

## 发布

每日出刊完成后运行：

```bash
python3 /Volumes/T7/每日快讯/scripts/publish_niuxiong_site.py --push
```

Git 远端必须为 HTTPS 地址。凭据由 Git credential helper 保存，不在脚本或仓库中保存 token。
