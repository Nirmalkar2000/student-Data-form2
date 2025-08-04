<!DOCTYPE html>
<html>
<head>
<title>input form</title>
</head>
<body style="background-color:#532FA8;">
 
<table>
<form action="/action_page.php">
  <label for="fname" style="color:white;">FIRST NAME:</label>
 <input type="text" id="fname" name="fname">
                               <label for="first name"style="color:white;">(max 30 characters a-z and A-Z)</label><br><br>
  <label for="lname"style="color:white;">LAST NAME:</label>
 <input type="text" id="lname" name="lname">
                               <label for="last name"style="color:white;">(max 30 characters a-z and A-Z)</label><br><br>
      <label for="DOB"style="color:white;">DATE OF BIRTH:</label>
               <select name="Days">
		<option value="Days">Days</option>
		<option value="01">01</option>
		<option value="02">02</option>
		<option value="03">03</option>
		<option value="04">04</option>
		<option value="05">05</option>
		<option value="06">06</option>
		<option value="07">07</option>
		<option value="08">08</option>
		<option value="09">09</option>
		<option value="10">10</option>
		<option value="11">11</option>
		<option value="12">12</option>
		<option value="13">13</option>
		<option value="14">14</option>
		<option value="15">15</option>
		<option value="16">16</option>
		<option value="17">17</option>
		<option value="18">18</option>
		<option value="19">19</option>
		<option value="20">20</option>
		<option value="21">21</option>
		<option value="22">22</option>
		<option value="23">23</option>
		<option value="24">24</option>
		<option value="25">25</option>
		<option value="26">26</option>
		<option value="27">27</option>
		<option value="28">28</option>
		<option value="29">29</option>
		<option value="30">30</option>
		<option value="31">31</option>
		</select>
		       <select name="Month">
		<option value="Month">Month</option>
		<option value="January">January</option>
		<option value="Febuary">Febuary</option>
		<option value="March">March</option>
		<option value="April">April</option>
		<option value="may">may</option>
		<option value="June">JUne</option>
		<option value="July">July</option>
		<option value="August">August</option>
		<option value="september">september</option>
		<option value="October">October</option>
		<option value="November">November</option>
		<option value="December">December</option>
		</select>
		        <select name="Year">
		<option value="Year">Year</option>
		<option value="1995">1995</option>
		<option value="1996">1996</option>
		<option value="1997">1997</option>
		<option value="1998">1998</option>
		<option value="1999">1999</option>
		<option value="2000">2000</option>
		<option value="2001">2001</option>
		<option value="2002">2002</option>
		<option value="2003">2003</option>
		<option value="2004">2004</option>
		<option value="2005">2005</option>
		<option value="2006">2006</option>
		<option value="2007">2007</option>
		<option value="2008">2008</option>
		<option value="2009">2009</option>
		<option value="2010">2010</option>
		<option value="2011">2011</option>
		<option value="2012">2012</option>
		<option value="2013">2013</option>
		<option value="2014">2014</option>
		<option value="2015">2015</option>
		<option value="2016">2016</option>
		<option value="2017">2017</option>
		<option value="2018">2018</option>
		<option value="2019">2019</option>
		<option value="2020">2020</option>
		<option value="2021">2021</option>
		<option value="2022">2022</option>
		<option value="2023">2023</option>
		<option value="2024">2024</option>
		<option value="2025">2025</option>
		</select><br><br>
             
  <label for="email"style="color:white;">EMAIL NUMBER:</label>
  <input type="email" id="email" name="email"><br><br>
       <label for="mobile no"style="color:white;">MOBILE NUMBER:</label>
       <input type="text" id="Mobile Number" name="10 digits number" maxlength="10" size="10">
	                                   <label for="mobile number"style="color:white;">(10 digits number)</label><br><br>

  <label for="Gender"style="color:white;">GENDER:</label>
  <input type="radio" id="male" name="gender">
  <label for="male"style="color:white;">Male</label>
  <input type="radio" id="female" name="gender">
  <label for="female"style="color:white;">Female</label>
  <input type="radio" id="other" name="gender">
  <label for="other"style="color:white;">Other</label><br>
      <label for="Address"style="color:white;">ADDRESS:</label>
     <textarea name="Address" rows="5" cols="30"style="textarea-align:center;"></textarea><br><br>
