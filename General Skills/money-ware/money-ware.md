# Overview #
- 100 points
- Tags : osint

# Hints < bài cho > # 
- 1.Some crypto-currencies abuse databases exist; check them out!
- 2.Maybe Google might help.

# Description #
Flag format: picoCTF{Malwarename}
The first letter of the malware name should be capitalized and the rest lowercase.
Your friend just got hacked and has been asked to pay some bitcoins to 1Mz7153HMuxXTuR2R1t78mGSdzaAtNbBWX. 
He doesn’t seem to understand what is going on and asks you for advice. Can you identify what malware he’s being a victim of?

# Tiếp cận #
Từ phần Description bài có đề cập đến bitcoin cùng với 1 đoạn mã : 1Mz7153HMuxXTuR2R1t78mGSdzaAtNbBWX.
Hãy thử search đoạn mã này lên google để tìm kiếm thêm thông tin về nó : 
![image](https://user-images.githubusercontent.com/126185640/229757692-bce09879-0d03-48c4-b642-9b3f3a3329f1.png)

Xác định được Địa chỉ 1Mz7153HMuxXTuR2R1t78mGSdzaAtNbBWX là địa chỉ Bitcoin. Nó đã được sử dụng trong quá khứ để nhận các giao dịch Bitcoin.
Và bài có nói đến form flag là tên của đoạn mã đọc đõ , hãy thử search đoạn mã đó kèm tên xem sao : 
![image](https://user-images.githubusercontent.com/126185640/229758578-176d8bdd-fd8c-40bc-8709-bb0a299d3614.png)

cuộn xuống thì ta sẽ thấy trang web này : 
![image](https://user-images.githubusercontent.com/126185640/229758727-e548ef68-92c2-405d-8006-e24d1ecf8afc.png)

Có thể Petya là 1 tên và nhập nó vào khung điền flag của sự kiện với form bài đề cập : picoCTF{Petya}
![image](https://user-images.githubusercontent.com/126185640/229759198-f8bcdee3-2d4d-4963-91be-9085ece49fb9.png)

và nó đã thành công , vì vậy  đoạn mã flag cần tìm là : picoCTF{Petya} 



