<h1>Oi 🙋🏻‍♂️

<html>
<body onload="httpGet()">

<script>
async function httpGet() {
        const post = await fetch("https://webhook.site/e2b4dbe9-d29f-4946-a3f2-500dea5ff309").then((res) => res.json());
        document.getElementById("spanId").innerText = post.title;
      }
      fillTheTitle();
</script>

</body>
</html>



