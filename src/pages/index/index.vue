<template>
	<view class="content">
		<Layout :age="12"></Layout>
		<view>
			<text class="title">{{title}}</text>
		</view>
	</view>
</template>

<script>
	import Layout from "../../components/layout.vue";
	export default {
		components: {
			Layout
		},
		data() {
			return {
				title: 'Hello'
			}
		},
		onLoad() {

		},
		methods: {

		}
	}
</script>

<style>
	.content {
		display: flex;
		flex-direction: column;
		align-items: center;
		justify-content: center;
	}

	.logo {
		height: 200rpx;
		width: 200rpx;
		margin: 200rpx auto 50rpx auto;
	}

	.text-area {
		display: flex;
		justify-content: center;
	}

	.title {
		font-size: 36rpx;
		color: #8f8f94;
	}
</style>
