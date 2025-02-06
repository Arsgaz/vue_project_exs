<script>
	export default {
		data() {
		    return {
                arr: ['x', 'y', 'z'],
                arr1: [1, 2, 3],
		    }
	    }
	}
</script>
<template>
	<div>
		<br>{{ arr[0] }}
        <br>{{ arr[1] }}
        <br>{{ arr[2] }}
        <br>{{  arr1[0] + arr1[1] + arr1[2] }}
	</div>
</template>