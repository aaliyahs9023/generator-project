<!DOCTYPE html>

<html>

<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width">
  <title>generator-project</title>
  <script src="//code.jquery.com/jquery-1.12.0.min.js"></script>
  <script>
    $(function() {
     $('button').click(function() {
        // get the inputs from the user
      var title = $('title').val()
      var color = $('color').val();
      var font = $('font').val();
      var date = $('date').val();
    
    $('p').hide();
    
    //if christmas is selected the size will remain h1
    if(title == "Christmas Tree"){
      
    }
    //if halloween is selected it will be h2 
    else(){
      
    }
    
    
    
    
      });


        

    });
  </script>
  <style>
  div{
    background:lightblue;
    
  }
  </style>
</head>

<body>
<h1><p>What is the name of your album?
<select id="title">
  <option value="Christmas Tree" selected>Christmas Tree</option>
  <option value="Halloween">Halloween</option>
</select>
<br>What color should your text be?
<select id="color">
  <option value="red" selected>green</option>
  <option value="black">orange</option>
</select></br>
What font do you want?
<select id="font">
  <option value="Times" selected>Times</option>
  <option value="Georgia">Georgia</option>

</select>
<br>When will your album drop?
    <select id="date">
  <option value="12/25" selected>12/25</option>
  <option value="10/31">10/31</option>
</select></br></p></h1>
 <br> <button>Generate Album Cover!</button></br>

</body>

</html>
