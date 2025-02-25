<script>
if ("serviceWorker" in navigator) {
    navigator.serviceWorker.register("sw.js")
        .then(() => console.log("Service Worker Registrado"))
        .catch(error => console.log("Error registrando el Service Worker:", error));
}
</script>
