#cmd操作

###dir(directory:目录)

`dir` 显示当前目录中的文件和子目录

`dir /a`显示当前目录中的文件和子目录，包括隐藏文件和系统文件a = all  

`dir c: /a:d` 显示 C 盘当前目录中的目录 d = directory  

`dir c: /a:-d` 显示 C 盘根目录中的文件 -d = not directory   

`dir c:\ /b/p`　　/b只显示文件名，/p分页显示  p = page  

`dir *.exe /s`　　显示当前目录和子目录里所有的.exe文件 

---

`cd\` 进入根目录

`cd`  进入

`d:`  进入d盘

---

`md d:\a\b\c`　如果 d:\a 不存在，将会自动创建中级目录  
          
如果命令扩展名被停用，则需要键入 mkdir \a\b\c。

---

`rd abc　`　删除当前目录里的 abc 子目录，要求为空目录  

`rd /s/q d:\temp` 删除 d:\temp 文件夹及其子文件夹和文件，/q安静模式  

---
 
`del d:\test.txt`删除指定文件，不能是隐藏、系统、只读文件 　　   
  
删除 d:\temp 文件夹里面的所有文件，包括隐藏、只读、系统文件，不包括子目录  
`del /q/a/f d:\temp\*.*  `  
  
删除 d:\temp 及子文件夹里面的所有文件，包括隐藏、只读、系统文件，不包括子目录  
`del /q/a/f/s d:\temp\*.*  `

---

`ren d:\temp tmp　` 支持对文件夹的重命名  

---

`copy 1.txt + 2.txt 3.txt ` 将1和2合并为3