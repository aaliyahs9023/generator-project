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
      var title = $('td[name=title]').val()
      var color = $('td[name=color]').val();
      var font = $('td[name=font]').val();
      var date = $('td[name=date]').val();
    
    $('p').fadeOut(2000);
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
<p>What is the name of your album?</p>
<select name="title">
  <option value="Christmas Tree" selected>Christmas Tree</option>
  <option value="Halloween">Halloween</option>
</select>
<br><p>What color should your album be?</p>
<select name="color">
  <option value="green" selected>green</option>
  <option value="orange">orange</option>
</select></br>
<p>What font do you want?</p>
<select name="font">
  <option value="Times" selected>Times</option>
  <option value="Georgia">Georgia</option>
 >
</select>
<br><p>When will your album drop?</p>
    <select name="date">
  <option value="12/25" selected>12/25</option>
  <option value="10/31">10/31</option>
</select></br>
 <br> <button>Generate Album Cover!</button></br>

</body>

</html>
