# AI-Project-Template

> 深度学习项目模板

## 目录结构

```
.
├── data                    # 数据集目录
│   └── ...
├── docs                    # 项目文档目录
│   └── ...
├── experiments             # 实验记录目录
│   └── ...
├── notebooks               # Jupyter Notebook 文件（可选）
│   └── ...
├── scripts                 # 训练/推理脚本目录
│   ├── prepare.sh          # 环境配置脚本
│   ├── train.sh            # 训练 shell 脚本
│   ├── infer.sh            # 推理 shell 脚本
│   └── ...
├── src                     # 源代码目录
│   ├── configs             # 配置文件目录
│   │   └── ...
│   ├── models              # 模型文件存放位置
│   │   └── ...
│   ├── utils               # 工具函数目录
│   │   └── ...
│   ├── train.py            # 训练 python 脚本
│   ├── infer.py            # 推理 python 脚本
│   └── ...
├── README.md               # 项目说明文档
├── Dockerfile              # Docker 镜像构建文件
├── .gitignore              # Git 忽略文件
├── requirements.txt        # Python 依赖包列表（Pip 环境必须）
└── environment.yml         # Python 依赖包列表（Conda 环境必须）
```
