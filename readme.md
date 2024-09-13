# Source: [Youtube](https://www.youtube.com/watch?v=QE_mkDiu4hE&t=1868s).

# Terms
- Repository
- Branch
- Conflict
- Local
- Remote

# Commands
## 1. Cac lenh khoi tao git
- git init 
- git status
- git add / git reset
- git commmit -m "..."
- git log / git log -- oneline
- git checkout {id/branch_name} *Chuyen nhanh*
- git branch
- git checkout -b {branch_name} *Tao nhanh moi tren local*
- git branch -d {branch_name} *Xoa nhanh*
## 2. Lenh gop 2 nhanh
- git merge {branch_name}

## 3. Cac lenh dua du lieu len github
- git remote add/set-url {name_alias/origin} {link}
- git push {link} {branch_name}
- git push -u {link} {branch_name} *push du lieu len 1 nhanh*

## 4. Cac lenh tai du lieu ve local
- git clone {link}
- git fetch origin
- git checkout -b {branch_name} origin/{branch_name} *clone 1 nhanh ve local*

## 5. Cap nhat du lieu tren github ve local
- git pull