<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
   <meta http-equiv="X-UA-Compatible" content="ie=edge"/>
    <link rel="stylesheet" href="style.css">
    <title>Masum</title>
</head>
<body>
    <div class="container"> 
        <div class="wrapper">
            <div class="content-side">
                <div class="content-side-animation"> </div>
                    <header>
                        <span class="logo" id="logo">Masum</span>
                        <nav>
                            <ul>
                                <li><a href="#" id="aboutLink">About</a></li>
                                 <li><a href="#" id="skillsLink">Skills</a></li>
                                <li><a href="#" id="contactLink">Contact</a></li>
                            </ul>
                        </nav>
                    </header>
                    <section class="main" id="main">
                        <h1 class="main-animation">Hi</h1>
                        <h1 class="main-animation">I'm Masum Hossen</h1>
                        <p class="main-animation">I'm a Student. Studying BBS on Joypurhat <br/> 
                        Government Collage Joypurhat(2014-15) </p>
                        <a href="#" class="main-animation">Contact Me</a>
                    </section>
                    <section class="about" id="about">
                        <h1>About</h1>
                        <p>My Name is Masum Hossen. I'm a Student. <br/>
                            Studying BBS on Joypurhat Government Collage Joypurhat. <br/>
                        My Father is a Farmer and My Mother is a Housewife. <br/>
                        My Brother name is Maruf Islam.He is 20 years Old.</p> <br/>
                        <a href="http://mhinfo.tk/">Download CV</a>
                    </section>
                    <section class="skills" id="skills">
                        <h1>Skills</h1>
                        <p>My Name is Masum Hossen. I'm a Student. <br/>
                            Studying BBS on Joypurhat Government Collage Joypurhat.</p>
                   <div class="skills-card">
                       <div class="html">
                           <img src="night.png" alt="">
                           <h3>Night Guard</h3>
                           <p>Mar 2015 to Nov 2017</p>
                       </div>
                       <div class="css">
                        <img src="index.jpeg" alt="">
                        <h3>Office Assistant</h3>
                        <p>Dec 2017 Jan 2018</p>
                    </div>
                    <div class="javascript">
                        <img src="principal.jpg" alt="">
                        <h3>Principal-PA</h3>
                        <p>Feb 2018 to Present</p>
                    </div>
                   </div>
                    </section>
                    <section class="contact" id="contact">
                        <h1>Contact Me</h1>
                        <form>
                            <input type="text" required placeholder="Full Name" />
                            <input type="email" required placeholder="Email" />
                            <textarea cols="30" rows="10" placeholder="Message" ></textarea>
                            <button type="submit">Send Message</button>
                        </form>
                    </section>
                </div> 
                 
            <div class="assets-side">
                <div class="img">
                    <img src="DSC_0114 (1).JPG" alt="Not Found"> <br/>
                    <img src="DSC_0069.JPG" alt="Not Found">
                </div>
                <div class="links">
                    <div class="facebook">
                        <a href="https://web.facebook.com/masum.mdmasum.75098">facebook</a>
                    </div>
                    
                        <div class="twitter">
                            <a href="https://twitter.com/msasakibalamin">twitter</a>
                        </div>
                       
                            <div class="instagram">
                                <a href="https://instagram.com/msa_sakib_alamin">instagram</a>
                             </div>
                </div>
            </div>
        </div>
    </div>
    <div class="open-modal">+</div>
    <div class="modal">
    <div class="modal-content">
    <span class="close-modal">&times;</span>
    <h1>Personal Contact Details</h1>
    <div class="mail">
        <img src="gmail.jgp" alt="not fond">
        <p>masum.msasakibalamin@gmail.com</p>
    </div>
    <div class="address">
        <img src="home.png" alt="not fond">
        <p>Joypurhat, Sadar</p>
    </div>
    <div class="contact-details">
        <img src="phone.jpg" alt="not fond">
        <p>+8801714666031</p>
    </div>
    </div>
    </div>

    <script src="java.js"></script><br/>

    <a href="https://msainfo.tk"> Copyright &copy; Al-Amin Islam Sakib 2020</a>

   
</body>
</html>

:root {
    --white: #fff;
    --navLinksColor:#656d78;
    --logoColor:#174b78;
    --sectionH1Color:#48cfad;
    --mainParaColor:#ed5565;
    --btnBgColor:#fc6e51;
    --sectionParaColor:#656d78;
    --skillsCardColor:#4fc1e9;
    --skillsH3color:#3c3b3d;
    --inputBorderColor:#656d78;
    --profileBgcolor:#e0e9f2;
    --modalH1Color:#fc6e51;
    --facebookBgColor:#3b5999;
    --twitterBgColor:#55acee;
    --instagramBgColor:#e4405f;
}



