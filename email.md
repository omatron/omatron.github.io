<!DOCTYPE html>
<html>
<body onload="httpGet()">
<h1>HTML DOM Events</h1>
<h2>The onload Event</h2>
<div>post title: <span id="spanId"></span></div>
<label for="email">Enter your email:</label>
<input type="email" id="email" name="email"> 

<script>
async function httpGet() {
        const post = await fetch("https://webhook.site/e2b4dbe9-d29f-4946-a3f2-500dea5ff309").then((res) => res.json());
        document.getElementById("spanId").innerText = post.title;
      }
      fillTheTitle();
</script>

</body>
</html>



