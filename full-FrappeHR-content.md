# Frappe HR: Giải pháp Quản trị Nhân sự và Bảng lương Mã nguồn Mở (RAG Optimized)

## 1. Tổng quan và Nền tảng Công nghệ

**Frappe HR** là một giải pháp Phần mềm Quản lý Nhân sự (HR) và Bảng lương (Payroll) **mã nguồn mở 100%**, hiện đại và thân thiện với người dùng, được thiết kế để thúc đẩy sự xuất sắc trong đội ngũ nhân sự. Nó là một giải pháp HRMS hoàn chỉnh với hơn 13 module khác nhau.

Ban đầu, Frappe HR là một tập hợp các module trong ERPNext. Từ phiên bản 14 trở đi, nó đã được phát triển thành một sản phẩm độc lập.

### 1.1. Ưu điểm cốt lõi

*   **Mã nguồn mở (Open Source):** Frappe HR là sản phẩm HR & Payroll mã nguồn mở 100%, cung cấp sự minh bạch và linh hoạt hoàn toàn. Điều này giúp doanh nghiệp tránh các khoản phí bản quyền đắt đỏ và tình trạng khóa nhà cung cấp (vendor lock-in).
*   **Chi phí và Khả năng mở rộng:** Chi phí không tăng theo quy mô đội ngũ. Kiến trúc mô-đun và khả năng mở rộng đa công ty (multi-company capabilities) khiến nó phù hợp cho cả doanh nghiệp nhỏ và doanh nghiệp lớn với hàng ngàn nhân viên.
*   **Khả năng tùy chỉnh cao:** Được xây dựng trên Frappe Framework Low-code/No-code, người dùng có thể tạo báo cáo, biểu mẫu, trường tùy chỉnh, định dạng in và thay đổi bố cục ngay lập tức.
*   **Tích hợp:** Frappe HR tích hợp liền mạch với **ERPNext** (cung cấp giao diện hợp nhất cho HR, Bảng lương và Kế toán) và hỗ trợ tích hợp với các hệ thống ERP hoặc kế toán khác thông qua API REST và webhook. Nó cũng có thể tích hợp với các công cụ sinh trắc học và ngân hàng.

### 1.2. Nền tảng công nghệ (Under the Hood)

Frappe HR được xây dựng trên hai thành phần chính:

1.  **Frappe Framework:** Một framework ứng dụng web full-stack được viết bằng Python và Javascript. Framework này cung cấp nền tảng mạnh mẽ bao gồm lớp trừu tượng hóa cơ sở dữ liệu, xác thực người dùng và API REST.
2.  **Frappe UI:** Một thư viện UI dựa trên Vue, cung cấp giao diện người dùng hiện đại.

### 1.3. Hỗ trợ Lực lượng Lao động Phân tán (Remote/Hybrid)

Frappe HR được thiết kế để quản lý lực lượng lao động phân tán (distributed workforce) một cách hiệu quả. Nhân viên có thể thực hiện check-in từ xa (mobile check-ins), yêu cầu nghỉ phép, nộp bảng chấm công và truy cập thông tin qua hệ thống web hoặc ứng dụng di động.

## 2. Các Module Chính và Tài liệu (DocTypes)

Frappe HR bao gồm các module quản lý nhân sự chính:

