---
title: "[ไทย] วิธีลง Tales Runner : Dream Journey by HOFTales บน Linux ง่าย ๆ สั้น ๆ"
author: Toonshouin!
pubDatetime: 2026-02-26T10:39:59.123Z
---

<img src="{{ site.baseurl }}/assets/posts/guide/linux-hof-talesrunner/Screenshot_20260226_163703.png"/>

Quick guide ง่อยเพื่อให้ท่านสามารถไปแหกปาก "I use arch btw," ลง Public Chat

> [!NOTE]
> สำหรับเวอรชั่นภาษาไทย, [คลิกที่นี้!](linux-hof-talesrunner-th)

## Prerequisite

- Linux (แน่นอนดิวะ)
- Bottles
- Flatpak
- เกมเวอร์ชัน ZIP (จะตัว Mini, Full ได้หมเ)


### แล้วไมไม่ใช้ตัวติดตั้ง .Msi หล่ะ
จริง ๆ ก็ได้ แต่ก็ต้องมี .Net Framework 4.8 ด้วย

## Let's start!

> [!NOTE]
> Guide นี้จะมุ่งไปใช้ Bottles เป็นหลัก แต่เอาไปประยุกต์กับตัวอื่นได้ (ใช้ใน Steam ยังได้) แต่ Bottles มันง่าย และลงใน Distro ไหนก็ได้ ขอให้มี Flatpak และมีเวอร์ชัน AUR (ซึ่งจะใช้เวอร์ชัน AUR แต่ Flatpak ก็ทำได้เหมือนกัน)

เริ่มจากสร้าง Bottles ใหม่เลย ใช้เป็น Gaming ไม่ได้จะได้ไม่ต้องลงส่วนเสริมพวก Direct3D

Note, ผมใช้ Wine ของ kron4ek, 9.22-staging-tkg. ใหม่กว่านี้ก็ใช่ได้ ลองหาตัวอื่น ๆ มาดูและลองไปก็ได้ เอาตัวที่ดีที่สุด

<img src="{{ site.baseurl }}/assets/posts/guide/linux-hof-talesrunner/Pasted%20image%2020260226171617.png"/>

พอสร้างเสร็จแล้ว ไปแถบ Dependency แล้วลง allfonts กับ WebView2 ให้ Launcher ด้วย (ใครจะใช้ตัวติดตั้ง อย่าลืมลง dotnet48)


หลังจากนั้นก็ลงเกมได้เลย หรือจะแตกไฟล์ตัวเกมไปไว้ไหนก็ได้ แล้วสร้าง Shortcut "talesrunner.exe" ไว้ใน Bottles

<img src="{{ site.baseurl }}/assets/posts/guide/linux-hof-talesrunner/Pasted%20image%2020260226171956.png"/>

หลังจากนั้นเล่นและสนุกกับการวิ่งได้

## Extra: แล้ว XIGNCODE3 (The AntiCheat) หล่ะ

อ่อ มัน Supported ผ่าน Wine (aka, Proton) มาสักพักและ มันเล่นได้ ไม่มีปัญหาหยังเลย ใครว่าโม้ [นี่หลักฐาน](https://www.gamingonlinux.com/anticheat/vendor/xigncode3/)

ใครมีตั้งค่าอะไรแนะนำ หรืออยากอวดอะไร เม้นมา!