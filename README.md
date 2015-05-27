# x2j
XML to JSON converter

Does what is says on the tin.

Usage:
Import the alchemy.x2j.js file into an HTML page using script tags:
  <script src="js/alchemy.x2j.js"></script>
  
x2j lives in a namespace called alchemy. Assuming your XML data is stored in a 
variable called xmlData, convert it to JSON and store in a new variable like so:
  var jsonData = alchemy.x2j.convert( fileContents );