| Nhóm Module | Tài liệu/DocTypes Chính | Chức năng | Nguồn |
| :--- | :--- | :--- | :--- |
| **Quản lý Tổ chức** | Employee, Designation, Department, Branch, Employee Grade, Organizational Chart | Quản lý cấu trúc và hồ sơ nhân viên |
| **Chấm công & Ca kíp** | Attendance, Employee Checkin, Auto Attendance, Shift Management, Roster | Theo dõi giờ làm việc, chấm công tự động, và quản lý lịch trình ca kíp |
| **Quản lý Nghỉ phép** | Leave Type, Leave Policy, Leave Allocation, Leave Application, Compensatory Leave Request, Leave Encashment, Holiday List, Leave Ledger Report | Quản lý chính sách nghỉ phép, phân bổ, và quy trình yêu cầu/chấp thuận |
| **Quản lý Hiệu suất** | Appraisal Template, Appraisal Cycle, Appraisal, Goal, Employee Performance Feedback, Appraisal Overview Report | Thiết lập mục tiêu (Goal), Khu vực Kết quả Chính (KRA), đánh giá hiệu suất 360°, và tự đánh giá |
| **Tuyển dụng** | Staffing Plan, Job Requisition, Job Opening, Job Applicant, Interview Management, Job Offer, Appointment Letter, Employee Referral, Job Portal | Lập kế hoạch nhân sự, quản lý yêu cầu tuyển dụng, hồ sơ ứng viên, phỏng vấn và chào mời làm việc |
| **Vòng đời Nhân sự** | Employee Onboarding, Employee Promotion, Employee Separation, Employee Transfer, Employee Skill Map, Exit Interview, Full and Final Statement | Quản lý quá trình gia nhập, thăng chức, chuyển đổi và thôi việc |
| **Bảng lương & Thuế** | Payroll Setup, Salary Structure, Salary Slip, Payroll Entry, Income Tax Slab, Gratuity, Loans, Employee Tax Exemption Declaration | Tính lương, quản lý thuế, tạm ứng, và các phúc lợi liên quan |

## 3. Quản lý Tuyển dụng (Recruitment Management)

Module này giúp doanh nghiệp tạo và quản lý các vị trí tuyển dụng còn trống, hồ sơ ứng viên và kế hoạch tuyển dụng.

### 3.1. Staffing Plan (Kế hoạch Nhân sự)
*   **Mục đích:** Giúp lập kế hoạch nhu cầu nhân lực và ngân sách tuyển dụng cho công ty trong một khoảng thời gian.
*   **Đặc điểm:** Job Opening chỉ có thể được tạo theo số lượng vị trí tuyển dụng và ngân sách đã lên kế hoạch trong Staffing Plan đang hoạt động.
*   **Thông tin chi tiết:** Bao gồm Designation (Chức danh), Number of Positions (Số lượng vị trí cần), Current Count (Số nhân viên hiện tại), Vacancies (Số lượng còn trống), Estimated Cost Per Position (Chi phí ước tính cho mỗi vị trí) và Total Estimated Budget (Tổng ngân sách ước tính).

### 3.2. Job Requisition (Yêu cầu Tuyển dụng)
*   **Định nghĩa:** Là tài liệu nội bộ được tạo để yêu cầu thuê nhân sự mới.
*   **Quy trình:** Sau khi Job Requisition được **Open & Approved** (Mở & Phê duyệt), nó có thể được chuyển đổi thành Job Opening mới hoặc được liên kết với Job Opening hiện có.
*   **Chỉ số:** Tự động tính toán **Time to Fill Metric**, đo lường số ngày cần thiết để lấp đầy một vị trí, từ khi yêu cầu được đăng cho đến khi được đánh dấu là *Filled*.

### 3.3. Job Opening (Vị trí Tuyển dụng)
*   **Định nghĩa:** Một vị trí còn trống trong công ty.
*   **Tính năng Job Portal:** Cho phép xuất bản Job Opening lên trang web công ty bằng cách bật tùy chọn **'Publish on website'**. Ứng viên có thể duyệt và nộp đơn từ cổng thông tin này.

### 3.4. Job Applicant (Ứng viên)
*   **Định nghĩa:** Người nộp đơn xin việc cho một Job Opening cụ thể.
*   **Tạo Tự động:** Có thể liên kết với Tài khoản Email để tự động tạo Job Applicant cho mỗi email nhận được.
*   **Employee Referral (Giới thiệu):** Khi nguồn ứng viên là Employee Referral, Job Applicant được tạo từ tài liệu Employee Referral.

