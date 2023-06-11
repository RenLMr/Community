<template>
	<view>
		<view class="li">
			<view class="top_totle">
				<view class="img_box">
					<image src="../../static/logo.png" style="width: 65rpx; height: 65rpx; border-radius: 32.5rpx"></image>
					<view class="title">
						<view>{{ item.title }}</view>
						<view>22019-07-08 下午4:22</view>
					</view>
				</view>
				<view class="but">关注</view>
			</view>
			<view class="content">今天是个好体耐。</view>
			<view class="content_img">
				<image src="../../static/logo.png" style="width: 100%; height: 100%; border-radius: 8rpx"></image>
			</view>
			<view class="bottom">
				<view>
					<text class="iconfont">&#xe702;</text>
					<span>1</span>
				</view>
				<view>
					<text class="iconfont">&#xe701;</text>
					<span>1</span>
				</view>
				<view>
					<text class="iconfont">&#xe648;</text>
					<span>1</span>
				</view>
				<view>
					<text class="iconfont">&#xe633;</text>
					<span>分享</span>
				</view>
			</view>
		</view>
	</view>
</template>

<script>
export default {
	name: 'conten_list',
	props: {
		item: {
			type: Object,
			default: () => {}
		}
	},
	data() {
		return {};
	}
};
</script>

<style lang="scss">
.li {
	width: 100%;
	padding: 20rpx;
	box-sizing: border-box;
}
.li .top_totle {
	height: 70rpx;
	margin-bottom: 20rpx;
	display: flex;
	justify-content: space-between;
	align-items: flex-end;
}
.li .top_totle .img_box {
	display: flex;
}
.li .top_totle .img_box .title {
	margin-left: 20rpx;
}

.li .top_totle .img_box .title view:nth-child(2) {
	color: #a09f9a;
	font-size: 26rpx;
}

.li .top_totle .but {
	width: 90rpx;
	height: 50rpx;
	line-height: 50rpx;
	text-align: center;
	background-color: #fd597c;
	border-radius: 8rpx;
	color: #fff;
}
.li .content_img {
	width: 100%;
	height: 350rpx;
}
.li .content {
	padding: 20rpx 0;
	box-sizing: border-box;
}
.li .bottom {
	display: flex;
	justify-content: space-between;
	align-items: center;
	padding: 20rpx 30px;
	box-sizing: border-box;
}
</style>
