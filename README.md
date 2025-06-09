#羽毛球运动员表现分析与可视化
这是一个用于分析羽毛球运动员比赛表现的 Python 项目，通过生成模拟数据、数据预处理和多种可视化技术，展示运动员的技术指标、体能状况与比赛结果之间的关系。
项目概述
本项目实现了以下功能：
生成模拟的羽毛球比赛数据，包括比赛结果、技术统计和体能数据
对数据进行预处理，计算关键指标如成功率、总得点等
创建多种可视化图表，分析运动员表现与比赛结果的关系
提供技术指标相关性分析和运动员综合能力对比
功能特点
数据生成：
生成 100 场比赛的模拟数据
包含 8 名知名运动员的基本信息
生成比赛结果、技术统计和体能数据三大类数据
数据预处理：
计算各项技术成功率
生成比赛结果分类变量
计算总得点等综合指标
可视化分析：
技术指标与比赛结果对比（小提琴图 + 箱线图）
运动员综合表现雷达图
技术指标相关性热力图
比赛时间与体能关系分析
运动员胜率与技术指标关系
技术栈
数据处理：Pandas, NumPy
可视化：Matplotlib, Seaborn, Plotly
统计分析：SciPy
文件操作：OS
安装指南
确保已安装 Python 3.6+
安装所需依赖：
bash
pip install pandas numpy matplotlib seaborn plotly scipy
使用方法
克隆仓库到本地：
bash
git clone https://github.com/yourusername/badminton-player-analysis.git
cd badminton-player-analysis
运行主程序：
bash
python badminton_analysis.py
程序将生成以下内容：
数据文件存储在 data/player_performance_data.csv
可视化图表存储在 visualizations/ 目录下
图表将同时在屏幕上显示
文件结构
plaintext
badminton-player-analysis/
├── badminton_analysis.py  # 主程序文件
├── data/                  # 数据存储目录
│   └── player_performance_data.csv  # 生成的运动员表现数据
└── visualizations/        # 可视化图表存储目录
    ├── performance_metrics_violin.png  # 技术指标对比图
    ├── player_radar_chart.png        # 运动员综合表现雷达图
    ├── correlation_heatmap.png       # 技术指标相关性热力图
    ├── stamina_vs_duration.png       # 比赛时间与体能关系图
    └── win_rate_correlation.png      # 胜率与技术指标关系图
示例输出
1. 技术指标对比图

技术指标对比图
image
2. 运动员综合表现雷达图

运动员综合表现雷达图
image
3. 技术指标相关性热力图

技术指标相关性热力图
image
4. 比赛时间与体能关系图

比赛时间与体能关系图
image
5. 胜率与技术指标关系图

胜率与技术指标关系图
image
自定义扩展
修改数据生成：
在 generate_sample_data() 函数中调整运动员列表、国家、年龄等基础数据
调整数据生成的分布参数以模拟更真实的比赛数据
添加新的分析指标：
在 preprocess_data() 函数中添加新的计算指标
在可视化函数中添加对新指标的分析图表
使用真实数据：
替换数据生成部分，读取真实的羽毛球比赛数据
调整数据格式以匹配现有数据结构
许可证
本项目采用 MIT 许可证，欢迎贡献和二次开发。
联系方式
如有问题或建议，请通过 GitHub Issues 与我联系。

