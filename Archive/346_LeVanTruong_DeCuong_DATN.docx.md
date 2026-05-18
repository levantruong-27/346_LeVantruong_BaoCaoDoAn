

| ![logo][image1] |  TRƯỜNG ĐẠI HỌC THUỶ LỢI  KHOA CÔNG NGHỆ THÔNG TIN  BẢN TÓM TẮT ĐỀ CƯƠNG ĐỒ ÁN TỐT NGHIỆP  |
| :---: | :---: |

***Tên đề tài:*** **Xây dựng hệ thống quản lý nhà hàng thông minh ứng dụng trí tuệ nhân tạo**	

*Sinh viên thực hiện*: Lê Văn Trường

*Lớp*: 64HTTT3

*Mã sinh viên:* 2251162195

*Số điện thoại:* 0386522328

*Email:* 2251162195@e.tlu.edu.vn

*Giáo viên hướng dẫn*: TS.Đỗ Oanh Cường        

*Email*: cuongdo@tlu.edu.vn

			          

**TÓM TẮT ĐỀ TÀI**  
Trong bối cảnh chuyển đổi số đang diễn ra mạnh mẽ, việc ứng dụng công nghệ thông tin vào quản lý nhà hàng không chỉ giúp tự động hóa quy trình vận hành mà còn nâng cao trải nghiệm khách hàng và tối ưu hóa doanh thu. Các phương pháp quản lý truyền thống (ghi chép thủ công, xử lý đơn hàng rời rạc) đang bộc lộ nhiều hạn chế như sai sót dữ liệu, chậm trễ xử lý và khó phân tích hiệu quả kinh doanh.  
Đề tài “Xây dựng hệ thống quản lý nhà hàng thông minh ứng dụng trí tuệ nhân tạo” hướng đến phát triển một hệ thống phần mềm trên nền tảng web, cho phép quản lý toàn diện các nghiệp vụ như: quản lý món ăn, đơn hàng, bàn, khách hàng, nhân viên và báo cáo doanh thu theo thời gian thực.

Hệ thống được thiết kế theo kiến trúc 3 tầng (Frontend – Backend – Database), sử dụng RESTful API để giao tiếp giữa các thành phần. Điểm nổi bật của hệ thống là tích hợp chatbot hỗ trợ người dùng, hoạt động dựa trên phương pháp rule-based (dựa trên kịch bản) kết hợp với việc gọi API từ hệ thống backend để truy xuất dữ liệu thực tế.

Cụ thể, chatbot được xây dựng bằng cách phân tích nội dung câu hỏi của người dùng và ánh xạ đến các kịch bản xử lý tương ứng. Sau đó, hệ thống sẽ gọi các API phù hợp để lấy dữ liệu như danh sách món ăn, thông tin đơn hàng, hoặc dữ liệu khách hàng, và trả về phản hồi cho người dùng dưới dạng ngôn ngữ tự nhiên.

Chatbot có thể thực hiện các chức năng như:

* Truy vấn và hiển thị danh sách món ăn   
* Gợi ý món ăn dựa trên dữ liệu có sẵn   
* Tra cứu trạng thái đơn hàng   
* Trả lời các câu hỏi cơ bản như giờ mở cửa, thông tin nhà hàng   
* Hỗ trợ nhân viên tìm kiếm nhanh thông tin trong hệ thống 

Ngoài ra, hệ thống còn tích hợp dashboard phân tích dữ liệu (Business Intelligence) giúp nhà quản lý theo dõi các chỉ số KPI quan trọng như doanh thu, số lượng đơn hàng và hành vi khách hàng, từ đó hỗ trợ đưa ra quyết định kinh doanh hiệu quả.

Đề tài hướng tới xây dựng một hệ thống quản lý nhà hàng hiện đại, dễ triển khai, có khả năng mở rộng và tích hợp các chức năng hỗ trợ thông minh ở mức cơ bản, phù hợp với nhu cầu thực tế của doanh nghiệp.

