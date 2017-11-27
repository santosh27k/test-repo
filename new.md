<!DOCTYPE html>
<html>
<head>
<script>
function insert_newElement()
{
        var newItem  = document.createElement("hr");
        var destParent   = document.getElementsByTagName("body")[0];
        destParent.insertBefore( newItem, destParent.firstChild);
}
</script>
</head>
<body onclick="insert_newElement()">
<h1 id= "my_text"> Please click on this page </h1>
</body>
</html>
