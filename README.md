# Stereo Matching Sử Dụng Các Đo Khoảng Cách Khác Nhau

Repository này chứa code Python để thực hiện việc khớp ảnh stereo sử dụng các phép đo khoảng cách khác nhau như L1, L2 và cosine similarity. Code sẽ xử lý các cặp ảnh stereo và tính toán bản đồ độ lệch (disparity maps) sử dụng phương pháp pixel-wise và window-based.

## Yêu Cầu

Để chạy code này, bạn cần cài đặt các gói sau:

- Python 3.x
- OpenCV
- NumPy
- Google Colab (nếu chạy trong môi trường đám mây)

## Cài Đặt

### Thiết Lập Cục Bộ

1. Clone repository này:
    ```bash
    git clone <repository-url>
    ```
   
2. Cài đặt các gói yêu cầu bằng cách sử dụng `pip`:
    ```bash
    pip install opencv-python numpy
    ```

3. Tải dữ liệu cần thiết:
    - Với bài toán 1 và 2, tải tập tin `tsukuba.zip` và `Aloe_images.zip` từ Google Drive sử dụng lệnh:
      ```bash
      !gdown --id <id-tsukuba-file>
      !unzip tsukuba.zip -d tsukuba

      !gdown --id <id-aloe-images-file>
      !unzip Aloe_images.zip
      ```
  
### Chạy Trên Google Colab

1. Nếu bạn sử dụng Google Colab, chỉ cần chạy từng cell trong notebook đã được cung cấp.

2. Thực hiện các bước cài đặt tương tự, tuy nhiên lệnh tải và giải nén sẽ được thực hiện trực tiếp trong Colab như ví dụ dưới đây:

    ```python
    !gdown --id <id-tsukuba-file>
    !unzip tsukuba.zip -d tsukuba

    !gdown --id <id-aloe-images-file>
    !unzip Aloe_images.zip
    ```

## Sử Dụng

1. Mở file Python hoặc notebook và chạy từng phần code.
2. Các hình ảnh đầu vào sẽ được đọc từ các tập tin đã tải xuống và bản đồ độ lệch (disparity map) sẽ được tính toán sử dụng các phương pháp khác nhau.
3. Kết quả sẽ được lưu dưới dạng các tập tin hình ảnh (`.png`) hoặc hiển thị trực tiếp trên màn hình.

## Lưu Ý

- Để thay đổi các tham số như `disparity_range` hay `kernel_size`, hãy chỉnh sửa các tham số này trực tiếp trong code.
- Các file ảnh đầu vào cần phải nằm đúng vị trí đã chỉ định trong code (`tsukuba/left.png`, `tsukuba/right.png`, v.v.).

## Tham Khảo

- Đối với các tập tin ảnh mẫu, vui lòng tham khảo các tập tin `left.png`, `right.png`, `Aloe_left_1.png`, và `Aloe_right_1.png`.

# Stereo Matching Sử Dụng Các Đo Khoảng Cách Khác Nhau

Repository này chứa code Python để thực hiện việc khớp ảnh stereo sử dụng các phép đo khoảng cách khác nhau như L1, L2 và cosine similarity. Code sẽ xử lý các cặp ảnh stereo và tính toán bản đồ độ lệch (disparity maps) sử dụng phương pháp pixel-wise và window-based.

## Yêu Cầu

Để chạy code này, bạn cần cài đặt các gói sau:

- Python 3.x
- OpenCV
- NumPy
- Google Colab (nếu chạy trong môi trường đám mây)

## Cài Đặt

### Thiết Lập Cục Bộ

1. Clone repository này:
    ```bash
    git clone <repository-url>
    ```
   
2. Cài đặt các gói yêu cầu bằng cách sử dụng `pip`:
    ```bash
    pip install opencv-python numpy
    ```

3. Tải dữ liệu cần thiết:
    - Với bài toán 1 và 2, tải tập tin `tsukuba.zip` và `Aloe_images.zip` từ Google Drive sử dụng lệnh:
      ```bash
      !gdown --id <id-tsukuba-file>
      !unzip tsukuba.zip -d tsukuba

      !gdown --id <id-aloe-images-file>
      !unzip Aloe_images.zip
      ```
  
### Chạy Trên Google Colab

1. Nếu bạn sử dụng Google Colab, chỉ cần chạy từng cell trong notebook đã được cung cấp.

2. Thực hiện các bước cài đặt tương tự, tuy nhiên lệnh tải và giải nén sẽ được thực hiện trực tiếp trong Colab như ví dụ dưới đây:

    ```python
    !gdown --id <id-tsukuba-file>
    !unzip tsukuba.zip -d tsukuba

    !gdown --id <id-aloe-images-file>
    !unzip Aloe_images.zip
    ```

## Sử Dụng

1. Mở file Python hoặc notebook và chạy từng phần code.
2. Các hình ảnh đầu vào sẽ được đọc từ các tập tin đã tải xuống và bản đồ độ lệch (disparity map) sẽ được tính toán sử dụng các phương pháp khác nhau.
3. Kết quả sẽ được lưu dưới dạng các tập tin hình ảnh (`.png`) hoặc hiển thị trực tiếp trên màn hình.

## Lưu Ý

- Để thay đổi các tham số như `disparity_range` hay `kernel_size`, hãy chỉnh sửa các tham số này trực tiếp trong code.
- Các file ảnh đầu vào cần phải nằm đúng vị trí đã chỉ định trong code (`tsukuba/left.png`, `tsukuba/right.png`, v.v.).

## Tham Khảo

- Đối với các tập tin ảnh mẫu, vui lòng tham khảo các tập tin `left.png`, `right.png`, `Aloe_left_1.png`, và `Aloe_right_1.png`.