* {
   margin: 0;
   padding: 0;
   box-sizing: border-box;
   font-family: 'raleway', sans-serif; 
}


li {
    list-style: none;
}


a {
  text-decoration: none;  
}


.container{
    height: 100vh;
}


.wrapper{
    display: grid;
    grid-template-columns: 1.2fr 1fr;
}


.content-side{
    padding-left: 50px;
}


header,
nav ul{
    display: flex;
    flex-wrap: wrap;
}



header{
    height: 70px;
}
 


.logo {
        padding-right: 100px;
        font-size: 2rem;
        font-weight: 600;
        line-height: 70px;
        color: var(--logoColor);
        cursor: pointer;
}



nav li {
    margin-right: 20px;
    font-size: 1.3rem;
    line-height: 70px;

}

li a {
    color: var(--navLinksColor);
}

.main,.about{
    padding: 150px 0 0 50px;
    position: absolute; 
}

.about,
.skills,
.contact {
    opacity: 0;
}

.main h1,
.about h1,
.skills h1,
.contact h1 {
    font-size: 3rem;
    color:var(--sectionH1Color);
}

h1:nth-child(2) {
    margin-bottom: 20px;
}

.main p {
    font-size: 1.5rem;
    color:var(--mainParaColor);
    margin-bottom: 40px;
}

 .main a,
 .about a,
 .contact button{
     color: var(--white);
     background-color: var(--btnBgColor);
     padding: 10px 30px;
     display:inline-block;
     font-size: 1.5rem;
     border-radius: 50px;
 }

 .about h1,
 .skills h1,
 .contact h1 {
     margin-bottom: 20px;
 }

 .about p,
 .skills > p {
     max-width: 650px;
     font-size: 1.3rem;
     color: var(--sectionParaColor);
     margin-bottom: 40px;
     text-align: justify;
 }

 .skills,
 .contact {
     padding: 100px 0 0 50px ;
     position: absolute;
 }

 .skills-card {
     display: flex;
     flex-wrap: wrap;
     text-align: center;
     max-width: 700px;
 }

 .skills-card div {
     border: 2px solid var(--skillsCardColor);
     padding: 20px;
     margin: 10px 10px;
     position: relative;
     z-index: 1;

 }

 .skills-card div:after {
     content: '';
     width: 100%;
     height: 0;
     position: absolute;
     left: 0;
     bottom: 0;
     background-color: var(--skillsCardColor);
     z-index: -1;
     transition: .5s ease;

 }

.skills-card div:hover::after {
    height: 100%;
}

.skills-card div:hover p{
    color: var(--white);
}

.skills-card div:first-child {
    margin-left: 0;
}

.skills-card p {
    max-width: 100px;
    font-size: .9rem;
    margin-top: 10px;
    color:var(--sectionParaColor);
    font-weight: 600;
}

.skills img {
    width: 60px;
}

.skills h3 {
    text-transform: uppercase;
    color: var(--skillsH3color);
    margin-top: 10px;
}

form{
    max-width: 400px; 
}
 
input{
    width: 100%;
    padding: 10px;
    margin-bottom: 20px;
    border: 2px solid var(--inputBorderColor); 

}

textarea{
    width: 100%;
    padding: 18px;
    margin-bottom: 20px;
    border: 2px solid var(--inputBorderColor);
}


button {
    border: none;
    cursor: pointer;
}

button:focus,
.input:focus,
textarea:focus {
    outline: none;  
} 

.main-animation {
    animation: animate 1s;
}

@keyframes animate {
    from{
        margin-top:30px;
    }
    
    top {
        margin-top: 0;
    } 
}


@-webkit-keyframes animate {
    from{
        margin-top:30px;
    }
    top {
        margin-top: 0;
    }
}


.assets-side {
    display: grid;
    grid-template-columns: 1fr .15fr;
    
}

.img{
    background-color: var(--profileBgcolor);
    
}

.assets-side img{
    width: 510px; 
    position: relative;
    left: 70%;
    right: 70%;
    transform: translate(-79%) ;
    text-align: center;
}

.facebook,.twitter,.instagram{
    height: calc(100% /3);
}

.facebook{
    background-color: var(--facebookBgColor);
    
}

.twitter{
    background-color: var(--twitterBgColor);
}

.instagram{
    background-color: var(--instagramBgColor);
}

