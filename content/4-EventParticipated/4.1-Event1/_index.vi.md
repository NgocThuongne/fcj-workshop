---
title: "AWS First Cloud AI Journey - Community Day"
date: 2026-05-23
weight: 1
chapter: false
pre: " <b> 4.1. </b> "
---



# Bài thu hoạch “AWS First Cloud AI Journey - Community Day”

### Mục Đích Của Sự Kiện

- Tối ưu ngữ cảnh (Context), tư duy xây dựng bộ nhớ dài hạn ("Second AI Brain") và lộ trình AI cho sinh viên.
- Tận dụng bộ công cụ No-code Amazon Quick để xử lý dữ liệu và tự động hóa workflow bằng ngôn ngữ tự nhiên.
- Làm chủ hạ tầng Amazon CloudFront giúp tăng tốc độ tải, củng cố bảo mật và tiết kiệm chi phí băng thông.
- Đúc kết quy trình phát triển sản phẩm MVP và kỹ năng xử lý khủng hoảng kỹ thuật từ áp lực 36 giờ Hackathon.
- Giải mã tính bất định của LLM khi tối ưu phần cứng và các chiến lược kiểm soát, giảm sai lệch kết quả.
- Ứng dụng kiến trúc Đa tác nhân (Multi-Agent System) để tự động hóa các luồng nghiệp vụ doanh nghiệp phức tạp.

### Danh Sách Diễn Giả

- **Pham Ng Hai Anh** – AWS Community Builder
- **Nguyen Tuan Thinh** – DevOps Engineer
- **Tinh Truong** – Platform Engineer, GoTymeX
- **Vy Lam** – Senior Business Systems Analyst, VPBank
- **Duc Dao** – Solution Architect, Cloud Kinetics
- **Team VIB-UTMorpho** - Building UTMorpho from Idea to Reality - LotusHacks 2026


### Nội Dung Nổi Bật

#### 1. Context Is Everything: Making AI Actually Work for You

**Diễn giả:** Pham Ng Hai Anh – AWS Community Builder

Bài trình bày giới thiệu Amazon Quick – nền tảng Agentic AI thống nhất giúp business user làm việc hiệu quả hơn. Thay vì phải thu thập thông tin thủ công từ nhiều nguồn, Amazon Quick cho phép:  

- Kết nối hơn 40 data connectors, file upload và database.
- Sử dụng Bedrock models, web search và hàng nghìn actions, tự động tạo MoM, gửi email, lên lịch họp, phân tích dữ liệu và xây dựng dashboard
- Cung cấp khả năng phân tách luồng tự động (Dynamic Workflow Routing) bằng cách sử dụng ngôn ngữ tự nhiên để kích hoạt các hàm API nội bộ (Function Calling)

#### 2. Amazon CloudFront – Foundation from Edge to Origin

**Diễn giả:** Nguyen Tuan Thinh – DevOps Engineer

Bài chia sẻ đi sâu vào vai trò của **Amazon CloudFront** như một nền tảng cốt lõi cho performance, security và cost optimization:

- Tối ưu hóa chi phí vận hành và giải phóng tài nguyên máy chủ gốc
- Thiết lập rào chắn an ninh vòng ngoài nghiêm ngặt (Defensive Perimeter)
    + Kết hợp chặt chẽ tính năng Origin Access Control (OAC) và Origin Shield tạo thành một vùng đệm an toàn
    + cô lập hoàn toàn Amazon S3 hoặc API Gateway phía sau để ngăn chặn các hành vi bypass CDN
- Bứt phá hiệu năng hệ thống và đảm bảo độ tin cậy tuyệt đối.


#### 3. Context Is Everything – Làm AI Thực Sự Hiệu Quả

**Diễn giả:** Tinh Truong – Platform Engineer, GoTymeX

Đây là một trong những phần trình bày ấn tượng nhất về phương pháp khai thác sức mạnh của trí tuệ nhân tạo một cách thực chất và tối ưu. Một số nội dung cốt lõi được đúc kết bao gồm:

- Tư duy ưu tiên chất lượng hơn số lượng trong quản lý bối cảnh
+ Nhấn mạnh nguyên tắc chất lượng của ngữ cảnh (Context quality) luôn vượt trội hơn số lượng từ ngữ (Context quantity) nạp vào mô hình.
- Mổ xẻ và phân tích 3 sai lầm kinh điển mà lập trình viên và người dùng thường mắc phải khi xây dựng prompt cho AI.
- Tối ưu hóa hiệu suất đầu ra thông qua việc áp dụng cấu trúc Framework tư duy 4 trụ cột:
+ Goal 
+ Relevant Info 
+ Constraints
+ Success Criteria
- Tầm nhìn chiến lược về tương lai của sự tiến hóa AI:
+ Chia sẻ góc nhìn về tương lai của AI: từ Prompt → Context → Memory (Second AI Brain)

