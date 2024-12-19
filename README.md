# lab5

## Point: 2

### Point:  2.1 - 2.2

![image](https://github.com/user-attachments/assets/23856b05-a386-4a9d-8f52-0581397a461a)

### Point:  2.3

1. cd .
  ```   
คำอธิบาย: . หมายถึง ไดเรกทอรีปัจจุบัน (current directory)

ผลลัพธ์: ไม่มีการเปลี่ยนแปลงตำแหน่ง (ยังอยู่ในไดเรกทอรีเดิม)
 ``` 
2. cd ..
 ``` 
คำอธิบาย: .. หมายถึง ไดเรกทอรีระดับบน (parent directory)

ผลลัพธ์: จะย้ายไปยังไดเรกทอรีที่อยู่เหนือไดเรกทอรีปัจจุบัน
 ``` 
3. cd ~
 ``` 
คำอธิบาย: ~ หมายถึง ไดเรกทอรีบ้านของผู้ใช้ (home directory) ซึ่งเป็นตำแหน่งเริ่มต้นของผู้ใช้งาน

ผลลัพธ์: จะย้ายไปยังไดเรกทอรี /home/<username> (ในกรณีนี้คือ /home/tonnoon2005)
 ``` 
4. cd /
 ```    
คำอธิบาย: / หมายถึง root directory หรือโฟลเดอร์ราก ซึ่งเป็นตำแหน่งสูงสุดในโครงสร้างของไฟล์ระบบ

ผลลัพธ์: จะย้ายไปยังไดเรกทอรี /
 ``` 
5. cd $
 ```   
คำอธิบาย: $ ไม่มีความหมายในบริบทของคำสั่ง cd (มันอาจหมายถึงการเรียกตัวแปรใน shell แต่ต้องตามด้วยชื่อของตัวแปร เช่น $HOME)

ผลลัพธ์: `ระบบแจ้งว่า "No such file or directory" เนื่องจากไม่มีไฟล์หรือไดเรกทอรีชื่อ $`
 ``` 
สรุป

cd . : อยู่ในไดเรกทอรีเดิม

cd .. : ถอยกลับไปยังไดเรกทอรีแม่

cd ~ : กลับไปยังไดเรกทอรีบ้านของผู้ใช้

cd / : ไปยังไดเรกทอรีรากของระบบ

cd $ : ใช้ผิด เพราะ $ ต้องตามด้วยตัวแปรที่ถูกต้อง เช่น $HOME

### Point: 2.4
  
![image](https://github.com/user-attachments/assets/492b2b3c-8d39-407f-87bc-3a5b0b4c30c7)


## Point: 3

### Point: 3.1

![image](https://github.com/user-attachments/assets/222f83e1-f7f4-4fa7-ab5d-19e50de335d6)


### Point: 3.2

![image](https://github.com/user-attachments/assets/47832afb-ea03-47ec-8797-9561badfc265)


![image](https://github.com/user-attachments/assets/61372802-f18f-49af-94f7-cba1e05c0bb2)


### Point: 3.3

ls: Lists the contents of a directory in a simple format (files and directories only, without details).

ls -alt:

 ```
-a: Shows all files, including hidden files (those starting with a .).
-l: Provides a detailed list (permissions, ownership, size, etc.).
-t: Sorts the list by modification time, showing the most recently modified files first.
 ```
### Point: 3.4

![image](https://github.com/user-attachments/assets/ca0d5d8f-c2ec-4c70-991b-b5845d67eee6)


### Point: 3.5 - 3.6

![image](https://github.com/user-attachments/assets/d38774bd-457c-4136-82d6-c77f348aa6f4)


### Point: 3.7 - 3.10

![image](https://github.com/user-attachments/assets/55027941-694c-41e3-b862-2fb0da0fe921)


![image](https://github.com/user-attachments/assets/31f41a39-c9a5-47e3-8b46-01c631f5cd8f)


## Point: 4

### Point: 4.1

![image](https://github.com/user-attachments/assets/39bf7e80-1da0-4b87-bffd-74db02393a42)


### Point: 4.2

![image](https://github.com/user-attachments/assets/0fdcc414-23a4-4e58-8d23-d7be064c6158)


### Point: 4.3

![image](https://github.com/user-attachments/assets/58d70d22-251d-4d32-bea5-7da24443568f)


wc name.csv: Stands for "word count". It outputs:
```
Number of lines,
Number of words,
Number of characters in the file.
```

### Point: 4.4

![image](https://github.com/user-attachments/assets/08975200-e746-4b29-87a4-553739ef52a4)


### Point: 4.5

cat: Displays the full content immediately.

more: Paginates the content for better readability in large files.

head: Displays the start of the file (first 10 lines).

tail: Displays the end of the file (last 10 lines).

wc: Counts lines, words, and characters; use -l to count only lines.

## Point: 5

### Point: 5.2

![image](https://github.com/user-attachments/assets/2fe543f7-fdc1-4115-8175-ca8cb34da9c1)


### Point: 5.3

![image](https://github.com/user-attachments/assets/e14f392c-d2de-4138-a18f-49775ff7edf5)


### Point: 5.4 - 5.5

![image](https://github.com/user-attachments/assets/4fa6e846-2662-4b2e-a130-35350ef57033)


### Point: 5.6


- 5.1 What is an environment variable?

คำตอบ: Environment Variable คือค่าที่กำหนดไว้ในระบบปฏิบัติการเพื่อเก็บข้อมูลที่เกี่ยวข้องกับการตั้งค่าของโปรแกรมและระบบ ตัวแปรเหล่านี้ช่วยให้กระบวนการ (process) และโปรแกรมสามารถแชร์ข้อมูลที่สำคัญร่วมกันได้ เช่น:
```
PATH: กำหนดไดเรกทอรีสำหรับการค้นหาโปรแกรม
HOME: โฟลเดอร์บ้านของผู้ใช้งาน
USER: ชื่อผู้ใช้ที่ล็อกอินในระบบ
```
ตัวแปรเหล่านี้ถูกจัดเก็บเป็นคู่ key=value และสามารถเรียกดูได้ด้วยคำสั่ง เช่น printenv หรือ env


- 5.2 What does the command echo $PATH output and what does it mean?

คำตอบ: คำสั่ง echo $PATH ใช้สำหรับแสดงค่าของ Environment Variable ที่ชื่อ PATH ซึ่งเป็นรายการของไดเรกทอรีที่ระบบจะค้นหาเมื่อคุณพิมพ์คำสั่ง ตัวอย่างผลลัพธ์:

javascript
```
/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin
```
ความหมาย:

แต่ละไดเรกทอรีใน PATH คั่นด้วย :

เมื่อคุณรันคำสั่ง เช่น ls ระบบจะค้นหาไฟล์ที่ชื่อ ls ในไดเรกทอรีเหล่านี้ตามลำดับ


- 5.3 What does the man which explain about the which command?

คำตอบ: 
```
คำสั่ง man which แสดงคู่มือของคำสั่ง which ซึ่งใช้สำหรับค้นหา absolute path ของคำสั่งหรือโปรแกรม
```

- 5.4 What is the absolute path of the ls command?
  
คำตอบ: ใช้คำสั่ง:
```
which ls

ผลลัพธ์: /bin/ls

Absolute Path ของ ls: /bin/ls
```
- 5.5 What is the absolute path of the man command?
  
คำตอบ: ใช้คำสั่ง:
```
which man

ผลลัพธ์: /usr/bin/man

Absolute Path ของ man: /usr/bin/man

```

## Point: 6

### Point: 6.1

![image](https://github.com/user-attachments/assets/e8244105-9787-4862-bc74-2946fe9ef38d)


### Point: 6.2

![image](https://github.com/user-attachments/assets/b4e140e0-d592-48c1-b8e7-f7de2e07fdca)


### Point: 6.3

![image](https://github.com/user-attachments/assets/906ee9b1-a824-4bc0-8290-c6f8ab57e9b0)


![image](https://github.com/user-attachments/assets/d48a2c51-2da1-4bfa-a75f-7e0f1ab59d5e)


### Point: 6.4

![image](https://github.com/user-attachments/assets/46bc2700-c0e0-4687-a872-b664fab9088e)


### Point: 6.5

- 6.1 Find your IP using the ifconfig command

คำสั่ง ifconfig ใช้เพื่อแสดงข้อมูลการตั้งค่าของเครือข่าย รวมถึง IP Address ของอินเทอร์เฟซเครือข่าย

คำสั่ง:
```
ifconfig
```

***หมายเหตุ: หากคำสั่ง ifconfig ไม่พร้อมใช้งาน ให้ติดตั้งด้วย: sudo apt install net-tools***

- 6.2 Find the IP of www.google.com using the nslookup command

คำสั่ง nslookup ใช้สำหรับค้นหา IP Address ของโดเมนผ่าน DNS (Domain Name System)

คำสั่ง:
```
nslookup www.google.com
```

***หมายเหตุ: หาก nslookup ไม่พร้อมใช้งาน ให้ติดตั้งด้วย: sudo apt install dnsutils***

- 6.3 Try to use ping and traceroute commands and explain what they are for
  
คำสั่ง ping

คำอธิบาย:ใช้ทดสอบความเชื่อมต่อระหว่างเครื่องของคุณและปลายทาง โดยส่งแพ็กเก็ต ICMP และตรวจสอบการตอบกลับ

คำสั่ง:
```
ping www.google.com
```

คำสั่ง traceroute

คำอธิบาย: ใช้ตรวจสอบเส้นทาง (hops) ที่ข้อมูลเดินทางจากเครื่องของคุณไปยังปลายทาง

คำสั่ง:
```
traceroute www.google.com
```

***หมายเหตุ: หาก traceroute ไม่พร้อมใช้งาน ให้ติดตั้งด้วย: sudo apt install traceroute***

6.4 Execute netstat -n and explain what the resultant table is

คำอธิบาย:คำสั่ง netstat -n ใช้เพื่อแสดงตารางการเชื่อมต่อเครือข่ายในรูปแบบตัวเลข (numeric)

คำสั่ง:
```
netstat -n
```

***หมายเหตุ: หาก netstat ไม่พร้อมใช้งาน ให้ติดตั้งด้วย: sudo apt install net-tools***



## Point: 7

### Point: 7.1

คำอธิบาย:

- คำสั่ง top ใช้สำหรับแสดงข้อมูลเกี่ยวกับกระบวนการ (processes) และทรัพยากรระบบ เช่น CPU, RAM และ Swap ที่ถูกใช้งานแบบเรียลไทม์
- มีประโยชน์สำหรับการตรวจสอบสถานะของระบบ เช่น:
- ดูว่ากระบวนการใดใช้ CPU หรือ RAM มากที่สุด
- ตรวจสอบว่าเครื่องมีการทำงานหนักหรือไม่
  
![image](https://github.com/user-attachments/assets/78e0880d-c87a-483c-8091-59538b5aba3f)


***การออกจากคำสั่ง: กด q เพื่อออกจาก top***

### Point: 7.2 - 7.3

คำอธิบาย:

- htop เป็นเครื่องมือที่คล้ายกับ top แต่มีอินเทอร์เฟซที่ใช้งานง่ายกว่า (แสดงผลในรูปแบบสีและสามารถเลื่อนดูได้)
- ผู้ใช้สามารถเลือกกระบวนการและจัดการ (kill, renice) ได้ง่ายขึ้น
  
![image](https://github.com/user-attachments/assets/50a6b14c-f5c0-4e74-98a9-ff3a927b3b36)


***หากยังไม่มี htop ให้ติดตั้งด้วยคำสั่ง: sudo apt install htop***

# 
Natthaphum Chaikhan 662115016

