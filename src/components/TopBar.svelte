<script>
    function openUrl(url) {
      window.open(url, '_blank'); // Opens the URL in a new tab
    }

    function initializeIFrameResize(node) {
			iFrameResize({ log: true }, node)
    }
	let showIFrame = false

</script>

<div class= "fixed top-0 left-0 h-24 w-screen m-0 flex flex-col bg-gray-600 text-white shadow-lg">

    <button type="button" class="text-white bg-gray-700  hover:bg-gray-900 focus:ring-4 focus:ring-gray-100 fixed top-7 left-200 rounded-lg px-3 py-2 me-2 mb-2">Home</button>
    <button on:click={() => showIFrame = true} type="button" class="text-white bg-gray-700  hover:bg-gray-900 focus:ring-4 focus:ring-gray-100 fixed top-7 left-220 rounded-lg px-3 py-2 me-2 mb-2">Control</button>
    <button type="button" class="text-white bg-gray-700  hover:bg-gray-900 focus:ring-4 focus:ring-gray-100 fixed top-7 left-242 rounded-lg px-3 py-2 me-2 mb-2">Config</button>
    <button type="button" class="text-white bg-gray-700  hover:bg-gray-900 focus:ring-4 focus:ring-gray-100 fixed top-7 left-262 rounded-lg px-3 py-2 me-2 mb-2">Logs</button>

    <!-- <button type="button" class="text-white bg-gray-700  hover:bg-gray-900 focus:ring-4 focus:ring-gray-100 fixed centered rounded-lg px-3 py-2 me-2 mb-2">Home</button>
    <button on:click={() => showIFrame = true} type="button" class="text-white bg-gray-700  hover:bg-gray-900 focus:ring-4 focus:ring-gray-100 fixed top-7 left-220 rounded-lg px-3 py-2 me-2 mb-2">Control</button>
    <button type="button" class="text-white bg-gray-700  hover:bg-gray-900 focus:ring-4 focus:ring-gray-100 fixed top-7 left-242 rounded-lg px-3 py-2 me-2 mb-2">Config</button>
    <button type="button" class="text-white bg-gray-700  hover:bg-gray-900 focus:ring-4 focus:ring-gray-100 fixed top-7 left-262 rounded-lg px-3 py-2 me-2 mb-2">Logs</button> -->

</div>



<!-- <div class="fixed top-24 w-screen">
{#if showIFrame}
<iframe id="myIframe"
src="https://colegio-prosthetics-research.github.io/esp32/"
use:initializeIFrameResize
></iframe>
{/if}
</div> -->


<style>
	iframe {
		width: 600px;
		min-width: 100%;
        height: 900px;
        
	}

</style>