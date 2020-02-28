<script>
    let years = 15;
</script>

<main class="container">
    <div class="row">
        <h1>Mortgage Calculator</h1>
    </div>
    <div class="row">
        <label>Loan Amount</label>
        <input min="1" type="number" placeholder="Enter loan amount" class="u-full-width">
    </div>
    <div class="row">
        <div class="columns six">
            <label>Years</label>
            <input type="range" min="1" max="50" class="u-full-width" bind:value={years}>
        </div>
        <div class="columns six outputs">
            {years} Years
        </div>
    </div>
</main>

<style>
    .outputs {
        font-size: 20px;
        border: solid black 2px;
        margin-top: 15px;
        text-align: center;
    }
</style>
