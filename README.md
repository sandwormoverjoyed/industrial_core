# industrial_core

可复用工业控制基础库。

本仓库用于沉淀工业上共享的设备通信、几何计算、点云处理、机器人、相机和采集等基础能力。

## 模块

- `industrial_core.core.geometry.abb_matrix`: ABB/激光坐标转换工具。
- `industrial_core.core.point_cloud.geometry`: 可复用的点云几何处理、圆柱拟合、边界检测、圆拟合、轮型网格创建以及管件点云预处理。
- `industrial_core.core.opcua`: 用于连接、读取、写入和批量操作的底层 OPC UA 客户端工具。
- `industrial_core.core.modbus`: 用于连接、读取和写入操作的底层 Modbus TCP 客户端工具。
- `industrial_core.core.point_cloud.io`: 点云 XYZ 数组、`.asc` 加载/保存以及 Open3D 转换辅助工具。
- `industrial_core.core.robot.protocol`: 机器人点位 CSV 格式化与响应解析辅助工具。
