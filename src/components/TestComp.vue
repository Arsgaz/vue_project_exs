<script>
	export default {
		data() {
		    
	    },
        methods: {
            show: function() {
		    alert(new Date());
	    }
	}
	}
</script>
<template>
	<div>
		{{ show() }}
	</div>
</template>