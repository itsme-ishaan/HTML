<!DOCTYPE html>
<html lang="en">
  <head>
     <title>My First Website</title>
  </head>
  <header style="color :brown"><h1>Header</h1></header>
  <body style="background-color : rgb(243, 178, 0)">
     <!-- This is heading tag with special character.-->
     <h1 style="color:rgb(247, 37, 0);">Hello World ! &hearts;</h1>
     <h1>This is my first Website.&#128516;</h1>
     <h1>My name is Ishaan.</h1> 
     <h1><a href="https://www.google.com">Open Google</a></h1>
     <img src="https://www.iconpacks.net/icons/2/free-opened-book-icon-4982-thumb.png" 
     alt="Wallpaper"/>
     <!-- <b> : Bold ; <i> : Italic ; <sup> : power of number ; <sub> : Log cofficient ; <hr> : Horizontal  Line ; -->
     <p>
         <hr> 
         <h2>Random Rubbish</h2> 
         <b> <i> Lorem, ipsum dolor sit amet consectetur adipisicing elit. Temporibus asperiores suscipit 10<sup>2</sup> and  Log<sub>2</sub>, <small> nemo error adipisci quod? </small> </i> </b>
         <pre><h2>
               This is a static Website
               and an example of rubbish 
               webpage . </h2>
         </pre>
     </p> 
     <!-- <hr> : Horizontal Line ; <ul> : Unordered List ; <ol> : Ordered List ; -->
     <p> 
         <h1>
          <hr> <hr>
          <h1>Unordered Shopping List</h1>
          <ul style="color:rgb(27, 36, 211)"> <b>
             <li>Milk</li>
             <li>Bread</li>
             <li>Wheat</li>
             <li>Pulses</li>
             <li>Maggie</li> </b>
          </ul>
         </h1>
         <hr style="color:red">

         <h1>Ordered Maggie Recipie</h1>
          <ol type="A">
            <li>Boil 2 glass of water.</li>
            <li>Add Masala after the water starts boiling.</li>
            <li>After half minute , add the raw noodles.</li>
            <li>Close the lid and let it boil for 5 minutes.</li>
            <li>Open the lid and let it boil on medium flame until the soup becomes thick. Remember to keep stirring.</li>
            <li>Your Maggie is ready. Enjoy. XD </li>
         </ol>
     </p>
     <hr style="color:red">
     <!-- Tables -->
     <!-- <rowspan> : to set more row with same data -->
     <div class="Table"><h1><table border="2">
       <thead style="color:rgb(106, 0, 255)">
          <th><b>Name</b></th>
          <th><b>Course</b></th>
          <th><b>Login</b></th>
       </thead>
       <tr>
         <td>Akash</td>
         <td>BCA</td>
         <td rowspan="2" style="color:red
         ">No</td>
      </tr>
      <tr>
         <td>Ravi</td>
         <td>BCA</td>
         <td></td>
      </tr>
       <tr>
          <td>Ankit</td>
          <td>BTech</td>
          <td style="color:green">Yes</td>
       </tr>
       <tfoot style="color:rgb(38, 0, 255)">
         <tr><td colspan="3"><b>Table Ban Gayi </b></td></tr>
       </tfoot>
       </h1>
       </table></div>
       <p1 class="cat" style="color:blueviolet">Abbrevation</p1>
       <p2 class="cat">Abbrevation</p2>
       <!-- label for attribute == input id -->
       <form><h2>
         <fieldset>
            <legend>Login Credentials</legend>
          <label for="email">Enter Email ID:</label>
          <input type="text" id="email> " placeholder="Enter Your Email Here">
          <br/>
          <br/>
          <label for="password">Enter Password</label>
          <input type="password" id="password" placeholder="Enter Your Password Here">
          <br/>
          <br/>
          <label for="Check">Male</label>
          <input type="radio" id="Check">
          <label for="Check">Female</label>
          <input type="radio" id="Check">
          <br/> 
          <br/>
          <label for="Select">Hindi</label>
          <input type="checkbox" id="Select">
          <label for="datepicker">Choose Date</label>
          <input type="date" id="datepicker"> 
          </br> </br>
          <select name="Food Items" id="selector">
            <option value="Pizza">Pizza</option>
            <option value="Burger">Burger</option>
            <option value="Fries">Fries</option>
          </select>
          </br>
          </br>
          <textarea name="TextArea" id="TextArea" cols="50" rows="10" placeholder="Enter Text Here ..." style="background-color:rgb(106, 0, 255)"></textarea>
          </br>
          </br>
          <label for="FileSelector"></label>
          <input type="file" name="FileSelector" id="FileSelect"></br></br>
          <input type="image" name="Image" id="ImageButton" alt="Download" src="data:image/jpeg;base64,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" width="80"
          <input type="submit" value="Login"></h2></fieldset>
       </form>
      </body>
      <body style="background-color : rgb(41, 0, 243)">
         <h1>
           <b>
              <p1>Lorem ipsum dolor sit amet consectetur adipisicing elit. Delectus, pariatur.</p1>
             <table border="2">
               <tr>
                  <td><h3><a href="https://www.google.com" style="color:blue">Help    </a></h3></td>
                  <td><h3><a href="https://www.google.com" style="color:blue">About    </a></h3></td>
                  <td><h3><a href="https://www.google.com" style="color:blue">Contact Us</a></h3></td>
               </tr>
             </table>
            </b>
         </h1>
      </body>
  
</html>
