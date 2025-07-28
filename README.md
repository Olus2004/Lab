Y/C tạo 1 reposory trên github.com với tk cá nhân làm các bài tập sau:

Bài tập C# cơ bản: Quản lý thông tin một học sinh
Viết chương trình nhập từ bàn phím các thông tin cơ bản của một học sinh gồm: tên, tuổi, điểm trung bình 3 môn (Toán, Lý, Hóa). Sau đó hiển thị thông tin ra màn hình và thông báo học sinh đó có đạt hay không (điểm trung bình >= 5 là đạt).
Yêu cầu:
Sử dụng các biến kiểu dữ liệu phù hợp
Sử dụng lệnh nhập xuất cơ bản (Console.ReadLine, Console.WriteLine)
Dùng toán tử, if else để tính điểm trung bình và kiểm tra điều kiện đạt

Bài tập C# trung bình: Xử lý enum, switch case, ép kiểu và dynamic
Viết chương trình quản lý trạng thái đơn hàng. Trạng thái đơn hàng (OrderStatus) dùng enum gồm các giá trị: New, Processing, Shipped, Delivered, Cancelled.
Chương trình:
Nhập trạng thái đơn hàng (dạng số nguyên) từ bàn phím
Ép kiểu số nguyên sang enum để xử lý
Dựa trên trạng thái nhập vào, dùng switch case để in ra thông báo phù hợp
Sử dụng biến dynamic để thử gán enum vừa ép kiểu vào và in ra kiểu dữ liệu thực sự (thông qua GetType())
Gợi ý sử dụng: enum, switch case, ép kiểu ngầm định/tường minh, dynamic

Bài tập C# nâng cao: Tổng hợp LINQ, danh sách, hằng số, toán tử
Viết chương trình quản lý danh sách sản phẩm. Mỗi sản phẩm gồm: mã sản phẩm, tên, loại sản phẩm (dùng enum), giá (const double), số lượng tồn kho.
Yêu cầu:
Nhập danh sách sản phẩm (ít nhất 5 sản phẩm, cho phép nhập tiếp tục hoặc dừng)
Tìm tất cả các sản phẩm thuộc một loại nhất định (dùng Linq)
Tính tổng giá trị tồn kho toàn bộ sản phẩm (giá * số lượng bằng Linq)
Tìm sản phẩm có giá cao nhất, thấp nhất (sử dụng các toán tử Linq)
In ra danh sách với các thông tin chi tiết
