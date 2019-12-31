# Data Science Final Project
# Thành viên nhóm:
- Nguyễn Thị Tình - 1612703
- Trang Trung Hoàng Phúc - 1612521
# Ý tưởng:
- Nhận diện các đoạn âm thanh đơn giản.
# Động lực:
- Vì giới hạn thời gian cũng như nhiều yếu tố khác nên nhóm chỉ làm nhận diện một vài âm thanh đơn giản.
- Từ ý tưởng bài toán, có thể phát triển để ứng dụng:
    + Làm robot giữ nhà ( ví dụ nghe tiếng chó sủa thì khởi động hệ thống an ninh).
    + Các assistants hỗ trợ nhận diện giọng nói.
    + ...
# Dữ liệu:
- Lấy dữ liệu từ https://freesound.org/
- Dữ liệu gồm các files âm thanh .wav (chưa tiền xử lý).
- Chia ra làm 3 class:
    + **Baby cry**: 75 files.
    + **Dog bark**: 75 files.
    + **Say go**: 74 files.
- Vấn đề: Có nhiều đoạn âm thanh trống, một record có thể có nhiều đối tượng, xử lý bằng cách bỏ đoạn âm thanh trống và chia nhỏ record thành nhiều đoạn nhỏ.
# Link data (chưa clean và tiền xử lý):
https://drive.google.com/file/d/1KaQX2O21fzsSVo-Ud8YjfdIhgW9ft1Z2/view?usp=sharing
# Preprocessed data
https://drive.google.com/drive/folders/195KgeibPbMgx2I3aVBvmyQLuuHyRNsZw?usp=sharing
