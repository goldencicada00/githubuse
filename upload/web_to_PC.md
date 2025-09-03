# 從`github網頁`上傳更新到`電腦資料夾`
###  支援情況:`github網頁`有更新；`電腦資料夾`無更新
1. `cd 你的專案資料夾`
2. `git status`         # 檢查是否乾淨（nothing to commit, working tree clean）
3. `git branch --show-current`         # 看目前分支，通常是 main
4. `git remote -v`         # 確認遠端是 origin
5. `git fetch origin`      # 抓最新的遠端資訊
6. `git switch main`       # 若你不是在 main，先切回 main（或你使用的分支名）
7. `git pull --rebase origin main`   # 把 GitHub 上的改動拉回來
