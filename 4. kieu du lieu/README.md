## Kiểu dữ liệu 
- là là tập hợp các nhóm dữ liệu có chung đặc tính, cách lưu trữ và thao tác xử lý. Nhờ có kiểu dữ liệu thì compiler nhận biết được kích thước của một biến và khả năng lưu trữ của nó.

## cac loai kieu du lieu

- Các kiểu dữ liệu nguyên thủy (Primitive Data Types)
- Các kiểu dữ liệu tham chiếu (Reference Types)

**Primitive Data Types**
    - Có đến 8 kiểu dữ liệu primitive trong Java
        1. Kiểu Boolean: chỉ sử dụng lưu trữ cho 2 giá trị: true và false. Mục đích kiểu Boolean thường được cho những câu điều kiện rẽ nhánh
        2. Kiểu byte: dữ liệu Byte dùng để lưu trữ kiểu số nguyên có kích cỡ bằng 1 byte (8 bit). Giá trị có thể lưu được nằm trong khoảng từ -128 ( -2^7) đến 127 (2^7-1)
        3. Kiểu Short: dùng để lưu trữ kiểu số nguyên có kích cỡ bằng 2 byte (16 bit). Giá trị có thể lưu được nằm trong khoảng từ -32,768 (-2^15) đến 32,767 (2^15-1)
        4. Kiểu Int: dùng để lưu trữ kiểu số nguyên có kích cỡ bằng 4 byte (32 bit). Giá trị có thể lưu được nằm trong khoảng từ -2,147,483,648 (-2^31) đến 2,147,483,647 (2^31-1)
        5. Kiểu Long: dùng để lưu trữ kiểu số nguyên có kích cỡ bằng 8 byte. Giá trị có thể lưu lưu được nằm trong khoảng từ -9,223,372,036,854,775,808 (-2^63) đến 9,223,372,036,854,775,807 (2^63-1). Giá trị gán cần có kí tự "l" phía sau
        6. Kiểu Float: dùng để lưu trữ số thực có kích cỡ bằng 4 byte (32 bit). Giá trị có thể lưu được nằm trong khoảng từ -3.4028235 x 10^38 đến -3.4028235 x 10^38. Giá trị gán cần có kí tự "f" phía sau
        7. Kiểu Double: dùng để lưu trữ số thực có kích cỡ bằng 8 byte (64 bit). Giá trị có thể lưu nằm trong khoảng từ -1.7976931348623157 x 10^308 đến -1.7976931348623157 x 10^308. Giá trị gán có thể có hoặc không kí tự "d" phía sau
        8. Kiểu Char: dùng để lưu trữ kí tự có kích cỡ bằng 2 byte. Bản chất Char lưu trữ code Unicode nhưng khi lại hiển thị ra "kí tự" ứng với mã đó. Giá trị có thể lưu trữ nằm trong khoảng "u0000" đến "uffff".

**Reference Types**
    - Kiểu dữ liệu tham chiếu là kiểu dữ liệu của đối tượng. Biến của kiểu dữ liệu tham chiếu chỉ chứa địa chỉ của đối tượng dữ liệu tại bộ nhớ Stack. Đối tượng dữ liệu lại nằm ở bộ nhớ Heap. Một số kiểu dữ liệu cụ thể như các mảng (Array), lớp đối tượng (Class) hay kiểu lớp giao tiếp (Interface)