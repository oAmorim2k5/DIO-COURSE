
# DIO | Summary Git and GitHub

Repository to store my overview of Git and GitHub, of the course "Versionamento de Código com Git e GitHub da [Digital Innovation One](https://www.dio.me/).

## 📖 Documentation

- [Documentation Git](https://git-scm.com/doc)
- [Documentation GitHub](https://docs.github.com/)

## 🖥️ Lessons overview
| Class | Overview |
|---------|----------|
| Creating and Cloning repository | [overview](https://web.dio.me/course/versionamento-de-codigo-com-git-e-github/learning/a377a00b-461c-4ab0-8258-3addd2fef14c?back=/track/microsoft-azure-ai-fundamentals&tab=undefined&moduleId=undefined)
| Restoring changes on local repository | [overview](https://web.dio.me/course/versionamento-de-codigo-com-git-e-github/learning/3f9f2336-6fd5-44cb-ba39-d1a4f6448023?back=/track/microsoft-azure-ai-fundamentals&tab=undefined&moduleId=undefined)
| Sending and Uploading changes from remote repository | [overview](https://web.dio.me/course/versionamento-de-codigo-com-git-e-github/learning/dd17c56e-2327-493c-942a-358a49a26549?back=/track/microsoft-azure-ai-fundamentals&tab=undefined&moduleId=undefined)
| Branches | [overview](https://web.dio.me/course/versionamento-de-codigo-com-git-e-github/learning/2c7fd2b1-e7c4-4947-9b07-ffcbfb4bd689?back=/track/microsoft-azure-ai-fundamentals&tab=undefined&moduleId=undefined)

### Create and Conect
```
git init
touch README.md
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/oAmorim2k5/DIO-COURSE.git
git push -u origin main
```

### Delete and Restore
```
rm -rf .git - Delete

git restore - Restore
git restore --staged "archive name"
git reset "archive name"
```

### Edit Last Commit and Reset
```
git commit --amend -m"Title" - Edit

git reset --soft hash-commit 
git reset --mixed "" or git reset ""
git reset --hard ""
```

### Copy repository
```
git remote add origin {Git repository url}
git pull -u origin main
```

### Branches
```
git checkout -b branch-name - Create a new branch
git merge teste - Merge branch test in main, if u are on main branch
git branch -d teste - To delete a Branch
```

## 🔍 References
- [DIO - Digital Innovation One](https://web.dio.me/home)
- [DIO - Eliana](https://github.com/elidianaandrade/dio-curso-git-github)

## 🐵 Curiosity
```
https://github.dev/oAmorim2k5/DIO-COURSE/blob/main/README.md

Switch github.com to github.dev to open git web editor. -"like vscode"

ERROR:
 ! [rejected]    main -> main (fetch first)
error: failed to push some refs to 'https://github.com/oAmorim2k5/DIO-COURSE.git'
hint: Updates were rejected because the remote contains work that you do not
hint: have locally. This is usually caused by another repository pushing to
RESOLUTION:
Use the command git pull to download recent changes from the remote repository for your local repository.
```
