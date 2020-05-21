<template>
	<view>
	       <view class="page-body">
	             <view class="page-section page-section-gap1" style="text-align: center;">
	                   <audio style="text-align: left" :src="current.src" :poster="current.poster" :name="current.name" :author="current.author" :action="audioAction" controls></audio>
	             </view>
				 <view class="page-section page-section-gap2" style="text-align: center;">
				       <audio style="text-align: left" :src="current.src" :poster="current.poster" :name="current.name" :author="current.author" :action="audioAction" controls></audio>
				 </view>
				 <view class="page-section page-section-gap3" style="text-align: center;">
				       <audio style="text-align: left" :src="current.src" :poster="current.poster" :name="current.name" :author="current.author" :action="audioAction" controls></audio>
				 </view>
				 <view class="page-section page-section-gap4" style="text-align: center;">
				       <audio style="text-align: left" :src="current.src" :poster="current.poster" :name="current.name" :author="current.author" :action="audioAction" controls></audio>
				 </view>
				 <view class="page-section page-section-gap5" style="text-align: center;">
				       <audio style="text-align: left" :src="current.src" :poster="current.poster" :name="current.name" :author="current.author" :action="audioAction" controls></audio>
				 </view>
				 <view class="page-section page-section-gap6" style="text-align: center;">
				       <audio style="text-align: left" :src="current.src" :poster="current.poster" :name="current.name" :author="current.author" :action="audioAction" controls></audio>
				 </view>
				 <view class="page-section page-section-gap7" style="text-align: center;">
				       <audio style="text-align: left" :src="current.src" :poster="current.poster" :name="current.name" :author="current.author" :action="audioAction" controls></audio>
				 </view>
				 <view class="page-section page-section-gap8" style="text-align: center;">
				       <audio style="text-align: left" :src="current.src" :poster="current.poster" :name="current.name" :author="current.author" :action="audioAction" controls></audio>
				 </view>
	        </view>

	    </view>
</template>

<script>
	export default {
	    data() {
	        return {
	            current: {
	                        poster: 'https://img-cdn-qiniu.dcloud.net.cn/uniapp/audio/music.jpg',
	                        name: '致爱丽丝',
	                        author: '暂无',
	                        src: 'https://img-cdn-qiniu.dcloud.net.cn/uniapp/audio/music.mp3',
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
