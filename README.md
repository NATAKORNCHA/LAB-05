#ใบงานที่ 5
##เรื่อง การใช้งานคำสั่ง Console.WriteLine()
##วัตถุประสงค์
1). เพื่อให้นักศึกษาบอกวิธีการใช้คำสั่งแสดงผลบน Text Mode ในภาษา C# ได้
2). เพื่อให้นักศึกษาสามารถปรับแต่งคำสั่งแสดงผลทางหน้าจอตามต้องการได้

##ขั้นเตรียมการทดลอง
1). สร้าง Project ตั้งชื่อเป็น Lab5 เพื่อทดลองการใช้งานคำสั่ง Console.WriteLine()
ลำดับขั้นการทดลอง
(หมายเหตุ ในรูปประกอบที่มี namespace เป็น Lab4 รบกวนแก้เป็น Lab5 ด้วยครับ)
2). ทดลองเรื่องจำนวนของอาร์กิวเมนต์ในคำสั่ง Console.WriteLine()

 2.1). แก้โปรแกรมตามรูปด้านล่างนี้

  ![](https://github.com/Desktop-Programming-Lab-2559/LAB-05/blob/master/img/pic1.png)

  2.2). รันโปรแกรม และบันทึกผลที่ได้
  
 <img src="https://github.com/NATAKORNCHA/LAB-05/blob/master/img/LAB5-1.png?raw=true">
 
 
 2.3). แก้โปรแกรมตามรูปด้านล่างนี้
 
  ![](https://github.com/Desktop-Programming-Lab-2559/LAB-05/blob/master/img/pic2.png)

 2.4). รันโปรแกรม และบันทึกผลที่ได้


  <img src="https://github.com/NATAKORNCHA/LAB-05/blob/master/img/LAB5-2.png?raw=true">


###คำถาม 5.1 เครื่องหมาย { }  ในคำสั่ง Console.WriteLine() มีลักษณะการใช้งานอย่างไร
{…} แทนตำแหน่งที่วางข้อมูลโดยใส่เลขลำดับเริ่มจาก 0
###คำถาม 5.2  ถ้ามีการใช้ตัวเลขใน { } ที่กระโดด เช่น {0} {2} {3} จะใช้งานได้หรือไม่ อย่างไร จงอธิบาย
ใช้งานได้ตำแหน่งที่เราจะแทนด้วยค่าของ object ซึ่งจะเริ่มจาก 0, 1, 2 ไปเรื่อยๆ

 
 2.5). แก้โปรแกรมตามรูปด้านล่างนี้

  ![](https://github.com/Desktop-Programming-Lab-2559/LAB-05/blob/master/img/pic3.png)

 2.6). รันโปรแกรม และบันทึกผลที่ได้

  <img src="https://github.com/NATAKORNCHA/LAB-05/blob/master/img/LAB5-3.png?raw=true">


3). ทดลองเรื่องการกำหนดความกว้างของอาร์กิวเมนต์

  3.1). แก้โปรแกรมตามรูปด้านล่างนี้

  ![](https://github.com/Desktop-Programming-Lab-2559/LAB-05/blob/master/img/pic4.png)

  3.2). รันโปรแกรม และบันทึกผลที่ได้
  
  <img src="https://github.com/NATAKORNCHA/LAB-05/blob/master/img/LAB5-4.png?raw=true">

###คำถาม 5.3 การกำหนดความกว้างของอาร์กิวเมนต์ด้วยเครื่องหมาย { , }  ในคำสั่ง Console.WriteLine() มีรูปแบบการใช้งานอย่างไร
 index เป็นจำนวนเต็มเริ่มต้นที่ศูนย์ใช้สำหรับระบุอาร์กิวเมนต์ที่ต้องการจะจัดรูปแบบเช่น ถ้า index มีค่าเป็น 0 จะหมายถึงค่าของอาร์กิวเมนต์ตัวแรกจะถูกแสดงในตำแหน่งที่ index
ปรากฏอยู่ และถ้า index มีค่าเป็น 1 จะหมายถึงค่าของอาร์กิวเมนต์ตัวที่สองจะถูกแสดงในตำแหน่งที่ index ปรากฏอยู่เป็นต้น ส่วน alignment เป็นจำนวนเต็มที่ใช้สำหรับระบุความกว้างหรือจำนวนตัวอักษรที่จะแสดงผลพร้อมกับจัดการแสดงผลแบบชิดซ้ายหรือชิดขวา ถ้า alignment มีค่าเป็นลบจะจัดชิดซ้ายและถ้า alignment มีค่าเป็นบวกจะจัดชิดขวา


4). ทดลองเรื่องการกำหนดรูปแบบของอาร์กิวเมนต์
  4.1). แก้โปรแกรมตามรูปด้านล่างนี้

  ![](https://github.com/Desktop-Programming-Lab-2559/LAB-05/blob/master/img/pic5.png)

  4.2). รันโปรแกรม และบันทึกผลที่ได้

 <img src="https://github.com/NATAKORNCHA/LAB-05/blob/master/img/LAB5-5.png?raw=true">
 
5). ทดลองเรื่องการกำหนดรูปแบบพร้อมความกว้างของอาร์กิวเมนต์
  5.1). แก้โปรแกรมตามรูปด้านล่างนี้
 
 ![](https://github.com/Desktop-Programming-Lab-2559/LAB-05/blob/master/img/pic6.png)

  5.2). รันโปรแกรม และบันทึกผลที่ได้
  
  <img src="https://github.com/NATAKORNCHA/LAB-05/blob/master/img/LAB5-6.png?raw=true">


6). ทดลองเรื่องการกำหนดรูปแบบพร้อมความกว้างของทศนิยมของอาร์กิวเมนต์
  6.1). แก้โปรแกรมตามรูปด้านล่างนี้

 ![](https://github.com/Desktop-Programming-Lab-2559/LAB-05/blob/master/img/pic7.png)

  6.2). รันโปรแกรม และบันทึกผลที่ได้
  
  <img src="https://github.com/NATAKORNCHA/LAB-05/blob/master/img/LAB5-7.png?raw=true">

## แบบฝึกหัด จงระบุ output ของบรรทัดคำสั่งต่อไปนี้

```csharp
1.  string name = "Hello";
    Console.WriteLine(String.Format("{0} there. I said {0}! {0}???", name));
2.    Console.WriteLine("{2:d} {0:d} {1:d}", 1, 2, 3);
3.    Console.WriteLine("Hello " + "World");
4.    Console.WriteLine("Here comes a slash \\");
5.    Console.WriteLine("|{0, 10}|", 999);
6.    Console.WriteLine("|{0,-10}|", 000);
7.    Console.WriteLine("The value: {0}.", 500);
8.    Console.WriteLine("The value: {0:C}.", 500);
9.    Console.WriteLine("{0,-10:F4}", 12.3456789);
10.   Console.WriteLine("{0,-10:C}", 12.3456789);
11.   Console.WriteLine("{0,-10:E3}", 12.3456789);
12.   Console.WriteLine("{0,-10:x}", 65535);
13.   Console.WriteLine("{0,-10:X}", 65535);
14.   int i; 
      Console.WriteLine("Value\tSquared\tCubed"); 
      for(i = 1; i < 10; i++) 
          Console.WriteLine("{0}\t{1}\t{2}", i, i*i, i*i*i); 
15.    Console.WriteLine("{0:#.###}.", 1234.56789);
```
<img src="https://github.com/NATAKORNCHA/LAB-05/blob/master/img/LAB5-8.png?raw=true">
