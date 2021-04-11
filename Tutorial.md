# autoCAD_printTool
Phần mềm có 2 chức năng chính là (.pdf file):
1. Chọn và in tự động block có trên cửa sổ hiện tại của AutoCAD
2. Chọn và in các page setup có trên cửa sổ hiện tại


1. In tự động block được chọn:
  ![image](https://user-images.githubusercontent.com/43318216/114314343-67f26980-9b24-11eb-829a-079f4674c682.png)
  
  Tùy chỉnh các thông số máy in và kích thước in phù hợp.
      ![image](https://user-images.githubusercontent.com/43318216/114314396-a0924300-9b24-11eb-9192-9a8d505d8ec5.png)
      
  1.1 In tất cả các block tìm kiếm được:
    Nếu như "Print all" được check. Tất cả các block tìm kiếm được sẽ được in tự động tất cả
      ![image](https://user-images.githubusercontent.com/43318216/114314748-2bc00880-9b26-11eb-9118-71c8d3fcf40c.png) 
      
  1.2 Tùy chỉnh trang in thủ cộng:
    Không tick vào ô "Print all", tiếp tục nhấn "Print" cửa sổ tùy chỉnh hiện ra:
    ![image](https://user-images.githubusercontent.com/43318216/114314825-80fc1a00-9b26-11eb-9e16-0a444b796e33.png)
    
    Danh sách thể hiện vị thứ tự, vị trí của block, kéo di chuyển để thay đổi vị trí của block cần thay đổi.
    (Shot key - Shift + Click chuột để chọn,
                Ctrl + Click chuột để bỏ chọn)
    Kéo ô này đễn vị trí ô khác để hoán đổi vị trí của nhau.
    
  1.3 Các chức năng in:
    Có thể lựa chọn các in của các block được tìm kiếm tự động:
    Top - > Right -> Bottom : In theo cột
    Top - > Bottom -> Right : In theo hàng
    
    ![image](https://user-images.githubusercontent.com/43318216/114315070-72623280-9b27-11eb-9ed0-da0432405bd6.png)
    
    Thông tin của file được in.
        ![image](https://user-images.githubusercontent.com/43318216/114315110-9160c480-9b27-11eb-9249-1af972da8d4c.png)
    
    - Chức năng tạo page setup từ block được chọn (không xuất ra file .pdf):
        ![image](https://user-images.githubusercontent.com/43318216/114315145-b81efb00-9b27-11eb-9eed-494d7027c6b5.png)

    
2 In page setup có sẳn:
  2.1 In page setup có sẳn:
    - Ở đây nếu tick vào ô "Print existing pagesetup" thì sẽ in những pagesetup có sẳn. Nhấn "Print" và cửa sổ tùy chọn
    page setup sẽ hiện ra.
    ![image](https://user-images.githubusercontent.com/43318216/114314496-29a97a00-9b25-11eb-88de-77de6cee436e.png)
    
    Kéo và di chuyển thứ tự các page cho phù hợp
  2.2 In danh sách người dùng nhập vào
    Tick vào ô "Use custom list", nhấn "Import", cửa sổ nhập danh sách hiện ra:
    ![image](https://user-images.githubusercontent.com/43318216/114314637-a50b2b80-9b25-11eb-8cfa-2e9bc21972f1.png)
    Nhập tên page setup phù hợp ới tên đã có trong bản vẽ.
    Để kiểm tra danh sách nhấn "Check", sau đó tắt cửa sổ lại và tiếp tục nhấn "Print"
  
