
安装示例

```shell
sudo apt-get update
sudo apt-get install -y python3-pip python3-venv git

curl -sSL https://install.python-poetry.org | python3 -

# 如果需要，添加 Poetry 路径到系统环境变量
echo 'export PATH="$HOME/.local/bin:$PATH"' >> ~/.bashrc
source ~/.bashrc

# 克隆项目并安装依赖
git clone https://github.com/jrspruitt/ubi_reader
cd ubi_reader
poetry install

# 激活虚拟环境
poetry shell

which ubireader_display_blocks 
/home/elliot/.cache/pypoetry/virtualenvs/ubi-reader-RBmMcrJk-py3.10/bin/ubireader_display_blocks
```