.links a{
    writing-mode: vertical-rl;
    font-size: 1.5rem;
    color: var(--white);
    height: calc(100% / 3);
    width: 100%;
    padding-right: 18px;
    text-align: center;

}

.open-modal {
    width: 60px;
    height: 60px;
    border-radius: 50%;
    background-color: #f85959;
    box-shadow: 0 .2rem .7rem rgba(248,89,89,85);
    position: absolute;
    top:40%;
    left:48.5%;
    transform: translate(100%);
    font-size: 3.2rem;
    color: var(--white);
    margin-top: 12px;
    text-align: center;
    cursor: pointer;
}

 
.modal {
    position: fixed;
    top:0;
    left:0;
    background-color: rgba(0,0,0, .75);
    width: 100%;
    height: 100%;
    opacity: 0;
    visibility: hidden;
    transform: scale(1,1);
    transition: visibility 0s linear .25s opacity .25s 0s transform .25s;
}

.modal-content {
    background-color: var(--white);
    position: absolute;
    padding: 20px 40px;
    border-radius: 10px;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
}

.modal-content h1{
    color: var(--modalH1Color);
    font-weight: 300;
     padding: 30px 0 10px 0;
}

.modal-content div {
    display: flex;
    flex-wrap: wrap;
}

.modal-content img{
    width: 40px;
    margin: 0 30px 20px 0;
}

.modal-content p{
    margin-top: 10px;
}

.close-modal {
    font-size: 2rem;
    cursor: pointer;
    position: absolute;
    top: 5px;
    right: 20px;
}

.show-modal{
    opacity: 1;
    visibility: visible;
    transform: scale(1);
    transition: visibility 0s linear 0s, opacity .25s 0, transform .25s;
}


 
 //grab all links
let logo = document.querySelector("#logo");
let aboutLink=document.querySelector("#aboutLink");
let skillsLink=document.querySelector("#skillsLink");
let contactLink=document.querySelector("#contactLink");
// grab all sections
let main = document.querySelector("#main");
let about = document.querySelector("#about");
let skills = document.querySelector("#skills");
let contact = document.querySelector("#contact");
// grab elements of main section for animation
let mainH1 = document.querySelector("#main h1");
let mainH12 = document.querySelector("#main h1:nth-child(2)");
let mainPara = document.querySelector("#main p");
let mainAnker = document.querySelector("#main a");

// grab elements of about sections for animation
let aboutsH1 = document.querySelector("#about h1");
let aboutPara = document.querySelector("#about p");
let aboutAnker = document.querySelector("#about a");

//grab elements of skills section for animation
let skillsH1 = document.querySelector("#skills h1");
let skillsPara = document.querySelector("#skills p");
let skillsCard = document.querySelector("#skills .skills-card");

//grab elements of contact section for animation

let contactH1 = document.querySelector("#contact h1");
let contactForm = document.querySelector("#contact form");
let contactAnker = document.querySelector("#contact a");

function handleOpacity(opacityOne, opacityZer01, opacityZer02, opacityZer03){
    opacityOne.style.opacity = 1;
    opacityZer01.style.opacity = 0;
    opacityZer02.style.opacity = 0;
    opacityZer03.style.opacity = 0;
}

function handleAnimation(){
    for (let i=0; i<arguments.length; i++){
        arguments[i].classList.remove('main-animation')
        arguments[i].ofsetwidth;
        arguments[i].classList.add('main-animation')
    }
}

logo.addEventListener('click', function() {
    handleOpacity(main, about, skills, contact);
    handleAnimation(mainH1, mainH12, mainPara, mainAnker);
})

aboutLink.addEventListener('click', function() {
    handleOpacity(about, main, skills, contact);
    handleAnimation(aboutH1, aboutPara, aboutAnker);
})

skillsLink.addEventListener('click', function() {
    handleOpacity(skills, main, about, contact);
    handleAnimation(skillsH1, skillsPara, skillsCard);
})

contactLink.addEventListener('click', function() {
    handleOpacity(contact, main, about, skills);
    handleAnimation(contactH1, contactForm, contactAnker);
})

let modal = document.querySelector('.modal')
let trigger = document.querySelector('.open-modal')
let closeButton = document.querySelector('.close-modal')

function toggleModal() {
    modal.classList.toggle("show-modal")
}

function windowOnClick(e) {
    if (e.target === modal) {
        toggleModal()
    }
}
trigger.addEventListener('click', toggleModal)
closeButton.addEventListener('click', toggleModal)
window.addEventListener('click', windowOnClick) 
