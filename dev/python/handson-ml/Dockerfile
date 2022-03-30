FROM python:3.9

RUN pip config set global.index-url https://mirrors.ustc.edu.cn/pypi/web/simple
RUN pip install --no-cache-dir jupyter matplotlib numpy pandas scipy scikit-learn

VOLUME [ "/workspace" ]