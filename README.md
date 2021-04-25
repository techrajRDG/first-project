<!DOCTYPE html>
<html>
<head>
<title>Example </title>
<link rel="stylesheet" href="project.css">
</head>
<body>
<div id="form">  
    <h1 id="header">Contact information <span id="required">*</span></h1>
</div>
<div class="box">
    <p>Name</p>
    <p>
        <input type="text" placeholder="Enter you first name" id="fname">
        <input type="text" placeholder="Enter you last name" id="lname">
    </p>
</div>
<div class="box">
    <p>Email <span id="required">*</span></p>
    <p>
        <input type="text" placeholder="xyz@gmail.com" id="email">
    </p>
</div>
<div class="box">
    <p>Address</p>
    <p>
        <input type="text" placeholder="Enter your address" id="address">
    </p>
</div>
<div class="box">
    <p>Number</p>
    <p>
        <input type="number" placeholder="Enter your Phone NO." id="PN">
    </p>
</div>
<div class="box">
    <p>Gender</p>
   <p><input type="radio" name="gender" value="Male">Male</p>
   <p><input type="radio" name="gender" value="Female">Female</p>
   <p><input type="radio" name="gender" value="Transgender">Transgender</p>
</div>
<div class="box">
    <p id="comment">Comment: <span id="required">*</span></p>
    <p id="smalltext"><a href="https://www.markdownguide.org/basic-syntax/">Markdown</a> Supported</p>
    <textarea id="comment" maxlength="300"></textarea>
    <span id="counter">0/300</span>
</div>
<input type="submit">
</div>
</body>
</form>
