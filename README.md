<!DOCTYPE html>

<html>

<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width">
  <title>generator-project</title>
  <script src="//code.jquery.com/jquery-1.12.0.min.js"></script>
  <script>
    $(function() {
  
      //hides the release date at first
      $('h2').hide();
      
     $('button').click(function() {
       
       
        // get the inputs from the user
      var title = $('#title').val();
      var color = $('#color').val();
      var date = $('#date').val();
       
       //shows the release date when the button is clicked
       $('h2').show();


  $('#album').css('color',color).html(date)
    $('h1').html(title).css('color',color);
     $('h2').css('color',color);


    
    
    
    
      });


        

    });
  </script>
  <style>




  </style>
</head>

<body>
    <h1></h1>
  
  <h2>the release date will be: <span id="album"></span></h2>

  
  
<div style= "background-color:lightblue">
<p>What is the name of your album?
<select id="title">
  <option value="Christmas Tree" selected>Christmas Tree</option>
  <option value="Halloween">This Is Halloween</option>
</select></p>

<p><br>What color should your text be?
<select id="color">
  <option value="green" selected>green</option>
  <option value="orange">orange</option>
</select></br></p>

<p><br>When will your album drop?
    <select id="date">
  <option value="12/25" selected>12/25</option>
  <option value="10/31">10/31</option>
</select></br></p>
 <br><button>Generate Album Cover!</button></br>
</div>
</body>

</html>
