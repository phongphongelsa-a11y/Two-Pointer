# Two-pointer
- Là kĩ thuật sử dụng 2 biến ở 2 vị trí khác nhau để xử lí dữ liệu, di chuyển 2 biến về phía nhau, hoặc ra xa nhau, hoặc theo cùng 1 hướng tùy vấn đề.
## Tại sao dùng Two-pointer
- Lợi dụng tính chất bài toán để quyết định move con trỏ, suy ra cách giải tốt hơn.
- Mỗi lần move phải loại trừ được gì đó , không cần thử.
- *Pattern chung là suy luận ra được luôn, mà không cần phải tính thử*

## Các dạng Two pointer
- 2 con trỏ đối xứng (từ 2 đầu vào giữa).
- 2 con trỏ cùng chiều (slow and fast).
## Độ phức tạp
- Thường giúp giảm từ O(n^2) xuống O(n) tùy bài toán vì làm in-place ( in-place ở đây nghĩa là làm luôn trên cái input mà đề bài cho, emm hiểu là vậy :))
## Ứng dụng 
- Các bài toán có thể lợi dụng được tính chất bài toán như Two Sum Input Sorted Array
- Các bài kiểm tra đối xứng.
- VD: Bài toán Two Sum Input Sorted Array (quyết định move con trỏ nào dựa trên so sánh với target)
  + Nếu đã sắp xếp, e thấy tính chất là
  + Nếu tổng quá nhỏ -> tăng right
  + Nếu tổng quá lớn -> giảm left


