<template>
	<div class="page">
		<div class="wrap"><img :src="Image1" class="image5" alt="Image Asset 1" />
			<div class="container">
				<div class="content">
					<div class="main">
						<p class="text">AK电竞网咖科技园店</p>
						<p class="text1">深圳市｜粤海街道东方科技大厦216</p>
					</div>
					<p class="text2">人均&nbsp;¥37</p>
				</div>
				<div class="content2">
					<div class="main2">
						<div class="section3">
							<div class="subSection3">
								<div class="block3">
									<div class="subBlock"></div>
									<div class="image2"><img :src="Image3" class="image3"
											alt="Image Asset 3" /></div>
								</div>
							</div>
							<div class="subSection4">
								<div class="block4">
									<p class="text6">网吧实力排行榜第1名</p>
								</div>
							</div><img :src="Image4" class="image4" alt="Image Asset 4" />
						</div>
					</div>
				</div>
				<div class="content1">
					<div class="main1">
						<div class="section">
							<img :src="Image5" class="image"
								alt="Image Asset 5" />
							<div class="subSection">
								<div class="block">
									<p class="text3">超凡网吧特权</p>
								</div>
							</div><img :src="Image6" class="image1" alt="Image Asset 6" />
						</div>
						<div class="section1">
							<div class="block1">
								<p class="text4">4090显卡</p>
							</div>
						</div>
						<div class="section2">
							<div class="block2">
								<p class="text5">240Hz显示屏</p>
							</div>
						</div>
					</div>
				</div>
			</div>
		</div><img :src="Image7" class="image6" alt="Image Asset 7" />
	</div>
</template>

<script>
import Image1 from '../assets/Image1.png'
import Image3 from '../assets/Image3.png'
import Image4 from '../assets/Image4.png'
import Image5 from '../assets/Image5.png'
import Image6 from '../assets/Image6.png'
import Image7 from '../assets/Image7.png'

export default {
	name: 'GeneratedComponent',

	props: {

	},
	setup(props) {
		return {
			Image1,
			Image3,
			Image4,
			Image5,
			Image6,
			Image7
		};
	},
};</script>