**CÁC MỤC TIÊU CHÍNH**

* Xây dựng hệ thống web quản lý nhà hàng đầy đủ chức năng theo mô hình MIS (Management Information System), hỗ trợ quản lý món ăn, đơn hàng, bàn, khách hàng và nhân viên   
* Phân tích và thiết kế hệ thống bằng các công cụ UML (Use Case Diagram, Sequence Diagram, Activity Diagram) nhằm mô hình hóa các nghiệp vụ chính của hệ thống   
* Thiết kế cơ sở dữ liệu quan hệ (MySQL/PostgreSQL) đảm bảo tính toàn vẹn dữ liệu, tối ưu truy vấn và hỗ trợ mở rộng trong tương lai   
* Xây dựng hệ thống backend theo kiến trúc RESTful API sử dụng NodeJS, đảm bảo khả năng mở rộng, bảo mật và dễ tích hợp với các hệ thống khác   
* Phát triển giao diện người dùng (Frontend) bằng ReactJS với thiết kế thân thiện, responsive, hỗ trợ đa thiết bị (desktop và mobile)   
* Xây dựng hệ thống phân quyền người dùng (Role-based Access Control) gồm các vai trò: Admin, Manager, Staff   
* Tích hợp chatbot hỗ trợ người dùng theo phương pháp rule-based kết hợp gọi API backend để truy xuất dữ liệu thực tế, giúp:   
  * Tra cứu thông tin món ăn   
  * Gợi ý món ăn dựa trên dữ liệu có sẵn   
  * Kiểm tra trạng thái đơn hàng   
  * Hỗ trợ tìm kiếm thông tin nhanh trong hệ thống   
* Xây dựng dashboard phân tích dữ liệu (Business Intelligence) để trực quan hóa các chỉ số quan trọng như doanh thu, số lượng đơn hàng, và hành vi khách hàng   
* Triển khai hệ thống trên môi trường VPS (Ubuntu) và cấu hình domain, sử dụng các công cụ như:   
  * Nginx làm web server và reverse proxy   
  * PM2 để quản lý tiến trình NodeJS   
  * SSL (HTTPS) để đảm bảo bảo mật khi truy cập hệ thống   
* Thực hiện kiểm thử hệ thống (Unit Test, Integration Test) nhằm đảm bảo tính ổn định và độ tin cậy của các chức năng   
* Đánh giá hiệu năng hệ thống dựa trên các tiêu chí như thời gian phản hồi, khả năng xử lý đồng thời và độ ổn định khi vận hành thực tế

                                             **NỘI DUNG CHÍNH**

### **1\. Phân tích yêu cầu hệ thống (Requirement Analysis)**

\- Thu thập yêu cầu từ thực tế (quy trình nhà hàng: order, thanh toán, quản lý bàn) 

\- Xác định: 

**\+** Use Case chi tiết cho từng actor (Admin, Staff, Manager, Customer) 

**\+** Functional Requirements: 

* CRUD món ăn, đơn hàng, khách hàng, bàn   
* Đặt bàn online   
* Thanh toán và cập nhật trạng thái đơn 

  **\+** Non-functional Requirements:

* Hiệu năng (response \< 2s) 

* Bảo mật (JWT, mã hóa dữ liệu) 

* Khả năng mở rộng (scalable)

### **2\. Thiết kế hệ thống (System Design)**

\- Thiết kế kiến trúc: 

\+ Mô hình 3-Tier Architecture 

\+ Frontend (React) – Backend (API) – Database 

\- Thiết kế UML: 

\+ Use Case Diagram 

\+ Sequence Diagram (luồng đặt món, thanh toán) 

\+ Activity Diagram (workflow hệ thống) 

\- Thiết kế cơ sở dữ liệu: 

\+ ERD (Entity Relationship Diagram) 

\+ Chuẩn hóa dữ liệu (3NF) 

\+ Các bảng chính: 

* Users, Orders, OrderDetails, Menu, Tables, Customers 

### **3\. Xây dựng hệ thống Backend**

