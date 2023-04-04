# Overview #
* Points : 200

# Description #
Someone might have hidden the password in the trace file.
Find the key to unlock this file. This tracefile might be good to analyze.

# Hints #
* 1.Download the pcap and look for the password or flag.
* 2.Don't try to use a password cracking tool, there are easier ways here.

# Tiếp cận và Giải quyết #
Download các file của bài và đánh giá đầu tiên về chúng.
Mở file với `wireshark` và tìm kiếm các trên các `protocol` có thể thấy 1 `protocol` khác biệt với số còn lại:

![image](https://user-images.githubusercontent.com/126185640/229847064-caa497f0-9142-4225-bfa8-8c04ab3d87e9.png)

lấy được đoạn mã sau : `AABBHHPJGTFRLKVGhpcyBpcyB0aGUgc2VjcmV0OiBwaWNvQ1RGe1IzNERJTkdfTE9LZF8=`
Decode với trang web sau sẽ khả dụng hơn so với các trang web mình đã đề cập trước đó : https://kt.gy/tools.html#conv/

thu được đoạn mã sau : `picoCTF{R34DING_LOKd_` , chú ý vào `Hints 2` thì có thể đây là `password` cần tìm , hãy thử nó lên file zip:

thu được flag cần tìm : `picoCTF{R34DING_LOKd_fil56_succ3ss_cbf2ebf6}` 






