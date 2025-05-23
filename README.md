# perfex
CRM
cd C:/Users/Debora/Desktop/flutex_admin/flutex_admin
git init
git remote add origin https://github.com/tuonomeutente/nomerepo.git
git add .
git commit -m "Prima versione"
git branch -M main
git push -u origin main
git add codemagic.yaml
git commit -m "Add Codemagic iOS build workflow"
git push
