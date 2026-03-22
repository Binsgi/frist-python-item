# 本项目依赖于pygame库

## 检查pygame

1. ### 运行`.py`文件
```python
import pygame
print(pygame.version.ver)  # 或者使用 print(pygame.__version__)
```
2. ### 使用终端命令行 `python -m pygame --version`

---

## 下载pygame
1. 创建虚拟环境
```bash
# Windows (CMD/PowerShell)
python -m venv venv
# 或者
py -m venv venv

# macOS / Linux
python3 -m venv venv
```

2. 激活虚拟环境
```cmd
venv\Scripts\activate
```

3.下载pygame `pip install pygame`
