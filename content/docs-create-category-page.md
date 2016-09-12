---json
{
    "slug": "docs-create-category-page",
    "layout": "docs-item.html",
    "category": "document.category",
    "tag": [],
    "title": "Page of the Category",
    "title-vn": "Trang Danh Mục",
    "description": "",
    "description-vn": "### Tạo Trang Danh Mục\n* Các trường thông tin được định nghĩa của một Danh Mục\n```\n{\n    \"sortBy\": \"date\",\n    \"reverse\": false,\n    \"metadata\": {\n    \t\"name\" : \"Configuration\"\n    },\n    \"displayName\": \"document.configuration\",\n    \"perPage\": 12,\n    \"noPageOne\": true,\n    \"layout\": \"default.category.html\",\n    \"first\": \":categoryPath/index.html\",\n    \"path\": \":categoryPath/page/:num/index.html\"\n}\n```\nNgoài ra EasyWeb quản lý các thông tin khác\n```\n    children: [],\n    parent: 'parent-category',\n    href: 'url',\n    files: [],\n    category: '',   \n```\n\n#### Truy cập dữ liệu của Danh Mục\n> Tất cả Danh Mục của website được quản lý bởi biến `AllCategory`, và sử dụng cú pháp HandleBar để truy cập \n\n* Sử dụng `lookupCategory` truy cập 1 Danh Mục\n\n```\n{{#with (lookupCategory AllCategory 'path-of-category') }}\n   {{href}}\n   {{displayName}}  \n{{/with}}\n```\n\n* Hoặc truy cập thuộc tính của Danh Mục\n```\n  (lookupCategory AllCategory 'path-of-category' 'files') \n```\n\n",
    "date": "12-09-2016 15:38:48"
}
---
