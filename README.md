# landingpage
Lading Page/Login using HTML 5/CSS 3
HTML 5

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link href="/styles/styles.css" rel="stylesheet">
    <link href="/styles/media.css" rel="stylesheet">
    <title>Landing Page</title>
</head>
<body>
    <header>
        <div id="title">
<h1>Creative</h1>
<h1>Content</h1>
        
        </div>
        <ul>
           <a href="#"><li>Home</li></a>
           <a href="#"><li>About</li></a>
           <a href="#"><li>Contact</li></a>
           <a href="#" id="subscribe-btn"><li>Already have an account?</li></a>
        </ul>
    </header>
    <main>
        <aside>
            <h2>Subscribe Now</h2>
            <h2>to our Newletter</h2>
            <p>
                If you want to practice being more creative, don’t worry about feeling stuck! We have researched some of the best tips from experts to help you get back into the creative flow.Find out more here!
            </p>
            <form>
                <input type="text"placeholder="Name">
                <input type="email"placeholder="E-mail">
                <input type="submit"placeholder="Send">
            </form>
        </aside>
        <article>
            <img src="./images/creative 1.png" alt="light">
        </article>
    </main>
</body>
</html>


CSS 3
body{
    background-color: #EF684F;
    color: antiquewhite;
    font-family: 'Lucida Sans Regular';
    max-width: 1200px;
    margin: 0 auto;
    padding: 15px;
}
header{
    display:flex;
    flex-direction: row;
    justify-content: space-between;
    align-items: center;
}
#title{
    flex-direction: column;
    line-height: 10px;

}
li{
    display: inline-block;
    margin: 20px;
}
a{
    color: antiquewhite;
}
a:hover{
color: #026c80;
}
#subscribe-btn{
    border: 2px solid #8db4ad;
    padding:10px;
    border-radius: 15px;

}
#subscribe-btn:hover{
    background-color: #026c80;
    color:antiquewhite;
}

h1{
    font-weight: 200;
}
main{
    display: flex;
    flex-direction: row;
    margin-top: 50px;
}
h2{
    font-size: 56px;
    line-height: 10px;
    font-family: 'Lucida Grande';
}
span{
    color: #91a066;
    transition: 0.3s all;
}
p{
    line-height: 20px;
    max-width: 500px;
    font-family: 'Lucida Sans';
}
img{
    width: 500px;
}
form{
    display: flex;
    flex-direction: column;
    width: 70%;
}

form [type="submit"]{
height: 50px;
width: 50%;
background-color: #026c80;
color:antiquewhite;
font-weight: bold;
}
form [type="submit"]:hover{
    cursor: pointer;
}

input{
    margin-top: 20px;
    height: 20px;
    padding: 15px;
    border-radius: 20px;
    border:none;
    font-size: 12px;

}