<label for="city"style="color:white;">CITY:</label>
  <input type="text" id="city" name="city">
                                       <label for="city"style="color:white;">(max 30 characters a-z and A-Z)</label><br><br>	 
       <label for="pin"style="color:white;">PIN CODE:</lable>
  <input type="text" id="pin" name="pin" maxlength="6" size="6">
                                       <label for="pin code"style="color:white;">(6 digits number)</label><br><br>
     <label for="state"style="color:white;">STATE:</label>
     <input type="text" id="State" name="State">
	                                   <label for="State"style="color:white;">(max 30 characters a-z and A-Z)</label><br><br>
           <label for="country"style="color:white;">COUNTRY:</label>
           <input type="text" id="country" name="country"><br><br>
                 <label for="Hobbies"style="color:white;">HOBBIES:</label>
                 <input type="checkbox" id="Hobbies" name="Hobbies" value="Drawing">
                 <label for="Hobbies"style="color:white;">Drawing</label>
                 <input type="checkbox" id="Hobbies" name="Hobbies" value="singing">
                 <label for="Hobbies"style="color:white;"> singing</label>
                 <input type="checkbox" id="Hobbies" name="Hobbies" value="Dancing">
                 <label for="Hobbies"style="color:white;"> Dancing</label>
				 <input type="checkbox" id="Hobbies" name="Hobbies" value="Sketching">
                 <label for="Hobbies"style="color:white;">Sketching</label>
                 <input type="checkbox" id="Hobbies" name="Hobbies">
				 <input type="text" id="Hobbies" name="Hobbies">
                 <label for="Hobbies"style="color:white;">others</label><br><br>

<style>
table, th, td {
  border:none;

}
</style><br>
<label for="Qualification"style="color:white;">QUALIFICATION:</label>
<table style="width:50%">
  <tr style="color:white;">
    <th>Sl No.</th>
    <th>Examination</th> 
    <th>Board</th>
    <th>Percentage</th>
    <th>Year of Passing</th>
  </tr>
  <tr style="color:white;">
    <td>01</td>
    <td>Class X</td>
    <td><input type="text"></td>
    <td><input type="text"></td>
    <td><input type="text"></td>
  </tr>
  <tr style="color:white;">
    <td>02</td>
    <td>Class XII</td>
    <td><input type="text"></td>
    <td><input type="text"></td>
    <td><input type="text"></td>
  </tr>
  <tr style="color:white;">
    <td>03</td>
    <td>Graduation</td>
    <td><input type="text"></td>
    <td><input type="text"></td>
    <td><input type="text"></td>
  </tr>
  <tr style="color:white;">
    <td>04</td>
    <td>Master</td>
    <td><input type="text"></td>
    <td><input type="text"></td>
    <td><input type="text"></td>
    </tr>
</table><br>

<label for="Cources applied for"style="color:white;">COURCES APPLIED FOR:</label>
  <input type="radio" id="BCA" name="cources">
  <label for="BCA"style="color:white;">BCA</label>
  <input type="radio" id="B.Com" name="cources">
  <label for="B.Com"style="color:white;">B.Com</label>
  <input type="radio" id="B.Sc" name="cources">
  <label for="B.Sc"style="color:white;">B.Sc</label>
  <input type="radio" id="B.A" name="cources">
  <label for="BA"style="color:white;">B.A</label><br><br>
  

 <input type="submit" value="Submit" style="text-align:center;">
    <input type="reset" style="text-align:center;">

</form> 
</body>
</html>
