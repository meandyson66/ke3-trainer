# 科目三 · 驾驶室模拟训练

跟教学视频练习灯光、转向、脚刹、挂挡等操作；支持跟读打点生成课表。按错时视频暂停。

## 在线使用

部署后访问：**https://meandyson66.github.io/ke3-trainer/**

本地打开：直接双击 `index.html`，或在本目录执行 `python -m http.server 8080` 后打开 http://localhost:8080/

## 文件说明

| 文件 | 说明 |
|------|------|
| `index.html` | 训练页（挡风玻璃播视频 + 中控台） |
| `ke3-lesson.json` | 口令课表（可跟读打点导出覆盖） |
| `media/subject3.mp4` | 内置教学视频 |

## 课表

1. 点「跟读打点」→ 播放视频 → 听到口令点对应开关  
2. 「完成打点 · 练」进入练习  
3. 高级里可导出 `ke3-lesson.json`