# Overview #
* Points : 100

# Description #
How about we take you on an adventure on exploring certificate signing requests
Take a look at this CSR file here.

# Hints #
Download the certificate signing request and try to read it.

# Tiếp cận và Giải quyết #
Tải file về máy để phân tích và đánh giá ban đầu.

file được lưu dưới dạng `.csr` và khi mở bằng `notepad` ta sẽ thấy nó đoạn mã hóa dưới dạng sau :

![image](https://user-images.githubusercontent.com/126185640/229822086-d85b59a2-3bd1-4e10-b1cb-dcb5fa8c389d.png)

Research trên các công cụ tìm kiếm mình thu được link này có thể dùng để `Decode` đoạn mã đó : https://redkestrel.co.uk/products/decoder/

Nhập đoạn mã vào và decode :

![image](https://user-images.githubusercontent.com/126185640/229822804-81c0865c-6daa-4c84-af80-f25022ac3dd3.png)

flag thu được : 	`picoCTF{read_mycert_a7163be8`


