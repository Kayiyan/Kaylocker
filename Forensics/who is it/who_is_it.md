# Overview #
* Points : 100
* Tags : `email`

# Description #
Someone just sent you an email claiming to be Google's co-founder Larry Page but you suspect a scam.
Can you help us identify whose mail server the email actually originated from?
Download the email file here. Flag: picoCTF{FirstnameLastname}

# Hints : #
whois can be helpful on IP addresses also, not only domain names.

# Tiếp cận và Giải quyết #

Download file bài cho , từ mục `Hints` đề cập đến `whois` hãy thử search và tìm hiểu về nó.

mở file dưới dạng `notepad` ta có thể thấy nội dụng file rõ hơn , đánh giá qua có thể thu được `client-ip` như sau :

![image](https://user-images.githubusercontent.com/126185640/229840278-a0b5d0cc-d649-41d8-8ea5-81df7c8acc0e.png)

thử dùng ip này và search với `whois` như `Hints` đã đề cập đến và thu được thông tin như sau :

![image](https://user-images.githubusercontent.com/126185640/229840897-1c6568db-ae57-4144-985b-2f8386fc4d4a.png)

![image](https://user-images.githubusercontent.com/126185640/229840950-b207d7b8-873f-4e4a-81fb-ebbcfdab9a02.png)

chú đến form flag bài đã gợi ý , và đây là cụm từ ta cần để mắt đến : `person:         Wilhelm Zwalina`

Thử nhập với form bài cho và thu được flag cần tìm : `picoCTF{WilhelmZwalina}`


