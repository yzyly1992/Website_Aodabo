## Aodabo 凹大卜
==============================

[https://aodabo.tech](https://aodabo.tech)A Personal **Webapp** written by David Yang. Referred from Micheal Liao's tutorial. 
The website is mainly built by **Python3**.  

#### Components

Database: MySQL;  
Services: nginx, supervisor, python3, mysql-server;  
Libraries in python3: aiomysql, aiohttp, jinja2;  
Front-end framework: UIkit;  
JavaScript framework: Vue.js;  
Writing format syntax: MarkDown;  

#### Webapp Features 

- Post Blog with title, summary, content, tag
- Comment System (Valine.js)
- Catagorize blogs through tags
- In-site Search
- Show multi-media through MarkDown
- Edit and manage Blogs
- Manage Users and Comments
- Read Count System (Bosuanzi.js)
- Mobile Adjustable Layout
- PWA
- Markdown & Code Syntax Highlight

#### Update History

- 2020.05.03: ADB_V4.1 Update frabric2 from frabric1.x, revise deployment script.
- 2020.05.02: ADB_V4.0 Update usage of aiohttp, remove deprecated code. Revise initiate sql code, remove existing user of www-data.
- 2019.10.19: ADB_V3.0 Migrate Website to new server (CentOS). Update setting of ssl, supervisord and nginx.
- 2019.05.16: ADB_V2.1 Fix minor errors in app.py and coroweb.py. Add new designed website under Aodabo.
- 2019.01.22: ADB_V2.0 Upgrade Webapp to PWA, change setting of Nginx - cache gzip http2... Page layout revised.
- 2019.01.11: ADB_V1.6 Add code syntax highlight function.
- 2019.01.05: ADB_V1.5 Upgrade tag system, pagination system and side page layout.
- 2018.12.25: ADB_V1.4 Adjust video iframe responsive, update markdown2.py.
- 2018.12.14: ADB_V1.3 Add new comment system, adjust mobile layout.
- 2018.10.18: ADB_V1.2 Add viewer counter(Busuanzi) and new comment system(Valine).
- 2018.10.17: ADB_V1.1 Add responsive mobile layout.
- 2018.10.10: ADB_V1.0 Update new icon, add pagination, tag and category system. 
- 2018.09.04: ADB_V0.0 Aodabo is online!
