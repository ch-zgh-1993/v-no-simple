<template>
	<div class="one-root"> <!-- 应该包含一个根元素 -->
		<p>Hello <strong>Wrold!</strong></p>
		<em>{{ authorName }}</em>
	</div>
</template>

<script type="text/javascript">
	export default {
		name: 'app',
		data () {
			return {
				authorName: 'zgh'
			}
		}
	}
</script>

<style>
	p {
		color: orange;
	}
</style>