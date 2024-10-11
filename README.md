# Async-Await-Javascript
# Async/Await Javascript
Bất đồng bộ trong **JavaScript** được sử dụng khi một thao tác có thể mất thời gian, như gọi **API**, đọc dữ liệu từ file, hoặc lấy thông tin từ thiết bị. Khi xử lý các tác vụ này, **JavaScript** sử dụng các đối tượng **Promise** để đại diện cho quá trình và trạng thái của tác vụ đó. **Promise** có 3 trạng thái chính: <br><br>
+) **1.Pending (Đang chờ):** Trạng thái khi Promise vừa được khởi tạo và đang chờ để hoàn thành. <br><br>
+) **2.Resolved (Thành công):** Trạng thái khi tác vụ bất đồng bộ đã hoàn thành thành công và trả về kết quả.<br><br>
+) **3.Rejected (Thất bại):** Trạng thái khi tác vụ bất đồng bộ gặp lỗi và không thể hoàn thành, trả về lỗi. <br><br>

## 
## Tóm Tắt về React Lifecycle Methods với Async/Await:
**1.componentDidMount:** Sử dụng để thực hiện các tác vụ bất đồng bộ ngay sau khi component được render.<br><br>
**2.componentDidUpdate:** Sử dụng để theo dõi các thay đổi về props hoặc state và thực hiện các tác vụ bất đồng bộ tương ứng. <br><br>
**3.componentWillUnmount:** Sử dụng để dọn dẹp các tác vụ bất đồng bộ trước khi component bị gỡ bỏ. <br><br>
**4.Redux Thunk/Saga:** Sử dụng để quản lý các tác vụ bất đồng bộ trong **Redux,** cho phép bạn **dispatch** các **actions** từ các phương thức **lifecycle.** <br><br>







