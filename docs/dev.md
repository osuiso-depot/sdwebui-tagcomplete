```bash
# set upstream
git remote add upstream https://github.com/DominikDoom/a1111-sd-webui-tagcomplete

# 元リポジトリの最新変更を取得
git fetch upstream

# ローカルブランチに反映
git merge upstream/main

# 自分のforkに反映
git push origin main
```
