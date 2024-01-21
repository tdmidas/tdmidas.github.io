---
title: "[PicoCTF2023] chrono - mở đầu của Cron task"
date: 2023-07-06 22:45:00 +0800
categories: [CTF]
tags: [ctf, forensics]
published: true
image:
  path: /chrono.png
  alt: Forensic
---

Lần này là một problem khá cơ bản của general skills, khi đã đặt tên chrono thì mình sẽ nghĩ ngay đến cron job liền :>>, vậy đầu tiên thì cron job là gì ?

## Cron job là gì ?

Ta có thể hiểu cron job là một daemon (bạn có thể hiểu nó như Services của Window) hoạt động dưới nền và nó xử lý các tác vụ lặp đi lặp lại bằng cách lên lịch cho một hành động cụ thể được lặp.

File crontab mặc định trong hệ thống được lưu ở `/etc/crontab`{: .filepath}

## Writeup

Như đã nêu bên trên, khi ta `cat` file `crontab` thì ta sẽ có flag như ảnh dưới. Và thế là bạn đã có được 100 point khá dễ dàng r nhỉ :>> .
![Desktop View](/assets/img/chrono1.png){: width="972" height="589" }
