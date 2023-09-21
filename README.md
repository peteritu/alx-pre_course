root@c92bb90a43a9:/# cd alx-pre_course/
root@c92bb90a43a9:/alx-pre_course#
root@c92bb90a43a9:/alx-pre_course# echo 'My first readme' > README.md
root@c92bb90a43a9:/alx-pre_course# cat README.md My first readme
root@c92bb90a43a9:/alx-pre_course# git config --global user.email "petendiritu@gmail.com"
root@c92bb90a43a9:/alx-pre_course# git config --global user.name "Peter Ndiritu"
root@c92bb90a43a9:/alx-pre_course# git add .
root@c92bb90a43a9:/alx-pre_course# git commit -m 'My first commit'
[master (root-commit) 98eef93] My first commit
 1 file changed, 1 insertion(+)
 create mode 100644 README.md
root@c92bb90a43a9:/alx-pre_course# git push                                                                                           
Enumerating objects: 3, done.                                                                                                         
Counting objects: 100% (3/3), done.                                                                                                   
Writing objects: 100% (3/3), 212 bytes | 212.00 KiB/s, done.                                                                          
Total 3 (delta 0), reused 0 (delta 0)                                                                                                 
To https://github.com/{peteritu}/alx-pre_course.git                                                                                       
 * [new branch]      master -> master
