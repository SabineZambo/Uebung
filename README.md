# Uebung<!doctype html>
<html lang="en">
 <head>
   <title>My project</title>
   <meta charset="utf-8">
   <link rel="stylesheet" href="css/CETEIcean.css" />
   <script src="js/CETEI.js"></script>
 </head>
 <body>
   <div id="TEI"></div>
   <script>

   var CETEIcean = new CETEI()

     CETEIcean.getHTML5("data/letter.xml", function(data) {
      document.getElementById("TEI").appendChild(data)

     })


   </script>
 </body>
</html>

tei-p{
 color: green
}

tei-hi: :before {
content: "***"
}

tei-hi: after{
content: "***"
}
