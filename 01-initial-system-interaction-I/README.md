<form action="#" method="POST">
    <!-- text
     password
     email
     number
     checkbox
     radio
     submit-->
      <!-- select options -->
<label for="firstname">Firstname</label>
<input type="text" placeholder="Enter your firstname" 
name="firstname" required>
<br />
<label for="Password">Password</label>
<input type="Password" placeholder="Enter your password" name="password">
<br />
<label for="Email">Email Address</label>
<input type="email" placeholder="Enter your email" name="email"
 value="sam@gmail.com" readonly>
<br />
<label for="Age">Age</label>
<input type="number" placeholder="Enter Age" name="age">

<fieldset>
    <legend>Select your courses</legend>
    <label for="Web App">Web Design and Development</label>
    <input type="checkbox" value="Web Design and Development" name="courses">
    <br />
       <label for="DSA">Data Structure and Algorithm</label>
    <input type="checkbox" value="Data Structure and Algorithm" name="courses">
    <br />
       <label for="SAD">Systems Analysis and Design</label>
    <input type="checkbox" value="Systems Analysis and Design" name="courses">
</fieldset>

<br />
<fieldset>
    <legend>Select Gender</legend>
   Male  <input type="radio" value="male" name="gender">
   <br />
   Female <input type="radio" value="female" name="gender">

</fieldset>

<label for="Country of Birth">Country of Birth</label>
<select name="country_of_birth" id="">
    <option value="">Choose One</option>
    <option value="Ghana">Ghana</option>
    <option value="Togo">Togo</option>
    <option value="Benin">Benin</option>
    <option value="Nigeria">Nigeria</option>
</select>

<input type="submit">
</form>