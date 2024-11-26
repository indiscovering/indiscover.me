---
avatar-name: "dyl's page"
avatar-url: "assets/img/avatar.png"
avatar-alt-text: "profile image"
interest-prefix: "my interests:"
---

▸ i'm dyl, also known by the usernames "indiscover" and "horizoned" online ◂



▸ sixteen - he / him ◂



▸ united kingdom ◂



<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>my time</title>
</head>
<body>
    <h1>the current time for me:</h1>
    <p id="gmt-time"></p>

    <script>
        function updateGMTTime() {
            var currentDate = new Date();
            var gmtTime = currentDate.toGMTString();
            document.getElementById("gmt-time").textContent = gmtTime;
        }

        updateGMTTime();
        setInterval(updateGMTTime, 1000);
    </script>
</body>
</html>






