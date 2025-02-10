# 项目结构

游戏主目录 位于`game/` 目录下.
- `scripts/` 包含脚本文件
  - `main.rpy`: 开场和游戏大体结构, 包含`label start:`, 是游戏入口
  - `chapter<n>.rpy`: 各章节内容
  - `screens.rpy`: 定义界面样式
  - `characters.rpy`: 人物图片
  - `transform.rpy`: 预定义transform
  - `gui.rpy`: 定义GUI配置变量
  - `options.rpy`: 项目的一些配置
- `images/`: 图片资源, 按照以下子目录分类存放
     - `BJ/`: 背景
     - `CG/`: CG
     - `LH/`: 立绘
     - `ZC`: 转场
     - `设备`: 乐队的乐器设备
- `audio/`: 音频资源
- `game/fonts/`: 字体资源
- `game/gui/`:  GUI(例如主菜单背景)使用的图像文件
- `game/tl/`: 翻译相关