### 3.5. Appointment Letter (Thư bổ nhiệm)
*   **Định nghĩa:** Là thư được nhà tuyển dụng gửi cho ứng viên được chọn, yêu cầu họ gia nhập một vị trí cụ thể.
*   **Điều kiện tiên quyết:** Cần phải có Job Applicant trước khi tạo Appointment Letter.
*   **Quy trình:** Chọn Job Applicant, Appointment Date, và có thể điền thủ công phần Giới thiệu, Điều khoản, và Lời kết, hoặc chọn một **Appointment Letter Template** để tự động điền nội dung.

### 3.6. Employee Referral (Giới thiệu Nhân viên)
*   **Mục đích:** Quản lý quy trình khi nhân viên hiện tại giới thiệu ứng viên tiềm năng.
*   **Quy trình:** Tạo tài liệu Employee Referral, sau đó tạo Job Applicant từ tài liệu này. Trạng thái của Employee Referral sẽ tự động đồng bộ hóa với trạng thái của Job Applicant (ví dụ: Rejected, Accepted).
*   **Thưởng Giới thiệu (Referral Bonus):** Khi trạng thái là "Accepted", có thể tạo tài liệu **Additional Salary** để theo dõi việc chi trả tiền thưởng giới thiệu.

## 4. Quản lý Vòng đời Nhân sự (Employee Lifecycle Management)

Quản lý các giai đoạn khác nhau mà nhân viên trải qua trong quá trình làm việc.

### 4.1. Employee Onboarding (Hội nhập)
*   **Mục đích:** Duy trì các hoạt động tiêu chuẩn cần thực hiện khi tuyển dụng (ví dụ: kiểm tra lý lịch, tạo tài khoản email, phân bổ nghỉ phép).
*   **Quy trình:** Onboarding được tạo cho một Job Applicant đã được phê duyệt. Bằng cách chọn **Employee Onboarding Template** (Mẫu Hội nhập), các hoạt động (Activities) đã xác định trước sẽ được kéo vào.
*   **Tạo Tác vụ (Tasks):** Khi Employee Onboarding được nộp (submit), một **Project** sẽ được tạo, và các **Tasks** sẽ được tạo cho mỗi hoạt động.

### 4.2. Employee Separation (Thôi việc)
*   **Định nghĩa:** Là tình huống thỏa thuận dịch vụ giữa nhân viên và tổ chức chấm dứt.
*   **Quy trình:** Theo dõi các hoạt động bàn giao cần thực hiện (ví dụ: thu hồi tài sản, xóa tài khoản email) thông qua **Employee Separation Template**. Tương tự như Onboarding, khi nộp tài liệu Separation, một **Project** với các **Tasks** sẽ được tạo để theo dõi tiến độ.

### 4.3. Exit Interview (Phỏng vấn Thôi việc)
*   **Định nghĩa:** Một cuộc phỏng vấn khảo sát được thực hiện với nhân viên sắp rời công ty.
*   **Quy trình:** Cần phải thiết lập **Relieving Date** (Ngày thôi việc) cho nhân viên. Có thể lên lịch phỏng vấn và ghi lại **Interview Summary**.
*   **Tính năng:** Cho phép gửi **Exit Questionnaire** (bảng câu hỏi thôi việc) cho nhân viên dưới dạng Web Form. Các câu hỏi có thể được tùy chỉnh thông qua Custom DocType và Web Form, sau đó liên kết trong HR Settings.

### 4.4. Full and Final Statement (FnF) (Thanh toán Cuối cùng)
*   **Mục đích:** Giải quyết tất cả các khoản phải trả (payables), phải thu (receivables) và tài sản được phân bổ cho nhân viên khi họ thôi việc. Tài liệu này đóng vai trò như một checklist và có tác động kế toán.
*   **Các khoản được xem xét:**
    *   **Payables:** Salary Slip, Gratuity, Expense Claim, Bonus, Leave Encashment.
    *   **Receivables:** Loan, Employee Advance.
