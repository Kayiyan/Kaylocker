# Overview 
* `100 points `
* Tags : `linux`

# Description 
How to automate tasks to run at intervals on linux servers?
Additional details will be available after launching your challenge instance.
# Tiếp cận với thử thách này :
Đầu tiên hãy khởi chạy phiên bản của thử thách để phân tích (launch instance).

Sau khi kết nối thành công cửa sổ Terminal sẽ hiện thị như sau :
![image](https://user-images.githubusercontent.com/126185640/229751801-4198ae8f-5618-4068-81e5-f69313e21f82.png)

# Giải quyết 
mình thực hiện một số lệnh linux cơ bản lên máy chủ sau khi đã kết nối :

![image](https://user-images.githubusercontent.com/126185640/229752623-abe3ae29-af03-459a-b5fb-2e253fb88148.png)

Quan sát và nhìn nhận chung thì đường dẫn challenge có thể chứa flag cần tìm nhất hoặc ta có thể check từng đường dẫn một :
- di chuyển vào trong đường dẫn `challenge` và xem bên trong có chứa những file gì :
 ![image](https://user-images.githubusercontent.com/126185640/229753241-937f8a18-eb69-475d-97e9-7db23cfd2276.png)

- cụ thể về `metadata.json file` : 
 
 ![image](https://user-images.githubusercontent.com/126185640/229753663-f8e0811f-d6c8-44ed-b45f-d042ce5f2601.png)
 
 Hãy thử đọc file này bằng câu lệnh  `cat` : 
 
 ![image](https://user-images.githubusercontent.com/126185640/229754046-14cc7165-1090-4563-921e-37a18eb9c557.png)
 
 và ta nhận được đoạn flag cần tìm của bài : `picoCTF{Sch3DUL7NG_T45K3_L1NUX_d83baed1}`
 

