# Overview #
- `Points : 100`
- Tags : `man`

# Description #
There's an interesting script in the user's home directory
The work computer is running SSH. We've been given a script which performs some basic calculations, explore the script and find a flag.

# Tiếp cận và giải quyết #

Đầu tiên hãy kết nối tới sever của thử thách và thực hiện 1 số lệnh linux cơ bản như `ls` để tìm kiếm hoặc như mình đã phân tích ở bài chrono:
https://github.com/Kayiyan/picoCTF-2023/blob/323f9a582b56519d9cb9606edad6439340253a84/General%20Skills/chrono/chrono.md

![image](https://user-images.githubusercontent.com/126185640/229768422-1f067718-3602-4195-be6b-021e2b58aac5.png)

Ta thấy 1 file tên `useless` ở đây nên hãy dừng ở đây và phân tích về nó xem :
* ![image](https://user-images.githubusercontent.com/126185640/229768839-8c76f459-f921-4001-89e0-a6cae9c56ae2.png)

Thử thêm một vài câu lệnh nhưng không có gì đặc biệt , bây giờ hãy chú đến phần `Tags` của bài : có đề cập đến `man` :
* giải thích ngắn gọn về man command :
* ![image](https://user-images.githubusercontent.com/126185640/229769378-10e76d3e-5f79-4d3f-b03b-ee8441c4aa44.png)
Để hiểu rõ hơn ta có thể truy cập vào https://explainshell.com/explain?cmd=man hoặc thử search `man command in linux` lên google để hiểu rõ hơn về nó :

Sau một lúc tìm hiểu và đọc , ta có thể thực hiện câu lệnh `man` lên file của bài như sau :

![image](https://user-images.githubusercontent.com/126185640/229769913-7ab8333e-cee4-4415-8345-6f81b5a9d69b.png)

cuối cùng đoạn flag cần tìm là : `picoCTF{us3l3ss_ch4ll3ng3_3xpl0it3d_7065}`
