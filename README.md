


<!Doctype html>
<html>
  <head></head>
  <body>
    <h4> Student registration in bordering states of Albania </h4><hr>
    <p> I recomend you to be <strong> honest</strong> with <em>yourself!</p>
    <form>
      <thead>
        <tr>
          <label> First Name: <input type="text" name="firstName" placeholder="firstName" required></label><br><br>
          <label> Last Name: <input type="text" name="lastName" placeholder="lastName" required></label><br><br>
          <label> Gender:</label>
          <label> Male <input type="radio" name="gender" value="male"></label>
          <label> Female <input type="radio" name="gender" value="female"></label>
          <label> Other <input type="radio" name="gender" value="other"></label><br><br>

          <tbody>
            <td>
              <label> Age <input type="number" name="age" min = "18" max="25" </label><br><br>
              <label> BirthDate <input type="date" name="birthday" value="birthday"></label><br><br>
              <select name = "country">
                <option value = ""> Country...</option>
                <option value="AL">Albania</option>
                <option value="MK"> Maqedonia</option>
                <option value="MY">Malaysia</option>
                <option value="GR">Greece</option>
                <option value="IT">Italy</option>
                <option value="BD">Bangladesh</option>
                <option value="KA">Kosovo</option>
              </select><br><br>

              	


              <label> City <input type="text" name="city"required> </label><br><br>
              <label> Email: <input type="email" name="email" placeholder="email"></label><br><br>
            </td>
           </tbody>
        </tr>
        <tr>
          <td> University applied for: </td><br>
          <td>
            Bachelor
            <input type="radio" name="education" value="Bachelor">
            Master
            <input type="radio" name="education" value="Master"><br><br>
          </td>
          <tr>
            <td>What do you like the most?</td><br><br>
            <label> Theory <input type="radio" name=theory value="theory"></label>
            <label>Practice <input type="radio" name=practice value="practice"></label><br><br>
            </tr>
            <tr>
              <td>
                Why you study science?<br><br>
                <label>Passion <input type="radio" name=passion value="Passion"></label><br><br>
                <label> need for money <input type="radio" name=money value="need for many"></label><br><br>
                <label>order by Allah <input type="radio" name=faith value="order by Allah"></label><br><br>
                <label> other <input type="text" name=other required></label><br><br>
              </td>
            </tr>
            <tr>
              <td> What is the reason that motivates you to learn? </td><br><br>
              <input type="checkbox" name=I value="myself">
              <label for="I"> myself</label><br><br>
              <input type="checkbox" name=mom&dad value="parents">
              <label for="mom&dad">parents</label><br><br>
              <label> other: <input type="text" name=other required></label><br><br>
            </tr>
            <tr>
              <td> Do you like to take risk for your dreams?</td><br><br>
              <label> Yes <input type="radio" name=yes value="Yes"></label> 
              <label> No <input type="radio" name=no value="No"></label><br><br>
            </tr>
            <tr>
              <td> Which is the purpose in your life? </td><br><br>
              <label> Explain: <input type="text" name= explanation required></label><br><br>
            </tr>
            <td>
          <select name="religion">
            <option value="">religion...</option>
            <option value="Islam">Islam</option>
            <option value="Christianity">Christianity</option>
            <option value="other">other</option>
            <option value="atheist">atheist</option><br><br>
          </select><br><br>
          </td>
        </tr>
        <tr>
          <td> Hobbies  </td><br>
          <input type="checkbox"  name="free time" value="Poetry">
          <label for="free time"> Poetry</label><br>
          <input type="checkbox" name="free time"  value="Meditation" >
          <label for="free time"> Meditation</label><br>
          <input type="checkbox" name="free time" value=Other>
          <label for="free time"> Other</label><br><br>
        </tr>

        <tr>
          <td> Finish</td>
          <label> <input type="submit" value="submit"> </label><hr>
        </tr>
             </thead>
      </form>
    </body>
    <p> Thank you for your time!</p>
</html>
