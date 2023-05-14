<p align="center">
 <h1 align="center">Tìm hiểu về mongodb</h1>
</p>

# MongoDB là gì?

- MongoDB là một chương trình quản lý cơ sở dữ liệu NoSQL mã nguồn mở . NoSQL (Không chỉ SQL) được sử dụng thay thế cho cơ sở dữ liệu quan hệ truyền thống.
- MongoDB là một công cụ có thể quản lý thông tin định hướng tài liệu, lưu trữ hoặc truy xuất thông tin.
- MongoDB được sử dụng để lưu trữ dữ liệu khối lượng lớn, giúp các tổ chức lưu trữ lượng lớn dữ liệu trong khi vẫn hoạt động nhanh chóng
-  MongoDB sử dụng lưu trữ dữ liệu dưới dạng Document JSON nên mỗi một collection sẽ các các kích cỡ và các document khác nhau.

# Tại sao MongoDB được sử dụng?

Một tổ chức có thể muốn sử dụng MongoDB cho những việc sau:

- Storage: MongoDB có thể lưu trữ khối lượng dữ liệu có cấu trúc và phi cấu trúc lớn và có thể mở rộng theo chiều dọc và chiều ngang. Chỉ mục được sử dụng để cải thiện hiệu suất tìm kiếm. Các tìm kiếm cũng được thực hiện theo các truy vấn trường, phạm vi và biểu thức.
- Tích hợp dữ liệu: tích hợp dữ liệu cho các ứng dụng, bao gồm cả các ứng dụng kết hợp và nhiều đám mây.
- Mô tả cấu trúc dữ liệu phức tạp: Document databases cho phép nhúng tài liệu để mô tả cấu trúc lồng nhau (cấu trúc bên trong cấu trúc) và có thể chấp nhận các biến thể của dữ liệu.
- Cân bằng tải. MongoDB có thể được sử dụng để chạy trên nhiều máy chủ.

# Các Features  trong mongodb

- Replication:  Một bộ bản sao là hai hoặc nhiều phiên bản MongoDB được sử dụng để cung cấp tính sẵn sàng cao . Bộ bản sao được tạo từ các máy chủ chính và phụ. Máy chủ MongoDB chính thực hiện tất cả các hoạt động đọc và ghi, trong khi bản sao phụ giữ một bản sao của dữ liệu. Nếu một bản sao chính không thành công, thì bản sao phụ sẽ được sử dụng.
- Scalability: MongoDB hỗ trợ chia tỷ lệ theo chiều dọc và chiều ngang. Chia tỷ lệ theo chiều dọc hoạt động bằng cách tăng thêm sức mạnh cho máy hiện có, trong khi tỷ lệ theo chiều ngang hoạt động bằng cách thêm nhiều máy hơn vào tài nguyên của người dùng.
- Load balancing: MongoDB xử lý cân bằng tải mà không cần bộ cân bằng tải chuyên dụng, riêng biệt, thông qua chia tỷ lệ theo chiều dọc hoặc chiều ngang.
- Schema-less: MongoDB là một cơ sở dữ liệu không có lược đồ, có nghĩa là cơ sở dữ liệu có thể quản lý dữ liệu mà không cần bản thiết kế.
- Document: Dữ liệu trong MongoDB được lưu trữ trong tài liệu với các cặp key-value  thay vì hàng và cột, giúp dữ liệu linh hoạt hơn khi so sánh với cơ sở dữ liệu SQL.

# Ưu điểm của MongoDB

- Khả năng mở rộng: Một chức năng cốt lõi của MongoDB là khả năng mở rộng theo chiều ngang, giúp nó trở thành một cơ sở dữ liệu hữu ích cho các công ty chạy các ứng dụng dữ liệu lớn. Ngoài ra, sharding cho phép cơ sở dữ liệu phân phối dữ liệu trên một cụm máy. MongoDB cũng hỗ trợ tạo vùng dữ liệu dựa trên khóa phân đoạn.
- Hỗ trợ của bên thứ ba: MongoDB hỗ trợ một số công cụ lưu trữ và cung cấp API công cụ lưu trữ có thể cắm được cho phép các bên thứ ba phát triển công cụ lưu trữ của riêng họ cho MongoDB
- linh hoạt: Giống như các cơ sở dữ liệu NoSQL khác, MongoDB không yêu cầu các lược đồ được xác định trước . Nó lưu trữ bất kỳ loại dữ liệu. Điều này cho phép người dùng linh hoạt để tạo bất kỳ số lượng trường nào trong tài liệu, giúp mở rộng cơ sở dữ liệu MongoDB dễ dàng hơn so với cơ sở dữ liệu quan hệ.
- hiệu suất: Dữ liệu lưu trữ phi cấu trúc, không có tính ràng buộc, toàn vẹn nên tính sẵn sàng cao, hiệu suất lớn và dễ dàng mở rộng lưu trữ.