\- Sử dụng NodeJS / FastAPI 

\- Xây dựng RESTful API: 

\+ /api/menu 

\+ /api/orders 

\+ /api/customers 

\+ /api/auth 

\- Xử lý: 

\+ Authentication (JWT) 

\- Kết nối Database: 

\+ MySQL 

\- Logging & Error Handling 

### **4\. Phát triển Frontend**

\- Sử dụng ReactJS: 

\+ Component-based architecture 

\- Xây dựng giao diện: 

\+ Dashboard quản lý 

\+ Trang đặt món 

\+ Trang quản lý nhân viên 

\- Responsive: 

\+ Hỗ trợ mobile \+ desktop 

\- Tích hợp API: 

\+ Axios / Fetch 

### **5\. Xây dựng hệ thống chatbot RAG**

* Xây dựng chatbot hỗ trợ người dùng dựa trên phương pháp rule-based kết hợp xử lý ngôn ngữ tự nhiên ở mức cơ bản (Natural Language Processing – NLP)   
* Thiết kế cơ chế phân tích và hiểu ý định người dùng (Intent Recognition) thông qua việc xử lý từ khóa, chuẩn hóa câu nhập (text preprocessing) và ánh xạ đến các kịch bản hội thoại phù hợp   
* Xây dựng tập các kịch bản hội thoại (conversation flows) cho các tình huống phổ biến như:   
  * Tra cứu danh sách món ăn   
  * Gợi ý món ăn   
  * Kiểm tra trạng thái đơn hàng   
  * Hỏi thông tin nhà hàng   
* Áp dụng cơ chế mapping giữa intent và hệ thống API backend**,** cho phép chatbot truy xuất dữ liệu theo thời gian thực thông qua các endpoint:   
  * /api/menu   
  * /api/orders   
  * /api/customers   
* Tích hợp cơ chế truy xuất dữ liệu động (dynamic data retrieval) từ hệ thống, đảm bảo thông tin phản hồi luôn chính xác và cập nhật   
* Xây dựng module xử lý và sinh phản hồi (response generation)**,** chuyển đổi dữ liệu từ API thành ngôn ngữ tự nhiên thân thiện với người dùng   
* Thiết kế kiến trúc chatbot theo hướng mở rộng (extensible)**,** cho phép nâng cấp trong tương lai sang các mô hình AI nâng cao như Machine Learning hoặc RAG-based chatbot   
* Tối ưu trải nghiệm người dùng thông qua việc xây dựng giao diện chat trực quan, phản hồi nhanh và hỗ trợ đa ngữ cảnh cơ bản

### **6\. Xây dựng Dashboard BI**

\- Sử dụng thư viện: 

\+ Chart.js / Recharts 

\- Hiển thị: 

\+ Doanh thu theo ngày/tháng 

\+ Top món ăn 

\+ Tỷ lệ khách quay lại 

\- KPI: 

\+ Revenue 

\+ Retention rate 

\+ Conversion rate 

### **7\. Kiểm thử hệ thống (Testing)**

\- Unit Test (backend API) 

\- Integration Test 

\- Test các luồng chính: 

\+ Đặt món → thanh toán 

\- Đánh giá: 

\+ Hiệu năng (response time) 

\+ Độ chính xác mô hình AI 

### **8\. Triển khai hệ thống (Deployment)**

* Hệ thống được triển khai trên VPS sử dụng Ubuntu, đảm bảo môi trường vận hành ổn định và dễ quản lý   
* Cài đặt môi trường chạy backend:   
  * NodeJS runtime   
  * Các thư viện và dependencies cần thiết   
* Sử dụng PM2 để:   
  * Quản lý tiến trình ứng dụng NodeJS   
  * Tự động restart khi xảy ra lỗi   
  * Theo dõi log hệ thống   
* Sử dụng Nginx làm reverse proxy:   
  * Điều hướng request từ domain đến backend   
  * Phục vụ frontend (file build production)   
  * Tối ưu hiệu năng và bảo mật   
