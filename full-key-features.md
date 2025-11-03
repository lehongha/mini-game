Tổng Quan Toàn Diện về Các Tính Năng Cốt Lõi của Frappe HR

Lời nói đầu

Tài liệu này cung cấp một bản phân tích toàn diện về các tính năng cốt lõi của nền tảng Frappe HR. Nội dung này được xây dựng như một cơ sở kiến thức nền tảng, chi tiết hóa các khả năng mà một chatbot sử dụng công nghệ RAG (Retrieval-Augmented Generation) có thể tận dụng để hỗ trợ người dùng trong việc giải đáp các thắc mắc liên quan đến lĩnh vực nhân sự.

1. Giới thiệu về Frappe HR: Nền tảng Quản trị Nhân sự Mã nguồn mở Toàn diện

Phần này cung cấp một cái nhìn tổng quan về Frappe HR, triết lý hoạt động và giá trị cốt lõi của nó như một giải pháp nhân sự hiện đại và tích hợp. Frappe HR là một phần mềm Quản lý Nhân sự và Tính lương thân thiện với người dùng và hoàn toàn mã nguồn mở. Ban đầu, nó được phát triển dưới dạng một tập hợp các module trong hệ thống ERPNext. Khi các module này dần hoàn thiện, từ phiên bản 14 trở đi, Frappe HR đã được tách ra thành một sản phẩm độc lập.

Nền tảng này mang lại nhiều lợi ích chiến lược cho các tổ chức đang tìm kiếm một giải pháp nhân sự linh hoạt và hiệu quả về chi phí.

* Mã nguồn mở 100% (100% Open Source): Frappe HR cung cấp sự minh bạch và linh hoạt hoàn toàn. Được hỗ trợ bởi một cộng đồng lớn, các doanh nghiệp có thể dễ dàng tải xuống, sử dụng, chỉnh sửa và tùy biến phần mềm theo nhu cầu riêng.
* Chi phí hợp lý và Toàn diện (Affordable & Inclusive): Frappe HR giúp doanh nghiệp thoát khỏi mô hình định giá SaaS theo người dùng thường bị đội giá. Với Frappe HR, chi phí phần mềm không tăng theo quy mô đội ngũ. Doanh nghiệp có thể lựa chọn tự lưu trữ (self-hosting) hoặc sử dụng dịch vụ đám mây được quản lý, giúp chi phí được kiểm soát và gắn liền với mô hình hỗ trợ và lưu trữ thay vì phí bản quyền trên mỗi nhân viên.
* Khả năng Tùy biến cao (Highly Customizable): Doanh nghiệp có thể cấu hình và tùy chỉnh hệ thống theo ý muốn, bao gồm việc tạo báo cáo, biểu mẫu, trường tùy chỉnh, định dạng in và thay đổi bố cục một cách nhanh chóng.
* Tích hợp Dễ dàng (Easy Integrations): Frappe HR có khả năng tích hợp liền mạch với ERPNext, giúp hợp nhất quy trình nhân sự, tính lương và kế toán. Ngoài ra, nó cũng có thể tích hợp với các công cụ sinh trắc học và phần mềm của bên thứ ba thông qua API.
* Bộ sản phẩm Nhân sự Tất cả trong một (All-in-one HR Suite): Nền tảng này là một giải pháp HRMS hoàn chỉnh với hơn 13 module khác nhau, cho phép quản lý tất cả các hoạt động nhân sự và tính lương từ một bảng điều khiển duy nhất và một ứng dụng di động dễ sử dụng, từ tuyển dụng đến thôi việc.

Về mặt kỹ thuật, Frappe HR được xây dựng trên nền tảng Frappe Framework, một framework low-code/no-code cho phép phát triển ứng dụng nhanh chóng. Nền tảng vững chắc này là yếu tố then chốt giúp Frappe HR cung cấp một bộ công cụ mạnh mẽ và linh hoạt. Tiếp theo, chúng ta sẽ đi sâu vào phân tích các module chức năng cụ thể của nền tảng.

2. Quản lý Quy trình Tuyển dụng (Recruitment Management)

Module tuyển dụng đóng vai trò chiến lược trong việc thu hút, đánh giá và tuyển dụng những tài năng hàng đầu một cách hiệu quả. Frappe HR cung cấp một bộ công cụ toàn diện để quản lý toàn bộ quy trình này, từ việc lập kế hoạch nhân sự cho đến khi gửi thư mời làm việc chính thức.

