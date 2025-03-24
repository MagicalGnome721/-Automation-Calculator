# 📊 Automation Calculator

Automation Calculator là một công cụ hỗ trợ tính toán tự động, giúp tiết kiệm thời gian và tối ưu hóa quy trình tính toán.

## 🔥 Giới thiệu

Automation Calculator là một công cụ giúp phân tích dữ liệu tài chính và tối ưu hóa danh mục đầu tư bằng Python. Dự án này sử dụng thư viện **PyPortfolioOpt** để tối ưu hóa danh mục cổ phiếu dựa trên dữ liệu từ Google Drive.

## 🛠️ Cài đặt

Trước khi chạy notebook, hãy đảm bảo bạn đã cài đặt các thư viện cần thiết:

```bash
pip install PyPortfolioOpt pandas matplotlib seaborn scipy requests plotly
```

Nếu bạn đang chạy trên **Google Colab**, hãy chạy lệnh sau trong notebook:

```python
!pip install PyPortfolioOpt
```

## 🚀 Hướng dẫn sử dụng

1. **Mở notebook**: Tải file `Automation_Calculator.ipynb` lên Google Colab hoặc Jupyter Notebook.
2. **Chạy các cell lần lượt** để import thư viện và tải dữ liệu.
3. **Kiểm tra dữ liệu**: Nếu dữ liệu từ Google Drive không load được, hãy kiểm tra lại quyền truy cập hoặc tải file CSV về máy.
4. **Tùy chỉnh mã cổ phiếu**: Nếu muốn phân tích mã cổ phiếu khác, chỉnh sửa danh sách `stock_list` trong code.
5. **Chạy thuật toán tối ưu hóa danh mục** để xem phân bổ tối ưu.

## ⚠️ Lỗi thường gặp

- **`ModuleNotFoundError: No module named 'pypfopt'`**

  - Chạy lệnh sau để cài đặt thư viện:
    ```bash
    pip install PyPortfolioOpt
    ```

- **Dữ liệu không tải được từ Google Drive**

  - Kiểm tra xem file CSV có ở chế độ public hay không.

- **`raw_input was called, but this frontend does not support input requests.`**

  - Nếu có `input()`, hãy thay thế bằng giá trị mặc định hoặc config file.

## 📌 Góp ý & Phát triển

Nếu bạn muốn đóng góp cho dự án, hãy mở pull request hoặc báo lỗi tại **GitHub Repository** này!

---

📩 **Liên hệ**: Nếu bạn có câu hỏi, hãy liên hệ qua email hoặc **GitHub Issues**! 🚀

