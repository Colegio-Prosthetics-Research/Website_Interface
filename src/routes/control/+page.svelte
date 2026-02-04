<!-- This is the Control Page route -->

<!-- This is the creation of the iframe, it will present the arm control taken from the github repository -->
<div class="fixed top-1rem w-screen">

    <iframe id="ControlIframe"
    src="https://colegio-prosthetics-research.github.io/esp32/" title="CPR Arm Control"
    use:initializeIFrameResize
    ></iframe>

</div>


<!-- This is the presentation of the iframe -->
<style>
	iframe {
		width: 600px;
		min-width: 100%;
    height: 900px;
    
	}

</style>