2.1. Lập Kế hoạch và Yêu cầu Tuyển dụng (Planning and Requisition)

* Kế hoạch Tuyển dụng (Staffing Plan): Tính năng này cho phép doanh nghiệp lập kế hoạch về nhu cầu nhân sự và ngân sách cho một khoảng thời gian nhất định. Kế hoạch này ghi lại các thông tin quan trọng như Chức danh (Designation), Số lượng vị trí trống (Vacancies) và Chi phí ước tính (Estimated Cost), giúp các nhà quản lý tuyển dụng tuân thủ ngân sách đã được duyệt.
* Yêu cầu Tuyển dụng (Job Requisition): Đây là một tài liệu nội bộ được sử dụng để đề xuất tuyển dụng một vị trí mới. Quy trình bắt đầu từ khi tạo yêu cầu, trải qua các bước phê duyệt và sau khi được chấp thuận, yêu cầu này có thể được chuyển đổi thành một Vị trí Tuyển dụng (Job Opening). Khi Vị trí Tuyển dụng tương ứng được đóng lại, trạng thái của Yêu cầu Tuyển dụng sẽ tự động cập nhật thành Đã lấp đầy (Filled). Hệ thống cũng tự động tính toán chỉ số "Thời gian để lấp đầy vị trí trống" (Time to Fill) để đo lường hiệu quả tuyển dụng.

2.2. Thu hút và Quản lý Ứng viên (Attracting and Managing Applicants)

* Vị trí Tuyển dụng (Job Opening): Tài liệu này đại diện cho một vị trí trống cụ thể trong công ty. Việc tạo một Vị trí Tuyển dụng bị giới hạn bởi số lượng đã được hoạch định trong Kế hoạch Tuyển dụng. Khi tùy chọn "Đăng tải lên trang web" (Publish on website) được kích hoạt, vị trí này sẽ hiển thị công khai trên Cổng thông tin Tuyển dụng.
* Cổng thông tin Tuyển dụng (Job Portal): Đây là giao diện dành cho ứng viên bên ngoài, nơi họ có thể duyệt, lọc và nộp đơn ứng tuyển cho các vị trí đang được đăng tải. Mỗi đơn ứng tuyển sẽ tự động tạo ra một bản ghi Hồ sơ Ứng viên trong hệ thống.
* Hồ sơ Ứng viên (Job Applicant): Các bản ghi này được tạo ra khi ứng viên nộp đơn qua Cổng thông tin Tuyển dụng hoặc được tạo thủ công. Một tính năng hữu ích là khả năng tự động tạo Hồ sơ Ứng viên từ các email được gửi đến một tài khoản email đã được liên kết, giúp tập trung hóa nguồn ứng viên.
* Giới thiệu Nhân viên (Employee Referral): Hệ thống hỗ trợ quản lý quy trình giới thiệu ứng viên từ nội bộ. Khi một nhân viên hiện tại giới thiệu một ứng viên, một Hồ sơ Ứng viên mới sẽ được tạo và liên kết với người giới thiệu, đồng thời cho phép theo dõi khoản thưởng giới thiệu.

2.3. Quy trình Phỏng vấn và Tuyển chọn (Interview and Selection Process)