* Cấu hình domain:   
  * Trỏ domain về địa chỉ IP của VPS   
  * Cho phép truy cập hệ thống qua URL   
* Cài đặt SSL (HTTPS):   
  * Sử dụng Certbot để cấp chứng chỉ   
  * Mã hóa dữ liệu giữa client và server   
* Triển khai frontend:   
  * Build ReactJS (production)   
  * Đưa lên server và cấu hình Nginx phục vụ   
* Thiết lập logging và monitoring:   
  * Theo dõi hoạt động hệ thống   
  * Phát hiện và xử lý lỗi   
* Kiểm tra và tối ưu sau triển khai:   
  * Đảm bảo tốc độ phản hồi   
  * Đảm bảo hệ thống hoạt động ổn định

### **9\. Đánh giá và hoàn thiện**

\- So sánh: 

\+ Trước khi có hệ thống 

\+ Sau khi áp dụng hệ thống 

\- Đánh giá: 

\+ Hiệu quả quản lý 

\+ Tăng trưởng doanh thu 

\- Hoàn thiện: 

\+ Báo cáo 

\+ Slide thuyết trình 

\+ Demo thực tế

**KẾT QUẢ DỰ KIẾN**

Xây dựng thành công hệ thống quản lý nhà hàng hoàn chỉnh trên nền tảng web với các module: 

### **\- Module MIS**

\+ Quản lý món ăn (CRUD, phân loại, giá, hình ảnh) 

\+ Quản lý đơn hàng (tạo đơn, cập nhật trạng thái, thanh toán) 

\+ Quản lý bàn (đặt bàn, trạng thái bàn) 

\+ Quản lý khách hàng (thông tin, lịch sử mua hàng) 

\+ Quản lý nhân viên và phân quyền (Admin/Staff/Manager) 

### **\- Module chatbot Rule-based**

\+ Xây dựng chatbot hỗ trợ người dùng dựa trên **rule-based**   
\+ Phân tích câu hỏi người dùng bằng từ khóa (keyword matching)   
\+ Mapping câu hỏi → API tương ứng  
\+ Gọi API backend:  
\+  /api/menu  
 \+ /api/orders  
 \+ /api/customers   
\+ Xử lý và format câu trả lời dạng text rõ ràng   
\+ Hỗ trợ các chức năng:

\+ Xem menu  
\+ Tra cứu đơn hàng  
\+ Tìm kiếm thông tin khách hàng 

### **\+** Thiết kế kịch bản hội thoại cơ bản, dễ sử dụng

### **\- Module BI (Dashboard)**

\+ Dashboard doanh thu theo thời gian 

\+ Biểu đồ top món bán chạy 

\+ Phân tích hành vi khách hàng 

\+ KPI: 

* Revenue   
* Retention rate   
* Conversion rate 

### **\- Hệ thống dữ liệu**

\+ Xây dựng pipeline dữ liệu: 

* Ingest → Clean → Transform → Store 

\+ Lưu trữ dữ liệu trong MySQL 

\+ Có khả năng mở rộng sang Data Warehouse 

### **\- Công nghệ & triển khai**

\+ Backend: NodeJS / FastAPI 

\+ Frontend: ReactJS 

\+ Database: MySQL  

\+ Nginx, pm2, vps

### **\- Chất lượng hệ thống**

\+ Giao diện hiện đại, responsive 

\+ Tốc độ xử lý nhanh, ổn định 

\+ Có logging và monitoring 

\+ Bảo mật: 

* JWT Authentication   
* Role-based access 

### **\- Demo & đánh giá**

\+ Demo đầy đủ luồng: 

* Đặt món → xử lý → thanh toán → báo cáo 

\+ So sánh: 

* Trước (quản lý thủ công)   
* Sau (hệ thống tự động) 

**KẾ HOẠCH THỰC HIỆN**

