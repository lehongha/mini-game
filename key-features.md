Dữ liệu Tính năng Frappe HR cho Chatbot

1.0 Quản lý Tuyển dụng (Recruitment Management)

Module Quản lý Tuyển dụng trong Frappe HR là một công cụ chiến lược, cho phép hoạch định nguồn nhân lực và tối ưu hóa toàn bộ quy trình thu hút nhân tài. Module cung cấp một khuôn khổ có cấu trúc để quản lý toàn bộ vòng đời tuyển dụng, từ việc lập kế hoạch và tìm kiếm ứng viên đến phỏng vấn, đưa ra đề nghị và hội nhập nhân viên mới. Bằng cách số hóa và tự động hóa các bước này, module giúp nâng cao chất lượng tuyển dụng, tiết kiệm thời gian và đảm bảo tổ chức luôn có đủ nhân tài để đạt được các mục tiêu kinh doanh.

1.1 Hoạch định và Yêu cầu

Kế hoạch nhân sự (Staffing Plan) và Yêu cầu tuyển dụng (Job Requisition) hoạt động cùng nhau như thế nào?

Trong Frappe HR, Kế hoạch nhân sự (Staffing Plan) và Yêu cầu tuyển dụng (Job Requisition) là hai công cụ phối hợp chặt chẽ để quản lý nhu cầu nhân sự và ngân sách:

* Kế hoạch nhân sự được sử dụng để hoạch định nhu cầu nhân lực và ngân sách cho một khoảng thời gian cụ thể. Nó xác định số lượng vị trí cần tuyển cho từng chức danh và chi phí ước tính.
* Yêu cầu tuyển dụng là một tài liệu nội bộ được tạo ra để đề xuất tuyển dụng một nhân sự mới. Các yêu cầu này có thể được lấy dữ liệu vào Kế hoạch nhân sự để phục vụ cho việc lập ngân sách.
* Hệ thống cho phép giới hạn số lượng Tin tuyển dụng (Job Opening) được tạo ra dựa trên số vị trí trống đã được xác định trong Kế hoạch nhân sự đang hoạt động, đảm bảo việc tuyển dụng luôn tuân thủ kế hoạch đã được phê duyệt.

1.2 Tìm kiếm và Thu hút Ứng viên

Tin tuyển dụng (Job Opening) được tạo và quản lý như thế nào trong Frappe HR?

Tin tuyển dụng (Job Opening) là bản ghi về một vị trí trống trong công ty. Quy trình tạo và quản lý tin tuyển dụng trong Frappe HR như sau:

1. Tạo mới: Người dùng tạo một Tin tuyển dụng mới bằng cách nhập Tiêu đề công việc và liên kết nó với một Chức danh (Designation) và Phòng ban (Department) cụ thể.
2. Đăng tải: Bằng cách kích hoạt tùy chọn "Publish on website", tin tuyển dụng sẽ được hiển thị công khai trên Cổng thông tin việc làm (Job Portal) của công ty, cho phép ứng viên bên ngoài xem và ứng tuyển.
3. Quản lý trạng thái: Mỗi tin tuyển dụng có thể được đặt ở trạng thái "Mở" (Open) hoặc "Đóng" (Closed). Khi một vị trí đã được lấp đầy, người dùng có thể đóng tin tuyển dụng để ngừng nhận hồ sơ mới.

Cổng thông tin việc làm (Job Portal) là gì và ứng viên sử dụng nó như thế nào?

Cổng thông tin việc làm (Job Portal) là một giao diện web cho phép các ứng viên tiềm năng duyệt và ứng tuyển vào các vị trí đang được đăng tuyển công khai. Quy trình cho ứng viên như sau:

