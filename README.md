📌 Git boshlang‘ich commandalar

git init — yangi git repository yaratadi

git clone <repo_url> — remote repositoriyani kompyuterga ko‘chiradi

git status — fayllar holatini ko‘rsatadi

git config --global user.name "Ism" — git username sozlash

git config --global user.email "email@gmail.com" — git email sozlash

📌 Fayllar bilan ishlash

git add . — barcha o‘zgarishlarni stage ga qo‘shadi

git add <file> — bitta faylni stage ga qo‘shadi

git reset <file> — stage dan chiqaradi

git restore <file> — faylni oldingi holatiga qaytaradi

📌 Commit qilish

git commit -m "commit message" — commit yaratadi

git commit --amend — oxirgi commitni o‘zgartiradi

git log — commitlar tarixini ko‘rsatadi

git log --oneline — qisqa ko‘rinish

📌 Branch bilan ishlash

git branch — barcha branchlarni ko‘rsatadi

git branch <branch_name> — yangi branch yaratadi

git checkout <branch_name> — branchga o‘tadi

git checkout -b <branch_name> — branch yaratib o‘tadi

git switch <branch_name> — branchga o‘tish (yangi usul)

git switch -c <branch_name> — yangi branch yaratib o‘tadi

git branch -d <branch_name> — branchni o‘chiradi

📌 Merge & Rebase

git merge <branch> — branchlarni birlashtiradi

git rebase <branch> — commitlarni qayta joylaydi

git merge --abort — merge ni bekor qiladi

📌 Remote (GitHub/GitLab)

git remote -v — remote manzillar

git remote add origin <url> — remote qo‘shadi

git push origin <branch> — kodni serverga yuboradi

git pull origin <branch> — serverdan yangilaydi

git fetch — yangilanishlarni yuklab oladi

📌 Xatolarni qaytarish (Undo)

git reset --soft HEAD~1 — commitni bekor qilib stage da qoldiradi

git reset --mixed HEAD~1 — commitni bekor qiladi

git reset --hard HEAD~1 — hammasini o‘chiradi ⚠️

git revert <commit_id> — xavfsiz bekor qilish

📌 Stash (vaqtincha saqlash)

git stash — o‘zgarishlarni vaqtincha saqlaydi

git stash list — stashlar ro‘yxati

git stash pop — oxirgi stashni qaytaradi

git stash clear — hammasini o‘chiradi

📌 Tekshiruv va taqqoslash

git diff — o‘zgarishlarni ko‘rsatadi

git show <commit_id> — commit ichini ko‘rsatadi

git blame <file> — kim qaysi qatorni yozganini ko‘rsatadi