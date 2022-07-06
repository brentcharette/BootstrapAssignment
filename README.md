# Todo List Assignment
<html>
  <head>
    <link rel="stylesheet" type="text/css" href="css\to do list.css">
  </head>
  <body>
    <div class="header">
      <h2 style="margin:5px">To Do List</h2>
      <input type="text" id="myInput" placeholder="Title...">
      <span onclick="newElement()" class="addBtn">Add</span>
    </div>
    <ul id="myUL">
      <li class="checked">Go through Shelleys List's JavaScript </li>
      <li>Practise the codes</li>
      <li>Read a book on JavaScript</li>
      <li class="checked">Practice makes perfect</li>
      <li>Create JavaScript projects</li>
      <li>Get the concepts first</li>
      <li>Take a break</li>
    </ul>
    <button type="button" id="clear-list" onclick="removeAll()">Clear Items</button>
    <script type="text/javascript" src="js\to do list.js"></script>
  </body>
</html>
