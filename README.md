# LOGIN-PAGE
THIS IS BASIC LOGIN PAGE BY USING HTML CSS AND JAVASCRIPT
author- PRINCE KUMAR,PRANJAL YADAV

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Html form></title>
</head>
<style>
body{ 
    display: flex;
    justify-content: centre;
    align-items:centre;
    height: 100vh;
    margin:0;
    background-color:#0ef1ad;
}
form{
    width: 400px;
    background-color: #f4f4f4;
    padding: 20px;
    border-radius: 8px;
    box-shadow: 0 0 10px rgba(19,13,13,0.1);
}
findset{
    border: 1px solid black;
    padding:10px;
    margin:0;
}
legend{
    font-weight: bold;
    margin-bottom: 10px;
}   
label{
    display:block;
    margin-bottom: 5 px;
}
input [type="text"]
    input[type="[password"]
    textarea,
    input[type="date"]{
        width:calc(100%-20px);
        padding: 8px;
        margin-bottom: 10px;
        box-sizing: border-box;
        border: 1px solid #ccc;
        border-radius: 4px;
}
.gender-group{
    margin-bottom: 10px;
}
.gender-group label{
    display: inline-block;
    margin-left: 10px;
}
input[type="radio"]{
    margin-left: 10px;
    vertical-align: middle;
}
input[type="submit"]{
    padding: 10px 20px;
    border-radius: 5px;
    cursor:pointer;
}
</style>
</head>
<body>
    <form>
        <fieldset>
            <legend>Personal Information</legend>
            <label for="name">Enter full name:</label>
            <input type="text" id="name" name="name" required/>
            <label for="email">Enter email:</label>
            <input type="email" id="email" name="email" required/>
            <label for="password">Enter password:</label>
            <input type="password" id="password" name="password" required/>
            <label for="confirm-password">confirm-password:</label>
            <input type="password" id="confirm-password" name="confirm-password" required/>
            <label>enter your gender:</label>
            <div class="gender-group">
                <input type="radio" name="gender" value="male"id="male" required/>
                <label for="male"></label>
                <input type="radio"name="gender" value="female"id="female" required/>
                <label for="others">others</label>
            </div>
            <label for="dob">enter for date of birth:</label>
            <input type="date" id="dob" name="dob" required/>
            <label for="address">enter your address:</label>
            <textarea id="address"name="address"required></textarea>
            <input type="submit" value="submit"/>
        </fieldset>
    </form>
</body>
</html>
