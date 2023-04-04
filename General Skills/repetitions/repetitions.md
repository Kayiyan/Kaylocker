# Overview #
100 points
Tags : base64 

# Hints < bài cho > : #
* Multiple decoding is always good.

# Tiếp cận và giải quyết  #
![image](https://user-images.githubusercontent.com/126185640/229762457-d6ac1289-b5aa-4c51-97db-b18c10eb909e.png)

Nhấp vào đường dẫn bài đề cập để tải file của bài về để phân tích.
Mở file đó ra sẽ nhận được 1 đoạn mã như sau :
VmpGU1EyRXlUWGxTYmxKVVYwZFNWbGxyV21GV1JteDBUbFpPYWxKdFVsaFpWVlUxWVZaS1ZWWnVh
RmRXZWtab1dWWmtSMk5yTlZWWApiVVpUVm10d1VWZFdVa2RpYlZaWFZtNVdVZ3BpU0VKeldWUkNk
MlZXVlhoWGJYQk9VbFJXU0ZkcVRuTldaM0JZVWpGS2VWWkdaSGRXCk1sWnpWV3hhVm1KRk5XOVVW
VkpEVGxaYVdFMVhSbFZrTTBKVVZXMTRWMDVHV2toalJYUlhDazFyV25sVVZXaHpWakpHZEdWRlZs
aGkKYlRrelZERldUMkpzUWxWTlJYTkxDZz09Cg==

![image](https://user-images.githubusercontent.com/126185640/229762825-5bff307d-a573-405f-9297-19450450ca1e.png)



có vẻ đây là 1 đoạn mã được encode dưới dạng base64 ( như bài đề cập ở phần Tags) , hãy thử decode nó trên web : https://cyberchef.org/
hoặc một số web khác có thể decode base64 cũng có thể được:
![image](https://user-images.githubusercontent.com/126185640/229763735-d1f73d97-a659-4714-a5c4-ebd543022a45.png)
![image](https://user-images.githubusercontent.com/126185640/229764139-609ce3b4-a988-44b2-826f-18cc5155b27f.png)

decode 1 lần sẽ không ra được bởi đoạn mã đã được encode nhiều lần.
Sau khi decode khoảng 5 lần , ta có đoạn flag cần tìm : picoCTF{base64_n3st3d_dic0d!n8_d0wnl04d3d_4557ec3e}
