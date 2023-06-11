<script>
export default {
	onLaunch: function () {
		console.log('App Launch');
	},
	onShow: function () {
		console.log('App Show');
	},
	onHide: function () {
		console.log('App Hide');
	}
};
</script>
<style>
/*每个页面公共css */
/* 引入官方样式库 */
@import '@/common/uni.css';

/* 引入字体图标库 */
@import '@/common/iconfont.css';

/* 引入我们的动画库 */
@import url('@/common/animate.min.css');

page {
	width: 100vw;
	height: 100vh;
}
</style>
