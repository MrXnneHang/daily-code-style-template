## 这里是 PaddlePaddle 的 CPP 和 Python 代码风格空仓库

详细参见`.pre-commit-config.yaml`文件<br>

你需要做的是：<br>

```shell
pip install pre-commit
pre-commit install
pre-commit run --all-files
```

不建议直接对大仓库进行代码规格化，会疯掉。<br>

建议之后自己要写 Python+CPP 的时候可以直接从这个基础上开始。<br>

而单纯 Python 的仓库，在那个主分支上有 black+isort ，实际上应该再加一个 Linter。<br>
