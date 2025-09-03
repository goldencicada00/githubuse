# 從`電腦資料夾`上傳更新到`github網頁`
### 支援`電腦資料夾`有更新且`github網頁`有更新之情況
1. `git add -A`
2. `git commit -m "remove logs stats.json"`   # 先把本機變更記錄起來
3. `git pull --rebase origin main`            # 取回遠端並把你的提交接在最前面
4. `git push`                                  # 推上遠端
