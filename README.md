# Trajectory Tracking Simulation

基于C++/Linux的二维轨迹跟踪与控制仿真系统

## 项目目标
- 实现小车运动学模型
- 实现PID轨迹跟踪控制
- 可视化仿真结果

## 模块规划
- `src/vehicle.cpp`: 小车运动学模型
- `src/controller.cpp`: PID控制器
- `src/trajectory.cpp`: 轨迹生成
- `src/main.cpp`: 主循环

## 构建方法
```bash
mkdir build && cd build
cmake ..
make
