<template>
<div class="Singing">
    <van-empty
  class="custom-image"
  image="https://gimg2.baidu.com/image_search/src=http%3A%2F%2Fimg.tuguaishou.com%2Fgif_complete_img%2F2019-05-05%2F5227fe6679dec8e1064ef4f44c405bbe.gif%21w1024_w%3Fauth_key%3D2208254025-0-0-ffea70a16bfc5a7de0d4ebdb036d0667&refer=http%3A%2F%2Fimg.tuguaishou.com&app=2002&size=f9999,10000&q=a80&n=0&g=0n&fmt=jpeg?sec=1616643895&t=aaa5cac74889e62a65ebb544f7f3ec64"
  description=""
/>
</div>
 
</template>

<script>
export default {

}
</script>

<style>
  .custom-image .van-empty__image {
    width: 100%;
    height:  100%;
    position: absolute;
    top: 0rem;
  }
  .custom-image .van-empty__image :after {
	content: ".";
	clear: both;
	height: 0;
	visibility: hidden;
	display: block;
}
</style>