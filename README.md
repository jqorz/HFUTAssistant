# 合工大教务助手 HFUT助手 https://coding.net/u/jqorz/p/HFUTAssistant

## HFUT助手

作者:jqorz

QQ:1055774013

### 说明
合肥工业大学宣城校区教务系统助手 for Android

### 功能
- 课表查看
- 成绩查询
- 教学班查询
- 教学计划查询
- 教学费用查询
- 宣区新闻查看

### 附加功能点
- 动态换肤
- JSoup抓取网页
- JS与Android通信
- 支持ListView的桌面控件
- 从服务器获取xml配置

### 使用框架
- [EventBus (事件总线框架)](https://www.baidu.com/s?tn=mswin_oem_dg&ie=utf-16&word=eventbus)
- [ButterKnife (注解框架)](http://jakewharton.github.io/butterknife/)
- [Jsoup (网页解析框架)](http://www.cnblogs.com/zyw-205520/p/3421687.html)
- [Xutils3 (多功能框架)](地址:http://blog.csdn.net/a1002450926/article/details/50364196)
- [OkUtil (网络通信框架)](http://blog.csdn.net/lmj623565791/article/details/47911083)
- [Gson (Java对象与Json数据转换的库)](http://blog.csdn.net/wanghao200906/article/details/45889955)
- [AndPermission (动态权限申请框架)](https://github.com/yanzhenjie/AndPermission/blob/master/README-CN.md)
- [SwipeBackHelper (仿微信侧滑关闭)](https://github.com/Jude95/SwipeBackHelper/blob/master/README_ch.md)
- [ToolTip (引导提示)](https://github.com/sephiroth74/android-target-tooltip)
- [BaseRecyclerViewAdapterHelper(万能适配器)](https://github.com/CymChad/BaseRecyclerViewAdapterHelper)

### 辅助说明
- 部分工具类使用了单例模式
- [支持ListView的桌面小控件](http://blog.csdn.net/sk719887916/article/details/47027263)
- 每次开学前要修改GitHub根目录下的config.xml中的startWeek(每次启动会从服务器获取开学日期，保存到本地)
- 更新校历列表要修改GitHub根目录下的config.xml中的schoolCalculator
