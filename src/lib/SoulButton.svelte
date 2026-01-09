<script>
    const { children } = $props();
</script>

<button>
    <img src="src/assets/soul.png" alt="red human soul" />
    {@render children()}
</button>

<style>
    button {
        color: white;
        background-color: black;
        border-style: none;

        font-family: "8bitOperatorPlus-Bold", "8bitOperatorPlus-Regular", "monospace";
        /* text-shadow: 1px 1px #000080; */
    }
    button img {
        image-rendering: pixelated;
    }
    button:hover {
        color: yellow;
    }
</style>
