<!-- form is used to take the user input in html -->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>form for user input</title>
</head>
<body>
    
    <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/d/d1/Mount_Everest_as_seen_from_Drukair2_PLW_edit.jpg/288px-Mount
    _Everest_as_seen_from_Drukair2_PLW_edit.jpg" alt="everest picture">
    
    <img src="image.png.jpeg" alt="">

    <h1>BADAL KHANAL</h1>
    <em><p>I am the ceo of the <strong> <a href="https://www.eemc.edu.np/">everest engineering college.</a></strong></p></em>
    <p>EEC is a one of the best engineering college located near sanepa,lalitpur.we offers the student to get bachlors degree of 
        mainly three faculties IT,COMP and CIVIL engineering.
    </p>
    <hr>

    <a href="offered course.html">our offered courses</a>

    <h3>additional offers</h3>
    <ol type="A">
        <li>we discount the fee of topper</li>
        <li>we conduct sports week once in a year</li>
    </ol>
    <a href="contact.html">our contact information</a>
    <h3>our fee structure</h3>
    <hr>
    <table border="1" bgcolor="pink">
        <head>
            <tr>
                <th>computer engineering</th>
                <th>it engineering</th>
                <th>civil engineering</th>
            </tr>
        </head>
        <body>
            <tr>
                <td>9lakh</td>
                <td>8lakh</td>
                <td>12 lakh</td>
            </tr>
        </body>
       
    </table>
   <center><h1>clinet details</h1>
           <h4>enter the details of the all incoming clients</h4>
           <br>
           <hr size="">
   </center>
    <form action="">
        <!-- <label for="">username</label>
        <input type="text"> <br>
        <label for="">password</label>
        <input type="password">
        <input type="submit">
        
<input type="button">
<input type="checkbox">
<input type="color">
<input type="date">
<input type="datetime-local">
<input type="email">
<input type="file">
<input type="hidden">
<input type="image">
<input type="month">
<input type="number">
<input type="password">
<input type="radio">
<input type="range">
<input type="reset">
<input type="search">
<input type="submit">
<input type="tel">
<input type="text">
<input type="time">
<input type="url">
<input type="week"> -->

<!-- create a wonderful form -->

<label for="">client name*</label>
<input type="text" name="" id="" required><br>
<label for="">company*</label>
<input type="text" name="" id="" required><br>
<label for="">title</label>
<input type="text" name="" id=""><br>

<label for="department">Department*</label><br>
<select id="department" name="department" required>
  <option value="account">Account Section</option>
  <option value="exam">Exam Section</option>
  <option value="library">Library Section</option>
  
</select><br>

<label for="">company webiste</label>
<input type="url" name="" id="" required><br>
<label for="">company logo</label>
<input type="file" name="" id=""><br>
<label for="">working hours*</label>
<input type="number"><br>
<label for="">billing cycle</label>
<input type="date"><br>
<label for="">additional information</label>
<input type="text"><br>
<input type="submit" name="" id="">
    </form>
</body>
</html>
