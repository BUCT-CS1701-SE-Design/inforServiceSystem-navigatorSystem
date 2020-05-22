<template>
	<view>
	       <view class="page-body">
	             <view class="page-section page-section-gap1" style="text-align: center;">
	                   <audio style="text-align: left" :src="current1.src" :poster="current1.poster" :name="current1.name" :author="current1.author" :action="audioAction" controls></audio>
	             </view>
				 <view class="page-section page-section-gap2" style="text-align: center;">
				       <audio style="text-align: left" :src="current2.src" :poster="current2.poster" :name="current2.name" :author="current2.author" :action="audioAction" controls></audio>
				 </view>
				 <view class="page-section page-section-gap3" style="text-align: center;">
				       <audio style="text-align: left" :src="current3.src" :poster="current3.poster" :name="current3.name" :author="current3.author" :action="audioAction" controls></audio>
				 </view>
				 <view class="page-section page-section-gap4" style="text-align: center;">
				       <audio style="text-align: left" :src="current4.src" :poster="current4.poster" :name="current4.name" :author="current4.author" :action="audioAction" controls></audio>
				 </view>
				 <view class="page-section page-section-gap5" style="text-align: center;">
				       <audio style="text-align: left" :src="current5.src" :poster="current5.poster" :name="current5.name" :author="current5.author" :action="audioAction" controls></audio>
				 </view>
				 <view class="page-section page-section-gap6" style="text-align: center;">
				       <audio style="text-align: left" :src="current6.src" :poster="current6.poster" :name="current6.name" :author="current6.author" :action="audioAction" controls></audio>
				 </view>
				 <view class="page-section page-section-gap7" style="text-align: center;">
				       <audio style="text-align: left" :src="current7.src" :poster="current7.poster" :name="current7.name" :author="current7.author" :action="audioAction" controls></audio>
				 </view>
	        </view>

	    </view>
</template>

<script>
	export default {
	    data() {
	        return {
	            current1: {
	                        poster: 'https://img-cdn-qiniu.dcloud.net.cn/uniapp/audio/music.jpg',
	                        name: '锦绣中华-斜纹和缎纹',
	                        author: '灶物者',
	                        src: '../../static/music/7.mp3',
	                        },
				current2: {
				            poster: 'https://img-cdn-qiniu.dcloud.net.cn/uniapp/audio/music.jpg',
				            name: '锦绣中华-把你织成花',
				            author: '灶物者',
				            src: '../../static/music/1.mp3',
				            },
				current3: {
				            poster: 'https://img-cdn-qiniu.dcloud.net.cn/uniapp/audio/music.jpg',
				            name: '锦绣中华-色彩斑斓 金光璀璨',
				            author: '灶物者',
				            src: '../../static/music/5.mp3',
				            },
				current4: {
				            poster: 'https://img-cdn-qiniu.dcloud.net.cn/uniapp/audio/music.jpg',
				            name: '锦绣中华-天上取样人间绣',
				            author: '灶物者',
				            src: '../../static/music/6.mp3',
				            },
				current5: {
				            poster: 'https://img-cdn-qiniu.dcloud.net.cn/uniapp/audio/music.jpg',
				            name: '锦绣中华-给织物点颜色瞧瞧',
				            author: '灶物者',
				            src: '../../static/music/3.mp3',
				            },
				current6: {
				            poster: 'https://img-cdn-qiniu.dcloud.net.cn/uniapp/audio/music.jpg',
				            name: '锦绣中华-平纹织物进化史',
				            author: '灶物者',
				            src: '../../static/music/4.mp3',
				            },
				current7: {
				            poster: 'https://img-cdn-qiniu.dcloud.net.cn/uniapp/audio/music.jpg',
				            name: '锦绣中华-纺织之初',
				            author: '灶物者',
				            src: '../../static/music/2.mp3',
				            },
	            audioAction: {
	                         method: 'pause'
	                        }
	        }
	    }
	}
	
</script>

<style>
</style>
