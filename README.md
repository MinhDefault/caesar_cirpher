Mật mã Caesar, còn được gọi là mật mã dịch chuyển Caesar hoặc mật mã dịch chuyển xoay, là một loại mật mã cổ điển và đơn giản. Nó đã được sử dụng bởi Julius Caesar để bảo mật thông tin quan trọng trong thời cổ đại. Mật mã Caesar hoạt động bằng cách thay thế mỗi ký tự trong văn bản gốc bằng một ký tự khác nằm ở vị trí cố định trong bảng chữ cái.

Cách thức hoạt động của mật mã Caesar như sau:

Chọn một số nguyên dương k, được gọi là "số dịch chuyển" hoặc "khóa". Số k này quyết định việc dịch chuyển các ký tự trong văn bản.

Dịch chuyển mỗi ký tự trong văn bản gốc k vị trí sang bên phải trong bảng chữ cái. Nếu bạn vượt quá biên giới của bảng chữ cái, bạn quay lại phía trước của bảng.

Kết quả sau khi đã áp dụng mật mã Caesar là văn bản đã mã hóa.

Để giải mã, bạn thực hiện ngược lại bước 2 bằng cách dịch chuyển các ký tự mã hóa về phía trái k vị trí. Khi có khóa đúng, bạn sẽ thu được văn bản ban đầu.

Ví dụ:

Với khóa k = 3, văn bản "HELLO" sẽ được mã hóa thành "KHOOR".
Để giải mã văn bản "KHOOR" với khóa k = 3, bạn dịch chuyển ngược lại 3 vị trí và thu được "HELLO" ban đầu.
Mật mã Caesar rất đơn giản và dễ hiểu, nhưng nó không an toàn cho việc bảo mật thông tin trong thời đại hiện đại do có thể dễ dàng bị tấn công bằng cách thử tất cả các khóa có thể (tấn công vét cạn). Tuy nhiên, nó vẫn có thể được sử dụng trong các trường hợp không cần độ bảo mật cao hoặc để mô phỏng mật mã trong các hoạt động học tập hoặc giảng dạy.