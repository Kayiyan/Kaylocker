# Overview #
* Points : 100
* Tags : `steganography`

# Description #
Every file gets a flag.
The SOC analyst saw one image been sent back and forth between two people. They decided to investigate and found out that there was more than what meets the eye here.

# Tiếp cận và Giải quyết #

Download file và thực hiện đánh giá ban đầu.

mở ảnh ra ta sẽ không thu được thông tin gì khả quan nhưng từ phần Tags có nói đến `steganography` ý nghĩa thông tin được ẩn trong bức ảnh , vì vậy hãy thử một lần nữa extract bức ảnh này.

Lần này mình sẽ dùng 1 command có thể extract file chứa ở trong ảnh ra :
`foremost -T picture_name.png` cụ thể là :

![image](https://user-images.githubusercontent.com/126185640/229830032-7246066e-55c6-421c-9bd0-7731ba945dd6.png)

tiếp theo đó có thể thực hiện đọc file ngay trên `terminal` hoặc vào thẳng thư mục thu được từ việc extract :
![image](https://user-images.githubusercontent.com/126185640/229830715-b85c5651-c0fd-4560-a60f-71a8e015b503.png)

ta có thể tìm kiếm trong mục nhỏ mà thư mục này cung cấp : 

![image](https://user-images.githubusercontent.com/126185640/229830920-616b1107-96cf-47e5-ba8e-f2999ad5319c.png)

Tìm kiếm trong các thư mục đó và sẽ thu được bức ảnh chứa đoạn flag cần :

![image](https://user-images.githubusercontent.com/126185640/229831111-db76ab44-4c4d-46af-b57d-f90d215a582e.png)

Nhập lại đoạn flag đó hoặc dùng các công cụ khác để lấy văn bản trong ảnh ra như Google Lens có thể là 1 ví dụ phổ biến.

Cuối cùng flag thu được : `picoCTF{Hiddinng_An_imag3_within_@n_ima9e_85304ab8}`
