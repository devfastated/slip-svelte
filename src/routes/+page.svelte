<script>
     let count = 0;
     let countminus = 0;
     let name = "Romer Jasen";
</script>

<button on:click={() => count++}> count is Count is {count} <br /> </button>
{name}

<button on:click={() => countminus--}>
     count is Count is {countminus} <br />
</button>
{name}