# Nhược điểm của MongoDB
-  giới hạn:  Nút chính duy nhất của MongoDB cũng giới hạn tốc độ ghi dữ liệu vào cơ sở dữ liệu. Việc ghi dữ liệu phải được ghi trên nút chính và việc ghi thông tin mới vào cơ sở dữ liệu bị giới hạn bởi khả năng của nút chính đó.
-  Tính nhất quán của dữ liệu: MongoDB không cung cấp tính toàn vẹn tham chiếu đầy đủ thông qua việc sử dụng các ràng buộc khóa ngoại, điều này có thể ảnh hưởng đến tính nhất quán của dữ liệu
-  Bảo mật:  xác thực người dùng không được bật theo mặc định trong cơ sở dữ liệu MongoDB. Tuy nhiên, các tin tặc độc hại đã nhắm mục tiêu một số lượng lớn hệ thống MongoDB không bảo mật trong các cuộc tấn công, dẫn đến việc bổ sung cài đặt mặc định chặn các kết nối được nối mạng tới cơ sở dữ liệu nếu chúng chưa được quản trị viên cơ sở dữ liệu định cấu hình.
-  Mọi thay đổi về dữ liệu mặc định đều chưa được ghi xuống ổ cứng ngay lập tức vì vậy khả năng bị mất dữ liệu từ nguyên nhân mất điện đột xuất là rất cao.
- Không có cơ chế transaction (giao dịch) để phục vụ các ứng dụng ngân hàng.

# Các thành phần chính MongoDB là gì?

- _id: Đây là trường bắt buộc trong mọi document MongoDB. Trường _id đại diện cho một unique value trong document MongoDB. Trường _id giống như primary key của document. Nếu bạn tạo một document mới mà không có trường _id, MongoDB sẽ tự động tạo trường. Vì vậy, ví dụ: nếu chúng ta thấy ví dụ về bảng customer ở trên, Mongo DB sẽ thêm 24 chữ số unique vào mỗi document trong collection.
- Collection: Đây là một nhóm các document MongoDB. Collection tương đương với một table được tạo trong bất kỳ RDMS nào khác như Oracle hoặc MSSQL. Một collection tồn tại trong một cơ sở dữ liệu duy nhất.
- Cursor: Đây là một con trỏ đến tập kết quả của một query. Client có thể lặp lại qua cursor để truy xuất kết quả.
- Database: Đây là vùng chứa cho các collection như trong RDMS, trong đó nó là vùng chứa cho các tables. Mỗi cơ sở dữ liệu có một bộ tệp riêng trên hệ thống tệp. Một máy chủ MongoDB có thể lưu trữ nhiều cơ sở dữ liệu.
- Document: Bản ghi trong collection MongoDB về cơ bản được gọi là document. Document sẽ bao gồm tên trường (name) và value.
- Field: Một cặp name-value trong document. Một document có thể không hoặc có nhiều filed. Các filed tương tự như các columns trong cơ sở dữ liệu quan hệ.
- JSON: Đây được gọi là JavaScript Object Notation. Đây là định dạng văn bản thuần túy, có thể đọc được bởi con người để thể hiện dữ liệu có cấu trúc. JSON hiện được hỗ trợ trong nhiều ngôn ngữ lập trình.

# Các kiểu dữ liệu trong MongoDB

- String: Đây là kiểu dữ liệu được sử dụng phổ biến nhất để lưu giữ dữ liệu. Chuỗi trong MongoDB phải là UTF-8 hợp lệ.
- integer: Kiểu dữ liệu này được sử dụng để lưu một giá trị số. Số nguyên có thể là 32 bit hoặc 64 bit phụ thuộc vào Server của bạn.
- Boolean: Kiểu dữ liệu này được sử dụng để lưu giữ một giá trị Boolean (true/false).
- Double: Kiểu dữ liệu này được sử dụng để lưu các giá trị số thực dấu chấm động.
- Min/ Max keys: Kiểu dữ liệu này được sử dụng để so sánh một giá trị với các phần tử BSON thấp nhất và cao nhất.
- Array: Kiểu dữ liệu này được sử dụng để lưu giữ các mảng hoặc danh sách hoặc nhiều giá trị vào trong một key.
- Timestamp: Đánh dấu thời điểm một Document được sửa đổi hoặc được thêm vào.
- Object: Kiểu dữ liệu này được sử dụng cho các Document được nhúng vào.
- Null: Kiểu dữ liệu này được sử dụng để lưu một giá trị Null.
- Symbol: Kiểu dữ liệu này được sử dụng giống như một chuỗi
- Date : Kiểu dữ liệu này được sử dụng để lưu giữ date và time hiện tại trong định dạng UNIX time.
- Object ID: Kiểu dữ liệu này được sử dụng để lưu giữ ID của Document.
- Binary data: Kiểu dữ liệu này được sử dụng để lưu giữ dữ liệu nhị phân.
- Code: Kiểu dữ liệu này được sử dụng để lưu giữ JavaScrip code vào trong Document.
- Regular expression: Kiểu dữ liệu này được sử dụng để lưu giữ Regular Expresion.

# Khi nào nên sử dụng MongoDB ?
- Sử dụng document để lưu trữ dữ liệu, dễ dàng thêm bớt, mở rộng dữ liệu tùy ý.
- Ứng dụng có tính chất Insert nhiều (write-intensive).
- Cần cơ chế Replication và High Availabity.
- Cần cơ chế Sharding

# Khi nào không nên sử dụng MongoDB ?
- Các ứng dụng cần sử dụng nhiều transaction (như ngân hàng) do Mongodb không có cơ chế transaction (giao dịch) để phục vụ cho các ứng dụng ngân hàng
- Các ứng dụng cần SQL (sử dụng joins).

# Kết thúc
- bạn có thể tìm hiểu các câu lệnh truy vấn [tại đây](https://www.mongodb.com/docs/manual/tutorial/query-embedded-documents/)
