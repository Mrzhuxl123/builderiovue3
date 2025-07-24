<template>
	<div class="page"><img :src="Image1" class="image" alt="Image Asset 1" />
		<div class="wrap">
			<div class="container">
				<p class="text">钻石网吧特权</p>
			</div>
		</div><img :src="Image2" class="image1" alt="Image Asset 2" />
	</div>
</template>

<script>
import Image1 from './assets/Image1.png'
import Image2 from './assets/Image2.png'

export default {
	name: 'GeneratedComponent',

	props: {

	},
	setup(props) {


		return {
			Image1,
			Image2

		};
	},
};</script>

<style lang="less" scoped>
.page {
	width: 97px;
	height: 18px;
	overflow: hidden;
	border-radius: 4px;
	box-sizing: border-box;
	display: flex;
	justify-content: flex-start;
	align-items: center;

	.image {
		width: 18px;
		height: 18px;
		box-sizing: border-box;
		background: linear-gradient(135deg, rgba(179, 252, 254, 1) 3%, rgba(95, 230, 250, 1) 31%, rgba(55, 191, 247, 1) 100%);
	}

	.wrap {
		width: 68px;
		height: 18px;
		box-sizing: border-box;
		display: flex;
		justify-content: center;
		align-items: center;

		.container {
			width: 68px;
			height: 18px;
			box-sizing: border-box;
			background: rgba(101, 192, 249, 0.12);
			display: flex;
			justify-content: flex-end;
			align-items: center;

			.text {
				margin-right: 2px;
				opacity: 0.8;
				font-family: 'PingFang SC';
				font-size: 10px;
				white-space: nowrap;
				color: rgba(76, 181, 246, 1);
				line-height: 16px;
				font-weight: 400;
			}
		}
	}

	.image1 {
		width: 11.20px;
		height: 18px;
		box-sizing: border-box;
		background: rgba(101, 192, 249, 0.12);
	}
}
</style>
