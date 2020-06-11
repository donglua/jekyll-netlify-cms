---
title: Flutter google/charts
---

    源代码版本：0.9.0


一、代码结构

```
lib
├── flutter.dart              -- 模块导出
└── src
    ├── bar_chart.dart              -- 柱状图
    ├── base_chart.dart              -- 图表基类
    ├── base_chart_state.dart              -- 图表基类状态
    ├── behaviors
    │   ├── a11y              -- Accessibility可访问性？
    │   │   └── domain_a11y_explore_behavior.dart              -- 控制图表范围？
    │   ├── calculation              -- 计算
    │   │   └── percent_injector.dart              -- 注入图表范围改变？
    │   ├── chart_behavior.dart              -- 包装图表交互？
    │   ├── chart_title
    │   │   └── chart_title.dart              -- 图表标题状态
    │   ├── domain_highlighter.dart              -- 高亮选中状态
    │   ├── initial_selection.dart              -- 初始高亮选中
    │   ├── legend              -- 图例说明
    │   │   ├── datum_legend.dart
    │   │   ├── legend.dart
    │   │   ├── legend_content_builder.dart
    │   │   ├── legend_entry_layout.dart
    │   │   ├── legend_layout.dart
    │   │   └── series_legend.dart
    │   ├── line_point_highlighter.dart              -- 线段选中高亮
    │   ├── range_annotation.dart              -- 范围？
    │   ├── select_nearest.dart              -- 选中事件监听（长按事件等）
    │   ├── slider
    │   │   └── slider.dart              -- 滑动控制
    │   ├── sliding_viewport.dart              -- 滑动可视范围
    │   └── zoom
    │       ├── initial_hint_behavior.dart
    │       ├── pan_and_zoom_behavior.dart              -- 移动和绽放
    │       └── pan_behavior.dart              -- 移动
    ├── canvas
    │   ├── circle_sector_painter.dart              -- 饼图选中部分
    │   ├── line_painter.dart              -- 画曲线图
    │   ├── pie_painter.dart              -- 画饼图
    │   ├── point_painter.dart              -- 画点
    │   └── polygon_painter.dart              -- 画多边形
    ├── cartesian_chart.dart              -- 直角坐标图
    ├── chart_canvas.dart              -- 图表画布
    ├── chart_container.dart              -- 图表绘图组件
    ├── chart_gesture_detector.dart              -- 手势控制
    ├── chart_state.dart              -- 图表状态
    ├── combo_chart
    │   └── combo_chart.dart              -- 图表组合
    ├── graphics_factory.dart              -- 绘图工具工厂
    ├── line_chart.dart              -- 曲线图
    ├── line_style.dart              -- 曲线样式
    ├── pie_chart.dart              -- 饼图
    ├── scatter_plot_chart.dart              -- 散点图
    ├── selection_model_config.dart              -- 选中配置
    ├── symbol_renderer.dart              -- 渲染器基类
    ├── text_element.dart              -- 用于文本测量和渲染
    ├── text_style.dart              -- 样式
    ├── time_series_chart.dart              -- 基于时间的图表
    ├── user_managed_state.dart              -- 图表状态配置
    ├── util
    │   └── color.dart              -- 颜色转换
    ├── util.dart              -- 工具类
    └── widget_layout_delegate.dart              -- 交互行为代理

```


