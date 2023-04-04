# Overview #
* Points : 400 
* Tags : `bash` `ssh`

# Description #

Reception of Special has been cool to say the least. 
That's why we made an exclusive version of Special, called Secure Comprehensive Interface for Affecting Linux Empirically Rad, or just 'Specialer'. 
With Specialer, we really tried to remove the distractions from using a shell. Yes, we took out spell checker because of everybody's complaining. 
But we think you will be excited about our new, reduced feature set for keeping you focused on what needs it the most. 
Please start an instance to test your very own copy of Specialer.

# Hints : #

What programs do you have access to?

# Tiếp cận và giải quyết #

Kết nối và thử tìm kiếm các từ khóa tương tự như ở Special mình đã đề xuất thì ở đây ta có thể chú ý đến `Secure Comprehensive Interface for Affecting Linux Empirically Rad`

Cụ thể hơn thứ mình cần tìm để giải quyết nó sẽ ở link này : https://www.w3resource.com/linux-system-administration/file-globbing.php 

Từ thông tin của đường dẫn thì lệnh `echo *` sẽ liệt kê < thay thế cho `ls`> còn `pushd` sẽ thay thế cho `cd` :

Đầu tiên hãy liệt kê các đường dẫn hoặc file có trong đường dẫn mình đang ở bằng lệnh : `echo *` :

![image](https://user-images.githubusercontent.com/126185640/229801980-1d897882-356c-42fb-a9c5-bf1108091750.png)

dùng lệnh `pushd` ( thay thế cho `cd`) để di chuyển giữa các đường dẫn với nhau < ở đây có 3 đường dẫn :

![image](https://user-images.githubusercontent.com/126185640/229802235-3499677f-57ef-4b83-993d-e002f1a59c36.png)

ngoài ra câu lệnh `pwd` vẫn hoạt động để kiểm tra xem mình đang ở đường dẫn nào : 

![image](https://user-images.githubusercontent.com/126185640/229802628-afc68923-e38e-4ea1-95b7-e297ddb86144.png)

dùng lệnh `echo *` để liệt kê các thư mục hay file chứa trong các đường dẫn : 

![image](https://user-images.githubusercontent.com/126185640/229803204-abcb5224-7702-4b73-ae51-a9cd3f25580b.png)

Thử đọc các nội dung bằng câu lệnh `echo` với syntax để đọc nội dung trong file thì cuối cùng mình sẽ nhận được flag cần tìm : 
![image](https://user-images.githubusercontent.com/126185640/229803841-d040a3c3-2e11-41d2-bf35-db846c9233ac.png)

Và flag có được là : `picoCTF{y0u_d0n7_4ppr3c1473_wh47_w3r3_d01ng_h3r3_c42168d9}`