1. Truy cập và tìm kiếm: Ứng viên truy cập vào trang việc làm của công ty (ví dụ: https://tencongty.com/jobs). Họ có thể tìm kiếm theo từ khóa hoặc lọc các vị trí theo công ty, phòng ban, hoặc loại hình công việc.
2. Xem chi tiết và ứng tuyển: Sau khi nhấp vào một tin tuyển dụng để xem mô tả chi tiết, ứng viên có thể nhấn nút "Apply Now".
3. Nộp hồ sơ: Một biểu mẫu web sẽ hiện ra để ứng viên điền thông tin cá nhân và tải lên hồ sơ. Khi nộp đơn, hệ thống sẽ tự động tạo một tài liệu Hồ sơ Ứng viên (Job Applicant) tương ứng trong Frappe HR.

Tính năng Giới thiệu nhân viên (Employee Referral) hoạt động ra sao?

Tính năng Giới thiệu nhân viên (Employee Referral) cho phép nhân viên hiện tại đề xuất các ứng viên phù hợp từ mạng lưới quan hệ của họ, giúp tiết kiệm chi phí và nâng cao chất lượng tuyển dụng. Quy trình hoạt động bao gồm hai chức năng chính:

* Tạo Hồ sơ Ứng viên và Đồng bộ Trạng thái:
  1. Một nhân viên tạo một bản ghi Giới thiệu nhân viên và điền thông tin cơ bản của ứng viên được giới thiệu.
  2. Sau khi gửi, một nút "Create Job Applicant" sẽ xuất hiện, cho phép người dùng tạo một Hồ sơ Ứng viên (Job Applicant) từ thông tin giới thiệu.
  3. Trạng thái của hồ sơ giới thiệu và hồ sơ ứng viên được đồng bộ hóa. Ví dụ, khi hồ sơ ứng viên được chấp nhận (Accepted) hoặc từ chối (Rejected), trạng thái của hồ sơ giới thiệu cũng sẽ tự động cập nhật tương ứng.
* Quản lý Thưởng giới thiệu:
  1. Nếu ứng viên được tuyển dụng và công ty có chính sách thưởng, người dùng có thể đánh dấu vào ô "Is applicable for referral bonus" trước khi gửi giới thiệu.
  2. Khi trạng thái giới thiệu được cập nhật thành "Accepted", một nút "Create Additional Salary" sẽ xuất hiện, cho phép tạo một tài liệu Lương bổ sung (Additional Salary) cho nhân viên đã giới thiệu để quản lý và thanh toán khoản thưởng này.

1.3 Quản lý Ứng viên và Phỏng vấn

Hồ sơ Ứng viên (Job Applicant) được tạo và sử dụng như thế nào?

Hồ sơ Ứng viên (Job Applicant) là một bản ghi về người đã ứng tuyển vào một vị trí công việc. Hồ sơ này có thể được tạo từ nhiều nguồn khác nhau:

* Website Listing: Khi ứng viên nộp đơn qua Cổng thông tin việc làm.
* Employee Referral: Khi nhân viên nội bộ giới thiệu ứng viên.
* Walk-In: Dành cho ứng viên đến nộp hồ sơ trực tiếp.
* Email: Frappe HR cho phép liên kết một tài khoản email (ví dụ: tuyendung@congty.com) với hệ thống. Mọi email nhận được tại địa chỉ này sẽ tự động tạo một Hồ sơ Ứng viên mới, giúp tập trung hóa việc quản lý hồ sơ từ nhiều kênh.

Quy trình quản lý phỏng vấn trong Frappe HR bao gồm những gì?

Frappe HR cung cấp một hệ thống quản lý phỏng vấn toàn diện với các thành phần chính sau:

1. Loại phỏng vấn (Interview Types): Cho phép định nghĩa các loại phỏng vấn khác nhau như phỏng vấn nhóm, phỏng vấn trực tiếp (tùy chọn).
2. Vòng phỏng vấn (Interview Rounds): Đây là bước thiết lập nền tảng, nơi bạn định nghĩa các vòng phỏng vấn tiêu chuẩn cho một vị trí (ví dụ: vòng kỹ thuật, vòng nhân sự). Tại đây, bạn chỉ định người phỏng vấn cho mỗi vòng và các kỹ năng cần được đánh giá.
3. Lịch phỏng vấn (Interviews): Sau khi đã có các vòng phỏng vấn, bạn có thể lên lịch một buổi phỏng vấn cụ thể cho một ứng viên nhất định, liên kết nó với một Vòng phỏng vấn đã định nghĩa trước đó.
4. Phản hồi phỏng vấn (Interview Feedback): Sau buổi phỏng vấn, người phỏng vấn gửi lại đánh giá của họ thông qua tài liệu này.

Phản hồi phỏng vấn (Interview Feedback) được ghi lại và tổng hợp như thế nào?

Quy trình ghi nhận và tổng hợp phản hồi được thực hiện một cách có hệ thống:

* Gửi phản hồi: Người phỏng vấn được ủy quyền sẽ tạo một tài liệu Phản hồi phỏng vấn (Interview Feedback), trong đó họ đánh giá ứng viên trên các kỹ năng đã được xác định trước trong Vòng phỏng vấn (Interview Round) bằng cách xếp hạng theo thang điểm sao và cung cấp nhận xét chi tiết.
* Tổng hợp tự động: Tất cả các phản hồi cho một buổi phỏng vấn sẽ được tổng hợp tự động trên bảng điều khiển (dashboard) của tài liệu Lịch phỏng vấn (Interview). Bảng tóm tắt này hiển thị điểm đánh giá trung bình chung, điểm trung bình cho từng kỹ năng và tất cả nhận xét từ người phỏng vấn, giúp người ra quyết định có cái nhìn tổng quan và dễ dàng so sánh, đánh giá ứng viên.

1.4 Đưa ra Đề nghị

Sự khác biệt giữa Thư mời nhận việc (Job Offer) và Thư bổ nhiệm (Appointment Letter) là gì?

Cả hai đều là những tài liệu quan trọng ở giai đoạn cuối của quy trình tuyển dụng nhưng có mục đích khác nhau:

* Thư mời nhận việc (Job Offer): Đây là tài liệu được gửi cho ứng viên đã được chọn, trong đó nêu rõ các điều khoản đề nghị như gói lương, chức danh, cấp bậc, phòng ban, số ngày nghỉ phép được hưởng và các thông tin khác. Ứng viên sẽ xem xét và phản hồi (chấp nhận hoặc từ chối) lời mời này.
* Thư bổ nhiệm (Appointment Letter): Đây là lá thư chính thức do nhà tuyển dụng soạn thảo để yêu cầu ứng viên đã chấp nhận lời mời đến nhận việc tại một vị trí cụ thể. Thư bổ nhiệm chỉ có thể được tạo dựa trên một Hồ sơ Ứng viên (Job Applicant) đã có trong hệ thống.

Sau khi tuyển dụng thành công, hành trình của nhân viên trong tổ chức bắt đầu, và giai đoạn tiếp theo là quản lý vòng đời của họ.


--------------------------------------------------------------------------------


2.0 Quản lý Vòng đời Nhân viên (Employee Lifecycle Management)

Module Quản lý Vòng đời Nhân viên trong Frappe HR được thiết kế để quản lý tất cả các giai đoạn quan trọng mà một nhân viên trải qua trong suốt thời gian làm việc. Từ ngày đầu tiên hội nhập, qua các giai đoạn phát triển, luân chuyển cho đến khi thôi việc, module này đảm bảo mọi quá trình chuyển đổi đều diễn ra suôn sẻ và được ghi nhận đầy đủ, giúp bộ phận nhân sự nâng cao trải nghiệm nhân viên, đảm bảo tuân thủ quy trình và hỗ trợ hiệu quả cho sự phát triển của tổ chức.

2.1 Hội nhập

Quy trình Hội nhập nhân viên (Employee Onboarding) trong Frappe HR hoạt động như thế nào?

Tính năng Hội nhập nhân viên (Employee Onboarding) giúp chuẩn hóa và theo dõi một tập hợp các hoạt động cần thiết khi một nhân viên mới bắt đầu làm việc. Quy trình này hoạt động như sau:

* Sử dụng Mẫu hội nhập: Người dùng tạo ra các Mẫu hội nhập (Employee Onboarding Template), đóng vai trò như một kế hoạch chi tiết chứa danh sách các hoạt động cần thực hiện (ví dụ: tạo tài khoản email, cấp phát máy tính). Đối với mỗi hoạt động, người dùng có thể chỉ định người hoặc vai trò (User or Role) chịu trách nhiệm thực hiện.
* Tạo quy trình cho nhân viên mới: Khi có nhân viên mới, một quy trình hội nhập được tạo ra bằng cách áp dụng mẫu tương ứng.
* Tự động tạo Dự án và Công việc: Khi quy trình được gửi đi, hệ thống sẽ tự động tạo một Dự án (Project) với các Công việc (Tasks) tương ứng cho mỗi hoạt động trong mẫu. Các công việc này được giao cho người hoặc vai trò đã được chỉ định và có thể theo dõi tiến độ.
* Hoàn thành quy trình: Trạng thái của quy trình hội nhập chỉ được đánh dấu là "Hoàn thành" (Completed) khi tất cả các công việc liên quan đã được hoàn thành, đảm bảo không bỏ sót bất kỳ bước quan trọng nào.

2.2 Phát triển và Thay đổi

Việc luân chuyển nhân viên (Employee Transfer) được ghi nhận như thế nào?

Luân chuyển nhân viên là việc điều chuyển một nhân viên sang một công việc, địa điểm hoặc phòng ban khác. Frappe HR sử dụng tài liệu Luân chuyển nhân viên (Employee Transfer) để ghi lại những thay đổi này một cách chính thức.

* Người dùng tạo một tài liệu luân chuyển, chọn nhân viên và chỉ định các thông tin mới (công ty mới, phòng ban mới, v.v.).
* Hệ thống cung cấp một tùy chọn "Tạo nhân viên mới" (Create New Employee). Nếu được chọn, một mã nhân viên mới sẽ được tạo cho vị trí mới, và mã nhân viên cũ sẽ được đánh dấu là đã thôi việc (relieved).
* Lưu ý quan trọng: Nếu một mã nhân viên mới được tạo, việc phân bổ ngày nghỉ phép cho nhân viên mới phải được tạo thủ công.

Sơ đồ Kỹ năng Nhân viên (Employee Skill Map) được sử dụng để làm gì?

Sơ đồ Kỹ năng Nhân viên (Employee Skill Map) là một công cụ để theo dõi và quản lý bộ kỹ năng, trình độ chuyên môn và các khóa đào tạo của một nhân viên.

* Khi tạo sơ đồ, các kỹ năng liên quan đến chức danh của nhân viên sẽ được tự động lấy ra. Người quản lý có thể đánh giá mức độ thành thạo của nhân viên cho từng kỹ năng.
* Dữ liệu này rất hữu ích trong các kỳ đánh giá hiệu suất (appraisals) và giúp xác định nhu cầu đào tạo bổ sung để phát triển năng lực cho nhân viên.

2.3 Thôi việc

Quy trình Thôi việc Nhân viên (Employee Separation) được quản lý ra sao?

Quy trình Thôi việc Nhân viên (Employee Separation) được áp dụng cho những nhân viên đã xin nghỉ việc hoặc bị chấm dứt hợp đồng. Tương tự như quy trình hội nhập, nó giúp chuẩn hóa các thủ tục bàn giao.

* Người dùng sử dụng một Mẫu thôi việc (Employee Separation Template) để định nghĩa các hoạt động tiêu chuẩn khi nhân viên nghỉ việc (ví dụ: thu hồi máy tính xách tay, xóa tài khoản email, thanh toán các khoản nợ).
* Khi gửi đi, một Dự án (Project) cùng các Công việc (Tasks) tương ứng sẽ được tạo ra để đảm bảo mọi thủ tục được theo dõi và hoàn thành đầy đủ.

Phỏng vấn thôi việc (Exit Interview) được thực hiện như thế nào?

Phỏng vấn thôi việc (Exit Interview) là một cuộc khảo sát dành cho nhân viên sắp rời khỏi công ty để thu thập phản hồi.

* Tài liệu Phỏng vấn thôi việc được dùng để ghi lại thông tin chi tiết về buổi phỏng vấn, tóm tắt nội dung và quyết định cuối cùng (giữ lại nhân viên hoặc xác nhận nghỉ việc - Retained/Exit Confirmed).
* Tính năng nổi bật là "Gửi Bảng câu hỏi thôi việc" (Send Exit Questionnaire), cho phép gửi email đến nhân viên với một liên kết đến Biểu mẫu Web (Web Form). Nhân viên có thể điền và gửi phản hồi của họ trực tuyến một cách thuận tiện.

Bảng Quyết toán Cuối cùng (Full and Final Statement) có mục đích gì?

Bảng Quyết toán Cuối cùng (Full and Final Statement) là tài liệu được sử dụng để giải quyết tất cả các khoản phải trả (lương, trợ cấp), phải thu (khoản vay, tạm ứng) và các tài sản đã cấp phát khi một nhân viên nghỉ việc.

* Nó hoạt động như một danh sách kiểm tra (checklist) để đảm bảo quá trình bàn giao diễn ra suôn sẻ với các tác động kế toán chính xác.
* Tài liệu này cũng bao gồm tùy chọn "Recover Cost" để thu hồi chi phí tài sản trong trường hợp nhân viên không trả lại tài sản đó cho công ty.

Việc quản lý tốt vòng đời nhân viên giúp xác định nhu cầu phát triển, từ đó dẫn đến các chương trình đào tạo phù hợp.


--------------------------------------------------------------------------------


3.0 Quản lý Đào tạo (Training Management)

Module Quản lý Đào tạo trong Frappe HR cung cấp các công cụ cần thiết để các tổ chức lập kế hoạch, thực hiện và đánh giá các sáng kiến phát triển nhân viên một cách có hệ thống. Mục tiêu của module này là giúp thu hẹp khoảng cách kỹ năng, nâng cao hiệu suất làm việc của đội ngũ và thúc đẩy văn hóa học tập liên tục, từ đó đóng góp vào lợi thế cạnh tranh và sự phát triển bền vững của doanh nghiệp.

3.1 Lập kế hoạch và Thực hiện Đào tạo

Sự khác biệt giữa Chương trình Đào tạo (Training Program) và Sự kiện Đào tạo (Training Event) là gì?

Trong Frappe HR, hai khái niệm này được phân biệt rõ ràng để dễ dàng quản lý:

* Chương trình Đào tạo (Training Program): Đây là một kế hoạch tổng thể, bao quát được thiết kế để đào tạo nhân viên về các kỹ năng cụ thể. Nó giống như một "khóa học" lớn, định hướng cho nhiều hoạt động đào tạo nhỏ hơn.
* Sự kiện Đào tạo (Training Event): Đây là một buổi đào tạo cụ thể, có lịch trình rõ ràng (như một buổi hội thảo, workshop hoặc seminar) được tổ chức trong khuôn khổ của một Chương trình Đào tạo.

Làm thế nào để lên lịch và mời nhân viên tham gia một Sự kiện Đào tạo?

Quy trình lên lịch và mời nhân viên rất đơn giản:

1. Tạo Sự kiện Đào tạo: Người dùng tạo một Sự kiện Đào tạo (Training Event) mới, điền các thông tin chi tiết như loại sự kiện, cấp độ (cho người mới bắt đầu, trung cấp, chuyên gia), người đào tạo và địa điểm.
2. Mời nhân viên: Trong tài liệu Sự kiện Đào tạo, có một bảng để thêm danh sách nhân viên được mời tham gia.
3. Gửi thông báo: Khi tài liệu được lưu và gửi đi (submit), hệ thống sẽ tự động gửi một thông báo qua email đến tất cả các nhân viên có trong danh sách mời để thông báo về lịch trình của sự kiện.

3.2 Đánh giá và Phản hồi

Kết quả Đào tạo (Training Result) của nhân viên được ghi lại như thế nào?

Sau khi một sự kiện đào tạo kết thúc, kết quả của từng nhân viên sẽ được ghi lại trong tài liệu Kết quả Đào tạo (Training Result).

* Tài liệu này cho phép người đào tạo hoặc người quản lý ghi lại số giờ tham gia, điểm số (grade) và nhận xét chi tiết cho mỗi nhân viên đã tham dự sự kiện. Điều này giúp theo dõi mức độ tiếp thu và hiệu quả của khóa học đối với từng cá nhân.

Nhân viên cung cấp Phản hồi Đào tạo (Training Feedback) bằng cách nào?

Để thu thập ý kiến từ người học, Frappe HR cung cấp tài liệu Phản hồi Đào tạo (Training Feedback).

* Sau khi khóa học hoàn tất, nhân viên có thể sử dụng tài liệu này để chia sẻ suy nghĩ và đánh giá của họ về sự kiện đào tạo.
* Họ chỉ cần chọn Sự kiện Đào tạo đã tham gia và nhập phản hồi. Thông tin này sau đó sẽ được bộ phận nhân sự xem xét để cải thiện chất lượng các chương trình đào tạo trong tương lai.

Việc đào tạo và phát triển nhân viên có liên quan mật thiết đến việc đánh giá và quản lý hiệu suất của họ.


--------------------------------------------------------------------------------


4.0 Quản lý Hiệu suất (Performance Management)

Module Quản lý Hiệu suất trong Frappe HR là một bộ công cụ tích hợp cho phép các công ty thiết lập mục tiêu, tiến hành đánh giá và cung cấp phản hồi liên tục. Mục tiêu của module này là nuôi dưỡng một văn hóa hiệu suất cao, cải thiện sự gắn kết và giữ chân nhân viên, đồng thời đảm bảo rằng những đóng góp của mỗi cá nhân đều trực tiếp thúc đẩy các kết quả kinh doanh quan trọng của tổ chức.

4.1 Thiết lập Mục tiêu và Tiêu chí

Mục tiêu (Goals) được thiết lập và theo dõi trong Frappe HR như thế nào?

Thiết lập Mục tiêu (Goals) là quá trình lập kế hoạch cho các mục tiêu cụ thể, có thể đo lường được cho nhân viên. Trong Frappe HR, tính năng này hoạt động như sau:

* Cấu trúc phân cấp: Các mục tiêu có thể được thiết lập theo cấu trúc cha-con. Tiến độ của mục tiêu cha sẽ được tự động tính toán dựa trên tiến độ của các mục tiêu con.
* Liên kết với đánh giá: Một mục tiêu có thể được liên kết với một Chu kỳ Đánh giá (Appraisal Cycle) và được gắn thẻ với một Lĩnh vực Kết quả Chính (KRA). Khi tiến độ mục tiêu được cập nhật, điểm số của KRA tương ứng trong bản đánh giá cũng sẽ được tự động cập nhật.

Vai trò của Mẫu đánh giá (Appraisal Template) là gì?

Mẫu đánh giá (Appraisal Template) là nơi xác định các tiêu chí dùng để đánh giá nhân viên. Vai trò chính của nó bao gồm:

* Định nghĩa KRA: Mẫu đánh giá dùng để xác định các Lĩnh vực Kết quả Chính (Key Result Areas - KRAs) cùng với trọng số (weightage) của chúng.
* Xác định Tiêu chí Phản hồi: Nó cũng là nơi để định nghĩa các Tiêu chí Phản hồi (Feedback Criteria) mà nhân viên sẽ được đánh giá dựa trên đó trong quá trình phản hồi hiệu suất và tự đánh giá.
* Áp dụng theo chức danh: Các mẫu có thể được tạo cho các chức danh khác nhau và được liên kết trực tiếp với chúng để đảm bảo tính nhất quán và phù hợp.

4.2 Thực hiện Đánh giá

Chu kỳ Đánh giá (Appraisal Cycle) được sử dụng để làm gì?

Chu kỳ Đánh giá (Appraisal Cycle) xác định một khoảng thời gian cụ thể mà trong đó hiệu suất của nhân viên được đánh giá (ví dụ: hàng quý, hàng năm). Chức năng chính của nó là:

* Xác định phạm vi và phương pháp: Cho phép lọc và chọn các nhân viên sẽ tham gia đánh giá, đồng thời chọn phương pháp đánh giá KRA: "Tự động dựa trên Tiến độ Mục tiêu" (Automated Based on Goal Progress) hoặc "Đánh giá thủ công" (Manual Rating).
* Tạo đánh giá hàng loạt: Từ một chu kỳ, người dùng có thể tạo hàng loạt các tài liệu Đánh giá (Appraisal) cho tất cả các nhân viên đã chọn.
* Tùy chỉnh công thức tính điểm: Mặc dù điểm cuối cùng mặc định là trung bình cộng của ba thành phần, người dùng có thể kích hoạt công thức tùy chỉnh để tính điểm theo cách riêng.

Quy trình Đánh giá (Appraisal) bao gồm những thành phần chính nào?

Tài liệu Đánh giá (Appraisal) là nơi tập trung để đánh giá một nhân viên trong một chu kỳ cụ thể. Nó bao gồm các thành phần chính sau:

* Đánh giá KRA: Phần này hiển thị điểm số của các KRA, được tính toán tự động dựa trên tiến độ mục tiêu hoặc được nhập thủ công.
* Lịch sử Phản hồi: Tổng hợp tất cả các Phản hồi Hiệu suất (Performance Feedback) mà nhân viên đã nhận được trong suốt chu kỳ.
* Tự đánh giá (Self Appraisal): Một khu vực để nhân viên tự đánh giá hiệu suất của mình dựa trên các tiêu chí đã được định sẵn.
* Điểm số cuối cùng (Final Score): Theo mặc định, điểm số cuối cùng được tính bằng trung bình cộng của Điểm Mục tiêu (Goal Score), Điểm Phản hồi Trung bình (Average Feedback Score) và Điểm Tự đánh giá (Self Appraisal Score).

4.3 Phản hồi và Báo cáo

Phản hồi Hiệu suất Nhân viên (Employee Performance Feedback) hoạt động như thế nào?

Tính năng này cho phép thu thập phản hồi 360 độ về hiệu suất của một nhân viên từ những người đánh giá (reviewers).

* Người đánh giá sử dụng tài liệu Phản hồi Hiệu suất Nhân viên (Employee Performance Feedback) để xếp hạng nhân viên dựa trên các tiêu chí được thiết lập trong Mẫu đánh giá (Appraisal Template) và có thể cung cấp nhận xét bằng văn bản.
* Điểm phản hồi trung bình sẽ được tự động tính toán và cập nhật vào tài liệu Đánh giá (Appraisal) được liên kết, cung cấp một góc nhìn đa chiều về hiệu suất của nhân viên.

Báo cáo Tổng quan Đánh giá (Appraisal Overview Report) cung cấp thông tin gì?

Báo cáo Tổng quan Đánh giá (Appraisal Overview Report) cung cấp một cái nhìn tổng quan về kết quả của các kỳ đánh giá. Nó hiển thị các điểm dữ liệu quan trọng cho mỗi nhân viên, bao gồm:

* Chu kỳ Đánh giá (Appraisal Cycle)
* Số lượng Phản hồi (Feedback Count)
* Điểm Mục tiêu (Goal Score)
* Điểm Phản hồi Trung bình (Avg Feedback Score)
* Điểm Tự đánh giá (Self Score)
* Điểm số Cuối cùng (Final Score)
