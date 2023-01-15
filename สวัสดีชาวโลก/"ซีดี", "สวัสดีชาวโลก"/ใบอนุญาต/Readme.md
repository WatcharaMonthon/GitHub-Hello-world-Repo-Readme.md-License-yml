 " Hello - World " 
  
 " CD ", " hello World " 

I gained valuable experience both academically and professionally.  during my studies  I have had the opportunity to learn  Working on a variety of projects with leading organizations  I learned more about Designer, Machine Learning, Engineering Soft ware.
  การเขียนโค้ดใน Github : 

     เขียนรหัสบางอย่างเริ่มต้นด้วย  Hello,  World 

  1.  เปิดพรอมต์คำสั่งและซีดีไปยังโฮมไดเร็กตอรี่ของคุณ

 #บน Linux หรือ Mac:

 " ซีดี "  

  #บน Windows:

  " ซีดี ", " hello World "

สร้างไดเร็กทอรี hello สำหรับซอร์สโค้ด Go แรกของคุณ
ตัวอย่างเช่น ใช้คำสั่งต่อไปนี้:

mkdir สวัสดี
ซีดี สวัสดี
เปิดใช้งานการติดตามการพึ่งพาสำหรับรหัสของคุณ
เมื่อโค้ดของคุณอิมพอร์ตแพ็คเกจที่อยู่ในโมดูลอื่น คุณจะจัดการการอ้างอิงเหล่านั้นผ่านโมดูลของโค้ดของคุณเอง โมดูลนั้นถูกกำหนดโดยไฟล์ go.mod ที่ติดตามโมดูลที่มีแพ็คเกจเหล่านั้น ไฟล์ go.mod นั้นจะอยู่กับโค้ดของคุณ รวมถึงในที่เก็บซอร์สโค้ดของคุณด้วย

ในการเปิดใช้การติดตามการพึ่งพาสำหรับโค้ดของคุณโดยการสร้างไฟล์ go.mod ให้รัน go mod initคำสั่งโดยให้ชื่อโมดูลที่โค้ดของคุณจะเข้าไป ชื่อคือพาธของโมดูลของโมดูล

ในการพัฒนาจริง พาธของโมดูลจะเป็นตำแหน่งที่เก็บข้อมูลซึ่งซอร์สโค้ดของคุณจะถูกเก็บไว้ ตัวอย่างเช่น เส้นทางของโมดูลอาจgithub.com/mymoduleเป็น หากคุณวางแผนที่จะเผยแพร่โมดูลของคุณเพื่อให้ผู้อื่นใช้ เส้นทางโมดูลจะต้องเป็นตำแหน่งที่เครื่องมือ Go สามารถดาวน์โหลดโมดูลของคุณได้ สำหรับข้อมูลเพิ่มเติมเกี่ยวกับการตั้งชื่อโมดูลด้วยพาธของโมดูล โปรดดูที่ การจัดการการขึ้นต่อกัน 

 
 5.  วางโค้ดต่อไปนี้ลงในไฟล์ hello.go ของคุณและบันทึกไฟล์ : 

 "แพคเกจหลัก"

นำเข้า "fmt"

ฟังก์ชันหลัก () {
    fmt.Println("สวัสดีชาวโลก!")
} 

   #สำหรับจุดประสงค์ของบทช่วยสอนนี้ เพียงใช้ example/hello.

ตัวอย่าง : $ go mod เริ่มต้น / สวัสดี
go: สร้าง go.mod ใหม่: ตัวอย่างโมดูล/สวัสดี
ในโปรแกรมแก้ไขข้อความ ให้สร้างไฟล์ hello.go เพื่อเขียนโค้ดของคุณ

วางโค้ดต่อไปนี้ลงในไฟล์ hello.go ของคุณและบันทึกไฟล์ 

  

 6.  เรียกใช้รหัสของคุณเพื่อดูคำทักทาย : 

$ไปวิ่ง.
สวัสดีชาวโลก! 

   write some code
 Start with Hello, World.

   1. Open a command prompt and CD to your home directory.

  #On Linux or Mac:

  "CD"

   #On Windows:

   " CD ", " hello World "

 Create a hello directory for your first Go source code.
 For example, use the following command:

 hello mkdir
 cd hello
 Enable dependency tracking for your code.
 When your code imports packages that are in other modules.  You manage those dependencies through your own code modules.  Modules are defined by a go.mod file that keeps track of the modules that contain those packages. The go.mod file stays with your code.  Also included in your source code repositories.

 To enable dependency tracking for your code by creating a go.mod file, run the go mod init command, giving it the name of the module your code will go into.  Name is the module path of the module.

 in actual development  The module path is the repository where your source code will be stored. For example, the module path might be github.com/mymodule as github.com/mymodule .  If you plan to publish your module for others to use.  The module path must be where the Go tool can download your modules.  For more information about naming modules with module paths, see Managing dependencies.

 
  5. Paste the following code into your hello.go file and save the file:

  "Main package"

 import "fmt"

 function main() {
     fmt.Println("Hello world!")
 }

    #For the purpose of this tutorial, just use example/hello.

 Example : $ go mod start /hello
 go: create new go.mod: example module/hello
 In a text editor, create a hello.go file to write your code.

 Paste the following code into your hello.go file and save the file.

  

  6. Run your code to see the greeting :

 $Go for a run.
 hello world 

 CCO - CC Ventivation License
 Commons: creativecommons.org/licenses
 This work is licensed under a Creative Commons Attribution 4.0 International license.

 <a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.  

 creativecommons.org/licenses/by/4.0/"><img  alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><  br />This work uses a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.  .
