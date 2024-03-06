# NPM IR Data Model

使用 DBT 对 NPM IR 进行数据建模。

## 环境准备

### 依赖环境

- docker
- python3

### 准备 python 环境

```shell
# 创建虚拟环境
python3 -m venv .venv
# 激活虚拟环境
source .venv/bin/activate
# 安装依赖
python -m pip install dbt-clickhouse
```

### 准备 clickhouse 环境

```shell
# 启动 docker 容器
docker compose up -d
```
