# หัวเรื่อง (Headings)

# h1 หัวเรื่อง
## h2 หัวเรื่อง
### h3 หัวเรื่อง
#### h4 หัวเรื่อง
##### h5 หัวเรื่อง
###### h6 หัวเรื่อง



# รูปแบบตัวอักษร 


**ตัวหนาแบบที่ 1**

__ตัวหนาแบบที่ 2__

*ตัวเอียงแบบที่ 1*

_ตัวเอียงแบบที่ 2_

~~ขีดฆ่า~~


# อ้างอิง (Blockquotes)

> อ้างอิงแบบปกติ
>> อ้างอิงซ้อนในอ้างอิง
> > > อ้างอิงซ้อนสามกันไปเลย


# รายการ (List)

## แบบไม่เรียงลำดับ (Unordered)

+ การสร้างรายการแบบไม่เรียงลำดับให้ขึ้นต้นบรรทัดด้วยเครื่องหมาย `+`, `-`, หรือ `*`
*  การสร้างรายการย่อยให้เคาะเว้นวรรค 2 ครั้ง 
  - เครื่องหมายด้านหน้าจะถูกเปลี่ยนก็ต่อเมื่อมีการขึ้นรายการใหม่
    * รายการที่ 1
    + รายการที่ 2
    - รายการที่ 3
+ รายการใหม่

## แบบเรียงลำดับ (Ordered)

1. รายการที่ 1
2. รายการที่ 2
3. รายการที่ 3


1. คุณสามารถทำให้ตัวเลขรันแบบต่อเนื่องได้
9. โดยใส่เลข `1.` หรือเลขใด ๆ ก็ได้

### สามารถกำหนดตัวลขเริ่มต้นของรายการ

20. โดยระบุตัวเลขที่คุณต้องการให้เป็นค่าเริ่มต้น
1. ค่าต่อ ๆ ไปก็ใส่เป็นเลข `1.` หรือเลขใด ๆ ก็ได้
1. เพื่อให้รายการต่อ ๆ ไปรันเลขต่อจากเลขที่เรากำหนดเป็นค่าเริ่มต้น

# โค้ด (Code)

การใส่โค้ดในบรรทัดนั้น (Inline) `code`

## การใส่โค้ดแบบหลายบรรทัดโดยการเคาะเว้นวรรค

    // คอมเม้นโค้ด
    สำหรับบการใส่โค้ดแบบหลายบรรทัดโดยการเว้นวรรค
    ต้องเริ่มเคาะเว้นวรรคอย่างน้อย 4 ครั้ง
    ถึงจะแสดงผลได้ตามที่ต้องการ


## การใส่โค้ดโดยใช้เครื่องหมาย backtick " ` " 

```
การสร้างโค้ดโดยใช้เครื่องหมาย backtick " ` " 3 ตัว
จะต้องสร้างปิดด้านบนและด้านล่างโค้ดของเรา
```

## ระบุ Syntax highlighting ของโค้ดเรา


``` js
var foo = function (bar) {
  return bar++;
};

console.log(foo(5));
```

# ตาราง (Tables)


| เรื่อง   | รายละเอียด   |
| ------ | ----------- |
| เรื่อง 1 | รายละเอียด 1 |
| เรื่อง 2 | รายละเอียด 2 รายละเอียด 2 |
| เรื่อง 3 | รายละเอียด 3 |

## จัดชิดขวา


| เรื่อง        | รายละเอียด    |
| ----------: | -----------: |
| เรื่อง 1      | รายละเอียด 1  |
| เรื่อง 2 เรื่อง | รายละเอียด 2 รายละเอียด 2 |
| เรื่อง 3      | รายละเอียด 3  |

## จัดชิดซ้าย

| เรื่อง        | รายละเอียด    |
| :---------- | :----------- |
| เรื่อง 1      | รายละเอียด 1  |
| เรื่อง 2 เรื่อง | รายละเอียด 2 รายละเอียด 2 |
| เรื่อง 3      | รายละเอียด 3  |

## จัดกลาง

| เรื่อง        | รายละเอียด    |
| :---------: | :----------: |
| เรื่อง 1      | รายละเอียด 1  |
| เรื่อง 2 เรื่อง | รายละเอียด 2 รายละเอียด 2 |
| เรื่อง 3      | รายละเอียด 3  |

# ลิงก์ (Links)


[ลิงก์](https://memokit.me)

[ลิงก์พร้อมแสดงไตเติ้ล](https://memokit.me "ลิงก์พร้อมแสดงไตเติ้ล")

ใส่ลิงก์อัตโนมัติ https://memokit.me 

# เส้นแบ่ง, เส้นคั่น

---
---
---
---
---

# รูปภาพ (Images)

![Indy](https://raw.githubusercontent.com/memokit/exam-markdown/master/790268.jpg)
![Luffy](https://raw.githubusercontent.com/memokit/exam-markdown/master/790267.jpg "Luffy Cat")