* Vòng Phỏng vấn (Interview Round): Frappe HR cho phép thiết lập một quy trình phỏng vấn có cấu trúc bằng cách định nghĩa các vòng khác nhau, chẳng hạn như vòng kỹ thuật, vòng nhân sự. Ở mỗi vòng, người phỏng vấn tương ứng sẽ được chỉ định, đồng thời các kỹ năng cần đánh giá cho vòng đó cũng được xác định trước.
* Lịch Phỏng vấn (Interview): Tài liệu này được tạo ra để lên lịch một buổi phỏng vấn cụ thể với một ứng viên cho một vòng phỏng vấn nhất định. Các lịch phỏng vấn đã lên kế hoạch có thể được xem trực quan trên giao diện lịch (calendar view).
* Phản hồi Phỏng vấn (Interview Feedback): Sau mỗi buổi phỏng vấn, người phỏng vấn cung cấp phản hồi thông qua một quy trình có cấu trúc. Hệ thống tự động điền bảng Đánh giá Kỹ năng (Skill Assessment) với các kỹ năng đã được định nghĩa sẵn trong Vòng Phỏng vấn. Người phỏng vấn sẽ cho điểm từng kỹ năng và cung cấp nhận xét chung. Các phản hồi này sau đó được tổng hợp lại trong một giao diện tóm tắt để dễ dàng so sánh và đánh giá.
* Đề nghị Nhận việc (Job Offer) và Thư mời làm việc (Appointment Letter): Hệ thống phân biệt rõ ràng giữa hai tài liệu quan trọng này. Đề nghị Nhận việc nêu rõ mức lương và các điều khoản được đề xuất. Sau khi ứng viên chấp nhận, Thư mời làm việc sẽ được tạo ra như một văn bản chính thức yêu cầu ứng viên gia nhập công ty.

Sau khi tuyển dụng thành công một nhân viên mới, bước tiếp theo là quản lý toàn bộ hành trình của họ trong tổ chức.

3. Quản lý Vòng đời Nhân viên (Employee Lifecycle Management)

Module này đóng vai trò là hệ thống ghi nhận (system of record) cho tất cả các thay đổi dữ liệu chính của nhân viên, đảm bảo tính toàn vẹn thông tin từ lúc hội nhập cho đến khi thôi việc. Frappe HR cung cấp các công cụ để quản lý tất cả các giai đoạn quan trọng trong hành trình của một nhân viên tại tổ chức một cách có hệ thống.

3.1. Hội nhập và Phát triển (Onboarding and Development)

* Quy trình Hội nhập Nhân viên mới (Onboarding): Frappe HR sử dụng Mẫu Hội nhập Nhân viên Mới (Employee Onboarding Template) để chuẩn hóa quy trình tiếp nhận nhân viên. Mẫu này định nghĩa một danh sách các hoạt động tiêu chuẩn (ví dụ: tạo tài khoản email, cấp phát tài sản). Khi áp dụng cho một nhân viên mới, hệ thống sẽ tự động tạo ra một Dự án (Project) với các Nhiệm vụ (Tasks) tương ứng để theo dõi tiến độ hoàn thành của từng hoạt động.
* Sơ đồ Kỹ năng Nhân viên (Employee Skill Map): Đây là công cụ để theo dõi và đánh giá các kỹ năng của nhân viên so với yêu cầu của chức danh họ đang nắm giữ. Dữ liệu này rất hữu ích trong việc xác định nhu cầu đào tạo và cũng có thể được sử dụng như một dữ liệu đầu vào khách quan tại thời điểm đánh giá hiệu suất.

3.2. Luân chuyển và Thăng tiến (Internal Mobility)

* Luân chuyển Nhân viên (Employee Transfer): Hệ thống hỗ trợ quy trình điều chuyển một nhân viên sang một công ty hoặc phòng ban khác trong cùng một tổ chức, giúp quản lý sự thay đổi vị trí một cách chính thức và có hệ thống.
* Thăng chức Nhân viên (Employee Promotion): Frappe HR cho phép quản lý các quyết định thăng chức như một phần của vòng đời nhân viên, ghi nhận sự phát triển và thay đổi vai trò của họ trong công ty.

3.3. Quy trình Thôi việc (Separation Process)

Frappe HR cung cấp các tính năng để quản lý quy trình khi một nhân viên rời khỏi công ty một cách chuyên nghiệp và có trật tự.

* Thôi việc Nhân viên (Employee Separation): Tài liệu này sử dụng các mẫu (template) để quản lý các hoạt động bàn giao. Khi được nộp, hệ thống sẽ tự động tạo một Dự án (Project) với các Nhiệm vụ (Tasks) tương ứng cho mỗi hoạt động (ví dụ: thu hồi tài sản, thanh toán công nợ), đảm bảo không bỏ sót công việc nào.
* Phỏng vấn Thôi việc (Exit Interview): Tính năng này giúp lên lịch và ghi lại nội dung các buổi phỏng vấn thôi việc. Đặc biệt, hệ thống cho phép gửi một bảng câu hỏi tùy chỉnh thông qua Biểu mẫu Web (Web Form) để thu thập phản hồi từ nhân viên một cách tiện lợi.
* Báo cáo Quyết toán Cuối cùng (Full and Final Statement): Đây là quy trình để giải quyết tất cả các khoản phải thu và phải trả với nhân viên sắp nghỉ việc. Tính năng này còn hỗ trợ việc thu hồi chi phí tài sản nếu cần thiết, đảm bảo quá trình thanh lý được minh bạch và chính xác.

