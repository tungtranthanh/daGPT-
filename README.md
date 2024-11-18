

### 1. Giới Thiệu về DAGPT

- **Tổng quan:** DAGPT là một công cụ phân tích dữ liệu sử dụng các mô hình ngôn ngữ lớn để hỗ trợ các tác vụ phân tích và thao tác dữ liệu qua giao diện đàm thoại.
- **Tính năng:**
  - **Tải lên tệp CSV:** Dễ dàng tải lên dữ liệu CSV qua thanh bên.
  - **Phân tích dữ liệu:** Nhập các truy vấn về dữ liệu và nhận phản hồi được hỗ trợ bởi LLMs.
  - **Trực quan hóa dữ liệu:** Tạo và hiển thị các biểu đồ dựa trên các truy vấn dữ liệu.
  - **Công cụ trực quan hóa tương tác:** Khám phá dữ liệu một cách tương tác bằng cách sử dụng các biểu đồ tùy chỉnh.

### 2. Công Cụ và Gói Cần Thiết

- **Python 3.9 hoặc cao hơn:** Ngôn ngữ lập trình chính để phát triển ứng dụng.
- **Langchain:** Khung phát triển ứng dụng sử dụng các mô hình ngôn ngữ lớn.
- **Streamlit:** Khung ứng dụng mã nguồn mở cho các dự án Machine Learning và Khoa học dữ liệu.
- **Pygwalker:** Công cụ tạo trực quan hóa tương tác.
- **OpenAI API (tùy chọn):** Sử dụng để truy cập các mô hình ngôn ngữ tiên tiến.

### 3. Hướng Dẫn Chi Tiết

#### Bước 1: Thiết Lập Cơ Bản

- Xây dựng cấu trúc dự án.
- Thiết lập môi trường ảo.
- Cài đặt các gói cần thiết.
- Thiết lập kho lưu trữ Git để lưu trữ mã nguồn dự án.

#### Bước 2: Xây Dựng Công Cụ "Chat Với Dữ Liệu"

- Sử dụng Streamlit để xây dựng giao diện người dùng.
- Sử dụng các bộ công cụ của Langchain để xây dựng công cụ phân tích dữ liệu.
- Sử dụng mô hình GPT của OpenAI.

#### Bước 3: Xây Dựng Công Cụ Trực Quan Hóa Tương Tác

- Nhúng Pygwalker vào giao diện Streamlit để xây dựng công cụ trực quan hóa tương tác.

### 4. Kết Luận

- Với khả năng của LLMs, việc viết một ứng dụng thực hiện các tác vụ phân tích dữ liệu phức tạp hàng ngày trở nên rất dễ dàng.
- Sử dụng Streamlit giúp dễ dàng xây dựng giao diện đàm thoại và các khả năng trực quan hóa mạnh mẽ, làm cho việc phân tích dữ liệu trở nên dễ tiếp cận hơn với mọi người.
- Pygwalker là một công cụ miễn phí và hữu ích thay thế cho Tableau và có thể được nhúng vào ứng dụng của chúng ta.
- Bằng cách làm theo hướng dẫn này, mọi người có thể tự xây dựng công cụ phân tích dữ liệu của riêng mình, tận dụng sức mạnh của LLMs và Streamlit.

## Liên Hệ

Nếu bạn có bất kỳ câu hỏi hoặc góp ý nào, hãy để lại bình luận dưới video hoặc liên hệ với mình qua email: [datasciencelab.ai@gmail.com].

## Liên Kết Hữu Ích

- [Streamlit Documentation](https://docs.streamlit.io/)
- [Pandas Documentation](https://pandas.pydata.org/docs/)
- [Langchain Documentation](https://langchain.com/docs/)
- [Pygwalker Documentation](https://pygwalker.github.io/)
- [OpenAI API](https://www.openai.com/)

## Phụ Lục: Cách Thiết Lập Khóa API của OpenAI

1. **Đăng Ký / Đăng Nhập vào OpenAI:**

   - Truy cập trang web OpenAI và tạo tài khoản hoặc đăng nhập nếu bạn đã có tài khoản.

2. **Đi tới API Keys:**

   - Sau khi đăng nhập, vào phần API trong bảng điều khiển tài khoản của bạn. Thường phần này nằm dưới tab "API Keys".

3. **Tạo Khóa API Mới:**

   - Nhấn vào nút "Create new secret key". Hệ thống sẽ tạo một khóa API mới cho bạn.

4. **Sao Chép Khóa API:**
   - Sau khi khóa được tạo, hãy sao chép nó và thay thế khóa API trong tệp `.env` của dự án.

Truy cập [OpenAI](https://www.openai.com/) để biết thêm chi tiết.
