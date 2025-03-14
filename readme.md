

##  Find The Version Of Git

`git --version`

##  Create A New Git Repository

1. Go to the fold of the project.

2. Run `git init`

##  Clone An Existing Git Repository

Cloning is the process of pulling down a copy of a repository stored on a server.

1. Go to the parent folder of where you want to repository's folder to be in.

2. `git clone [url to repository's git file] [name of folder / repository you want]`

##  Check The Status Of A Git Repository

`git status`

##  Tell Git To Track A File

`git add readme.md`

##  Make A Commit

`git commit --m "First commit"`

##  Tell Git To Track A Whole Folder

`git add chapter2/`

##  Tell Git To Track (And Stage) All Files And Subfolders In A Directory

`git add -A`

##  View All Branches

`git branch`

##  Create A New Branch

`git branch new_model`

##  Switch To A Branch

`git checkout new_model`

##  Create A New Branch And Switch To It

`git checkout -b new_ux`

##  Merge One Branch Into Another

1. Switch to the branch you want to pull changes into: `git checkout master`

2. Pull changes from another branch into your branch: `git merge new_ux`

##  Set A Remote Github Repository

1. Go to GitHub.com and create a new repository.

2. Set that repository's url as the origin repo: `git remote add origin https://github.com/chrisalbon/git_tutorial.git`

##  Push Master Branch To A Github Repository

The `-u` sets the origin as the default for this branch

`git push -u origin master`

##  Pull Down From A Branch From A GitHub Repository To Local Repository

`git pull origin master`

##  Pull Down All Branches From GitHub

`git fetch origin`

##  View All Remote Branches

`git branch --remote`

##  View Log

`git log`

##  View Unstagged Changes To Files

`git diff`

##  Unstage A File

`git reset filename`

##  Undo Last Commit, Move Commits Changes To Staging

`git reset --soft HEAD^`

##  Undo Last Commit, Remove All Changes In Your Working Directory

`git reset --hard HEAD^`

##  Clone A Remote Repository Locally 

`git clone url`

##  Show Changes From A Particular Commit

`git show --pretty="format:" <commitID>`

##  Revert A Commit By Creating A New Commit With Opposite Changes

`git revert <commitID>`



##  Xem danh sách các commit kèm theo file bị thay đổi

`git log --name-only`

##  Xem danh sách file bị thay đổi trong commit cuối cùng

`git show --name-only`

## Xem chi tiết thay đổi của một file cụ thể

`git log -p [tên file]`

## Xem thông tin chi tiết của một commit

`git show [mã commit]`

## Xóa một nhánh từ xa

`git push origin --delete [tên nhánh]`

## Xóa một nhánh cục bộ

`git branch -d [tên nhánh]`

## Đổi tên một nhánh

`git branch -m [tên nhánh cũ] [tên nhánh mới]`

## Tải về và hợp nhất các thay đổi từ nhánh từ xa

`git pull`

## Tải về các thay đổi từ nhánh từ xa mà không hợp nhất

`git fetch`

## Bỏ commit cuối cùng nhưng giữ lại thay đổi

`git reset --soft HEAD~1`

## Bỏ commit cuối cùng và không giữ lại thay đổi

`git reset --hard HEAD~1`

## Xoá tất cả các thay đổi chưa được commit

`git checkout .`

