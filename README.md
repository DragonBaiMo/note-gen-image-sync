# SignFlow YOLOv8 手语手势识别系统

基于 YOLOv8 目标检测构建的静态手语手势识别与记录系统。项目在公开手语检测数据与可复现任务初始化基础上完成类别对齐、检测头迁移微调、数据增强、ONNX CPU 部署、自适应时序确认及桌面端完整业务闭环。

主要功能：

- 本地视频识别
- 摄像头实时识别
- 图片识别与样例图库
- 手势位置、类别和置信度可视化
- 识别事件时序确认与重复抑制
- SQLite 历史记录、截图与 CSV 导出
- 摄像头采集、图片导入、YOLO 框选标注
- 24 类静态手指字母训练与复现脚本
- 自动 GitHub Actions 构建完整发布包

## 快速使用

优先从 GitHub Releases 下载 `SignFlow_YOLOv8_GitHub_Release.zip`。Windows 端准备 Python 3.13 x64 后运行 `START.cmd`。

源码中的详细设计、训练、数据规范、验收与来源记录位于 `docs/`。