#### 4. Enterprise-Grade Multi-Agent System

**Diễn giả:** Vy Lam – Senior Business Systems Analyst, VPBank

Bài trình bày mang đến góc nhìn thực tế về việc triển khai mô hình Multi-Agent AI System nhằm giải quyết bài toán phức tạp mang tên Startup Credit Scoring.

##### Những vấn đề của hệ thống truyền thống

- Startup thường thiếu hụt nghiêm trọng các chỉ số đánh giá chuẩn quy trình:
  + Credit history để đối chiếu rủi ro.
  + Financial statements dài hạn để chứng minh dòng tiền.
  + Collateral rõ ràng theo quy chuẩn tài sản thế chấp truyền thống.
- Nguồn thông tin thu thập thường phi cấu trúc, đa chiều và thay đổi với tốc độ nhanh.

##### Multi-Agent Architecture

Hệ thống được phân rã thành nhiều agent chuyên biệt hoạt động theo mô hình hướng sự kiện bất đồng bộ:
- **Financial Analyst**: Phân tích sâu các chỉ số tài chính và dòng tiền.
- **Market Analyst**: Đánh giá tiềm năng quy mô và áp lực cạnh tranh của thị trường.
- **Team Evaluator**: Định lượng năng lực điều hành của đội ngũ sáng lập.
- **Risk Assessor**: Nhận diện rủi ro hệ thống và dự báo kịch bản bất lợi.
- **Compliance Agent**: Giám sát luồng quyết định nhằm bảo đảm tính tuân thủ pháp lý.

##### Lợi ích của Multi-Agent System

- Tăng tốc độ xét duyệt hồ sơ nhờ cơ chế Parallel processing.
- Mang lại khả năng Auditability và traceability logic rõ ràng hơn cho kiểm toán viên.
- Fault tolerance cao hơn single-agent nhờ khả năng cô lập lỗi khi một agent gặp sự cố.
#### 5. Enterprise AI & Security + Non-Determinism của LLM

**Diễn giả:** Duc Dao và các diễn giả khác

Nội dung nhấn mạnh rằng AI trong doanh nghiệp không chỉ cần hoạt động tốt mà còn phải đạt các tiêu chuẩn vận hành nghiêm ngặt:

- Secure: Bảo mật dữ liệu, mã hóa luồng truyền tải.
- Reliable: Hệ thống ổn định, giảm thiểu lỗi phản hồi.
- Scalable: Mở rộng hạ tầng xử lý lưu lượng lớn.
- Compliant: Tuân thủ quy định pháp lý và an toàn doanh nghiệp.

Ngoài ra, phần trình bày cũng giải thích tính **non-deterministic** của LLM dù đã set `temperature = 0`.

##### Một số nguyên nhân chính

- Floating-point arithmetic trên GPU: Sai số làm tròn toán học số thập phân dấu phẩy động.
- Parallel execution order: Thứ tự chạy song song bất đồng bộ không cố định của phần cứng.
- Inference batching từ provider: Cơ chế gộp cụm truy vấn làm thay đổi cấu trúc tính toán.

##### Mitigation Strategies

- Structured outputs: Ép định dạng đầu ra chuẩn.
- Majority voting: Gọi mô hình nhiều lần, lấy kết quả theo số phiếu cao nhất.
- Ensemble approach: Phối hợp đa dạng nhiều mô hình khác nhau.
- Testing kỹ lưỡng: Thiết lập quy trình kiểm thử tự động cho tầng suy luận.

#### 6. Hackathon Project – UTMorpho

Đây là phần chia sẻ về dự án AI UI Generator được phát triển trong hackathon LotusHacks.

##### Ý tưởng chính

Một AI UI Generator cho phép:

- Generate UI từ prompt
- Chỉnh sửa trực tiếp trên canvas
- Không cần re-prompt nhiều lần
- Giữ consistency giữa các lần chỉnh sửa

##### Các khó khăn gặp phải

- Token limits: Giới hạn độ dài ngữ cảnh khi xử lý source code lớn.
- Burnout trong hackathon: Tình trạng kiệt sức khi làm việc cường độ cao.
- AI overgeneration: Mô hình tự sinh mã nguồn dư thừa làm nhiễu thiết kế.
- Áp lực thời gian: Quỹ thời gian 36 giờ ngặt nghèo để hoàn thiện demo.

##### Những bài học rút ra

