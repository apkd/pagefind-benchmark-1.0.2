<link href="assets/_pagefind/pagefind-ui.css" rel="stylesheet">
<script src="assets/_pagefind/pagefind-ui.js" type="text/javascript"></script>

<div id="search"></div>
<script>
    window.addEventListener('DOMContentLoaded', (event) => {
        new PagefindUI({ element: "#search", showImages: false, bundlePath: "https://docs.unity3d.com/2023.1/Documentation/" });
    });
</script>