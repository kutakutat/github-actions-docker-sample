# github-actions-docker-sample


## Descripotion

Github Actions の動作検証を行うためのリポジトリです。
[Configure GitHub Actions](https://docs.docker.com/ci-cd/github-actions/#optimizing-the-workflow) を参考にしています。

## How to Use

```bash
#Run
docker run -p80:80 github-actions-docker-sample

# Build
docker build -t github-actions-docker-sample .



```