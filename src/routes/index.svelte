<script>
	let count = 0;

	function incrementCount() {
		count += 1;
	}
</script>

<div class="wraper">
    <button on:click={incrementCount}>
        Clicked {count} {count === 1 ? 'time' : 'times'}
    </button>
</div>

<style lang="scss">
    .wraper{
        margin: 0 auto;

        button {
            color: rgb(185, 44, 19);
            background: blue;
            border-radius: 13px;
            width: 50%;
            height: 50px;    
        }   
    }
    
</style>
