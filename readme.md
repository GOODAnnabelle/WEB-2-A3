PublicWelfareWeb/
├── .env
├── package.json
├── package-lock.json
├── server.js
├── simple_server.js
├── start.bat
├── database/
│   ├── charityevents_db.sql
│   └── registrations_table.sql  // 新增注册表结构和初始数据
├── models/
│   └── event_db.js  // 增强事件查询功能，新增注册和事件管理功能
├── routes/
│   └── events.js  // 新增注册、创建、更新、删除事件的API端点
├── public/
│   ├── index.html
│   ├── search.html
│   ├── about.html
│   ├── contact.html
│   ├── event-details.html  // 更新页面结构以显示注册信息和报名按钮
│   ├── registration.html  // 新增活动报名页面
│   ├── css/
│   │   └── style.css
│   ├── js/
│   │   ├── main.js
│   │   ├── home.js
│   │   ├── search.js
│   │   ├── event-details.js  // 更新以显示注册列表和链接到报名页面
│   │   └── registration.js  // 新增报名页面逻辑
│   └── admin/
│       ├── index.html  // 新增管理员后台主页面
│       └── admin.js  // 新增管理员后台功能逻辑
└── README.md 

###启动方式

1. 安装依赖包：npm install
2. 更新数据库文件：database/charityevents_db.sql
3. 启动服务器：node server.js