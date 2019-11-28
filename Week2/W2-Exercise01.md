# Bài tập tuần 1

**Câu 1**. Giả sử bạn có người thân từ nước ngoài về Việt Nam. Người thân của bạn thường than phiền với gia đình về nhiệt độ Việt Nam gần đây rất nóng và kể rằng ở nước ngoài thường rất mát mẻ, không khí thường dưới 60 độ F. Gia đình bạn không biết độ F là gì và vô cùng hoang mang. 

Hãy viết một chương trình chuyển đổi độ F thành độ C. 

**Lưu ý**: Output cần được làm tròn.

| Input | Output |
|-------|--------|
| 80    | 26     |
| 60    | 15     |

**Câu 2**. Khi bước đến một giai đoạn T của cuộc đời, sẽ thật khó để đếm số tuổi của bản thân mình. Qua đó với năm sinh của một người, viết chương trình xuất ra số tuổi của người đó tính đến năm 2019.

| Input | Output |
|-------|--------|
| 1990  | 29     |
| 2000  | 19     |

**Câu 3**. Cho biết bán kính của đường tròn. Tính chu vi và diện tích của hình tròn đó. 
**Lưu ý**: 
  - Output cần được làm tròn tới vị trí thập phân thứ 1.
  - Quy ước: số pi = 3.14

| Input | Output             |
|-------|--------------------|
| 5     | 31.4 78.5          |
| 1988  | 12484.6 12409732.2 |

**Câu 4**. Các môn trên Đại học thường được tổ chức theo hình thức tín chỉ học phần. Các môn thường được chia ra các cột điểm với quy ước trọng số % khác nhau. Để qua môn, bạn cần điểm tổng kết của môn học lớn hơn hoặc bằng 5,0.<br>
Vì tuổi thanh xuân bận "cày game đua top" nên bạn giờ đây phải học hệ Liên kết của Trường Đại học X.<br> 
Vì điều kiện gia đình chỉ đủ trang trải việc học nên bạn đặt mục tiêu không rớt môn. Mà trong cuộc sống, đôi khi mọi thứ không như ta mường tượng. <br>
Bạn học Đại học với một ông thầy khó tính chuyên ra đề cuối kỳ đánh rớt sinh viên. Cuối kỳ thường chiếm trọng số cao, bạn sẽ phải tính toán các thang điểm từ những cột điểm khác (đã có điểm rồi) để nhắm chừng mình cần bao nhiêu điểm cho bài thi cuối kỳ để qua môn.

**Input**
<br>Nhập lần lượt a, b, c, d tương ứng tỷ lệ % tương ứng các cột điểm Quá trình, Thực hành, Giữa kỳ và Cuối kỳ.
<br>Nhập tiếp tục i, j, k tương ứng với số điểm của các cột Quá trình, Thực hành và Giữa kỳ.

**Output**
<br>Xuất ra số điểm tối thiểu bạn cần ở bài thi cuối kỳ để qua môn. Nếu không có số điểm tối thiểu nào phù hợp thì xuất ra 0. 

**Lưu ý**: 
  - Output cần được làm tròn tới vị trí thập phân thứ 2.
  - Điểm số ở trường không làm tròn, tính theo mốc 0,25. Ví dụ: 9,75.
  
| Input                       | Output |
|-----------------------------|--------|
| 20 30 0 50<br>1 7.75 0      | 0      |
| 15 15 10 60 <br>0 9.75 2.75 | 5.5    |

**Câu 5**. Bạn đang bị biệt giam trong một căn phòng không có gì ngoài chiếc đồng hồ treo tường có thời gian chính xác cùng 1 chiếc laptop đầy pin (**nhưng không Internet, hỏng hệ thống xác định giờ và máy chỉ có duy nhất một chương trình soạn thảo Python hoạt động được**).
<br>
Bạn nhìn vào chiếc máy một cách vô vọng, bỗng dưng có thông báo từ ban quản lý báo rằng còn N giây nữa bạn sẽ được thả. Thật quái gở khi bạn không hề biết chính xác mình sẽ được thả khi nào mặc dù bạn biết mình sẽ được thả trước 23:59 cùng ngày.
<br>
Với chương trình Python trong máy, hãy tính khung giờ chính xác bạn được thả từ N giây nghe được từ ban quản lý.

