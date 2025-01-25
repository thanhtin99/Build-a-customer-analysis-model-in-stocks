# Build a customer analysis model in stocks
 Build a customer analysis model in stocks
![image](https://github.com/user-attachments/assets/77c2a92b-2ce7-4bb1-923c-709e37990f72)

#### Nhận xét vùng giá trị và đặc điểm của từng cụm, từ đó em đặc tên cho từng cụm như sau:
- Cụm 0: "Mua Mạnh - Bán Yếu"  
Sell thấp: Tập trung nhiều ở giá trị từ 0 - 20.  
Buy cao: Tập trung nhiều trong khoảng 10 - 100.  
Waitbuy cao: Tập trung nhiều từ 50 - 200.  
Waitsell thấp: Chỉ từ 10 - 80.  
Cụm này có các đặc điểm cho thấy hoạt động mua vào (buy) mạnh mẽ, trong khi bán ra (sell) yếu, waitbuy cao chứng tỏ sự kỳ vọng mua vào lớn, và waitsell thấp cho thấy ít áp lực bán ra.

- Cụm 1: "Chờ Bán - Mua Yếu"  
Sell tập trung: Trong khoảng 0 - 40.  
Buy tập trung: Trong khoảng 0 - 40.  
Waitsell cao: Tập trung nhiều trong khoảng 100 - 200.  
Waitbuy thấp: Chỉ từ 0 - 90.  
Cụm này có xu hướng chờ đợi bán ra với waitsell cao, trong khi mua vào (buy) khá yếu và waitbuy thấp, cho thấy ít mong đợi về sự tăng giá. 

- Cụm 2: "Chờ Cơ Hội - Thị Trường Bình Ổn"  
Sell tập trung: Trong khoảng 0 - 40.  
Buy tập trung: Trong khoảng 0 - 40.  
Waitbuy trung bình: Tập trung nhiều trong khoảng 10 - 150.  
Waitsell trung bình: Tập trung nhiều trong khoảng 10 - 100.  
Cụm này cho thấy thị trường ổn định với cả hai chỉ số waitbuy và waitsell đều ở mức trung bình, thể hiện sự chờ đợi cơ hội mà không có hành động mạnh mẽ từ phía nhà đầu tư.  

- Cụm 3: "Bán Mạnh - Mua Yếu"  
Sell cao: Tập trung nhiều trong khoảng 40 - 120.  
Buy thấp: Tập trung nhiều trong khoảng 0 - 20.  
Waitsell, waitbuy trải dài: Giá trị phân bố rộng, ảnh hưởng không đáng kể.  
Cụm này cho thấy hoạt động bán ra mạnh mẽ với chỉ số sell cao, trong khi mua vào (buy) yếu, waitsell, waitbuy trải dài không có xu hướng rõ ràng.