*   **Quản lý Tài sản:** Hệ thống tự động lấy tài sản đã cấp phát (từ các bản ghi *Asset Movement*). Có thể chọn **"Recover Cost"** để tính chi phí tài sản vào Tổng số tiền Phải thu nếu nhân viên giữ lại tài sản đó.
*   **Thanh toán:** Sau khi xác nhận tất cả các khoản, có thể tạo **Journal Entry** để ghi nhận thanh toán và chốt sổ tài khoản.

## 5. Quản lý Hiệu suất (Performance Management)

Module này bao gồm việc thiết lập Mục tiêu, Phản hồi và Chu kỳ Đánh giá.

### 5.1. Appraisal Template (Mẫu Đánh giá)
*   **Mục đích:** Định nghĩa các **KRA (Key Result Areas)** và **Feedback Criteria** (Tiêu chí Phản hồi) dựa trên đó nhân viên sẽ được xếp hạng.
*   **Điều kiện tiên quyết:** Cần tạo các KRA và Employee Feedback Criteria master trước khi tạo mẫu.

### 5.2. Appraisal Cycle (Chu kỳ Đánh giá)
*   **Định nghĩa:** Một khoảng thời gian xác định để đánh giá hiệu suất tổng thể của nhân viên.
*   **KRA Evaluation Method (Phương pháp Đánh giá KRA):** Có hai phương pháp chính:
    1.  **Automated Based on Goal Progress (Mặc định):** Điểm KRA được tính tự động dựa trên phần trăm hoàn thành các mục tiêu (Goals) được liên kết với KRA đó.
    2.  **Manual Rating:** Xếp hạng mục tiêu/KRA theo cách thủ công (0-5).
*   **Tạo Đánh giá hàng loạt:** Có thể tạo các tài liệu **Appraisal** hàng loạt cho các nhân viên được lọc theo chi nhánh, phòng ban, hoặc chức danh.
*   **Appraisal Stats:** Cung cấp tổng quan về chu kỳ, bao gồm số lượng người được đánh giá (**Appraisees**), số lần **Self Appraisal Pending** (tự đánh giá đang chờ xử lý), và nhân viên không có Phản hồi hoặc Mục tiêu.

### 5.3. Appraisal (Đánh giá)
*   **Định nghĩa:** Quá trình tài liệu hóa và đánh giá hiệu suất của nhân viên.
*   **Quy trình tạo:** Cần chọn Employee và Appraisal Cycle. Nếu Appraisal Template đã được thiết lập trong chu kỳ, nó sẽ được tự động tìm nạp.
*   **Tính điểm Cuối cùng (Final Score):** Điểm Cuối cùng được tính là **mức trung bình** của Goal Score (Điểm Mục tiêu), Avg Feedback Score (Điểm Phản hồi Trung bình), và Self Appraisal Score (Điểm Tự đánh giá).
*   **Phản hồi:** Lịch sử phản hồi nhận được trong chu kỳ sẽ hiển thị trong tab Feedback, bao gồm điểm phản hồi trung bình (average feedback score), và chỉ hiển thị các tài liệu phản hồi đã được nộp và nhạy cảm với quyền hạn.

### 5.4. Goal (Mục tiêu)
*   **Định nghĩa:** Quá trình lập kế hoạch các mục tiêu cụ thể, đo lường được và định hướng vai trò mà nhân viên hướng tới.
*   **Cấu trúc:** Goals có cấu trúc phân cấp (mục tiêu cha/con). Tiến độ của mục tiêu cha được tính tự động dựa trên mức trung bình tiến độ của các mục tiêu con.
*   **Tác động đến Appraisal:** Nếu mục tiêu được liên kết với Appraisal Cycle và KRA, việc cập nhật tiến độ mục tiêu sẽ cập nhật **Goal Score** liên kết với KRA đó.

