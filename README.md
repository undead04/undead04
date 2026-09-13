# Chào bạn, tôi là Trần Văn An 

Tôi là Backend / Data Engineer tập trung vào việc xây dựng luồng dữ liệu (data pipelines), API hiệu năng cao và xử lý các bài toán trong hệ thống phân tán. Định hướng của tôi là ưu tiên kiến trúc sạch (clean architecture), tự động hóa hạ tầng và đảm bảo khả năng giám sát hệ thống (observability).

### 🛠 Tech Stack
*   **Ngôn ngữ lập trình:** Python, SQL, Bash (Scripting)
*   **Data Engineering:** Apache Spark, Kafka, Apache Airflow, dbt, PostgreSQL, Minio
*   **Hạ tầng & DevOps:** Docker, Linux, Google Cloud Platform
*   **Công cụ:** Git, uv (Python env management)

### 🚀 Các dự án cốt lõi (Core Projects)
*   **[ELT-Weather]([link-repo]):** Pipeline dữ liệu tự động hóa quy trình ELT. Thu thập dữ liệu thời tiết thô từ Open-Meteo API, điều phối luồng chạy bằng Airflow, transform dữ liệu qua các mô hình dbt, lưu trữ vào kho dữ liệu PostgreSQL và trực quan hóa bằng Looker Studio.
*   **[predict-toxic-comments]([link-repo]):** Hệ thống xử lý dữ liệu streaming thời gian thực. Sử dụng Kafka và Spark để thu thập và xử lý hàng loạt bình luận YouTube, kết hợp mô hình Machine Learning để phát hiện nội dung độc hại. Cấu trúc được thiết kế để chịu tải cao (high throughput).
*   **[malware-for-android-detect]([link-repo]):** Pipeline phân tích mã độc. Tự động hóa quá trình trích xuất đặc trưng tĩnh và hành vi từ các file APK (sử dụng Androguard, dexdump). Hệ thống được đóng gói bằng Docker và triển khai trên môi trường ảo hóa lồng nhau (nested virtualization) tại GCP.

### 🧠 Tư duy kỹ thuật (Engineering Mindset)
*   **Thiết kế chịu lỗi (Design for failure):** Luôn giả định hệ thống mạng hoặc API bên ngoài có thể gặp sự cố để xây dựng cơ chế xử lý lỗi (failure handling) phù hợp.
*   **Tái tạo môi trường (Reproducibility):** Sử dụng Containerization (Docker) để đóng gói ứng dụng, loại bỏ hoàn toàn vấn đề "code chỉ chạy được trên máy cá nhân".
*   **Quản lý luồng dữ liệu (Data Flow):** Luôn kiểm soát chặt chẽ vòng đời của dữ liệu từ lúc Ingest, Transform cho đến khi Serving.

---
📫 **Liên hệ:**
*   **Email:** [antran.261004@gmail.com]