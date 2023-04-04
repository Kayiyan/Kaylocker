# Overview #
- Points : 100
- Tags : `Analog`

# Description #
Can you crack this black box?
We grabbed this design doc from enemy servers: Download. We know that the rotation of the red axle is input and the rotation of the blue axle is output. The following input gives the flag as output: Download.

# Hints #
Rotating the axle that number of times is obviously not feasible. Can you model the mathematical relationship between red and blue?

# Solutions #

file được lưu dưới dạng .dae nên sẽ cần một số ứng dụng riêng để mở nó , ở đây mình sẽ đề xuất `blender` , cụ thể cách sử dụng có thể được tìm hiểu qua đường link này : 

https://youtube.com/playlist?list=PLjEaoINr3zgFX8ZsChQVQsuDSjEqdWMAD

Sau khi extract và gỡ bỏ một số lớp bên ngoài sẽ thu được như sau : 

![image](https://user-images.githubusercontent.com/126185640/229868832-8fe5d889-2520-439d-b697-b60480314da0.png)

![image](https://user-images.githubusercontent.com/126185640/229868912-88058d43-9410-4891-a4f1-90c9a8d7268d.png)

![image](https://user-images.githubusercontent.com/126185640/229868957-be066cf5-89f3-481f-b715-3268cb7d0534.png)

Từ gợi ý của `Hints` ta sẽ nhận ra cơ chế hoạt động của các bánh răng này và tính được giá trị cần thiết từ đầu vào là tệp `input.txt` là : `198614235373674103788002620892906122161486462450519979543690291018195820925`

decode nó với https://kt.gy/tools.html#conv/picoCTF%7Bg34r5_0f_m0r3_3537e50a%7D sẽ thu được flag cần tìm : `picoCTF{g34r5_0f_m0r3_3537e50a}`




