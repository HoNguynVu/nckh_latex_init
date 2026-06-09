# Khung LaTeX báo cáo NCKH

## Cách dùng trên VS Code

1. Cài TeX Live hoặc MiKTeX.
2. Cài extension `LaTeX Workshop` trong VS Code.
3. Mở thư mục này bằng VS Code.
4. Mở `metadata.tex` và sửa tên đề tài, GVHD, MSSV, lớp.
5. Mở `main.tex` và bấm Build LaTeX Project.

## Lưu ý khổ giấy

File Word mẫu đang dùng khổ Letter 21.59 x 27.94 cm, lề 2.54 cm. Nếu trường/khoa yêu cầu A4, đổi dòng đầu trong `main.tex`:

```tex
\documentclass[12pt,a4paper,oneside]{report}
```

## Cấu trúc nội dung

- `chapters/01_mo_dau.tex`: bối cảnh, mục tiêu, phạm vi, đóng góp.
- `chapters/02_co_so_ly_thuyet_va_phap_ly.tex`: cơ sở pháp lý, nhóm vi phạm, bài toán NLP/multimodal.
- `chapters/03_du_lieu_va_gan_nhan.tex`: nguồn dữ liệu, crawling, nhãn, nguyên tắc gán nhãn.
- `chapters/04_phuong_phap_de_xuat.tex`: pipeline, tiền xử lý, mô hình, huấn luyện.
- `chapters/05_thuc_nghiem_va_danh_gia.tex`: thống kê dữ liệu, kết quả, threshold, phân tích lỗi.
- `chapters/06_ket_luan_va_huong_phat_trien.tex`: kết luận và hướng phát triển.