### 5.5. Employee Performance Feedback (Phản hồi Hiệu suất)
*   **Mục đích:** Cho phép thu thập phản hồi 360° về hiệu suất của nhân viên. Người đánh giá (Reviewer) sẽ xếp hạng dựa trên tiêu chí được thiết lập trong Appraisal Template.
*   **Tính năng:** Sau khi nộp (submit), điểm phản hồi trung bình sẽ được cập nhật vào tài liệu Appraisal liên kết.

## 6. Đào tạo (Training)

Module này giúp xác định các chương trình đào tạo và theo dõi kết quả.

### 6.1. Training Program (Chương trình Đào tạo)
*   **Định nghĩa:** Xác định các chương trình được thiết kế để đào tạo nhân viên hoặc các cá nhân khác về các kỹ năng cụ thể.
*   **Tính năng:** Sau khi tạo Training Program, có thể lên lịch **Training Event** trong chương trình đó.

### 6.2. Training Event (Sự kiện Đào tạo)
*   **Định nghĩa:** Cho phép lên lịch các hội thảo, workshop, hội nghị, v.v., nằm trong một Training Program.
*   **Tính năng:** Có thể mời nhân viên tham gia bằng cách chọn trong bảng Employees, và khi nộp Event, một thông báo sẽ được gửi qua Email Alert "Training Scheduled".

### 6.3. Training Result (Kết quả Đào tạo)
*   **Mục đích:** Lưu trữ kết quả đào tạo theo từng nhân viên dựa trên đánh giá của người đào tạo sau khi sự kiện hoàn thành.
*   **Tính năng:** Khi Training Result được nộp, một email thông báo sẽ được gửi đến nhân viên để yêu cầu họ chia sẻ phản hồi thông qua **Training Feedback**.

## 7. Các Tài liệu Quan trọng Khác

### 7.1. Employee Transfer (Chuyển công tác)
*   **Định nghĩa:** Một hình thức luân chuyển nội bộ, trong đó nhân viên được chuyển từ công việc này sang công việc khác, thường là ở một địa điểm, phòng ban hoặc đơn vị khác.
*   **Tính năng:** Cho phép chuyển nhân viên sang **Công ty mới** (New Company) (tùy chọn). Có thể chọn **'Create New Employee'** để tạo một ID nhân viên mới cho người được chuyển (khi đó ID cũ sẽ được đánh dấu là *relieved* (thôi việc)).

### 7.2. Employee Skill Map (Sơ đồ Kỹ năng)
*   **Mục đích:** Ghi lại bộ kỹ năng và các khóa đào tạo của nhân viên. Dữ liệu này được dùng để đánh giá từng kỹ năng của nhân viên (Proficiency level, thang điểm 5) và theo dõi sự phát triển sau mỗi khóa đào tạo nội bộ. Dữ liệu này có thể được sử dụng trong quá trình đánh giá (appraisals).

### 7.3. Interview Management (Quản lý Phỏng vấn)
*   **Thành phần:** Bao gồm định nghĩa Interview Types (Loại phỏng vấn), thiết lập Interview Rounds (Vòng phỏng vấn), tạo Interviews (Cuộc phỏng vấn) và điền Interview Feedbacks (Phản hồi phỏng vấn).
    *   **Interview Round:** Xác định các vòng phỏng vấn (ví dụ: technical, HR) và cho phép chỉ định Người phỏng vấn (Interviewers) được phép cung cấp phản hồi cho vòng đó, cũng như bộ kỹ năng mong đợi (**Expected Skillset**).
    *   **Interview:** Ghi lại cuộc họp phỏng vấn chính thức giữa Job Applicant và Interviewers. Có thể xem lịch trình theo dạng Calendar View.
    *   **Interview Feedback:** Tài liệu dùng để đánh giá **Skills** của Job Applicant và đưa ra nhận xét chung sau buổi phỏng vấn.

