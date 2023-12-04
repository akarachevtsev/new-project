mkdir new-project
cd new-project
git init
echo init > README.md
git add README.md
git commit -m "init"
git branch -M main
git checkout -b development
git add README.md
git commit -m "Add instructions to README.md"
git checkout main
git merge development
git satus
git commit -m "Merging development to main"
