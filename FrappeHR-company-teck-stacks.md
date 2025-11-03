Dựa trên các nguồn thông tin được cung cấp, **Frappe HR** được phát triển bởi **Frappe Technologies**, một công ty phần mềm hàng đầu Ấn Độ.

Dưới đây là các chi tiết cụ thể liên quan đến nguồn gốc của Frappe HR:

*   **Nhà phát triển:** Frappe HR là giải pháp quản trị nhân sự được phát triển dựa trên **PHẦN MỀM FRAPPE HR** của **Frappe Technologies**—một công ty phần mềm hàng đầu Ấn Độ.
*   **Hệ sinh thái:** Frappe HR được xây dựng trên **Frappe Framework**, một khung ứng dụng web full-stack, low-code/no-code được viết bằng Python và Javascript.
*   **Quan hệ với ERPNext:** Frappe Technologies cũng là công ty đã phát triển **ERPNext**, một giải pháp hoạch định nguồn lực doanh nghiệp (ERP) mã nguồn mở và miễn phí. Ban đầu, Frappe HR là một tập hợp các mô-đun nằm trong ERPNext. Tuy nhiên, từ **phiên bản 14 trở đi**, Frappe HR đã được tạo ra như một **sản phẩm riêng biệt**.
*   **Mã nguồn mở:** Frappe HR là một giải pháp quản trị nhân sự & tính lương **mã nguồn mở 100%**. Mã nguồn của Frappe HR được lưu trữ trên GitHub dưới tài khoản **`frappe/hrms`**.

---

Dựa trên các nguồn thông tin được cung cấp, Frappe HR là một giải pháp quản trị nhân sự mã nguồn mở được xây dựng trên một ngăn xếp công nghệ và framework cụ thể.

Các công nghệ và framework cần thiết để phát triển và tùy chỉnh Frappe HR là:

### 1. Frappe Framework (Low-code/No-code Platform)

Frappe HR được **xây dựng trên nền tảng Low-code/No-code Frappe Framework**. Đây là nền tảng cốt lõi, cung cấp kiến trúc và khả năng phát triển ứng dụng nhanh chóng:

*   **Tính chất:** Frappe Framework là một **khung ứng dụng web full-stack** (*full-stack web application framework*).
*   **Ngôn ngữ Lập trình:** Framework này được viết bằng **Python và Javascript**. Đối với ERPNext (cũng sử dụng cùng framework), mã nguồn chủ yếu là Python (80.3%) và JavaScript (17.3%).
*   **Chức năng Cốt lõi:** Framework cung cấp một nền tảng vững chắc để xây dựng các ứng dụng web, bao gồm **lớp trừu tượng hóa cơ sở dữ liệu** (*database abstraction layer*), **xác thực người dùng** (*user authentication*), và một **REST API**.
*   **Mô hình Dữ liệu:** Frappe Framework là một **framework hướng dữ liệu siêu dữ liệu** (*meta-data-driven framework*) cho phép phát triển ứng dụng nhanh.
*   **Khả năng Tùy chỉnh (Low-code/No-code):** Framework này cho phép người dùng cấu hình và tùy chỉnh cao.
    *   Nó cho phép **xây dựng các biểu mẫu riêng** (*build your own forms*).
    *   Thiết lập **quy trình phê duyệt nâng cao** (*advanced approval workflows*).
    *   Quản lý vai trò và quyền hạn.
    *   Tạo **báo cáo và bảng điều khiển** (*reports and dashboards*).
    *   Người dùng có thể tạo **trường tùy chỉnh** (*custom fields*), **định dạng in** (*print formats*), và **thay đổi bố cục** (*change layouts*) ngay lập tức.

### 2. Ngăn xếp Công nghệ Giao diện người dùng (UI Stack)

Đối với giao diện người dùng, Frappe HR sử dụng thư viện được phát triển bởi Frappe:

*   **Frappe UI:** Đây là một **thư viện UI dựa trên Vue** (*Vue-based UI library*) được sử dụng để cung cấp giao diện người dùng hiện đại.
*   **Công nghệ Frontend:** Frappe HR sử dụng **Vue** (10.4% mã nguồn), **JavaScript** (15.5%) và **HTML/CSS/SCSS**. Thư viện Frappe UI cung cấp nhiều thành phần khác nhau để xây dựng các ứng dụng một trang (*single-page applications*) trên nền Frappe Framework.

### 3. Phụ thuộc và Môi trường Vận hành

Để triển khai Frappe HR, cần có môi trường nền tảng và các công nghệ phụ thuộc liên quan đến hệ sinh thái Frappe:

*   **Cơ sở dữ liệu:** Mặc dù không được đề cập trực tiếp cho Frappe HR, nhưng giải pháp mẹ ERPNext được xây dựng trên **hệ thống cơ sở dữ liệu MariaDB**.
*   **ERPNext:** Mặc dù Frappe HR là một sản phẩm riêng biệt từ phiên bản 14, nó vẫn được thiết kế để **tích hợp kế toán liền mạch với ERPNext**. Trong quá trình thiết lập cục bộ cho Frappe HR, người dùng được hướng dẫn **lấy ứng dụng ERPNext** (`bench get-app erpnext`) trước khi cài đặt ứng dụng HRMS (`bench get-app hrms`), cho thấy ERPNext có thể là một phụ thuộc nền tảng hoặc cung cấp các DocTypes và dịch vụ tài chính cần thiết.
*   **Phát triển Ứng dụng Di động:** Frappe HR hỗ trợ **ứng dụng di động** (*Mobile App*). Mã nguồn Frappe HR có đề cập đến chủ đề **PWA** (*Progressive Web App*) và **Mobile App Installation/Push Notification**.
*   **Công cụ Tích hợp:** Hệ thống hỗ trợ tích hợp với các ứng dụng bên thứ ba thông qua **REST APIs** và **webhook support**, cũng như tích hợp với **thiết bị chấm công sinh trắc học** (*Biometric Attendance Devices*).

Tóm lại, để phát triển hoặc tùy chỉnh Frappe HR, cần nắm vững:

| Khía cạnh | Công nghệ/Framework Bắt buộc | Chi tiết Ngôn ngữ |
| :--- | :--- | :--- |
| **Nền tảng Phát triển** | **Frappe Framework** (Low-code/No-code) | **Python** (Backend Logic/Framework core) |
| **Giao diện Người dùng** | **Frappe UI** | **JavaScript**, **Vue** (Frontend/UI library) |
| **Cơ sở dữ liệu** | MariaDB (theo thông tin của ERPNext) | |
| **Môi trường** | Frappe Bench, Docker (cho thiết lập phát triển/sản xuất) | |