# 奇妙半糖梦境 · 话题页

纯静态、完全本地化（字体/图片/视频/游戏均已内置，无外链）。

## 部署 GitHub Pages
```bash
git init && git add . && git commit -m "奇妙半糖梦境"
git branch -M main
git remote add origin https://github.com/<用户名>/<仓库名>.git
git push -u origin main
```
Settings → Pages → Source: `main` + `/ (root)`

## 说明
- 桌面端自动呈现为居中画板（430px），手机端满屏
- 视频为本地 mp4（原 HLS 流已转码内置）
- 两个小游戏为单文件内嵌版（assets/games/）
- 精选作品为动态拉取（需联网），离线时自动隐藏
