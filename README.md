# unit-9
CS 81
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Problem 2</title>
</head>
<body>
<p><strong>We</strong> have just started <strong>this</strong> section for the users (<strong>beginner</strong> to intermediate)
who want to work with <strong>various</strong> JavaScript <strong>problems</strong> and write scripts online to <strong>test</strong>
their JavaScript <strong>skill</strong>.</p>
<script>
  var highlightedWords = document.getElementsByTagName("strong");
   for (var i = 0; i < highlightedWords.length; i++) {
     highlightedWords[i].addEventListener("mouseover", function () {
            this.style.color = "red";
        })
</script>
</body>
</html>
