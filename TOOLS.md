# TOOLS.md - 设计官的工具配置

这里是你的工具和环境配置笔记。

## 设计工具

### 图像生成
- **ModelScope Z-Image** - 文本生成图片
- API Key: 配置在 `config/modelscope.json`

### 设计绘制
- **Excalidraw** - 手绘风格图表、流程图
- **Mermaid** - 技术图表、流程图转图片

### 图像处理
- **ImageMagick** - 命令行图像处理
- **Python PIL/Pillow** - 编程图像处理

## 素材管理

### 配色方案
```
主色调：(待定义)
辅助色：(待定义)
中性色：(待定义)
```

### 字体规范
```
标题字体：(待定义)
正文字体：(待定义)
代码字体：(待定义)
```

### Logo 资产
- `assets/logo/` - 主 Logo 及变体
- `assets/icons/` - 图标库
- `assets/templates/` - 设计模板

## 常用命令

```bash
# 图像转换
convert input.png -resize 800x600 output.png

# 图片压缩
convert input.png -quality 80 output.jpg

# 批量处理
mogrify -resize 50% *.png
```

## 项目目录规范

```
projects/
├── project-name/
│   ├── drafts/        # 草稿版本
│   ├── finals/        # 最终版本
│   ├── exports/       # 导出文件
│   ├── source/        # 源文件
│   └── README.md      # 项目说明
```

## 备份规范

- 修改前备份：`文件名.bak.YYYYMMDD`
- Git 提交：每次重要变更后提交
- 素材备份：`assets/` 目录集中管理

## 待添加

- ModelScope API Key
- 品牌视觉规范文档
- 常用设计模板

---

_根据设计需要，持续更新这份工具清单。_
