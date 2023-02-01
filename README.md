# Student_Data_Generator
1 TRƯỜNG CẤP 3 có 3 cấp 10,11,12

  Khối 10: 20 lớp
  Khối 11: 18 lớp
  Khối 12: 15 lớp
  Mỗi lớp sẽ có random từ 30-36 mỗi học sinh sẽ được identify bằng school ID tăng dần từ 1 -> tổng số học sinh. Class ID số thứ tự trong lớp từ 1 -> số học sinh một lớp.   Mỗi học sinh có 1 aray chứa điểm theo thứu tự: toán, lý , hóa , ngữ văn , sử , địa, anh văn, công nghệ, GDCD, tin học

### <div align="center">------ require generator------ </div>
  - Thư mục lớn: Tên trường
  - 3 thư mục nhỏ :3 khối trong thư mục nhỏ có file theo tên lớp: 10A1.js,..... -> bên trong chứa Array Json : chứa từng json là từng học sinh trong lớp HS:{SCHOOL ID :      INT, CLASS ID:INT, SCORES:[average theo định nghĩa random theo Float ]} ~70% học sinh phải có điểm TB môn > TB , ~30% học sinh có điểm dưới trung bình

### <div align="center">----- require read file -----<div align="center">
  Xuất ra 1 cái folder y chang trên chứa them rank của từng khối với điểm học sinh và loại học sinh

  Tổng số học sinh giỏi ,tổng số học sinh khá, tổng học sinh trung bình tạo ra 1 file thống kê

  Xuất ra 3 file chứa tổng học sinh giỏi , tổng học sinh khá, tổng học sinh trung bình từng khối

  Lọc ra top 3 học sinh giỏi nhất của từng khối
