### 课程介绍
本课程主要讲解如何使用Swift进行iOS编程，课程包含Swift的使用技巧、设计模式的使用和iOS媒体资源的使用等

### 翻牌游戏设计1
**卡片**： 以`UIButton`为基本控件，通过设置背景颜色和内容控制正反面
**计数器**： 使用属性观察器`didSet`在`UILabel`上同步更新翻动次数 
**卡片数组**：使用字符串数组存储资源，按钮数组存储显示的卡片。

**数据驱动：**按钮绑定了统一的`touchBegan`事件，通过数组的`index`下标索引找到对应的资源和按钮，更新更新点击的对应按钮。

#####涉及到的语法知识点：

* 可选类型
* 枚举
* 数组（包括下标的使用）
* Swift的类型推断

### 阅读作业
前三周阅读Swift的语法
