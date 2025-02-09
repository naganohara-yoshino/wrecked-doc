# 代码风格与代码规范

## 标签

各章在每个章节文件的最开头使用(全局)标签`chapter<n>`表示, 例如: `label chapter1:`

~~ 章节中的场景用局部标签`.scene<n>`表示, 例如`label .scene2:` ~~

> 💡使用`jump <global_label>.<local_name>`跳转至指定标签, 例如`jump chapter1.scene2`

## 资源文件管理

## 图片

~ (需要铺满窗口的)图片的大小暂时是2400*2400*4000 ~~

**立绘**图片名称包含人名缩写(两个字母)、季节缩写(`spr`，`sum`，`aut`，`win`)、人物表情, 并按`<name>_<season>_<facial expression>.<fmt>`的格式用下划线连接. 例如`cy_win_calm.png`, `ym_win_calm.png`.

**背景和CG**图片名称包含图片类型、编号、描述, 并按`<type>_<number>_<description>.<fmt>`的格式用下划线连接. 例如`bg_1_streetwithsnow.png`, `cg_1_wreckedsawa`.

**UI**相关图片可采用短名字. 例如`splash.png`, `transition<n>.png`

## 音频

按整体风格放于特定目录, 文件名表示特定场景/气氛.