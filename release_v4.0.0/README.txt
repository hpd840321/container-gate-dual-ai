===========================================
码头集装箱道闸双短柜AI识别系统 - V4.0.0
Version: v4.0.0
Release Date: 2026-03-05
===========================================

【版本亮点】

V4.0.0 是重大更新版本，主要改进：

1. ✅ 修正双20尺柜空间布局
   - 从错误的"横向并排"修正为正确的"纵向排列"
   - 两个20尺集装箱一前一后纵向连接，总长12m
   - 车道宽度3.5m（符合标准）

2. ✅ 修正车辆行驶方向
   - 从左到右行驶
   - 车头在右侧（出口侧）
   - 车尾在左侧（入口侧）
   - 集装箱顺序：车尾 → 后箱 → 前箱 → 车头

3. ✅ 全新重绘SVG图形
   - deployment_mode1.svg: 侧壁安装模式（16KB）
   - deployment_mode2.svg: 头尾安装模式（18KB）
   - camera_coverage.svg: 视野覆盖与映射（24KB）
   - scenario_comparison.svg: 三场景对比（19KB）
   - 所有图形与文字描述完全一致

4. ✅ 5.5摄像头方案
   - 5基础相机：C5+C6+C3+C4
   - 1辅助相机：C7（按需触发）
   - 相机职责与纵向布局匹配

5. ✅ 通用AI检测描述
   - 去除YOLOv8/YOLOv5特定技术术语
   - 改用通用"AI目标检测"描述
   - 方案更加通用灵活

【文件说明】

1. 入口文件:
   index.html - 可视化方案演示页面（用浏览器打开）

2. 设计文档:
   README_DESIGN.md - 系统架构设计说明
   道闸双柜识别方案.md - 详细技术方案文档（46KB）

3. SVG示意图:
   - deployment_mode1.svg - 模式一：侧壁安装（纵向双箱）
   - deployment_mode2.svg - 模式二：头尾安装（纵向双箱）
   - flowchart.svg - 核心处理流程图
   - scenario_comparison.svg - 三场景对比图
   - camera_coverage.svg - 视野覆盖与坐标映射
   - infrared_barrier.svg - 红外光栅栏示意图
   - flowchart_v2.svg, flowchart_v3.svg, flowchart_v4.svg - 历史版本

4. 预览图片:
   - flowchart.svg.png
   - flowchart_v2.svg.png
   - flowchart_v3.svg.png

【快速开始】

1. 用浏览器打开 index.html 查看完整方案演示
2. 点击顶部导航切换不同模块
3. 查看 SVG 文件了解详细技术架构

【系统特点】

- 支持双20尺柜、单20尺柜、单40尺柜三种模式
- AI视觉识别，识别率 ≥ 99.2%
- 坐标映射技术实现精准ROI裁剪
- 双部署模式适应不同场地条件
- 全流程响应时间 ≤ 2秒

【技术支持】

广州创飞人工智能技术有限公司
