#noun
repository(repo)

#command
git init // khoi tao tao repo
git status // hien thi trang thai du an
git add // vao trang thai chuan bi luu
git reset // quay lai trang thai chuan bi luu

git commit // luu vao repo

git log // xem lai thoi diem commit

git log --oneline  // thu gon cua git log

git checkout {id_commit} // quay lai thoi diem commit nao do


git checkout {branch_name} // quay lai hien tai

git branch 

git checkout -b {branch_name}  // tao branch

git merge {branch_name} // tron vao branch hien tai

git branch -d {branch_name} // xoa branch

git push {url} {branch_name} // dua du an len github

git remote add {name} {url}  //thay url bang name

git push {name} {branch_name} //dua du an len github

git push -u {name} {branch_name} // dua branch tu local len remote

[
    nap branch tu remote vao local
    git fetch {name}
    git checkout -b {branch_name} {name}/{branch_name}
]

