<script>
    window.RufflePlayer = window.RufflePlayer || {};
    window.addEventListener("load", (event) => {
        const ruffle = window.RufflePlayer.newest();
        const player = ruffle.createPlayer();
        const container = document.getElementById("container");
        container.appendChild(player);
        player.ruffle().load("https://Neonraven1991.github.io/surgesnake.swf");
    });
</script>
<script src="https://unpkg.com/@ruffle-rs/ruffle"></script>
