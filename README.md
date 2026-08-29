# 马云龙 - 视频剪辑师作品集网站

## 文件结构

```
.
├── index.html          # 网站主文件
└── videos/             # 作品视频（压缩版）
    ├── work01_lancome.mp4      # AI广告片：兰蔻防晒乳 (7.3M)
    ├── work02_icecream.mp4     # 广告片：冰得宝 (9.1M)
    ├── work03_powerbank.mp4    # 广告片：充电宝 (5.7M)
    ├── work04_monster.mp4      # 广告片：魔爪 (7.6M)
    ├── work05_militarydog.mp4  # 口播：美国军犬的故事 (22M)
    ├── work06_workplace.mp4    # 口播：职场 (4.7M)
    └── work07_vocabulary.mp4   # 课程切片：单词速记 (3.7M)
```

## 部署方式

### GitHub + Netlify

1. 在 GitHub 创建一个新仓库（如 `mayunlong-portfolio`）
2. 将 `index.html` 和 `videos/` 文件夹上传到仓库
3. 登录 [Netlify](https://app.netlify.com/)，选择 "Import from Git"
4. 连接 GitHub 仓库，部署设置：
   - Build command: 留空
   - Publish directory: `.`
5. 点击 Deploy，等待完成后获得在线链接

> 注意：`videos/work05_militarydog.mp4` 为 22MB，低于 GitHub 100MB 单文件限制，可正常上传。
