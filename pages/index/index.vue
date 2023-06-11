<template>
	<view>
		<block v-for="(item, index) in contenList" :key="index">
			<conten-list :item="item"></conten-list>
		</block>
	</view>
</template>

<script>
export default {
	data() {
		return {
			title: 'Hello',
			contenList: [{ title: '张三' }, { title: '张三' }, { title: '李四' }]
		};
	},
	onLoad() {},
	methods: {}
};
</script>

<style></style>
