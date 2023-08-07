 <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title> web dev project 6</title>
    <link rel="shortcut icon" href="logo.png" type="image/x-icon">
</head>
<body>
    <div style="display: grid; grid-template-columns: repeat(2,1fr);"> 
    <div > 
        
        <section> 
    <table>
        <tr>
            <h1>REGISTER HERE :</h1>
            <input type="text" name="email" id="email" placeholder="Email">
            <br>
            <br>
            <input type="password" name="pass" id="pass" placeholder="Password">
            <br>
            <br>
            <input type="password" name="confirm pass" id="confirm pass" placeholder=" Confirm Password">
            <br>
            <br>
            <select name="security options" id="security options">
                    <option value="">security options</option>
                    <option value="security options">Pin Code</option>
                    <option value="security options">Pattern</option>
                    <option value="security options">Passwaord</option>
                    <option value="security options">Face matching</option>
            </select>
            <br>
            <br>
            <textarea name="address" id="adress" cols="30" rows="10" placeholder="Address"></textarea>
            <br>
            <br>
            <h2><strong>QUALIFICATIONS :</strong></h2>
            <select name="university" id="university">
                <option value="" style="color: gray;">Select university</option>
                <option value="university">IIT DELHI</option>
                <option value="university">IIT BOMBAY</option>
                <option value="university">IIT MADRASS</option>
                <option value="university">IIT KANPUR</option>
            </select>
            <br>
            <br>
            <select name="QUALIFICATIONS" id=" QUALIFICATIONS">
                <option value="" style="color: gray;"> HIGHEST QUALIFICATIONS</option>
                <option value="QUALIFICATIONS">B.TECH</option>
                <option value="QUALIFICATIONS">M.TECH</option>
                <option value="QUALIFICATIONS"> PHD</option>
                <option value="QUALIFICATIONS">BCA</option>
            </select>
            <br>
            <br>
            <select name="grade" id="grade">
                <option value="">Grade points</option>
                <option value="grade">A</option>
                <option value="grade">A+</option>
                <option value="grade">A++</option>
                <option value="grade">B</option>
            </select>
    </table>
</section>
<br>
<br>
<button type="reset" style="background-color: green; color: beige;">SUBMIT APPLICATION</button>

</div>
<div >
  <h1>Yours Details</h1>
  <input type="text" placeholder="First Name">
  <br>
  <br>
  <input type="text" placeholder=" Last Name">
  <br>
  <br>
  <label for="relocate" style="margin-right:0.5cm;"><strong>Relocation required*</strong>  </label>
  <input type="radio" name="relocate" id="relocate">
  <label for="relocate"style="margin-right:0.25cm;">Yes</label>
  <input type="radio" name="relocate" id="relocate">
  <label for="relocate">No</label>
  <br>
  <br>
  <select name="country" id="country">
    <option value="">Country</option>
    <option value="country">India</option>
    <option value="country">England</option>
    <option value="country">Australia</option>
    <option value="country">America</option>
  </select>
  <br>
  <br>
  <input type="text" placeholder="Phone Number">
  <br>
  <br>
  <input type="text" placeholder="dd-mm-yyyy">
  <br>
  <br>
  <br>
  <br>
  <input type="file">
</div>
</div>
</body>
</html>
