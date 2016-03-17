# 源码使用说明

1、使用XCode打开Clan.xcodeproj项目文件。

2、在XCode左侧的文件列表中找到ThemeStyle.plist文件（路径：Clan/Application/ThemeStyle.plist）。

3、对Plist文件中的字段进行配置，其中配置项说明如下表所示：
|YZBaseURL|论坛地址|
|YZBasePath|插件接口的路径，固定为：api/mobile/iyz_index.php|
|APPSTYLE|应用样式。1.tab风格，2.侧边栏风格|
|YZSegMent|主题颜色|
|YZBBSName|论坛名称，作为某些页面的视图标题（如首页）以及分享时的出处。|
|kAPP_DOWNLOAD_URL|应用下载地址，用于跳转AppStore评价应用|
|ShareAppkeySina|新浪微博的AppKey（用于分享）|
|ShareAppSecretSina|新浪微博的AppSecret（用于分享）|
|ShareAppRedirectUriSina|新浪微博的授权回调地址（用于分享）|
|ShareAppkeyWechat|微信的AppKey（用于分享、登录）|
|ShareAppSecretWechat|微信的AppSecret（用于分享、登录）|
|ShareAppkeyTecent|QQ的AppKey（用于分享、登录）|
|ShareAppSecretTecent|QQ的AppSecret（用于分享、登录）|


4、编译运行应用。
