<template>
	<view class="page">
		<view class="cu-bar tabbar bg-white foot">
			<view class="action text-green">
				<view class="cuIcon-homefill"></view> 首页
			</view>
			<view class="action text-gray">
				<view class="cuIcon-search"></view> 分类
			</view>
			<view class="action text-gray add-action">
				<button class="cu-btn cuIcon-add bg-green shadow"></button>
				发布
			</view>
			<view class="action text-gray">
				<view class="cuIcon-cart">
					<view class="cu-tag badge">99</view>
				</view>
				圈子
			</view>
			<view class="action text-gray">
				<view class="cuIcon-my">
					<view class="cu-tag badge"></view>
				</view>
				我的
			</view>
		</view>
	</view>
</template>

<script>
	export default {
		data() {
			return {
				
			}
		},
		onLoad() {

		},
		methods: {

		}
	}
</script>

<style>
	@import url("index.css");
</style>
