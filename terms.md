首页界面所用到的词汇：
1. 框架与模块相关术语
WXAPI：微信小程序 API 封装库（可能是第三方库）
apifm-wxapi：API 服务模块，用于与后端交互
CONFIG：配置文件，存储全局配置信息
TOOLS：工具函数模块
getApp()：获取小程序实例的全局函数
Page()：小程序页面构造函数
2. 数据结构与变量术语
inputVal：搜索框输入值
goodsRecommend：推荐商品列表
kanjiaList：砍价商品列表
pingtuanList：拼团商品列表
categories：商品分类数据
activeCategoryId：当前选中的分类 ID
curPage / pageSize：分页参数（当前页 / 每页数量）
coupons：优惠券数据
shopInfo：店铺信息
scrollTop：页面滚动位置
3. 业务功能术语
banners：轮播图广告
indexAD：首页广告位
goodsCategory：商品分类
noticeList：公告列表
wxaMpLiveRooms：微信小程序直播房间
kanjia：砍价功能
pingtuan：拼团功能
referrer：推荐人 ID
shareProfile：分享文案
4. 页面交互术语
switchTab：切换底部 Tab 页
navigateTo：跳转到新页面
showLoading：显示加载提示
stopPullDownRefresh：停止下拉刷新
onReachBottom：页面触底事件
onPageScroll：页面滚动事件
TabBarBadge：底部 Tab 栏角标