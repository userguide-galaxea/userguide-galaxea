![](GALAXEA+GD.png)
![](GALAXEA_ROBOT.png)

Founded in September 2023, Galaxea is a cutting-edge AI technology company specializing developing of Embodied AI foundation models and embodied AI robots. Anchored in its “Hardware + Intelligence” strategy and driven by an open, collaborative philosophy, Galaxea is dedicated to partnering with global leaders in Embodied AI to build and continuously empower a thriving ecosystem, bringing embodied AI technologies seamlessly into real-world applications and everyday life.


[![Bilibili](https://img.shields.io/badge/Bilibili-Galaxea-FF69B4?logo=bilibili&logoColor=white)](https://space.bilibili.com/3546640453471155)
[![YouTube](https://img.shields.io/badge/YouTube-GalaxeaAI-FF0000?logo=youtube&logoColor=white)](https://www.youtube.com/@Galaxea_youtube)
[![知乎](https://img.shields.io/badge/知乎-星海图-0084FF?logo=zhihu&logoColor=white)](https://www.zhihu.com/org/xing-hai-tu-14)
[![小红书](https://img.shields.io/badge/小红书-Galaxea-FF2442)](https://www.xiaohongshu.com/user/profile/5d0724e00000000010011a06)
[![官网](https://img.shields.io/badge/官网-Galaxea-181717?logo=googlechrome&logoColor=white)](https://galaxea-dynamics.com)

### 🤖 Galaxea A1Z

A1Z: Your First Desktop Smart Assistant – Ready to Use Out of the Box, Customizable for Any Scenario

| 仓库 | 语言 / 格式 | 用途 |
|:-----|:----:|:-----|
| [galaxea_a1z](https://github.com/userguide-galaxea/galaxea_a1z) | Python | A1Z 机器人控制 SDK 主仓库（`a1z` 包）：硬件接口与遥操基础能力 |
| [a1z-t](https://github.com/userguide-galaxea/a1z-t) | Python | 官方产品版 A1Z-T 遥操作系统 |
| [a1z-data-collect](https://github.com/userguide-galaxea/a1z-data-collect) | Python | 遥操作数据采集脚本与工具 |
| [a1z-g05-deploy](https://github.com/userguide-galaxea/a1z-g05-deploy) | Python | 基于 G05 框架的模型训练与部署 |
| [a1z-pi05-deploy](https://github.com/userguide-galaxea/a1z-pi05-deploy) | Python | 基于 π0.5 的模型训练与部署 |
| [a1z-lerobot](https://github.com/userguide-galaxea/a1z-lerobot) | Python | 基于 LeRobot 框架的模型训练与部署 |
| [OpenA1Z-T](https://github.com/userguide-galaxea/OpenA1Z-T) | Python | 3D 打印版 A1Z-T 遥操作系统 |
| [URDF](https://github.com/userguide-galaxea/URDF) | CMake | 机器人 URDF 模型文件 |
| [STP](https://github.com/userguide-galaxea/STP) | STP | 机器人 STP 数模文件 |
| [USD](https://github.com/userguide-galaxea/USD) | USD | 机器人 USD 数模文件 |

部署仓库（`a1z-g05-deploy`、`a1z-pi05-deploy`）运行 `python3 scripts/bootstrap.py` 会自动 clone 并更新 `a1z-data-collect`、`a1z-t` 与 `galaxea_a1z` 三处依赖，不需要手动初始化子模块。
