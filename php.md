Tài liệu về lộ trình PHP
==================


Mục lục
======
<!--ts-->
  - Kiến trúc của một website
	  - [Mô hình client - server](#user-content-mô-hình-client---server)
	  - [Cách hoạt động của một website tĩnh](#user-content-cách-hoạt-động-của-một-website-tĩnh)
	  - [Cách hoạt động của một website động](#user-content-cách-hoạt-động-của-một-website-động)
- Kiến thức cơ bản về website
	- [HTML](#user-content-html)
	- [CSS](#user-content-css)
	- [Javascript](#user-content-javascript)
<!--te-->


Nội dung
=======

# Kiến trúc của một website
##  Mô hình client - server
	là mô hình mạng máy tính bao gồm 2 thành phần chính là máy khách (client) và máy chủ (server). Trong mô hình này, server là nơi lưu trữ tài nguyên, cài đặt các chương trình dịch vụ và thực hiện các yêu cầu của client. Client đón vai trò gửi yêu cầu đến server. Client gồm máy tính và thiết bị điện tử nói chung.
	Mô hình Client server  cho phép  mạng tập trung các ứng dụng và chức năng tại một hoặc nhiều máu dịch vụ file chuyên dụng. Các máy này trở thành trung tâm của hệ thống. Hệ điều hành của Client server cho phép người dùng chia sẻ đồng thời cùng một tài nguyên, không quan trọng vị trí địa lý.

**Mô hình web client-server** là một mô hình nổi tiếng trong mạng máy tính, được áp dụng rất rộng rãi và là mô hình của mọi trang web hiện có. Một mô hình ngược lại là mô hình master-slaver, trong đó máy chủ (đóng vai trò ông chủ) sẽ gửi dữ liệu đến máy con (đóng vai trò nô lệ) bất kể máy con có cần hay không.

**Mô hình client/server**  như sau: Client/Server là mô hình tổng quát nhất, trên thực tế thì một server có thể được nối tới nhiều server khác nhằm làm việc hiệu quả và nhanh hơn. Khi nhận được 1 yêu cầu từ client, server này có thể gửi tiếp yêu cầu vừa nhận được cho server khác ví dụ như database server vì bản thân nó không thể xử lý yêu cầu này được. Máy server có thể thi hành các nhiệm vụ đơn giản hoặc phức tạp.
##  Cách hoạt động của một website tĩnh
website tĩnh là trang web sử dụng hoàn toàn ngôn ngữ HTML, sau khi tải trang HTML từ máy chủ xuống, trình duyệt sẽ biên dịch mã và hiển thị nội dung trang web, người dùng hầu như không thể tương tác với trang web.
## Cách hoạt động của một website động
website động là một tập hợp các dữ liệu số hóa được tổ chức thành cơ sở dữ liệu, các dữ liệu số hóa được gọi ra trình diễn trên các trang web dưới dạng văn bản, âm thanh, hình ảnh.nó có thêm các phần xử lý thông tin và truy xuất dữ liệu còn website tĩnh thì không.  
Khác với web tĩnh, web động luôn luôn có thông tin mới do các thông tin này được cập nhật bởi phần mềm quản trị web do các công ty thiết kế website cung cấp. Các thông tin mới này được lưu vào cơ sở dữ liệu của website và đưa ra sử dụng dựa theo yêu cầu của người dùng.
# Kiến thức cơ bản về website
## HTML
**HTML**  (viết tắt của từ  **Hypertext Markup Language**, hay là "Ngôn ngữ Đánh dấu Siêu văn bản") là một  [ngôn ngữ đánh dấu](https://vi.wikipedia.org/wiki/Ng%C3%B4n_ng%E1%BB%AF_%C4%91%C3%A1nh_d%E1%BA%A5u "Ngôn ngữ đánh dấu")  được thiết kế ra để tạo nên các  [trang web](https://vi.wikipedia.org/wiki/Website "Website")  trên  [World Wide Web](https://vi.wikipedia.org/wiki/World_Wide_Web "World Wide Web"). Cùng với  [CSS](https://vi.wikipedia.org/wiki/CSS "CSS")  và  [JavaScript](https://vi.wikipedia.org/wiki/JavaScript "JavaScript"), HTML là một trong những ngôn ngữ quan trọng trong lĩnh vực thiết kế website. HTML được định nghĩa như là một ứng dụng đơn giản của  [SGML](https://vi.wikipedia.org/wiki/SGML "SGML")  và được sử dụng trong các tổ chức cần đến các yêu cầu xuất bản phức tạp. HTML đã trở thành một chuẩn mực của  [Internet](https://vi.wikipedia.org/wiki/Internet "Internet")  do tổ chức  [World Wide Web Consortium](https://vi.wikipedia.org/wiki/W3C "W3C")  (W3C) duy trì. Phiên bản chính thức mới nhất của HTML là HTML 4.01 (1999). Sau đó, các nhà phát triển đã thay thế nó bằng  [XHTML](https://vi.wikipedia.org/wiki/XHTML "XHTML"). Hiện nay, phiên bản mới nhất của ngôn ngữ này là  [HTML5](https://vi.wikipedia.org/wiki/HTML5 "HTML5").

Lưu ý: HTML không phải là ngôn ngữ lập trình.

Bằng cách dùng  [HTML động](https://vi.wikipedia.org/wiki/HTML_%C4%91%E1%BB%99ng "HTML động")  hoặc  [Ajax](https://vi.wikipedia.org/wiki/Ajax_(l%E1%BA%ADp_tr%C3%ACnh) "Ajax (lập trình)"), lập trình viên có thể được tạo ra và xử lý bởi số lượng lớn các công cụ, từ một chương trình soạn thảo văn bản đơn giản – có thể gõ vào ngay từ những dòng đầu tiên – cho đến những công cụ xuất bản  [WYSIWYG](https://vi.wikipedia.org/wiki/WYSIWYG "WYSIWYG")  phức tạp.  **Hypertext**  là cách mà các trang Web (được thiết kế bằng HTML) được kết nối với nhau. Và như thế, đường link có trên trang Web được gọi là Hypertext. Như tên gọi đã nói,  **HTML**  là ngôn ngữ đánh dấu bằng thẻ (**Markup Language**), nghĩa là bạn sử dụng HTML để đánh dấu một tài liệu text bằng các  **thẻ (tag)**  để nói cho trình duyệt Web cách để cấu trúc nó để hiển thị
## CSS
**CSS là chữ viết tắt của cụm từ Cascading Style Sheets** – dịch sang tiếng Việt có nghĩa là tập tin định vị theo tầng. CSS được sử dụng nhằm miêu tả cách trình bày của các loại tài liệu viết bằng ngôn ngữ HTML và XHML. Lúc này CSS sẽ hỗ trợ người dùng có thể thiết kế hay cho thêm vào các phần từ HTML một vài thứ mới mẻ, lạ mắt như thay đổi màu của trang web, thay đổi màu chữ, chuyển đổi cấu trúc,… Ngoài ra CSS cũng có thể được sử dụng cho XML, XUL, SVG,.. Tất cả các hoạt động của **CSS được W3C (World Wide Web Consortium) duy trì và phát triển**.
## Javascript
JavaScript là một [ngôn ngữ lập trình](https://quantrimang.com/16-ngon-ngu-lap-trinh-se-thay-doi-thoi-van-cua-ban-trong-nam-2016-118729 "16 ngôn ngữ lập trình sẽ thay đổi thời vận của bạn") được sử dụng để tạo ra những trang web tương tác. Nó được tích hợp và nhúng trong [HTML](https://quantrimang.com/html5-va-css3-68239 "HTML5 và CSS3 "). JavaScript cho phép kiểm soát các hành vi của trang web tốt hơn so với khi chỉ có một mình HTML. JavaScript kết hợp vào HTML, chạy trên Windows, Macintosh và các hệ thống hỗ trợ Netscape khác.
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTE5MDYzMjA5OTMsLTEzMzAzNTYzNzQsLT
IwNzEzNjgyMTksLTIwNzEzNjgyMTksMTIxMTA2NzI2Myw5NzEw
NjgwMTEsODI5MTgwNjY1LC02MzI3MzMzODNdfQ==
-->