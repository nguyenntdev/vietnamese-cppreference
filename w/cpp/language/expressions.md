# Biểu thức trong C++
### Bài gốc: [cppreference](https://en.cppreference.com/w/cpp/language/expressions)

Biểu thức là một dãy các toán hạng và các toán tử chỉ định sự tính toán.

Thực hiện một biểu thức có thể cho ra một kết quả nào đó (ví dụ: `2 + 2` cho ra kết quả `4`) và có thể tạo ra các side-effects(?) (ví dụ: thực hiện `std::printf("%d",4)` sẽ in ký tự `'4'` trong đầu ra tiêu chuẩn).

### Tổng quát
- Các danh mục giá trị (lvalue, rvalue, glvalue, prvalue, xvalue) phân loại biểu thức theo giá trị của chúng.
- Thứ tự đánh giá các đối số và biểu thức phụ chỉ rõ thứ tự mà các kết quả trung gian thu được.