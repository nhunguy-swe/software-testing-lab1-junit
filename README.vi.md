[English](README.md) | Tiếng Việt

# LAB 1.1: UNIT TESTING & SỬA LỖI (BUG FIXING)

## I. MỤC TIÊU

- Triển khai unit test bằng **JUnit 5**.
- Áp dụng phương pháp **Test-Driven Development (TDD)** và **White-box testing**.
- Xác định, ghi nhận và sửa các lỗi logic trong hệ thống Ngân hàng (Banking System).

---

## II. CẤU TRÚC DỰ ÁN

- **`a_Introductory`**: Sửa lỗi trong các lớp Fibonacci và Geometry.
- **`b_Money`**:
  - Khắc phục lỗi làm tròn (rounding) trong lớp `Currency`.
  - Triển khai logic `Money` và xây dựng bộ test cho `Bank`/`Account`.
  - Thêm comment `// BUG FOUND` để đánh dấu các lỗi đã phát hiện trong source code.

---

## III. QUY TRÌNH THỰC HIỆN (Checklist)

- [x] Soạn test cho `Money` & `Currency` kèm lý do (motivation) rõ ràng.
- [x] Triển khai source code để đạt **Green Bar** (toàn bộ test pass).
- [x] Phát hiện lỗi trong `Bank` & `Account` thông qua các test JUnit fail.
- [x] Tái cấu trúc (refactor) code và xác minh lại độ ổn định cuối cùng.

---

## IV. CÁCH CHẠY

1. Mở dự án bằng **IntelliJ IDEA**.
2. Chạy toàn bộ test trong thư mục `test/`.
3. **Kết quả mong đợi:** 100% Passed (Green Bar — toàn bộ thanh trạng thái màu xanh).
