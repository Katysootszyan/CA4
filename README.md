# CA4
<!DOCTYPE html>

<html lang="en">
    <head>
        <meta charset="utf-8">
        <meta http-equiv="X-UA-Compatible" content="IE=edge">
        <title>Home page</title>
        <meta name="description" content="">
        <meta name="viewport" content="width=device-width, initial-scale=1">
        <link rel="stylesheet" href="css/demo.css">
    </head>
    <body>
      <header>
        <element class="sidenav">
    <a :hover>
        <div class="container">
          <div id="branding">
            <h1><span class="highlight">My Portolio</span></h1>
          </div>
          <nav>
            <ul>
              <li><a href="index.html">Home</a></li>
              <li><a href="#C1">About</a></li>
              <li><a href="chat.html">Chat</a></li>
            </ul> 
        </div>
    </a>
        </element>

      </header>

      <section id="showcase">
        <div class="container">
          <h1>My Journey</h1>
          <p>Thoughout my life, I experienced various things in different stages, from childhood, primary school, univerity, to workplace. Each stage is transformative and inspiring. From a young age, I've always had a deep curiosity and a thirst for knowledge. This curiosity led me to explore various fields and discover my passions along the way.</p>
          <br>
          <p>My professional journey has been a dynamic and fulfilling one, filled with growth and valuable experiences. From the moment I embarked on my knowledge and career, I've been driven by a passion for excellence and a desire to make a meaningful impact in my field, which is business.</p>
        </div>
      </section>

      <section id="client">
        <div class="container">
          <h1>How do I find my objective?</h1>
          <h3>You can input your email to receive more information about how do I find my goals</h3>
          <form>
            <input type="email" placeholder="Enter Email...">
            <button type="submit" class="button_1">Send</button>
          </form>      
      </section>

      <element id="boxes">
        <div class="container">
            <h3>Personal Portfolio</h3>
            <img src="Personal profolio.png" style="width:500px;height:400px">
            <p>I seized every chance I had to study and develop during my time in school. I studied both the history and geoghic, which helped me to acquire a broad viewpoint and a variety of talents. These encounters have made me a more flexible and adaptive person who is ready to approach problems in a variety of ways.</p>
            <p>I had challenges and disappointments along the road that put my fortitude and tenacity to the test. But I never allowed these difficulties to define who I am or stop me from going after my goals. Rather, I saw them as stepping stones that strengthened my will to succeed and keep me motivated.</p>
            <p>However, if I encounter some obstacles that I cannot overcome, I will give up and do not waste the time since everyone have its own shortcome.</p>

            <p>This is <a href="http://skhlmc.icampus.hk/website/"><i>my secondary school</i></a> that affect positively in my personal and academc grwoth.</p>
            <p><a href="https://www.cityu.edu.hk/"><i>The City University of Hong Kong</i></a> is the university that I am studying.</p>
          </div>
<br>
          <div class="container">
            <h3>Professional Portfolio</h3>
            <img src="Professional Profolio.jpeg" style="width:500px;height:400px">
            <p>By means of diligence, commitment, and a strong desire to learn, I have refined my abilities and broadened my domain of knowledge. I've had the honor of cooperating on fascinating projects that have pushed my boundaries and required me to use my creativity while working with varied teams.</p>
            <p>The things I have accomplished in my career make me proud. Every accomplishment, from conquering difficult obstacles to reaching important benchmarks, has increased my drive and strengthened my conviction in the efficacy of tenacity and hard effort.</p>

            <p><h1><a href="https://www.mansfieldhk.com/en">Mansfield</a></h1> is my first internship company in Hong Kong</p>
            <p>My first iternship impact me a lot. It provides various opportunities to gain practical skills and knowledge related to a specific field or industry, such as problem-solving, communication skills, and techniques skills. These skills can be valuable assets in future career endeavors. Moreover, during the internship, I had the chance to hold an event and connect with professionals already established in their desired industry. This is a valuebale chance to build my social network for my future job opportunities.</p>
          </div>

        </div>
      </element>
      <br>
      <section id="Aboutme">
        <div class="container">
          <h1 id="C1"> About me</h1>
        <h3><i>My future goal</i></h3>
        <p>In the future, I can't wait to use my abilities and experiences to provide value and increase the company's earnings. I have a strong interest in marketing and am committed to having a significant influence in these fields. I am excited to take on new challenges, work with like-minded people, and contribute to initiatives that could result in positive change.</p>
        <p>Everyone may encounter difficulties in the life. Whether you're a recent graduate, a career changer, or someone looking for new opportunities, I am here to support you throughout your journey.</p>
        
          </div>
        
        <section id="client">
          <div class="container">
          <p><a href="client.js">Client information</a></p>
        </section>
