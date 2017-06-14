# BAITHI_JAVA
Nói qua về app:
1: Sử dụng 9 Button, 7 Label, 1 Progress Bar.
2: Button ĐỘ KHÓ: Người chơi chọn 1 trong 3 độ khó nếu không chọn mạc định là 1-100.
3: Button BẮT ĐẦU: Người chơi nhấn bắt đầu thì các Button(CỨU, HỒI SINH, ĐỘ KHÓ) sẽ setEnabled(false).
4: Hai Button ĐÚNG và SAI: Mỗi lần chọn chính xác sẽ cộng thêm 1 điểm. Nếu chọn không chính xác
	thì Label Câu hỏi sẽ báo "Sai rồi" và Button BẮT ĐẦU sẽ thành Button CHƠI LẠI.
5: Button CỨU: Mỗi 5 điểm (em là thấp để test cho nhanh) thì CỨU sẽ hiện lên. Nếu dùng thì sẽ setEnabled(False).
6: Button HỒI SINH: Mỗi 10 điểm thì hồi sinh sẽ hiện lên. Nếu hết giờ vẫn dùng được. Dùng thì sẽ setEnabled(False).
7: Progress Bar: Cứ mỗi 5 điểm thì thời gian sẽ giảm đi 15% và chỉ giảm 4 lần.
	Khi hết thời gian Label CÂU HỎI sẽ hiện kết thúc và điểm của người chơi.
8: Hai Label ĐIỂM và KỶ LỤC sẽ hiện điểm và điểm cao nhất.
Nguồn tham khảo: Video Hướng Dẫn Làm Game Đơn giản Bằng JAVA của Sói IT.
https://www.youtube.com/watch?v=3j5J8cNOagM