- Team chemistry rất quan trọng
- Real frustration tạo ra real ideas
- AI nên được xem như teammate thay vì chỉ là tool: Coi AI là cộng sự cùng giải quyết bài toán.

### Những gì học được

#### Tư Duy Kiến Trúc

- MHệ thống Multi-Agent tối ưu cho nghiệp vụ phức tạp quy mô doanh nghiệp.
- Context Engineering là kỹ năng cốt lõi khi làm việc với AI.
- Bảo mật và tuân thủ (Security & Compliance) cần thiết kế ngay từ đầu.
- CloudFront là nền tảng cốt lõi giúp tăng hiệu năng và tối ưu chi phí.

#### Kiến Thức AI

- Hiểu sâu cơ chế tầng suy luận: LLM inference, Non-determinism, Guardrails, Structured outputs.
- Nhận thức rõ phản hồi đầu ra của AI luôn mang tính xác suất.

#### Kiến Thức Cloud & AWS

- Nắm vững các dịch vụ chuyên sâu: Amazon Quick, Bedrock Guardrails, CloudFront, Origin Shield, OAC, HTTP/3, Edge Computing.

#### Kỹ Năng Thực Tế

- Quy trình triển khai hệ thống AI vào môi trường Production thực tế.
- Phương pháp luận thiết kế hạ tầng mở rộng (Scalable Architecture).
- Tư duy business-first và context-driven khi làm việc với AI.

### Ứng Dụng Vào Công Việc Và Học Tập

- Áp dụng Context Framework khi sử dụng AI hỗ trợ lập trình và học tập
- Triển khai Amazon CloudFront vào các đồ án môn học để tối ưu tốc độ và chi phí.
- Thử nghiệm xây dựng Multi-Agent mini hoặc Personal Second AI Brain.
- Tích hợp Bedrock Guardrails và structured output vào ứng dụng AI
- Áp dụng kiến trúc microservices, event-driven và domain-based vào các project 

### Trải nghiệm trong event

Tham gia sự kiện AWS Vietnam Community Day 2026 mang lại cho tôi những trải nghiệm vô cùng thực tế và đắt giá. Khác với lý thuyết trên giảng đường, ngày hội công nghệ này đã mở ra góc nhìn toàn diện về cách các tập đoàn lớn vận hành, tối ưu hóa hệ thống AI và cấu trúc hạ tầng Cloud ở quy mô thực chiến.

#### Học hỏi từ các chuyên gia

Các diễn giả đã chia sẻ rất nhiều kinh nghiệm thực tế liên quan đến:

- Cách phân rã một bài toán siêu phức tạp của ngân hàng thành các nhiệm vụ nhỏ cho Multi-agent AI xử lý.
- Phương pháp xây dựng trục hạ tầng phân phối vững chắc bằng CloudFront foundational architecture.
- Quy trình thiết kế bối cảnh (Context Engineering) và chuẩn hóa kiến trúc doanh nghiệp.
- Các giải pháp kiểm soát an ninh, mã hóa và bảo mật hệ thống (AI Security & Compliance).

#### Mở rộng kiến thức về AI

Tôi đặc biệt ấn tượng với các chủ đề:

- Context Is Everything
- Guardrails cho GenAI
- Agentic capabilities của Amazon Quick

#### Trải nghiệm cộng đồng công nghệ

Từ các anh chị architect, developer cho đến các bạn sinh viên đều trao đổi rất cởi mở, tạo nên môi trường trao đổi kiến thức rất năng động. 

Thông qua networking và các bài chia sẻ, tôi học được:

- Phương pháp luận định hình một cấu trúc hệ thống (System Design) ngoài thực tế.
- Những rào cản kỹ thuật khi doanh nghiệp tích hợp GenAI vào hệ thống sẵn có.
- Bí quyết quản trị rủi ro, phân chia task.

#### Bài học rút ra

- Đầu tư vào cấu trúc ngữ cảnh (Context) là giải pháp bền vững nhất để tối ưu hiệu suất mô hình.
- Mô hình Nhiều tác nhân (Multi-agent) là chìa khóa để xử lý các luồng nghiệp vụ đa chiều.
- Sự thấu hiểu nội bộ (Teamwork) và giao tiếp rõ ràng quyết định 90% sự thành công của dự án.

#### Một số hình ảnh khi tham gia sự kiện

![Check-in on the 26th floor](/images/4-eventparticipated/event1.jpg)

> Tổng thể, AWS Vietnam Community Day 2026 không chỉ giúp tôi học thêm nhiều kiến thức mới về AI và Cloud mà còn truyền động lực để tôi tiếp tục tự tin hơn trong việc định hướng, nghiên cứu và phát triển các project công nghệ trong tương lai.