Trong suốt vòng đời của mình, việc đánh giá hiệu suất của nhân viên là một quy trình liên tục và quan trọng.

4. Quản lý Hiệu suất (Performance Management)

Module quản lý hiệu suất có giá trị chiến lược trong việc thúc đẩy sự phát triển của nhân viên và liên kết những đóng góp cá nhân với các mục tiêu chung của công ty. Frappe HR cung cấp một khuôn khổ có cấu trúc để thiết lập mục tiêu, thực hiện đánh giá và cung cấp phản hồi liên tục.

4.1. Thiết lập Mục tiêu và Đánh giá (Goal and Appraisal Setup)

* Thiết lập Mục tiêu (Goal Setting): Tính năng này cho phép thiết lập các mục tiêu theo một cấu trúc phân cấp, bao gồm các mục tiêu chính (parent goals) và các mục tiêu phụ (sub-goals). Tiến độ của các mục tiêu chính được tự động tính toán dựa trên mức độ hoàn thành trung bình của các mục tiêu phụ, giúp theo dõi tiến trình một cách trực quan.
* Mẫu Đánh giá (Appraisal Template): Đây là công cụ để định nghĩa các Khu vực Kết quả Chính (Key Result Areas - KRAs) và các tiêu chí phản hồi cho các vai trò khác nhau trong công ty. Việc sử dụng mẫu giúp đảm bảo tính nhất quán và công bằng trong quá trình đánh giá.
* Chu kỳ Đánh giá (Appraisal Cycle): Tính năng này xác định một khoảng thời gian cụ thể cho việc đánh giá hiệu suất (ví dụ: hàng quý, hàng năm). Nó cho phép tạo ra các tài liệu đánh giá hàng loạt cho tất cả các nhân viên tham gia vào chu kỳ đó, giúp tiết kiệm thời gian quản trị.

4.2. Thực thi Đánh giá (The Appraisal Process)

Tài liệu Đánh giá (Appraisal) là trung tâm của quy trình, nơi tổng hợp tất cả thông tin liên quan đến hiệu suất của một nhân viên trong một chu kỳ.

* Phương pháp Đánh giá KRA (KRA Evaluation Methods): Frappe HR cung cấp hai phương pháp để đánh giá KRA:
  * Tự động dựa trên Tiến độ Mục tiêu (Automated Based on Goal Progress): Điểm số KRA được tự động tính toán dựa trên phần trăm hoàn thành của các mục tiêu đã được liên kết với KRA đó.
  * Xếp hạng Thủ công (Manual Rating): Người quản lý có thể đánh giá và cho điểm các KRA một cách thủ công dựa trên quan sát và nhận định của mình.
* Phản hồi Hiệu suất Nhân viên (Employee Performance Feedback): Tính năng này hỗ trợ quy trình đánh giá 360 độ (360-degree feedback), cho phép thu thập phản hồi từ nhiều người đánh giá khác nhau (quản lý, đồng nghiệp).
* Tự đánh giá (Self Appraisal): Nhân viên có cơ hội tự suy ngẫm và đánh giá về hiệu suất của chính mình, góp phần tạo nên một cái nhìn toàn diện hơn.
* Tính điểm Cuối cùng (Final Score Calculation): Điểm số cuối cùng được tính toán dựa trên điểm trung bình của Điểm Mục tiêu (Goal Score), Điểm Phản hồi (Feedback Score) và Điểm Tự đánh giá (Self Appraisal Score).
* Báo cáo Tổng quan Đánh giá (Appraisal Overview Report): Báo cáo này cung cấp một cái nhìn tổng hợp về điểm số đánh giá của tất cả nhân viên, giúp ban lãnh đạo có được cái nhìn toàn cảnh về hiệu suất của tổ chức.

Kết quả đánh giá hiệu suất thường là cơ sở để xác định các cơ hội đào tạo và phát triển, giúp thu hẹp khoảng cách kỹ năng của nhân viên.

