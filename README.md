# spider-task-01\

## git commands used \

```bash
git clone {repoLink}\
cd spider-task-01\
new-item commit1_master.txt\
start commit1_master.txt\
git add .&&git commit -m "commit 1"\
git checkout -b Develop\
new-item commit2_Develop.txt\
start commit2_Develop.txt\
git add .&&git commit -m "commit 2"\
git checkout master\
new-item commit3_master.txt\
start commit3_master.txt\
git add .&&git commit -m "commit3"\
git checkout Develop\
new-item commit4_spider.txt\
start commit4_spider.txt\
git add .&&git commit -m "commit 4"\
git checkout master\
git merge Develop\
git checkout -b spider\
new-item commit5_spider.txt\
start commit5_spider.txt\
git aadd .&&git commit -m "commit 5"\
new-item commit6_spider.txt\
start commit6_spider.txt\
git add .&&git commit -m "commit 6"\
git checkout master\
git merge spider\
git branch -d spider\
git branch -d Develop\
git push origin master\

```
