<!doctype html>
<html lang="en">
  
<head>
    <meta charset="utf-8">
    <link href=
"https://code.jquery.com/ui/1.10.4/themes/ui-lightness/jquery-ui.css"
        rel="stylesheet">
    <script src=
        "https://code.jquery.com/jquery-1.10.2.js">
    </script>
      
    <script src=
        "https://code.jquery.com/ui/1.10.4/jquery-ui.js">
    </script>
  
    <script>
        $(function () {
            $("#gfg").tabs();
            var a = $("#gfg").tabs("option");
            console.log(a)
        });
    </script>
</head>
  
<body>
    <h1>GeeksforGeeks</h1>
    <h3>jQuery UI tabs option method</h3>
  
    <div id="gfg">
        <ul>
            <li><a href="#gfg1">Tab 1</a></li>
            <li><a href="#gfg2">Tab 2</a></li>
            <li><a href="#gfg3">Tab 3</a></li>
        </ul>
  
        <div id="gfg1">
            <p>
                tab Number -1
            </p>
        </div>
  
        <div id="gfg2">
            <p>
                tab Number -2
            </p>
        </div>
  
        <div id="gfg3">
            <p>
                tab Number -3
            </p>
        </div>
    </div>
</body>
  
</html>
