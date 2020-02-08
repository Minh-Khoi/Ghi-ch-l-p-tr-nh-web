# Ghi chú về Lập trình Web fullstack
Hướng dẫn về sau


Có 3 cách xây dựng một trang web, hoặc ứng dụng web FULLSTACK bằng framework <br>
Cách 1: Sử dụng framework Server side với frontend được quy định sẵn bằng template.<br>
Cách 2: Sử đụng framework client-side với backend được viết bằng ngôn ngữ thuần và được nhúng vào thư mục public sau khi đóng gói mã nguồn client-size<br>
Cách 3: Sử dụng đồng thời các framework ở cả server và client-side. Bên phía server phụ trách Khung làm việc và điều hướng. Bên phía client phụ trách giao diện rồi đóng gói mã nguồn rồi tích hợp vào khung làm việc của server side.<br>


Trường hợp 1: Backend có framework, front-end không: Toàn bộ Khung làm việc, Điều hường, giao diện phải tuân theo framework của backend.<br>
Trường hợp 2: Frontend có framework, backend không: Frontend quy định giao diện và điều hường. Khung làm việc Backend viết code thuấn. Sau đó đóng gói frontend và nhúng thư mục backend vào thư mục frontend đã đóng gói<br>
Trương hợp 3: Cả frontend và backend đều có framework: Framework backend phụ trách Khung làm việc, Điều hướng. Frontend phụ trách giao diện. Frontend sau khi đóng gói thì tích hợp vào khung làm việc của backend<br>



Thứ 1: Nếu Backend là code thuần, thì nhúng thư mục backend vào thư mục frontend (thuần hoặc đã đóng gói).<br>
Thứ 2: Nếu Backend là framework, Thư mục frontend sau khi đóng gói được tích hợp vào khung làm việc của backend.<br>
