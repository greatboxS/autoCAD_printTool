# autoCAD_printTool

Author: greatboxs
Date: 01/04/2021
Print tool for autocad

Main feature:
  1. Auto create and print multi sheet base on specific block.
  2. Print multi sheet of current autocad windows pagesetup.
    - User print pagesetup list by modify the order of pages.

/***************************************************************************/
Hướng dẩn thêm tool vào autoCAD

Bước 1:
Copy file các file sau vào thư mục cài đặt Autocad. Ví dụ "C:\Program Files\Autodesk\AutoCAD 2019"
  PrintTool.dll
  PrintTool.dll.xml
  printTool2021.lsp
  
Bước 2: 
Cấp quyền truy cập cho file "PrintTool.dll.xml" vửa copy. => Full Control
Bước 3:
- Chạy ứng dụng autoCAD và gỏ lệnh
    netload
- Cửa sổ tìm kiếm file .dll hiện lên, quay trở lại thử mục cài đặt và trở tới file "PrintTool.dll"
 
- Tiếp tục vào AutoCAD gỏ lệnh 
    appload
Cửa số tìm kiếm file hiện ra, tìm tới file "printTool2021.lsp" được copy trước đó
Ở góc phải bên dưới nhấn vào Content để chọn file .lsp chạy khi autocad Startup.
Chọn tới file .lsp và nhấn OK.
![image](https://user-images.githubusercontent.com/43318216/114313966-f239ce00-9b22-11eb-8956-7454628bdd81.png)

Sau đó gỏ lệnh
    aprint
Cửa sổ ứng dụng auto print hiện ra, vậy là đã cài xong.:))
![image](https://user-images.githubusercontent.com/43318216/114314108-82781300-9b23-11eb-928b-39b5c3fbdbd0.png)
