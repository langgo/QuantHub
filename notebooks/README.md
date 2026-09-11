# Notebooks

这里存放量化研究与回测教程 Notebook。

## 文件

- `backtesting_py_交互式实战.ipynb`：面向初学者的 `backtesting.py + AKShare` 回测教程，示例标的为 `515450` 和 `603993`。
- `金融股票指标入门_matplotlib.ipynb`：金融/股票常见指标入门教程，讲解指标含义、公式、计算方法，并用 `603993` 示例和 Matplotlib 可视化。

## 安装依赖

项目已使用 `uv` 管理依赖。首次使用执行：

```bash
uv sync
```

## 启动 Jupyter

```bash
uv run jupyter notebook
```

然后在浏览器中打开：

```text
notebooks/backtesting_py_交互式实战.ipynb
```

## 导出 HTML

```bash
uv run jupyter nbconvert --to html notebooks/backtesting_py_交互式实战.ipynb
```

生成文件：

```text
notebooks/backtesting_py_交互式实战.html
```

## 执行后再导出 HTML

如果希望重新运行所有代码并把输出一起导出：

```bash
uv run jupyter nbconvert \
  --to html \
  --execute \
  --ExecutePreprocessor.timeout=600 \
  notebooks/backtesting_py_交互式实战.ipynb
```

## 注意事项

- Notebook 会通过 AKShare 下载数据，首次运行需要联网。
- 下载后的数据会缓存到 `data/` 目录。
- `515450` 是场内 ETF，使用 AKShare 的 ETF 接口。
- `603993` 是 A 股股票，使用 AKShare 的股票接口。
- AKShare 支持 `1 / 5 / 15 / 30 / 60` 分钟数据，但 1 分钟数据通常只支持近 5 个交易日，长期回测建议用日线。
