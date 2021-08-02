<!DOCTYPE html>
<html>

<head>
  <meta charset="utf-8">
  <title>smart class</title>
  <link rel="stylesheet" href="css.css">
  <script type="text/javascript">
  function updatemenu() {
    if (document.getElementById('responsive-menu').checked == true) {
      document.getElementById('menu').style.borderBottomRightRadius = '0';
      document.getElementById('menu').style.borderBottomLeftRadius = '0';
    }else{
      document.getElementById('menu').style.borderRadius = '50px';
    }
  }
  </script>

  </script>
  <link href="https://fonts.googleapis.com/css?family=Merriweather|Montserrat|Sacramento" rel="stylesheet">
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Itim&family=Permanent+Marker&display=swap" rel="stylesheet">
  <link rel="icon" href="favicon.ico">
</head>

<body>
  <nav id='menu'>
  <input type='checkbox' id='responsive-menu' onclick='updatemenu()'><label></label>
  <ul>
    <li><a href='smart clases.html'>Home</a></li>
    <li><a class='dropdown-arrow' href='http://'>results</a>
      <ul class='sub-menus'>
        <li><a href='class X.html'>class X</a></li>
        <li><a href='http://'>class IX</a></li>
        <li><a href='http://'>class vIII</a></li>
        <li><a href='http://'>class vIII</a></li>
      </ul>
    </li>
    <li><a href='http://'>courses</a></li>
    <li><a class='dropdown-arrow' href='http://'>CCA</a>
      <ul class='sub-menus'>
        <li><a href='http://'>Sub Menu 1</a></li>
        <li><a href='http://'>Sub Menu 2</a></li>
        <li><a href='http://'>Sub Menu 3</a></li>
      </ul>
    </li>
    <li><a href='mailto:kinnngpinku93@gmail.com'>Contact Us</a></li>
  </ul>
</nav>
  <img class="bottom-cloud" src="smart class logo .png" alt="cloud">
  <img class="top-cloud" src="ezgif-4-8979b67af35a.gif" alt="cloud">
  <div class="top-container">
    <div class="title-text">
      <h1>Smart classes</h1>
      <h2>climb the mountain of education with us.</h2>
    </div>
    <!-- <img class="mountain" src="mountain.png" alt="mountain-img">  -->
  </div>

  <div class="middle-container">
    <div class="profile">
      <h2>Founder: Biswajit sir</h2>
      <img class="pinku" src="IMG_20210802_075725.jpg" alt="PINKU SIR-img">
      <p class="intro">warm and caring teacher who wants all children to be sucessful
learners and works to create a classs room atmosphere that is simulating,
encouraging and various needs of students.</p>
    </div>
    <hr>
    <table>
      <thead>
        <tr>
          <th colspan="2"><h2>Some of Intresting Programs we Do</h2></th>
        </tr>
      </thead>

      <td>
        <div class="skills">
          <div class="skill-row">
            <img class="code-img" src="giphy (1).gif" alt="code-img">

            <h3>Quiz competition</h3>
            <p>we often arrange quize competition for students to improve their general knowledge and thia also helps them to perform better in their intra-school competition.</p>

          </div>
          <div class="skill-row">
            <img class="chilli-img" src="mountaineering-cartoon-illustration-young-climber-ce8c1dec2c29b3a3a406efc11e8f9eab.png" alt="img">

            <h3>Excursion</h3>
            <p>We made this program, to make the study of history esier and to get intrested in it. unless we all know how much history makes us sleepy.</p>

          </div>
      </td>
      <td>
        <div class="skills">
          <div class="skill-row">
            <img class="code-img" src="https://media.giphy.com/media/5cTRVc3d5YxMPix8pg/giphy.gif" alt="code-img">

            <h3>picnic</h3>
            <p>picnic is heart and soule of every coaching center.
            we do go to picnic on winters ,probably on new years.</p>

          </div>
          <div class="skill-row">
            <img class="chilli-img" src="https://media.giphy.com/media/47JVzsEEKhnWVEjief/giphy.gif" alt="chillies-img">

            <h3>Puja</h3>
            <p>we celebrate both ganeah puja and saraswati puja here and make classes off on major hindu festivals.</p>

          </div>
      </td>
    </table>
    <div class="skills">
      <h2>Course info.</h2>
      <div class="skill-row">
        <img class="code-img" src="https://media4.giphy.com/media/Y1gXMxPNEmfpP6RovN/giphy.gif?cid=ecf05e47ubkyw78whpl6r2cp0c6ac7g0rxb50qdw6rh0fkw7&rid=giphy.gif&ct=s" alt="code-img">

        <h3>Brief on our courses</h3>
        <p>We offer courses for both CBSE and STATE BOARD students. from class VIII to class X. We also give computer education with central govt. registered ceertificate(This course can only be taken after class X.).</p>
    </div>
    <img class="contactbulb" src="giphy (2).gif" alt="">
    <hr>
    <div class="contact-me">
      <h2 id = wantaddmission>Get In Touch</h2>
      <h3 id="betterresult">If you want a better result.</h3>
      <p class="contact-message">take this advantage now 👇</p>
      <a class="btn" href="mailto:kinnngpinku93@gmail.com">CONTACT US</a>
    </div>
  </div>

  <div class="bottom-container">
    <a class="footer-link" href="">LinkedIn</a>
    <a class="footer-link" href="">Twitter</a>
    <a class="footer-link" href="">Telegram</a>
    <p class="copyright">© 2021 smart classes @ DeveloperRK .</p>
  </div>
</body>

</html>
