# qybc-banner
# 插件使用说明
# 1.在页面引入插件：import banner from '../../components/qybc-banner/qybc-banner.vue'
# 2.注册插件:components:{qybcBanner}
# 3.使用<qybc-banner></qybc-banner>
# 4.参数说明:
# 参数        类型         是否必传      默认值      说明
# list		 Array 			是			[]         轮播图数据，格式为:[{id:12,url:''}]
# vertical	 Boolean        否          false      轮播图方向：默认为水平方向
# circular   Boolean        否          true       是否采用衔接滑动
# autoplay   Boolean		否          true       是否自动轮播
# dots       Boolean        否          true       是否显示指示器