# js-lab-39
### Lab39 Conditiona: Guess Result14
โค้ดด้านล่าง มีคำสั่ง alert อันไหนบ้างที่จะทำงาน   
หริณ มาเบ้า

```JavaScript
if (-1 || 0) alert('first');
if (-1 && 0) alert('second');
if (null || (-1 && 1)) alert('third');
```
```shell
if (-1 || 0) alert('first'); -----> ทำงาน
if (-1 && 0) alert('second'); -----> ไม่ทำงาน เพราะ (-1 && 0) คืนค่า 0 false 
if (null || (-1 && 1)) alert('third'); -----> ทำงาน
```
