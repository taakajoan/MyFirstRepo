<!DOCTYPE html>
<html lang="en" dir="ltr">
  <head>
    <meta charset="utf-8">
    <link rel="stylesheet" href="D:\Andela\GitHub\Andela-Women-Tech-challenge\ACL challenge 2.css">
    <title></title>
  </head>
<style>
body {background-color: powderblue;}
</style>
  
  
  </head>
  <body>
    <h1 id="title">Survey Form</h1>
    <div id="form-outer">
      <p id="description">
        Let us know how we can help you find a Job
      </p>
      <form id="Job Seeker survey-form" method="GET" action="https://crossorigin.me/https://freecodecamp.com">
        <label id="name-label" for="name">* Name: </label>
          </div>
          <div class="rightTab">
            <input autofocus type="text" name="Name" id="Name" class="input-field" placeholder="Enter your name" required>
          </div>
        </div>
        <div class="rowTab">
          <div class="labels">
            <label id="email-label" for="email">* Email: </label>
          </div>
          <div class="rightTab">
            <input type="email" name="email" id="email" class="input-field" required placeholder="Enter your Email">
          </div>
        </div>
        <div class="rowTab">
          <div class="labels">
            <label id="number-label" for="age">* Age: </label>
          </div>
            <input type="email" name="email" id="email" class="input-field" required placeholder="Enter your Email">
          </div>
        </div>
        <div class="rowTab">
          <div class="labels">
           
          </div>
        </div>
        <div class="rowTab">
          <div class="labels">
            <label for="currentPos">1. How long have you been looking for a job?</label>
          </div>
          <div class="rightTab">
            
          <option disabled value>Select an option</option>
          <div class="rightTab">
            <ul style="list-style: none;">
              <div class="rightTab">
                <ul id="preferences" style="list-style: none;">
                  <li class="checkbox"><label><input name="prefer" value="1" type="checkbox" class="userRatings">0-6 months</label></li>
                  <li class="checkbox"><input name="prefer" value="2" type="checkbox" class="userRatings">1-1.5 years</li>
                  <li class="checkbox"><label><input name="prefer" value="3" type="checkbox" class="userRatings">1.5-2 years</label></li>
                  <li class="checkbox"><label><input name="prefer" value="4" type="checkbox" class="userRatings">2years and more</label></li>
          </ul>
              </div>
            </div>
    
        <div class="rowTab">
          <div class="labels">
            <label for="userRating">2. What type of work do you prefer?</label>
          </div>
          <div class="rightTab">
            <ul style="list-style: none;">
              <li class="radio"><label>On Free Labour Market<input name="radio-buttons" value="1"  type="radio" class="userRatings" ></label></li>
              <li class="radio"><label>Protected Jobs<input name="radio-buttons" value="2"  type="radio" class="userRatings" ></label></li>
              <li class="radio"><label>Not sure<input name="radio-buttons" value="3"  type="radio" class="userRatings" ></label></li>
            </ul>
          </div>
        </div>
        <div class="rowTab">
          <div class="labels">
            <label for="most-like">3. Did you meet with discrimination in your job search?</label>
          </div>
          <div class="rightTab">
              <div class="rightTab">
                  <ul style="list-style: none;">
<div class="rightTab">
            <ul id="preferences" style="list-style: none;">
              <li class="checkbox"><label><input name="prefer" value="6" type="checkbox" class="userRatings">Yes</label></li>
              <li class="checkbox"><label><input name="prefer" value="7" type="checkbox" class="userRatings">No</label></li>
              <li class="checkbox"><label><input name="prefer" value="8" type="checkbox" class="userRatings">Not sure</label></li>
             </ul>
          </div>
        </div>
          
          <label for="most-like">If yes please state in what situation: </label></div>
<div class="rowTab">
          <div class="labels">
<label for ="prefences">.....................................................................................</label>
          </div>


         
<div class="rowTab">
          <div class="labels">
            <label for="preferences">4. Are you willing to spend your free time for further education?</label>
</div>
<div class="rowTab">
          <div class="labels">
<label for ="prefences">......................................................................................</label>
          </div>
        </select>
          </div>
        </div>
        <div class="rowTab">
          <div class="labels">
            <label for="preferences">5. What activities do you use to find a job?<br>(Check all that apply): </label>
          </div>
          <div class="rightTab">
            <ul id="preferences" style="list-style: none;">
              <li class="checkbox"><label><input name="prefer" value="1" type="checkbox" class="userRatings">NewsPapers</label></li>
              <li class="checkbox"><input name="prefer" value="2" type="checkbox" class="userRatings">Internet</li>
              <li class="checkbox"><label><input name="prefer" value="3" type="checkbox" class="userRatings">TV & Radio</label></li>
              <li class="checkbox"><label><input name="prefer" value="4" type="checkbox" class="userRatings">Information family,friends & neighbourhood</label></li>
              <li class="checkbox"><label><input name="prefer" value="5" type="checkbox" class="userRatings">Others please state.......................</label></li>
             </ul>
          </div>
        </div>

<div class="rowTab">
          <div class="labels">
            <label for="preferences">6. What is important for you  while choosing a job? <br>(Check all that apply): </label>
          </div>
          <div class="rightTab">
            <ul id="preferences" style="list-style: none;">
              <li class="checkbox"><label><input name="prefer" value="6" type="checkbox" class="userRatings">Financial Independance</label></li>
              <li class="checkbox"><label><input name="prefer" value="7" type="checkbox" class="userRatings">Social Status increase</label></li>
              <li class="checkbox"><label><input name="prefer" value="8" type="checkbox" class="userRatings">Obtaining new contacts</label></li>
              <li class="checkbox"><label><input name="prefer" value="9" type="checkbox" class="userRatings">Gaining new experience & knowledge</label></li>
              <li class="checkbox"><label><input name="prefer" value="10" type="checkbox" class="userRatings">Qualification Increase</label></li>
              <li class="checkbox"><label><input name="prefer" value="10" type="checkbox" class="userRatings">Additional Courses</label></li>
            </ul>
          </div>
        </div>
        <div class="rowTab">
          <div class="labels">
              <i>
            <label for="comments">Thank you for your cooperation</label>
            </i>
          </div>
          
        </div>
         
        <button id="SUBMIT" type="SUBMIT">Submit</button>
        
      
      </form>
    </div>

  </body>
</html>
