<template>
	<div>
		<swiper :indicator-dots="dots" :autoplay="autoplay" :circular="circular" :vertical="vertical">
			<swiper-item v-for="(item,index) in list" :key="item.id">
				<view>
					<image :src="item.url" style="width: 100%;height: 280rpx;"></image>
				</view>
			</swiper-item>
		</swiper>
	</div>
</template>

<script>
	export default {
		props:{
			list:{
				type:Array,
				value:[]
			},
			vertical:{
				type:Boolean,
				default:false
			},
			circular:{
				type:Boolean,
				default:true
			},
			autoplay:{
				type:Boolean,
				default:true
			},
			dots:{
				type:Boolean,
				default:true
			}
		}
	}
</script>

<style scoped>

</style>
