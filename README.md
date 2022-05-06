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


## 環境とブランチ
### ブランチ
- main
- develop
- feature/xxxx

### 環境

### 本番環境

以下の 2 つのイベントでデプロイされます
1. main ブランチへの push
2. main ブランチへの pull request の merge 
### ステージング環境
1. develop ブランチへの push
2. develop への pull request の merge 