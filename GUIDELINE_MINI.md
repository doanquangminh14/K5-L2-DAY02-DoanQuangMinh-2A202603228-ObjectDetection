# Mini guideline — bài làm cá nhân

> Điền nội dung này trước khi bắt đầu gán nhãn. Giữ lại các quyết định sau khi self-QC.

## Định nghĩa lớp

| Lớp | Định nghĩa của bạn | Ví dụ/điểm phân biệt |
| --- | --- | --- |
| `car` | Xe chở người cỡ nhỏ, thường 4–7 chỗ | Sedan, SUV, taxi, xe bán tải. Không tính xe buýt, xe tải, xe máy. |
| `truck` | Xe dùng để chở hàng, có thùng hàng tách riêng hoặc là đầu kéo | Xe tải thùng, xe ben, xe đầu kéo container. Xe bán tải nhỏ thì tính là `car`. |
| `bus` | Xe lớn chở nhiều hành khách, thân dài, nhiều cửa sổ dọc hai bên | Xe buýt thành phố, xe buýt nối toa, minibus chở khách. Thân dài và cao hơn hẳn xe con. |
| `van` | Xe thân hộp, mui cao hơn xe con nhưng ngắn hơn xe buýt | Xe van chở hàng, minivan chở người. Nếu không chắc là van hay bus/car thì ghi lại và hỏi giảng viên. |

## Quy tắc chung

- Box bám sát vật thể nghĩa là: bốn cạnh box chạm điểm ngoài cùng của thân xe nhìn thấy được, không lấy thêm mặt đường, trời hay xe bên cạnh, và không cắt vào thân xe.
- Vật thể bị che khuất: nếu phần còn lại vẫn đủ để nhận ra loại xe thì vẽ box quanh phần nhìn thấy, không đoán phần bị che. Xe chồng lên nhau thì mỗi xe một box riêng, box được phép chồng nhau.
- Vật thể bị cắt bởi rìa ảnh: vẫn gán box, cạnh box chạm đúng mép ảnh, không đoán phần nằm ngoài khung.
- Vật thể rất nhỏ/mơ hồ: nếu không xác định chắc được lớp thì không tự đoán; ghi tên ảnh vào bảng ca mơ hồ bên dưới và hỏi giảng viên.

## Ghi lại quyết định cho ít nhất ba ca mơ hồ

| Ảnh | Tình huống | Quyết định cuối | Lý do theo schema |
| --- | --- | --- | --- |
| `drive_001` | Xe con màu trắng bị cột đèn chắn ngang thân, chia thành hai phần nhìn thấy ở hai bên cột | Vẽ một box `car` bao cả hai phần, kéo qua cột | Đây vẫn là một chiếc xe. Tách làm hai box sẽ thành hai xe, sai quy tắc mỗi xe một box. Hai phần nhìn thấy đủ để nhận ra xe con. |
| `drive_026` | Hàng xe nối đuôi nhau sát sau xe buýt, các xe che một phần của nhau | Mỗi xe một box riêng, box được phép chồng lên nhau | Không gộp cả hàng thành một box. Mỗi box chỉ ôm phần nhìn thấy của đúng xe đó. |
| `drive_029` | Xe buýt ở góc dưới bên phải bị xe con màu bạc che khoảng một nửa | Vẫn vẽ box `bus` quanh phần buýt nhìn thấy, và vẽ thêm box `car` riêng cho xe con | Phần còn lại vẫn đủ để nhận ra là xe buýt. Theo schema, xe bị che một phần vẫn cần box nếu nhận diện được lớp. |
