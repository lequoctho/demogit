1. git init
2. git status
3. git add *tên file* ( hoặc git add . (. để thêm tất cả các file))
4. git commit -m 'message'

5. git log (xem lịch sử commit)
6. git show *mã tem* (xem chi tiết 1 lịch sử commit)
7. git diff (để xem sự thay đổi của file đã modify)

8. gitk (mở GUI)

**thuật ngữ
	+ working directory
	+ staging area
	+ git repository
**
9. git checkout *tên file* (undo lại file đã modify ) tương tự có git restore *tên file*
10. git reset *tên file* (reset 1 file không add nữa)

11. git checkout -b <branch> (tạo ra nhánh và sử dụng trên nhánh này)
12. git checkout <branch> (chuyển sang nhánh này sử dụng)
13. git merge (merge vào nhánh nào đó)
14. git branch (check đang ở branch nào)
15. git branch -D <branch> (delete a branch)