<style lang="less" scoped>
.page {
	width: 390px;
	height: 112px;
	overflow: hidden;
	box-sizing: border-box;
	display: flex;
	flex-direction: column;
	justify-content: flex-start;
	align-items: flex-start;

	.wrap {
		width: 357px;
		height: 84.89px;
		margin-top: 11.11px;
		margin-left: 17px;
		display: flex;
		justify-content: space-between;
		align-items: flex-start;

		.image5 {
			width: 80px;
			height: 80px;
			box-sizing: border-box;
			margin-top: 4.89px;
		}

		.container {
			width: 265px;
			height: 84.89px;
			display: flex;
			flex-direction: column;
			justify-content: flex-start;
			align-items: flex-start;

			.content {
				width: 265px;
				height: 37.89px;
				display: flex;
				justify-content: space-between;
				align-items: flex-start;

				.main {
					width: 157px;
					height: 37.89px;
					position: relative;

					.text {
						position: absolute;
						top: 0px;
						left: 0px;
						font-family: 'PingFang SC';
						font-size: 16px;
						white-space: nowrap;
						color: rgba(51, 51, 51, 1);
						line-height: 24px;
						font-weight: 500;
					}

					.text1 {
						position: absolute;
						top: 21.89px;
						left: 0px;
						font-family: 'PingFang SC';
						font-size: 10px;
						white-space: nowrap;
						color: rgba(132, 132, 132, 1);
						line-height: 16px;
						font-weight: 400;
					}
				}

				.text2 {
					margin-top: 21.89px;
					font-family: 'PingFang SC';
					font-size: 10px;
					white-space: nowrap;
					text-align: right;
					color: rgba(132, 132, 132, 1);
					line-height: 16px;
					font-weight: 400;
				}
			}

			.content2 {
				width: 210px;
				height: 18px;
				box-sizing: border-box;
				display: flex;
				flex-direction: row;
				flex-wrap: nowrap;
				justify-content: flex-start;
				align-items: center;
				gap: 8px;
				margin-top: 5px;

				.main2 {
					width: 127px;
					height: 18px;
					overflow: hidden;
					border-radius: 4px;
					box-sizing: border-box;
					display: flex;
					flex-direction: row;
					flex-wrap: nowrap;
					justify-content: center;
					align-items: center;

					.section3 {
						width: 127px;
						height: 18px;
						display: flex;
						justify-content: flex-start;
						align-items: center;

						.subSection3 {
							width: 17px;
							height: 18px;
							box-sizing: border-box;
							background: rgba(245, 88, 83, 0.08);
							display: flex;
							justify-content: flex-end;
							align-items: flex-start;

							.block3 {
								margin-right: 2px;
								position: relative;
								width: 12px;
								height: 15.46px;

								.subBlock {
									width: 12px;
									border-radius: NaNpx;
									box-sizing: border-box;
									background: linear-gradient(-45deg, rgba(255, 114, 70, 1) 27.27%, rgba(255, 174, 99, 1) 75.76%);
									min-height: 4.5px;
									position: absolute;
									top: 0px;
									left: 0px;
								}

								.image2 {
									position: absolute;
									top: 3.46px;
									left: 0px;
									display: flex;
									justify-content: flex-start;
									align-items: flex-start;
									width: 12px;
									height: 12px;
									background-image: url('../assets/Image2.png');
									background-size: 100% 100%;
									background-repeat: no-repeat;

									.image3 {
										width: 5.08px;
										height: 7.38px;
										margin-top: 2.08px;
										margin-left: 3.23px;
									}
								}
							}
						}

						.subSection4 {
							width: 99px;
							height: 18px;
							box-sizing: border-box;
							display: flex;
							justify-content: center;
							align-items: center;

							.block4 {
								width: 99px;
								height: 18px;
								box-sizing: border-box;
								background: rgba(245, 88, 83, 0.08);
								display: flex;
								justify-content: center;
								align-items: center;

								.text6 {
									opacity: 0.6;
									font-family: 'PingFang SC';
									font-size: 10px;
									white-space: nowrap;
									color: rgba(245, 88, 83, 1);
									line-height: 16px;
									font-weight: 500;
								}
							}
						}

						.image4 {
							width: 11.20px;
							height: 18px;
							box-sizing: border-box;
							background: rgba(245, 88, 83, 0.08);
						}
					}
				}
			}

			.content1 {
				width: 226px;
				height: 18px;
				box-sizing: border-box;
				display: flex;
				flex-direction: row;
				flex-wrap: nowrap;
				justify-content: center;
				align-items: center;
				gap: 4px;
				margin-top: 6px;

				.main1 {
					width: 226px;
					height: 18px;
					display: flex;
					justify-content: flex-start;
					align-items: center;

					.section {
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
							background: linear-gradient(133deg, rgba(151, 106, 254, 1) 0%, rgba(255, 255, 255, 1) 50.93%, rgba(127, 197, 255, 1) 102.85%);
						}

						.subSection {
							width: 68px;
							height: 18px;
							box-sizing: border-box;
							display: flex;
							justify-content: center;
							align-items: center;

							.block {
								width: 68px;
								height: 18px;
								box-sizing: border-box;
								background: rgba(119, 137, 255, 0.12);
								display: flex;
								justify-content: flex-end;
								align-items: center;

								.text3 {
									margin-right: 2px;
									opacity: 0.8;
									font-family: 'PingFang SC';
									font-size: 10px;
									white-space: nowrap;
									color: rgba(127, 143, 246, 1);
									line-height: 16px;
									font-weight: 500;
								}
							}
						}

						.image1 {
							width: 11.20px;
							height: 18px;
							box-sizing: border-box;
							background: rgba(119, 137, 255, 0.12);
						}
					}

					.section1 {
						width: 52px;
						height: 18px;
						overflow: hidden;
						border-radius: 4px;
						box-sizing: border-box;
						display: flex;
						flex-direction: row;
						flex-wrap: nowrap;
						justify-content: center;
						align-items: center;
						margin-left: 4px;

						.block1 {
							width: 52px;
							height: 18px;
							box-sizing: border-box;
							background: rgba(245, 245, 245, 1);
							display: flex;
							flex-direction: row;
							flex-wrap: nowrap;
							justify-content: center;
							align-items: center;
							gap: 10px;

							.text4 {
								opacity: 0.8;
								font-family: 'PingFang SC';
								font-size: 10px;
								white-space: nowrap;
								color: rgba(132, 132, 132, 1);
								line-height: 16px;
								font-weight: 400;
							}
						}
					}
				}

				.section2 {
					width: 69px;
					height: 18px;
					overflow: hidden;
					border-radius: 4px;
					box-sizing: border-box;
					display: flex;
					flex-direction: row;
					flex-wrap: nowrap;
					justify-content: center;
					align-items: center;
					margin-left: 4px;

					.block2 {
						width: 69px;
						height: 18px;
						box-sizing: border-box;
						background: rgba(245, 245, 245, 1);
						display: flex;
						flex-direction: row;
						flex-wrap: nowrap;
						justify-content: center;
						align-items: center;
						gap: 10px;

						.text5 {
							opacity: 0.8;
							font-family: 'PingFang SC';
							font-size: 10px;
							white-space: nowrap;
							color: rgba(132, 132, 132, 1);
							line-height: 16px;
							font-weight: 400;
						}
					}
				}
			}
		}
	}
}


.image6 {
	width: 360px;
	height: 0.50px;
	margin-top: 15.50px;
	margin-left: 14px;
}
</style>
