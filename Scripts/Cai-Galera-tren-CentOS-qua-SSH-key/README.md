### Hướng dẫn sử dụng

- Bước 1. Khai báo IP các node vào file `conf.cfg`

    ```
    export IP1=192.168.100.196
    export IP2=192.168.100.197
    export IP3=192.168.100.198
    ```
    
- Bước 2. Copy các key ssh và đặt tên lần lượt theo mẫu `node1`, `node2` và `node3` tương ứng với file key của các node

    *Lưu ý:* Các file trên nằm trong cùng thư mục với script.

- Bước 3. Phân quyền chạy cho script
    
    ```
    chmod 755 galera.bash
    ```
- Bước 4. Chạy script

    ```
    ./galera.bash
    ```
    
*Chúc các bạn thành công!*