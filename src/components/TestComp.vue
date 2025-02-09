<script>
	export default {
		data() {
		    return {
                
            }
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
		<button @click = "show">text</button>
        <br> <button @mouseover = "show">text</button>
	</div>
</template>