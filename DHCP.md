# 1.Gói tin request.
xuất hiện sau khi **DHCP client** gửi gói tin yêu cầu **DHCPDISCOVER** để tìm máy chủ **DHCP sever** bằng địa chỉ broadcast, khi máy chủ **DHCP server** nhận được gói tin **DHCPDISCOVER** từ máy **DHCP client** nó sẽ gửi lại bằng một gói tin **DHCPOFFER** khi **DHCP client** nhận được gói tin **DHCPOFFER** thì **DHCP client** sẽ gửi gói tin **DHCPREQUEST** có nhiệm vụ xác nhận với máy chủ DHCP và gói tin **DHCPREQUEST** chứa các thông tin như:
- **DHCPREQUEST** bao gồm các thông tin về DHCP đã cấp IP cho nó qua gói tin **DHCPOFFER**
- **DHCPREQUEST** cũng có nhiệm vụ thông báo cho các DHCP server khác không gửi gói tin **DHCPOFFER** tới **DHCP client** nữa ( trong trường hợp có nhiều máy chủ DHCP trong cùng một mạng )
