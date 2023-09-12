[Back to My User Page](https://juicyjons.github.io/)

[View Model](CryptoWaveDynamics.html)

<button id="toggleButton">Show/Hide Model</button>

<div id="iframeContainer" style="display: none;">
    <iframe src="CryptoWaveDynamics.html" width="100%" height="1000px"></iframe>
</div>

<script>
    document.getElementById("toggleButton").addEventListener("click", function() {
        var container = document.getElementById("iframeContainer");
        if (container.style.display === "none") {
            container.style.display = "block";
        } else {
            container.style.display = "none";
        }
    });
</script>



{% include_relative ../README.md %}

{% include_relative Documentation.md %}