5. Đào tạo và Phát triển (Training and Development)

Module đào tạo hỗ trợ sự phát triển của nhân viên và giúp lấp đầy các khoảng trống kỹ năng được xác định thông qua đánh giá hiệu suất hoặc sơ đồ kỹ năng. Frappe HR cung cấp các công cụ để lập kế hoạch, thực hiện và ghi nhận các hoạt động đào tạo một cách có hệ thống.

5.1. Lập kế hoạch và Thực hiện Đào tạo (Planning and Executing Training)

* Chương trình Đào tạo (Training Program): Đây là tài liệu dùng để lập kế hoạch tổng thể cho các sáng kiến đào tạo. Nó xác định mục tiêu và phạm vi của một chương trình đào tạo lớn hơn.
* Sự kiện Đào tạo (Training Event): Dựa trên một chương trình đào tạo, tính năng này được sử dụng để lên lịch các buổi học cụ thể như hội thảo (workshops) hoặc chuyên đề (seminars). Hệ thống cũng hỗ trợ quá trình mời nhân viên tham gia vào các sự kiện này.

5.2. Ghi nhận Kết quả và Phản hồi (Recording Results and Feedback)

* Kết quả Đào tạo (Training Result): Sau khi một sự kiện đào tạo kết thúc và nhân viên được đánh giá, tài liệu này được sử dụng để lưu trữ kết quả của từng nhân viên, bao gồm điểm số (grades), nhận xét từ người huấn luyện (comments) và các thông tin liên quan khác.
* Phản hồi Đào tạo (Training Feedback): Tính năng này cho phép nhân viên đã tham dự cung cấp phản hồi của riêng họ về sự kiện đào tạo. Điều này giúp tổ chức đánh giá chất lượng và hiệu quả của các chương trình đào tạo để cải tiến trong tương lai.

Từ các hoạt động phát triển có mục tiêu, chúng ta chuyển sang các quy trình vận hành thiết yếu hàng ngày để quản lý lực lượng lao động.

6. Các Tính năng Vận hành Nhân sự Khác (Other Key HR Operations Features)

Phần này đề cập đến các module thiết yếu khác đảm bảo hoạt động nhân sự hàng ngày diễn ra suôn sẻ, từ quản lý chấm công, nghỉ phép đến bảng lương và chi phí.

* Quản lý Chấm công và Ca làm việc (Attendance and Shift Management): Cung cấp các công cụ để quản lý thời gian làm việc của nhân viên, bao gồm chấm công qua di động (mobile check-in), quản lý lịch làm việc theo ca (roster management), tự động hóa việc ghi nhận chấm công (auto-attendance) và khả năng tích hợp với các thiết bị sinh trắc học.
* Quản lý Nghỉ phép (Leave Management): Cho phép cấu hình các chính sách nghỉ phép phức tạp, quản lý danh sách ngày nghỉ lễ, xử lý đơn xin nghỉ phép của nhân viên và quản lý các khoản thanh toán cho ngày phép chưa sử dụng (encashments).
* Quản lý Chi phí (Expense Management): Hỗ trợ quy trình tạm ứng cho nhân viên (employee advances), yêu cầu công tác (travel requests) và kê khai chi phí (expense claims). Tính năng này tích hợp liền mạch với phân hệ kế toán của ERPNext.
* Bảng lương và Thuế (Payroll & Taxation): Cung cấp khả năng tạo các cấu trúc lương đa dạng, cấu hình bậc thuế thu nhập, thực hiện quy trình tính lương và xử lý các khoản lương bổ sung như lương ngoài chu kỳ (off cycle payments), thưởng giữ chân (retention bonus) và các khoản khuyến khích nhân viên (employee incentive).
* Ứng dụng Di động Frappe HR (Frappe HR Mobile App): Cung cấp các chức năng chính ngay trên điện thoại thông minh, cho phép nhân viên thực hiện các tác vụ như xin nghỉ phép, chấm công ra/vào và truy cập hồ sơ cá nhân một cách tiện lợi.

Tóm lại, Frappe HR khẳng định vị thế là một nền tảng toàn diện và tích hợp, đáp ứng đầy đủ các nhu cầu của quản trị nguồn nhân lực hiện đại.
