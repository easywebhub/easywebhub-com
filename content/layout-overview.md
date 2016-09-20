---json
{
    "slug": "layout-overview",
    "layout": "docs-item.html",
    "category": "document.layouts",
    "tag": [],
    "title": "Layout Overview",
    "title-vn": "Sơ lược về Layout",
    "description": "",
    "description-vn": "### Sơ lược về Layout (giao diện) của trang web\n\n##### `Layout`được định nghĩa là tập hợp `HTML, CSS` code dùng để hiển thị giao diện của một trang web. Giao diện hiển thị cho người dùng hoàn toàn được quyết định bởi cách lập trình, xây dựng Layout.\n\n> EasyWeb cho phép bạn tự do phát triển `Layout` cho website của mình mà không phụ thuộc vào server, `PHP, Asp.Net, Java,...` như các nền tảng lập trình web hiện tại.\n\n##### Dữ liệu định nghĩa trong `Content` cũng được dễ dàng hiển thị ra `Layout` bằng cách sử dụng thư viện HandleBarJS. Ví dụ cơ bản\n\n - Định nghĩa biến trong Content\n```\n\"tieu-de\" : \"Đây là website của bạn\"\n```\n - Lấy dữ liệu của biến này trong phần Layout\n``` \n<h1> {{tieu-de}} </h1>\n```\n - Trang web sẽ hiển thị\n```\n<h1>Đây là website của bạn</h1>\n```\n\n`{{...}}` là cú pháp cơ bản nhất của HandlebarJS để hiển thị dữ liệu được định nghĩa trong `Content` ra `Layout`.\n\n#### Danh sách các cú pháp thường dùng\n + Binding dữ liệu cơ bản\n   - `{{...}}` lấy dữ liệu cơ bản\n   - `{{{...}}}` lấy dữ liệu nhưng encode `HTML,CSS`\n + Binding đối tượng\n   - \n   ```\n   \"đối tượng\" : {\n     \"thuộc-tính-1\" : \"giá trị\"\n   }\n   ```\n   -  Sử dụng dấu `.`,  `{{đối-tượng.thuộc-tính-1}}\n \n + Binding array:\n ```\n \"đối-tượng\" : [\n   {},\n   {}\n ]\n ```\n  - Sử dụng dấu `.[:num]`\n  - Lặp giữa các phần tử, sử dụng `{{#each}} ... {{/each}}`\n  ```\n  <h2>{{đối-tượng.[0]}}</h2>  //cho phần tử đầu tiên\n  {{#each đối-tượng}}\n  \t<li>{{this}}<li>\n  {{/each}}\n  ```\n \n \n",
    "date": "2016-08-26 17:15:46"
}
---
