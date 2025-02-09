<script>
	export default {
		data() {
		    return {
                num1: 1,
				num2: 2,
            }
	    },
        methods: {
            show: function() { 
			var a = this.num1 + this.num2;
		    alert(a);
	    }
	}
	}
</script>
<template>
	<div>
		{{show()}}
	</div>
</template>