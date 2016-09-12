---json
{
    "slug": "docs-category-how-to-create",
    "layout": "docs-item.html",
    "category": "document.category",
    "tag": [],
    "title": "How to create Category",
    "title-vn": "Tạo mới Danh Mục",
    "description": "",
    "description-vn": "### Tạo mới Danh Mục\n\n* Bấm vào `Category` để tạo mới Danh Mục. Điền tên của Danh Mục vào trường `displayName`, `fileName` tương ứng được tạo ra.\n\n> EasyWeb sử dụng cú pháp `.` khi đặt tên `fileName` để tạo mối quan hệ giữa hai Danh Mục.\n> Nếu muốn tạo Danh Mục con, hãy đặt tên sao cho `fileName` có cấu trúc `danh-muc.danh-muc-con.json`. Để làm được điều này, `displayName` nhập vào có thể chưa hợp lý, nhưng chúng ta có thể điều chỉnh sau.\n\n* Danh Mục vừa tạo mới sẽ hiển thị trong tab `Meta`, chứa tất cả danh mục của website\n\n### Thiết lập Trang Danh Mục\n> Ngoài việc gom nhóm bài chi tiết, Danh Mục có thể được hiển thị trên website dưới 1 trang Danh Mục, là trang tổng hợp danh sách bài chi tiết thuộc danh mục đó. \n> Trang này cho phép phân trang nếu số lượng bài chi tiết quá nhiều.Và có thể chứa dữ liệu riêng cho chính Danh Mục đó, như banner, hình ảnh, ... \n\n* Dữ liệu của Danh Mục gồm các trường thông tin\n```\n{\n    \"sortBy\": \"date\",\n    \"reverse\": false,\n    \"metadata\": {\n    \t\"name\" : \"Configuration\"\n    },\n    \"displayName\": \"document.configuration\",\n    \"perPage\": 12,\n    \"noPageOne\": true,\n    \"layout\": \"default.category.html\",\n    \"first\": \":categoryPath/index.html\",\n    \"path\": \":categoryPath/page/:num/index.html\"\n}\n```\n\n#### Cấu hình giao diện trang Danh Mục\n* `layout` dùng để thiết lập giao diện mà trang Danh Mục sẽ áp dụng, mặc định là `default.category.html`. \n\n* `first`, `path` dùng thiết lập đường dẫn tới Trang Danh Mục này, cũng như cơ chế phân trang tương ứng\n\n* `perPage`: số lượng bài chi tiết trong 1 page của Trang Danh Mục. Các bài viết này được sắp xếp bởi thiết lập `sortBy` áp dụng cho thuộc tính của bài viết chi tiết.\n\n#### Dữ liệu của trang Danh Mục\n> Dữ liệu dành riêng cho trang Danh Mục được thiết lập trong `metadata` theo cấu trúc json. Bạn tùy ý bổ sung các dữ liệu này\n\n* Ví dụ: Nếu muốn Tên hiển thị Danh Mục khác với `displayName`, có thể tạo ra 1 trường thông tin mới với dữ liệu mong muốn như bên dưới\n```\n\"metadata\": \n{\n    \"name\" : \"Configuration\"\n},\n```\n\n##### Chi tiết cách sử dụng các thuộc tính này để tạo trang Danh Mục, xem hướng dẫn tiếp theo\n\n",
    "date": "20-08-2016 17:07:03"
}
---
