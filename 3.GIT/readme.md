## GIT

1. slide 27 repository ให้สร้าง git repository ใหม่ ขึ้นมาว่า git test ทำการสร้าง folder ที่จะเก็บไฟล์ภายในเครื่อง คลิกขวาที่ folder ที่สร้างขึ้นมาใหม่และรัน git bash

   - ทำการเชื่อม github กับ computer เรา
   - สร้างไฟล์ Readme.md
     > [git test](https://github.com/cchayanin/git-test)

2. slide 34 markdown ให้ลองเขียน markdown file สร้าง README.md ให้ใส่รายละเอียด reprository หรือ ข้อมูลพื้นฐานต่างๆ

   - ใช้คำสั่ง header
   - สร้าง link
   - สร้าง list
   - สร้าง ตัวหนา ตัวเอียง
   - สร้าง `<hr>`
   - สร้าง blockquotes

3. slide 43 git flow

   - ให้ลองเขียน สร้างไฟล์ .txt
   - พิมพ์ข้อความอะไรก็ได้  
     ![text](./slide43/text.png)
   - save และ ทำการ add file ขึ้น repository ของเรา
   - เข้าไปเช็คว่าไฟล์ของเราขึ้นไปหรือไม่ที่เว็บ git  
     ![add](./slide43/add.png)
   - ลองลบไฟล์ .txt ออก
   - ลอง git restore จาก repo มาที่เครื่องเรา  
     ![restore](./slide43/restore.png)

4. slide 50 git branch

   - สร้าง branch ใหม่ด้วย
   - git branch
   - checkout ไป branch ใหม่
   - สร้าง ไฟล์ .txt
   - แก้ไข ไฟล์ .txt
   - upload file ขึ้น branch ใหม่
   - สลับกลับมา master
   - ดูการเปลี่ยนแปลงที่เกิดขึ้น  
     ![branch](./slide50/branch.png)
   - ลบ branch ด้วย
   - git branch -d branch_name
   - ลอง ใช้คำสั่ง git checkout -b branch_name
   - สร้างไฟล์ .txt upload
   - สลับมา master
   - ดูการเปลี่ยนแปลง  
     ![checkout](./slide50/checkout.png)

5. slide 56 git merge

   กรณีมี conflict

   - แก้ไข file .txt ใน master  
     ![master](./slide56/master.png)
   - push ขึ้น repo
   - สลับไป branch ที่สร้างเมื่อกี้
   - แก้ไข file.txt ให้ไม่เหมือนใน master  
     ![feature](./slide56/feature.png)
   - push ขึ้น repo
   - ทำการ merge เข้ากับ master  
     ![merge](./slide56/merge.png)  
     ![accept](./slide56/accept.png)

   กรณี ไม่มี conflict

   - สลับมา branch ใหม่
   - แก้ไขไฟล์ .txt  
     ![edit2](./slide56/edit2.png)
   - push ขึ้น repo
   - ทำการ merge เข้ากับ master
     ![merge2](./slide56/merge2.png)
   - อีกรอบ
   - กรณีมี การเพิ่ม comment  
     ![comment](./slide56/comment.png)
   - สลับมา branch ใหม่
   - แก้ไขไฟล์ .txt แบบ comment
   - push ขึ้น repo
   - ทำการ merge เข้ากับ master อีกรอบ  
     ![merge3](./slide56/merge3.png)

6. slide 65 git rebase

   กรณีมี conflict

   - สร้าง branch ใหม่
   - แก้ไข file .txt ใน master  
     ![master](./slide65/master.png)
   - push ขึ้น repo
   - สลับไป branch ที่สร้างเมื่อกี้
   - แก้ไข file.txt ให้ไม่เหมือนใน master  
     ![rebase](./slide65/rebase.png)
   - push ขึ้น repo
   - ทำการ rebase เข้ากับ master  
     ![conflict](./slide65/conflict.png)  
     ![continue](./slide65/continue.png)

   กรณี ไม่มี conflict

   - สลับมา branch ใหม่
   - แก้ไขไฟล์ .txt  
     ![edit2](./slide65/edit2.png)
   - push ขึ้น repo
   - ทำการ rebase เข้ากับ master อีกรอบ  
     ![rebase2](./slide65/rebase2.png)

7. slide 69 git ignore

   - ลอง สร้างไฟล์ .html, .css, .js
   - push repo  
     ![new](./slide69/new.png)
   - ignore ไฟล์ .html  
     ![html](./slide69/html.png)
   - git rm --cached file_name
   - push repo  
     ![rmhtml](./slide69/rmhtml.png)
   - edit ignore ไฟล์ .css  
     ![css](./slide69/css.png)
   - push repo
   - git rm --chached file_name
   - push repo
     ![rmcss](./slide69/rmcss.png)
   - edit ignore ไฟล์ .js  
     ![js](./slide69/js.png)
   - push repo
   - git rm --cached file_name
   - push repo  
     ![rmjs](./slide69/rmjs.png)
