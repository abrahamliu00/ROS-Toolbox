# ROS Toolbox: Handy Utilities for ROS-Based Projects

This repository provides a collection of small but useful tools designed to simplify and streamline tasks within the ROS (Robot Operating System) environment. These utilities are especially helpful for robotics developers working with point cloud data and other common ROS message types.

## 🔧 Features

- **Point Cloud Saver**  
  Subscribe to a specific topic publishing `sensor_msgs/PointCloud2` messages and automatically save incoming point cloud data to files (e.g., `.pcd`, `.ply`).

- *(More tools will be added here in the future)*

## 🧭 Getting Started

### Prerequisites

- ROS 1 (e.g., Noetic) or ROS 2 (e.g., Foxy) depending on the version of your tool
- Python 3
- `pcl_tools`, `pypcd`, or other point cloud libraries as needed

Make sure your ROS environment is properly sourced before running any scripts:

```bash
source /opt/ros/noetic/setup.bash





























## 📜 License

This project is licensed under a custom **Non-Commercial Academic License**.

✅ Academic use and personal non-commercial use are allowed.  
❌ Commercial use is strictly prohibited.

See [LICENSE](./LICENSE) for full terms.  
For commercial licensing, contact: Yuhan594@connect.hku.hk