<br>
        <section id="chat box">
          <div class="container">
            <h3>Do you want to ask questions?</h3>
            <img src="Chat box.jpeg" style="width:125px;height:100px">
            <p><a href = "chat.html">Chat with us</a></p>
          </div>
        </section>

      <footer>
        <p>Website development</p>
      </footer>


        
        <script src="js/client.js" async defer></script>
     

    </body>
</html>

* {
    box-sizing: border-box;
  }
  
  body {
    margin: 0;
    font-family: Arial, Helvetica, sans-serif;
  }
  
  /* Style the side navigation */
  .sidenav {
    height: 100%;
    width: 200px;
    position: fixed;
    z-index: 1;
    top: 0;
    left: 0;
    background-color: #f9eaea;
    overflow-x: hidden;
  }

  /*make the active user text inherit style from container*/
  
  .inbox__people{
      color: white;
      padding: 16px;
  }

  .container{
    width:70%;
    margin:auto;
    overfloe:hidden;
  }

  
  
  /* Side navigation links */
  .sidenav a {
    color: orange;
    padding: 16px;
    text-decoration: none;
    display: block;
    font-size: 17px;
  }

  .sodeav ul{
    margin:0;
    padding:0;
  }

  header #branding{
    float:left;
  }

  header #branding h1{
    margin:0;
  }
  
  header nav{
    flaot:right;
    margin-top:10px;
  }

  header .highlight, header .current a{
    color: blue;
    font-weight:bold;
  }

  /* Change color on hover */
  .sidenav a:hover {
    background-color: #35424a;
    color: tomato;
    padding-top: 30px;
  }
 
  /*showcase */
  #showcase{
    min-height:400px;
    background:url('showcase2.jpeg') no-repeat 0 -300px;
    text-align:center;
    color: tomato;
  }
  
  #showcase h1{
    margin-top:100px;
    font-size:55px;
    margi-bottom:10px;
  }

  #showcase p{
    font-size:20px;
  }

  #client{
    padding:15px;
    color:black;
    background:lightblue;
  }

  #client h1{
    float:middle;
  }

  #client form{
    float:right;
    margin-top:15px
  }

  #client input[type="email"]{
    padding:4px;
    heigth:25px;
    width:250px;
  }

  .button_1{
    height:30px;
    background:tomato;
  }

  /*chat*/
  .button{
    botder: none;
    padding: 10px;
    cursor: pointer;
  }

  .button:hover{
    filter: brightness(0.9);
  }

  .button:active{
    transform: translateY(2px);
  }

  .person-selector{
    dispaly: flex;
    justify-contnt: center;
    gap: 1em;
    margin: 3em auto 1em;
    max-width:40em;
  }

  .person-selector-button{
    width: 100%;
    background-color: tomato;
    color: white;
    font-size: 1.1em;
  }

  .active-person{
    background: blue;
  }

  .chat-container{
    background: darkblue
    font-family: 'Roboto', sans-serif;
    border-radius: 0.5em;
    padding: 0.5em 1.25em;
    margin: auto;
  }

  .chat-header{
    margin-bottom: 1em;
    color: green;
  }

  .chat-header h2{
    font-size: 1.25em;
    font-weight: bold;
  }

  .chat-messages{
    height: 23em;
    overflow-y: scroll;
  }

  /*boxes*/
  #boxes{
    margin-top:20px;
  }

  #boxes .boxes{
    float:left;
    width:30%;
    padding:10px;
    text-align: center;
  }

  #boxes .boxes img{
    width:90px;
  }

  /* Style the content */
  .content {
    margin-left: 200px;
    padding-left: 20px;
  }

  footer{
    padding:20px;
    margin-top:20px;
    color:whitesmoke;
    background-color:grey;
    text-align:center;
  }

  body {
    margin: 0;
    padding: 0;
    font-family: Arial, sans-serif;
}

.sidenav {
    max-width: 600px;
    margin: 20px auto;
    border: 1px solid Blue;
    border-radius: 5px;
    overflow: hidden;
}

.inbox__people {
    background-color: Orange;
    padding: 10px;
    text-align: center;
}

.chat-messages {
    padding: 10px;
    max-height: 300px;
    overflow-y: auto;
}

.message {
    margin-bottom: 10px;
    padding: 5px;
    background-color: rgb(194, 194, 194);
    border-radius: 5px;
}

.message-sender {
    font-weight: bold;
}

.message-content {
    margin-top: 5px;
}

.message_form {
    display: flex;
    align-items: center;
    padding: 10px;
    background-color: #f0f0f0;
}

.message_form input[type="text"] {
    flex: 1;
    padding: 5px;
    border: 1px solid #ccc;
    border-radius: 3px;
}

.message_form button {
    margin-left: 10px;
    padding: 5px 10px;
    border: none;
    background-color: #4caf50;
    color: #fff;
    border-radius: 3px;
    cursor: pointer;
}

.message_form button:hover {
    background-color: #45a049;
}
