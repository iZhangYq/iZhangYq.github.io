---
title:      Ubuntu版chrome内核浏览器改为中文
date:       2023-07-29
catalog: true
tags:
    - Ubuntu软件配置
---

# 1.chrome浏览器

```bash
cd /opt/google/chrome
sudo vim google-chrome
```

在最开始添加中文设置
```bash
export LANGUAGE=ZH-CN.UTF-8
```

![export_CN](/assets/images/posts/2023-07-29-ubuntu_chrome_chinese/export_CN.png)

若浏览器更新，则会失效

# 2.Edge浏览器

```bash
cd /opt/microsoft/msedge
sudo vim microsoft-edge
```

添加中文设置和chrome一致