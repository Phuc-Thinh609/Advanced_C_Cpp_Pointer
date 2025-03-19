#Bitmask 
* Bitmask là kỹ thuật thao tác với các bit riêng lẻ trong một biến
* Mục đích của Bitmask là tối ưu hóa bộ nhớ
* Sử dụng các phép toán bitwise (AND, OR, XOR, NOT, <<, >>) để bật, tắt, kiểm tra từng bit.
** NOT bitwise
  -  NOT bitwise hình dung là phép nghịch đảo (đảo bit)
    ```cpp
      int a = 0b0101; //5
      int b = 0b1001; 
      int result_1 = ~a; // 1010
      int result_2 = ~b; // 0110
    ```
  - 
