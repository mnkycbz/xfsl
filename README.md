# 星海实验高级中学 · 第一届星海超级足球联赛 · 宣传网站

苏茜足球社主办的校园足球联赛单页宣传网站，纯静态（HTML + CSS），无需后端，可直接部署到 GitHub Pages 或其他静态托管。

## 目录结构

```
website/
├── index.html        # 网站主文件（全部内容、样式、脚本均内置）
├── cover_field.jpg   # 首屏背景图
├── wechat_qr.png     # 报名群二维码（点击「立即报名」弹出）
└── README.md         # 本说明文件
```

## 本地预览

直接用浏览器打开 `index.html` 即可；或在本文件夹下启动一个本地服务：

```bash
python3 -m http.server 8000
# 浏览器访问 http://localhost:8000
```

## 部署到 GitHub Pages

1. 在 GitHub 新建一个仓库（例如 `campus-football`）。
2. 把本文件夹内的文件（`index.html`、`cover_field.jpg`、`wechat_qr.png`、`README.md`）推送到仓库。
3. 仓库 → **Settings → Pages**，Source 选择 `main` 分支（或你使用的默认分支）、目录选 `/ (root)`。
4. 稍等片刻，访问 `https://<你的用户名>.github.io/<仓库名>/` 即可。

## 内容版块

- 首屏 Hero（联赛口号 + 报名入口）
- 联赛简介与三大目标
- 联赛亮点
- 赛制方案（瑞士轮 + 季后赛）与对比
- 赛程时间线
- 荣誉奖项
- 报名须知
- 比赛规则要点

## 自定义说明

- 替换 `cover_field.jpg` 可更换首屏背景。
- 点击「立即报名」会弹出报名群二维码弹窗（图片 `wechat_qr.png`）；要更换二维码，只需替换该图片文件即可。
- 文案、队伍数量、赛程等可直接编辑 `index.html` 中对应文字。
