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

16. git reset --soft *mã* (reset trở về commit theo mã id, và các file của các commit bị reset sẽ trở về trạng thái đã add)
17. git reset --mixed *mã* (reset trở về commit theo mã id, và các file của các commit bị reset sẽ trở về trạng thái chưa add)
18. git reset --hard *mã* (reset trở về commit theo mã id, và các file của các commit bị xóa đi hết)

19. git revert *mã* (revert lại commit có mã id và nên hạn chế revert lại commit có version quá cũ)

** thuật ngữ ** 
.gitignore : chứa những folder, file mà không muốn commit lên ví dụ như node module

20. git remote add origin *link github* (pull repo về)
21. git push (để push code lên repo)