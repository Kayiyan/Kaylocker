# Overview #
Points : 200

# Description #
Put this flag in standard picoCTF format before submitting. If the flag was `h1_1m_7h3_f14g` submit `picoCTF{h1_1m_7h3_f14g}` to the platform.
[Windows game](https://artifacts.picoctf.net/c/285/win.zip), [Mac game](https://artifacts.picoctf.net/c/285/mac.app.zip)

# Solutions #

Cần tải công cụ [dnSpy](https://github.com/dnSpy/dnSpy/releases) để có thể chỉnh sửa file và dữ liệu của game trong thử thách này : <mình sẽ dùng dnSpy cho windows>

![image](https://user-images.githubusercontent.com/126185640/230114742-07e79166-80b0-4c65-9c80-47cc3380e068.png)

Mở file này của game với `dnSpy` :

![image](https://user-images.githubusercontent.com/126185640/230115134-c74b8382-3d1c-4a5e-b021-ea4ba95f76e3.png)

![image](https://user-images.githubusercontent.com/126185640/230115194-b301e886-4dd4-4921-a7de-df4c95d812f8.png)

Xóa đoạn code này đi , nhân vật trong game sẽ không bị rơi khi nhảy < vì mục đích cần chạm đến flag trong game ở cao > :

![image](https://user-images.githubusercontent.com/126185640/230116317-d7519b85-671b-4772-9568-5df238c5abb7.png)

![image](https://user-images.githubusercontent.com/126185640/230116910-6cd03aac-693e-4993-b523-3dcff990a810.png)

chỉnh sửa một chút :

![image](https://user-images.githubusercontent.com/126185640/230120484-f00841f0-433f-4a4f-8fac-83ba2ebfc41c.png)

cụ thể đoạn code chỉnh sửa :  kiểm tra nếu phím E được nhấn xuống bởi người chơi, thì giá trị y của biến `moveDirection` sẽ được đặt về 0. Nếu phím Q được nhấn xuống, giá trị y của `moveDirection` sẽ được đặt về một giá trị âm `(-jumpSpeed)`. 

Mục đích nếu xóa đoạn code ban đầu của game thì khi nhân vật nhảy lên sẽ không dừng lại nên mình chỉnh sửa một chút để thêm phím dừng đến mức mình muốn và có thể hạ xuống nếu quá cao. 

Tuy nhiên mình không đặt câu lệnh này trong vòng lặp nên chỉ thực hiện được 1 lần.


Lưu lại những chỉnh sửa vừa rồi và mở lại game :

![image](https://user-images.githubusercontent.com/126185640/230121441-54830e7f-0858-4564-ace2-b94eff123fb3.png)

Di chuyển đến cột cờ của game và lấy flag yêu cầu : 

![image](https://user-images.githubusercontent.com/126185640/230121358-0ce87c86-3256-4438-9c2d-bbf1ec31a0c0.png)

flag thu được có dạng : `picoCTF{đoạn mã trong hình}`


