---json
{
    "slug": "tong-quan-ve-easywebhub-va-easybuilder",
    "category": "tutorials",
    "tag": [],
    "layout": "Huong-Dan.html",
    "title": "Tổng quan về EasyWebHub và EasyBuilder",
    "description": "",
    "date": "2016-08-17 16:03:26",
    "featureImage": "https://github.com/easywebhub/easyapp/blob/master/documents/EasyWebBuilder/create-website.png?raw=true"
}
---
#### I.EasyWebHub 
  + là nền tảng giúp xây dựng website chỉ với kiến thức về ```HMTL, CSS``` (*) 
  + Đơn giản trong việc lập trình, rút ngắn thời gian thực hiện nhưng vẫn có được website chất lượng cao, tối ưu cho nhiều thiết bị là mục đích hướng tới của EasyWebHub
  + Cho phép Chuyển đổi từ các nền tảng khác dễ dàng, nhanh chóng, như wordpress, joomla, drupal,...

#### II. EasyBuilder là phần mềm (**) giúp xây dựng, quản lý websites theo nền tảng EasyWebHub được dễ dàng, nhanh chóng.
   + EasyBuilder cũng là thư viện website có sẵn, chỉ cần lựa chọn, thay đổi nội dung và triển khai vào thực tế.
   ![](https://github.com/easywebhub/easyapp/blob/master/documents/EasyWebBuilder/create-website.png?raw=true)

   + Cho phép xây dựng website từ các theme có sẵn, cung cấp bởi [ThemeForest](https://themeforest.net/) hoặc các nhà cung cấp tương tự
   + Cho phép xây dựng website từ thiết kế sẵn có, sau khi cắt ```HTML, CSS```
   + Sử dụng như công cụ AdminCP để thay đổi nội dung, điều chỉnh giao diện của website

###### III. Các tính năng chính của EasyBuider

![](https://github.com/easywebhub/easyapp/blob/master/documents/EasyWebBuilder/website-overview.png?raw=true)

  + Quick Search, số ```(1)```
    + Content: nội dung cơ bản của website, nội dung trang chủ, từng trang chi tiết. 
    + Meta: nội dung dùng chung trong website, như menu, header, footer, category, tag
    + Layout: danh sách files chứa ```HTML, CSS, JS``` code, cũng như 

  + Editor, số ```(2)```
    + Content: form editor để điều chỉnh nội dung từng trang
    + RAW:  json format dùng để lưu dữ liệu gốc của files
    + Layout: editor để điều chỉnh ```HTML, CSS```
    + Config: editor để customize bố cục, hiển thị trong phần Content Editor
    + Sử dụng Save hoặc Delete, số ```(6)``` lưu dữ liệu

  + Add Content, số ```(3)```
    + Add Layout: thêm 1 layout mới, hoặc 1 partial layout, sử dụng chung giữa nhiều layout. Cho phép chọn lựa là layout dùng cho trang liệt kê danh sách Category, Tags
    + Add Category: thêm 1 category cho website, có thể là sub-category của 1 cateogry có sẵn, sử dụng ```.``` trong filename
    + Add Tags: thêm 1 tag vào website.
    + Add Page: thêm 1 trang mới, sử dụng layou tạo ra trước đó. Có thể thiết lập trang này thuộc Category có sẵn (tạo bởi Add Category) hoặc  Tags có sẵn.

  + Preview, số ```(4)```
    + Build để preview website tại máy local. Preview sẽ cập nhật ngay lập tức sau khi có thay đổi, điều chỉnh dữ liệu hoặc layout
    + Build Dev, dùng để preview website với chế độ Dev
    + Refresh: rebuild lại website cho trường hợp bị lỗi, hoặc cần refresh

  + Synch and Deploy, số ```(6)``` 
  
    + Sync: lưu công việc thực hiện lên Cloud để có thể đồng bộ với users khác
    + Deploy: triển khai website ở local lên server thực tế
    + Set Domain: Thiết lập domain mà website sẽ triển khai

**Giải thích thêm**

(*) EasyWebHub cho phép xây dựng website hoàn toàn dựa trên ngôn ngữ lập trình front-end như HTML, CSS, và JS. Ngay cả Designers có kiến thức về HTML, CSS cũng đủ sức xây dựng website. Các phần xử lý server sẽ do EasyWebHub đảm nhiệm, nên sẽ không cần hiểu biết về lập trình PHP, C# hay các open source như WordPress, Joomla, Drupal,...

(**) Phần mềm cài đặt trên máy tính (Windows, sắp tới sẽ hỗ trợ Linux, Mac OS)