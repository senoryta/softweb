# Ex.07 Software Product Company Website

## Date:8-11-23

## AIM:
To develop a static company website to display the softwares and services provided by the company.

## DESIGN STEPS:

### Step 1:
Requirement collection.

### Step 2:
Creating the layout using HTML and CSS.

### Step 3:
Updating the sample content.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:
Validate the layout in various browsers.

### Step 6:
Validate the HTML code.

### Step 7:
Publish the website in the given URL.

## PROGRAM:
## page.html:
```
<!DOCTYPE html>
<html>
    <head>
           <meta charset="UTF-8">
            <meta http-equiv="x-UA-Compatible" content="IE-edge">
            <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Ashmi S</title>
        <link rel="stylesheet" href="Page.css">
   </head>
    <body>
        <div id="header" style="background-image: url(background1.webp);" >
              <div class="container">
        <nav>
            <img src="1.png" class="logo">
            <ul>
                <li><a href="#header">Home</a></li>
                <li><a href="#about">About us</a></li>
                <li><a href="#services">Products</a></li>
                <li><a href="#mywork">Testimony - People</a></li>
                <li><a href="#contact">Contact Us</a></li>
            </ul>
        </nav>
        <div class="header-text">
            <h1>INNOVATION <span> & IGNITION</span>,</h1>
            <pre> </pre>
            <pre> </pre> 
            <p>At <span><b>ASHMI'S</b></br> INNOVATION AND IGNITION</span> , we believe in the transformative power of well-designed websites. As a leading</br> web development company, we specialize in turning your digital vision into reality. Our team of </br>skilled developers, designers, and strategists collaborates seamlessly to deliver innovative, user-centric web solutions.</br>We are a team of experienced and passionate web developers who are dedicated to helping businesses succeed</br> online. We specialize in creating custom websites that are designed to meet your specific needs and objectives.</p>
    </div>
</div>

</div>

<div id="about">
    <div class="container">
        <div class="row">
            <div class="about-column1">
<img src="User.jpeg" width="500px" height="700px" >
            </div>
            <div class="about-column2">
<h1 class="subtitle">About Us , </h1>
<p>With years of experience in the ever-evolving digital landscape, we bring a wealth of expertise to every project. Our team stays at the forefront of web development trends, ensuring your website is not just a digital presence but a powerful, future-proof asset.We understand that every business is unique. That's why we take a personalized approach to each project, creating bespoke web solutions that align with your brand identity, goals, and user needs.Beyond aesthetics, we prioritize user experience. Our designs are not just visually appealing but also intuitive, ensuring that visitors engage seamlessly with your content and convert into loyal customers.Technology is at the heart of what we do. We leverage the latest web development tools and frameworks to build robust, scalable, and high-performance websites that set you apart from the competition.
</p>
<div class="tab">
    <p class="tab-links active-link" onclick="opentab('skills')">Services</p>
    <p class="tab-links" onclick="opentab('achievements')">Company's Profile</p>
    <p class="tab-links" onclick="opentab('educational Profile')"></p>
</div>  
<div class="tab-contents active-tab" id="skills">
    <ul>
        <li><span>Website design and development</span><br/>Crafting websites that captivate and convert.</li>
        <li><span>
            E-commerce development
            </span><br/>Empowering your online store with seamless shopping experiences.

        </li>
        <li><span>Content management system (CMS) development</span><br/>Unleash the power of content with user-friendly CMS solutions.</li>
        </ul>
</div> 
<div class="tab-contents" id="educational Profile">
    <ul>
        <li><span>Bachelors</span><br/>B.E Computer Science Engineering at Saveetha Engineering College</li>
        <li><span>Higher Secondary</span><br/>at Ponjesly Public School</li>
        <li><span>High School</span><br/>at Ponjesly Public School</li>
        </ul>
</div>  
<div class="tab-contents" id="achievements">
    <ul>
        <li><span>Expert Web Development Solutions</span><br/>Crafting Websites that Drive Success</li>
        <li><span>Tailored E-commerce Platforms</span><br/> Empowering Your Online Business</li>
        <li><span>Digital Marketing Strategies that Resonate</span><br/>SElevating Your Brand Presence</li>
        </ul>
</div>            
</div>
        </div>
    </div>
</div>


<div id="services">
    <div class="container">
        <h1 class="subtitle">Products </h1>  
        <div class="services-list">
            <div>
                <i class="fa-solid fa-code" style="color: #fafafa;"></i>
                <h2>Custom Website Design and Development</h2>
<p>We create stunning and functional websites that reflect your brand and capture your audience's attention. Our experienced designers and developers work closely with you to understand your needs and craft a website that exceeds your expectations.</p>                <a href="#">learn more</a>
            </div>
            <div>
                <i class="fa-sharp fa-solid fa-pen-nib" style="color: #f1f2f3;"></i>
                <h2> E-commerce Development

                    
                    </h2>
<p>                    We build robust and scalable e-commerce platforms that empower your business to thrive online. Our solutions streamline your sales process, provide a seamless shopping experience for your customers, and drive conversions.
</p>                <a href="#">learn more</a>
            </div><div>
                <i class="fa-solid fa-flask-vial" style="color: #f9fafa;"></i>
                                <h2>Content Management System (CMS) Development

                                </h2>
<p>                                    We implement user-friendly CMS solutions that empower you to easily manage and update your website's content. With our CMS, you can maintain a dynamic and engaging online presence without technical expertise.</h2>
</p>         <a href="#">learn more</a>
            </div>
            <div>
                <i class="fa-brands fa-app-store-ios" style="color: #f6f7f9;"></i>
            <h2>Search Engine Optimization (SEO)

</h2>
<p>Search Engine Optimization (SEO)

    We optimize your website to rank higher in search engine results, increasing your visibility and attracting more organic traffic. Our SEO strategies are tailored to your industry and target audience.</p>                <a href="#">learn more</a>
            </div>
            <div>
                <i class="fa-solid fa-code" style="color: #fafafa;"></i>
                <h2>Pay-Per-Click (PPC) Advertising</h2>
            <p>                    We create targeted PPC campaigns that deliver high-quality leads and drive conversions. Our PPC experts manage your campaigns effectively, ensuring you get the most out of your advertising budget.
            </p>            </div>
            <div>
                <i class="fa-sharp fa-solid fa-pen-nib" style="color: #f1f2f3;"></i>
                <h2> Social Media Marketing
                    </h2>
<p>                    We develop engaging social media strategies that connect you with your target audience and amplify your brand message. Our social media management services ensure a consistent and impactful online presence.
</p>                <a href="#">learn more</a>
            </div><div>
                <i class="fa-solid fa-flask-vial" style="color: #f9fafa;"></i>
                                <h2>Mobile App Development</h2>
<p>                                    We create native mobile apps that deliver a seamless user experience and enhance your brand engagement. Our mobile app development process ensures compatibility across various platforms.
</p>
                                <a href="#">learn more</a>
            </div>
            <div>
                <i class="fa-brands fa-app-store-ios" style="color: #f6f7f9;"></i>
            <h2>Cloud-Based Solutions</h2>
<p>                We leverage cloud technologies to provide secure and scalable solutions for your business needs. Our cloud-based services offer flexibility, cost-efficiency, and enhanced collaboration.
</p>
            </div>
            <div>
                <i class="fa-solid fa-code" style="color: #fafafa;"></i>
                <h2>CWebsite Maintenance and Support</h2>
<p>Website Maintenance and Support

    We offer ongoing website maintenance and support services to ensure your website remains up-to-date, secure, and performing optimally. Our proactive approach keeps your website running smoothly.</p>            </div>
            <div>
                <i class="fa-sharp fa-solid fa-pen-nib" style="color: #f1f2f3;"></i>
                <h2>Digital Marketing Consulting</h2>
<p>                    We offer comprehensive digital marketing consulting services to help you develop and implement a winning online strategy. Our experienced consultants provide expert guidance and tailored solutions.
</p>                <a href="#">learn more</a>
            </div>
            <div>
                <i class="fa-solid fa-flask-vial" style="color: #f9fafa;"></i>
                                <h2>Website Analytics and Reporting</h2>

<p>                                    We provide detailed website analytics and reporting to help you understand your user behavior and optimize your website for better performance. Our insights empower you to make data-driven decisions.
</p>         <a href="#">learn more</a>
            </div>
            <div>
                <i class="fa-brands fa-app-store-ios" style="color: #f6f7f9;"></i>
            <h2>Custom Software Development</h2>

<p>                We develop custom software applications tailored to your specific business needs. Our experienced software developers create solutions that streamline processes, enhance productivity, and achieve your business goals.
</p>            </div>
        </div>
    </div>
</div>






<div id="mywork">
    <div class="container">
        <h1 class="subtitle">Testimony</h1> 
        <h3>From our Employees</h3> 
   <div class="worklist">
    <div class="work1">
        <img src="pp7.jpeg">
        <div class="layer">
            <h3>John</h3>
<p>Working at [Your Company Name] has been an incredible experience. The team is incredibly supportive and collaborative, and everyone is always willing to go the extra mile to help each other out. I've learned so much since I've been here, and I'm grateful for the opportunity to work on such challenging and rewarding projects.</p>            </p>
            <a href="#"><i class="fa-solid fa-arrow-up-right-from-square" style="color: #dddfe4;"></i></a>
        </div>
    </div>
<div class="work1">
        <img src="pp2.jpeg">
        <div class="layer">
            <h3>David</h3>
<p>"I've always been passionate about web design, and I'm so glad that I found a company that shares my passion. [Your Company Name] is a creative and innovative place where I'm encouraged to think outside the box and come up with new ideas. I'm proud of the work that we do here, and I'm excited to see what the future holds."</p>        
        <a href="#"><i class="fa-solid fa-arrow-up-right-from-square" style="color: #dddfe4;"></i></a>
    </div>
    </div><div class="work1">
        <img src="pp3.jpeg">
        <div class="layer">
            <h3>Mary</h3>
<p>"I'm a digital marketing specialist, and I love helping businesses grow their online presence. [Your Company Name] provides me with the resources and support I need to do my job effectively. I'm always learning new things, and I'm constantly challenged to come up with new and innovative ways to market our clients' businesses."</p>        <a href="#"><i class="fa-solid fa-arrow-up-right-from-square" style="color: #dddfe4;"></i></a>
    </div>
    </div>
    <div class="work1">
        <img src="pp4.jpeg">
        <div class="layer">
            <h3>Linda</h3>
<p>"I'm a project manager, and I love the challenge of managing complex projects from start to finish. [Your Company Name] provides me with the tools and resources I need to be successful. I'm always working with new and exciting clients, and I'm proud of the projects that we've completed together.            </p>
            <a href="#"><i class="fa-solid fa-arrow-up-right-from-square" style="color: #dddfe4;"></i></a>
        </div>
    </div>
<div class="work1">
        <img src="pp6.jpeg">
        <div class="layer">
            <h3>Micheal</h3>
<p>"I'm a customer service representative, and I love interacting with our clients and helping them solve their problems. [Your Company Name] provides me with the training and support I need to do my job effectively. I'm always learning new things, and I'm constantly challenged to provide excellent customer service."

</p>        
        <a href="#"><i class="fa-solid fa-arrow-up-right-from-square" style="color: #dddfe4;"></i></a>
    </div>
    </div><div class="work1">
        <img src="pp5.jpeg">
        <div class="layer">
            <h3>Patricia</h3>
<p>"I'm a human resources generalist, and I love working with people. [Your Company Name] provides me with the opportunity to make a real difference in the lives of our employees. I'm always looking for new ways to improve our employee experience, and I'm proud of the work that we've done to create a positive and supportive work environment."

</p>        <a href="#"><i class="fa-solid fa-arrow-up-right-from-square" style="color: #dddfe4;"></i></a>
    </div>
    </div>
   </div>
   <a href="#" class="btn">See More</a>
    </div>
</div>







<div id="contact">
    <div class="container">
        <div class="row">
           <div class="contactleft">
<h1 class="subtitle">Contact Us</h1>
<p><i class="fa-solid fa-paper-plane"></i>ashmistalin@gmail.com</p>
<p><i class="fa-solid fa-phone"></i>9500-760-840</p>
<p><i class="fa-solid fa-phone"></i>Saveetha Engineering college, Thandalam</p>
<div class="socialicons">
    <a href="https://m.facebook.com/"><i class="fa-brands fa-facebook"></i></a>
    <a href=""><i class="fa-brands fa-square-twitter"></i></i></a>
    <a href="https://instagram.com/ashmi_stalin?igshid=YmMyMTA2M2Y="><i class="fa-brands fa-instagram"></i></i></a>
    <a href=""><i class="fa-brands fa-linkedin"></i></i></a>

</div>
<a href="images/my cv.pdf" download class="btn btn2">Get in touch</a>
           </div>
           <div class="contactright">
<form >
    <input type="text" name="Name" placeholder="Your name " required>
    <input type="email" name="E-Mail" placeholder="Your e-mail " required>
    <textarea name="Message"  rows="6" placeholder="Your Message"></textarea>
    <button type="submit" class="btn btn2">Submit</button>

</form>
           </div> 
        </div>
    </div>
    <div class="copyright">
      <p>Copyright <i class="fa-regular fa-copyright"></i> Ashmi Stalin <i class="fa-solid fa-heart"></i></p>  
    </div>
</div>









<script>
    var tablinks=document.getElementsByClassName("tab-links");
    var tabcontents=document.getElementsByClassName("tab-contents");
function opentab(tabname)
{
    for(tablink of tablinks ){
        tablink.classList.remove("active-link");
    }
    for(tabcontent of tabcontents){
        tabcontent.classList.remove("active-tab");
    }
    event.currentTarget.classList.add("active-link");
    document.getElementById(tabname).classList.add("active-tab")

}
</script>

</body>
</html>

    </body>
    </html>
```
## page.css:
```
*{
    margin: 0;
    padding: 0;
    font-family: 'Noto-serif',serif;
    box-sizing: border-box;
}
html{
    scroll-behavior: smooth ;
}
body{
    background: black;
    color: aliceblue;
}
#header{
    width:100%;
    height: 100vh;
    background-image: url(images/background13.png);
    background-size:cover;
    background-position: center;
}
.container{
    padding: 10px 50px;
}
nav{
    display: flex;
    align-items: center;
    justify-content: space-between;
    flex-wrap: wrap;
}

.logo{
    width: 200px;
    height: 150px;
}
nav ul li{
    display:inline-block;
    list-style: none;
    margin-top: 1px;
    margin-left: 20px;
}
nav ul li a{
    color: white;
    text-decoration: none;
    font-size: 30px;
    position: relative;
}
nav ul li a::after{
content: ' ';
width: 0%;
height: 3px;
background: lightcoral;
position: absolute;
left: 0;
bottom: -6px;
transition: 0.5s;
}
nav ul li a:hover::after{
    width: 100%;
}
.header-text{
    margin-top: 100px;
    font-size: 19px;
}
.header-text h1{
    font-size: 50px;
}
.header-text h1 span{
    color:lightcoral;
}
.header-text h2{
    text-size-adjust:  20px;
}
.header-text p{
    font-size: 25px;
}
.header-text p span{
    color:lightcoral;
}






#about{
    padding: 50px 0px;
    color: white;
}
.row{
    display: flex;
    justify-content: space-between;
    flex-wrap: wrap;
}

.about-column1{
    flex-basis: 35%;
}
.about-column1 img{
    border-radius: 15px;
}
.about-column2{
    flex-basis: 60%;
}
.subtitle{
font-size: 100px;
font-weight: 600;
color: lightcoral;
font-family: 'Poppins',sans-serif;
}
.about-column2 p{
    margin-top: 20px;
    font-size: 25px;
    font-family: 'Libre Baskerville', serif;
}

.tab{
    display: flex;
    margin: 20px 0 40px;
}
.tab-links{
    margin-right: 50px;
    font-size: 20px;
    font-weight: 400px;
    cursor: pointer;
    position: relative;

}
.tab-links::after{
    content: '';
    width: 0;
    height: 3px;
    background: lightcoral;
    position: absolute;
    left: 0;
    bottom: -8px;
    transition: 0.5s;
}
.tab-links.active-link::after{
    width: 50%;
}
.tab-contents ul li{
    list-style: none;
    margin: 20px 0px;
    font-size: 25px;
}
.tab-contents ul li span{
color:lightcoral;
font-size: 25px;
}
.tab-contents{
    display: none;
}
.tab-contents.active-tab{
    display: block;
}







#services{
    padding: 30px 0;
}
.services-list{
    display: grid;
    grid-template-columns: repeat(auto-fit,minmax(250px,1fr));
    grid-gap: 40px;
    margin-top: 50px;
}
.services-list div{
    background: #262626;
    padding: 30px;
    font-size: 14px;
    font-weight: 300px;
    border-radius: 20px;
    transition: background 0.5s, transform 0.5s;
}
.services-list div i{
    font-size: 40px;
    margin-bottom: 10px;
}
.services-list div h2{
    font-size: 25px;
    font-weight: 500;
    margin-bottom: 15px;
    color: lightcoral;
}
.services-list div p{
    font-family: 'Lato', sans-serif;
    font-size: 15px;
}
.services-list div a{
    text-decoration: none;
    color: aliceblue;
    font-size: 13px;
    margin-top: 20px;
    display: inline-block;
}
.services-list div a:hover{
    color:lightcoral;
}
.services-list div:hover{
    background: rgb(45, 33, 40);
    transform: translateY(-10px);
}
.services-list div h2:hover{
    color: white;
}





#mywork{
    padding: 50px 0;
}
h3{
    margin-top: 30px;
        font-size: 20px;
}
.worklist{
    display: grid;
    grid-template-columns: repeat(auto-fit,minmax(250px,1fr));
    grid-gap: 40px;
    margin-top: 50px;
}
.work1{
    border-radius: 10px;
    position: relative;
    overflow: hidden;
}
.work1 img{
    width: 350px;
    height: 350px;
    border-radius: 10px;
    transition: transform 0.5s;
}
.layer{
    width: 100%;
    height:0;
    background: linear-gradient(rgba(0,0,0,0.6),#ff004f);
    border-radius: 10px;
    position: absolute;
    left:0;
    bottom: 0;
    overflow: hidden;
    display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column;
    padding: 0 40px;
    text-align: center;
    font-size: 18px;
    transition: heigth 0.5s;
}
.layer h3{
    font-weight: 500px;
    margin-bottom: 20px;
}
.work1:hover img{
    transform: scale(1.1);
}
.work1:hover .layer{
    height: 100%;
}
.btn{
    display:block;
margin: 50px auto;
width: fit-content;
border: 1px solid #ff004f;
padding: 14px 50px;
border-radius: 6px;
text-decoration: none;
color: white;
transition: background 0.5s;
}
.btn:hover{
    background:#ff004f;
}



.cotactleft{
    flex-basis: 35%;

}
.contactleft p{
margin-top: 30px;

}
.contactleft p i{
    color: lightcoral;
    margin-right: 30px;
    font-size: 15px;
}
.contactright{
    flex-basis:60%;
}
.socialicons{
margin-top: 30px;
}
.socialicons a{
       text-decoration: none;
       font-size: 30px;
       margin-right: 15px;
       color: #abaaba;
       display: inline-block;
       transition: transform 0.5s;
}
.socialicons a:hover{
    color: lightcoral;
    transform: translateY(-5px);
}
.btn.btn2{
    display: inline-block;
    background: lightcoral;
}
.btn.btn2:hover{
    background-color: #ff004f;
}
.contactright form{
    width: 100%;

}
form input,form textarea{
    width:100%;
border:0 ;
outline: none;
background:#262626;
padding: 15px;
margin: 15px 0;
color: #fff;
font-size: 18px;
border-radius: 6px;
}
form .btn2{
    padding: 14px 60px;
    font-size: 18px;
    margin-top: 20px;
    cursor: pointer;
}
form .btn2:hover{
    background-color: #ff004f;
}
.copyright{
    width: 100%;
    text-align: center;
    padding: 25px 0;
    background:#262626;
    font-weight: 300px;
    margin-top: 40px;

}
.copyright i{
    color: rgb(122, 5, 5);
}
```

## OUTPUT:
![Screenshot (425)](https://github.com/senoryta/softweb/blob/main/Screenshot%20(71).png)
![Screenshot (426)](https://github.com/senoryta/softweb/blob/main/Screenshot%20(72).png)
![Screenshot (427)](https://github.com/senoryta/softweb/blob/main/Screenshot%20(73).png)
![Screenshot (428)](https://github.com/senoryta/softweb/blob/main/Screenshot%20(74).png)




## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