| TT | Thời gian | Nội dung công việc | Kết quả đạt được |
| :---: | :---: | :---: | :---: |
| 1 | Tuần 1-2 | Khảo sát thực tế, thu thập yêu cầu, xác định user (Admin, Staff, Manager), phân tích KPI hệ thống | Xây dựng tài liệu SRS đầy đủ, xác định rõ yêu cầu chức năng & phi chức năng, định nghĩa KPI làm cơ sở phát triển hệ thống |
| 2 | Tuần 3-4 | Thiết kế hệ thống: Use Case, BPMN, Sequence Diagram, ERD, kiến trúc hệ thống (3-tier) | Hoàn thiện bộ sơ đồ UML và kiến trúc hệ thống, đảm bảo mô hình hóa đầy đủ luồng nghiệp vụ và cấu trúc dữ liệu |
| 3 | Tuần 5-6 | Xây dựng backend (API REST), thiết kế database, xử lý dữ liệu (clean, transform) | Phát triển hệ thống API REST ổn định, database chuẩn hóa, dữ liệu được xử lý sạch và sẵn sàng phục vụ hệ thống |
| 4 | Tuần 7-8 | Phát triển Frontend (React), tích hợp API, xây dựng các module MIS (CRUD, workflow) | Hoàn thiện giao diện người dùng, tích hợp API thành công, các chức năng quản lý MIS hoạt động mượt và đúng nghiệp vụ |
| 5 | Tuần 9-10 | Xây dựng chatbot theo hướng rule-based: phân tích câu hỏi bằng keyword, mapping → API | Xây dựng chatbot có khả năng hiểu truy vấn cơ bản, kết nối API và phản hồi chính xác các thông tin như menu, đơn hàng, khách hàng |
| 6 | Tuần 11 | Xây dựng dashboard BI, trực quan hoá dữ liệu, KPI | Xây dựng dashboard trực quan, hiển thị KPI rõ ràng, hỗ trợ phân tích và ra quyết định |
| 7 | Tuần 12 | Kiểm thử hệ thống (unit, integration), tối ưu hiệu năng, bảo mật (JWT, phân quyền) | Hệ thống được kiểm thử toàn diện, cải thiện hiệu năng, đảm bảo bảo mật với cơ chế xác thực và phân quyền |
| 8 | Tuần 13 | Triển khai hệ thống trên VPS: cấu hình PM2, Nginx, domain, SSL, logging & monitoring | Triển khai hệ thống thành công trên môi trường thực tế, đảm bảo truy cập ổn định, bảo mật HTTPS và có cơ chế giám sát |
| 9 | Tuần 14 | Hoàn thiện báo cáo, slide, demo, chuẩn bị bảo vệ | Hoàn thiện tài liệu báo cáo, slide trình bày và hệ thống demo ổn định, sẵn sàng bảo vệ |

**TÀI LIỆU THAM KHẢO** 

1. [https://oanhcuongdo.com/](https://oanhcuongdo.com/) 

2. Han et al., *Data Mining: Concepts and Techniques* 

3. Ian Sommerville, *Software Engineering* 

4. Tài liệu chính thức NodeJS: [https://nodejs.org](https://nodejs.org) 

5. Tài liệu ReactJS: [https://react.dev](https://react.dev) 

6. Tài liệu FastAPI: [https://fastapi.tiangolo.com](https://fastapi.tiangolo.com) 

7. Tài liệu MySQL: [https://dev.mysql.com/doc](https://dev.mysql.com/doc) 

8. Tài liệu PostgreSQL: [https://www.postgresql.org/docs](https://www.postgresql.org/docs)

9. OpenAI API Documentation (Chatbot / RAG): [https://platform.openai.com/docs](https://platform.openai.com/docs)

10. LangChain Documentation (RAG Framework): https://docs.langchain.com 

11. PM2 Documentation (Process Manager): https://pm2.keymetrics.io/docs 

12. Nginx Documentation: https://nginx.org/en/docs 

13.  DigitalOcean Tutorials (VPS, Deploy, Nginx): https://www.digitalocean.com/community/tutorials

[image1]: <data:image/png;base64,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>