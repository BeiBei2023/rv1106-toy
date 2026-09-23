# 基于RV1106G3的智能陪伴玩具的设计

PCB 丝印二维码指向的在线页面仓库。扫码打开：

**https://beibei2023.github.io/rv1106-toy/**

## 目录结构

```
index.html   主页面：BOM 表格、接线提示、PCB 图片
images/      图片素材（pcb-top.jpg / pcb-bottom.jpg / wiring.png）
qrcode/      二维码文件（SVG 导入 PCB，PNG 预览）
```

## 以后如何更新内容

1. 修改 `index.html`（BOM 表格、接线文字）
2. 图片放进 `images/`，并在 `index.html` 中引用（取消对应注释）
3. 提交并推送：

```powershell
cd D:\my_project\rv1106-toy
git add .
git commit -m "更新BOM/接线内容"
git push
```

约 1 分钟后生效，**二维码无需更换**。

## 二维码规格（已生成，印刷勿改）

- 内容：`https://beibei2023.github.io/rv1106-toy/`
- 纠错等级：H
- 建议印刷尺寸：≥ 20×20mm，白底黑码，四周留 ≥ 2mm 静默区
- SVG：`qrcode/rv1106-toy-qr.svg`（导入丝印层）
- PNG：`qrcode/rv1106-toy-qr.png`（打印预检）

## GitHub Pages 设置（仅首次）

仓库 Settings → Pages → Source: Deploy from a branch → Branch: `master` / root → Save。
