# Global & Adaptive Otsu Thresholding

## Giới thiệu
Dự án này triển khai các phương pháp **Global Thresholding**, **Adaptive Thresholding** và **Otsu's Method** để xử lý ảnh nhị phân, sử dụng Python và OpenCV.

## Yêu cầu
Cài đặt các thư viện cần thiết:
```bash
pip install opencv-python numpy matplotlib
```

## Cách chạy
1. Mở file notebook `_global_adaptive_otsu_aio.ipynb`.
2. Chạy các cell theo thứ tự.
3. Thay đổi đường dẫn ảnh test (`test1.tif`, `test2.tif`) để kiểm tra.

## Nội dung notebook
Notebook bao gồm các bước:
- Đọc ảnh grayscale.
- Thực hiện **Global Thresholding** với giá trị T cố định.
- Thực hiện **Otsu's Thresholding** để tìm ngưỡng tối ưu tự động.
- Thực hiện **Adaptive Thresholding** (mean và gaussian).
- Hiển thị và so sánh kết quả.


## Kết quả minh họa
Ảnh gốc và ảnh sau khi thresholding sẽ được hiển thị trực tiếp trong notebook.
Ví dụ với `test1.tif` và `test2.tif`:

![Test1](test1.tif)
![Test2](test2.tif)

## Dataset
- test1.tif
- test2.tif
