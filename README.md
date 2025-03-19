#Bitmask 
* Bitmask là kỹ thuật thao tác với các bit riêng lẻ trong một biến
* Mục đích của Bitmask là tối ưu hóa bộ nhớ
* Sử dụng các phép toán bitwise (AND, OR, XOR, NOT, <<, >>) để bật, tắt, kiểm tra từng bit.
  ##NOT bitwise
  -  NOT bitwise hình dung là phép nghịch đảo (đảo bit)
    ```cpp
      int a = 0b0101; //5
      int b = 0b1001; 
      int result_1 = ~a; // 1010
      int result_2 = ~b; // 0110
    ```
  ##AND bitwise
  - AND bitwise hình dung là phép nhân
    ```Cpp
      int a = 0b0101; //5
      int b = 0b1001; 
      int result = a & b; // 0001
    ```
  ##OR bitwise
  - OR bitwise hình dung là phép cộng
    ```Cpp
    int a = 0b0101; //5
    int b = 0b1001; 
    int result = a | b; // 1101
    ```
  ##XOR bitwise
  - XOR bitwise hình dung dễ hiểu là đếm tổng số 1 trong cùng một cột, nếu lẻ là 1, ngược lại chẵn là 0
    ```Cpp
    int a = 0b0101; //5
    int b = 0b1001; 
    int c = 0b1101; 
    int d = 0b1011; 
    int result = a ^ b ^ c ^ d; // 0b1010
    ```


    

