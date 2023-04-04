# Overview #
* Points : 300
* Tags : `bash` `ssh`
# Description #
Don't power users get tired of making spelling mistakes in the shell? Not anymore! Enter Special, the Spell Checked Interface for Affecting Linux. Now, every word is properly spelled and capitalized... automatically and behind-the-scenes! Be the first to test Special in beta, and feel free to tell us all about how Special streamlines every development process that you face. When your co-workers see your amazing shell interface, just tell them: That's Special (TM)
Start your instance to see connection details.

# Hints : #
Experiment with different shell syntax.

# Tiếp cận  #
Kết nối là bước đầu tiên của thử thách này : 

![image](https://user-images.githubusercontent.com/126185640/229771463-ee6d64ac-3cdb-47a4-9f70-08f37b8f3d0e.png)

Ở bài này có phần khác , các câu lệnh có chút đặc biệt như tên của thử thách `Special` gần như nó không hoạt động bình thường như các thử thách trước : 
![image](https://user-images.githubusercontent.com/126185640/229771947-0860ec5f-7008-48bc-92fe-889d3c414ebb.png)

Quay lại Description của bài : chú ý đến Spell Checked Interface for Affecting Linux có phần đặc biệt , hãy thử tìm kiếm nó trên google xem :
![image](https://user-images.githubusercontent.com/126185640/229772615-3fbb20a8-09a0-49d0-a514-5990de07d55d.png)

có thể đọc thêm qua đường dẫn này : https://www.maketecheasier.com/do-spelling-check-linux-terminal/

Rồi, ngắn gọn thì nó sẽ thay thế các chữ trong câu lệnh của mà mình thực hiện, các chữ cái đầu sẽ luôn được tự động viết hoa và các chữ cái sẽ thay thế , cho có nghĩa.

# Giải quyết #
 Đây là hướng giải quyết của mình, cụ thể là mình đã thử một vài syntax với các kí tự đặc biệt trong câu lệnh cần dùng : 


![image](https://user-images.githubusercontent.com/126185640/229772272-d79c59c5-5a5d-4705-989d-94e91a2e7d08.png)

![image](https://user-images.githubusercontent.com/126185640/229773684-d7fd7397-b8f0-4f5c-a963-42e1871a00cd.png)

Có vẻ như việc lồng câu lệnh vào dấu ngoặc và kết thúc bằng dấu ; thì câu lệnh sẽ được thực hiện. 
Chú ý đến phần `Hints` của bài cho có đề cập đến các shell syntax khác nhau.

thì về linux ta có linux shell hoặc về window ta có window shell, ngoài ra khi học về python mình sẽ có python shell mở python shell ngay trên terminal đang sử dụng.
Hãy thử mở python shell bằng câu lệnh sau : `(python3);` :

![image](https://user-images.githubusercontent.com/126185640/229790735-aaa4a3f9-d566-4e90-85c7-3b5fc64b07c8.png)

lệnh `cat` hay `ls` thường dùng là lệnh của hệ điều hành nên không thể thực hiện trên `python shell` nếu chưa khai báo vì vậy cần khai báo trước bằng câu lệnh sau :
`import os` :
![image](https://user-images.githubusercontent.com/126185640/229791265-91f2f833-bbd1-4542-bb57-65a4cf336c73.png)

vì vậy ta cần chạy được các lệnh của hệ điều hành trên `python shell` , cụ thể có ví dụ về lệnh `cat` từ link này : https://www.geeksforgeeks.org/using-the-cat-command-in-python/


Theo chỉ dẫn từ bài viết đọc ở đường link trên , mình có thể thực hiện lệnh ls bằng syntax như vậy : 

![image](https://user-images.githubusercontent.com/126185640/229794548-d0f10e84-64cb-45ea-81e9-853d6de02c2c.png)

và ở mục ` Tiếp cận ` lệnh `ls` mình đã sử dụng để liệt kê ra các đường dẫn hay file có trong đường dẫn hiện tại nên ta tiếp tục thực hiện `ls` lên đường dẫn `blargh` này và tìm thấy file `flag.txt` đọc nó bằng lệnh `cat` với syntax đúng như mẫu và ta có được flag cần tìm : `picoCTF{5p311ch3ck_15_7h3_w0r57_b741d1b1}`





