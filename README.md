# Ex09 Event Registration Web Application
## Date:26-12-2024

## AIM:
To design, develop and deploy a web application for event registration.

## DESIGN STEPS:

### Step 1:
Create a new frame.

### Step 2:
Select any one preset size of your choice.

### Step 3:
Select the shapes you need.

### Step 4:
Import images as needed.

### Step 5:
Create pages based on your need and link them.

### Step 6:

Validate the HTML and CSS code.

### Step 6:

Publish the website in the given URL.

## DESIGN TOOL:
Figma

## CODE:

frame1.html
```
<div class="frame-1">
    <img class="mobile-login-amico" src="mobile-login-amico0.svg" />
    <img class="rectangle-10" src="rectangle-100.svg" />
    <div class="sign-in">Sign In</div>
    <img class="logo-2" src="logo-20.png" />
    <div class="welcome-back">Welcome Back !</div>
  </div>
```
frame1.css
```
.frame-1,
.frame-1 * {
  box-sizing: border-box;
}
.frame-1 {
  background: #9168c3;
  border-radius: 30px;
  height: 937px;
  position: relative;
  overflow: hidden;
}
.mobile-login-amico {
  height: auto;
  position: absolute;
  left: 149px;
  top: 490px;
  overflow: visible;
}
.rectangle-10 {
  border-radius: 0px;
  width: 141px;
  height: 73px;
  position: absolute;
  left: 239px;
  top: 331px;
  overflow: visible;
}
.sign-in {
  color: #1e1e1e;
  text-align: left;
  font-family: "Inter-Regular", sans-serif;
  font-size: 32px;
  font-weight: 400;
  position: absolute;
  left: 258px;
  top: 349px;
  width: 105px;
  height: 36px;
}
.logo-2 {
  width: 598px;
  height: 90px;
  position: absolute;
  left: 7px;
  top: 21px;
  object-fit: cover;
}
.welcome-back {
  color: #66d7ac;
  text-align: left;
  font-family: "Inter-Black", sans-serif;
  font-size: 40px;
  font-weight: 900;
  position: absolute;
  left: 137px;
  top: 151px;
  width: 337px;
  height: 94px;
  display: flex;
  align-items: center;
  justify-content: flex-start;
}
```

frame2.html
```
<div class="frame-2">
    <div class="rectangle-4"></div>
    <div class="rectangle-12"></div>
    <div class="rectangle-7"></div>
    <div class="log-in">Log In</div>
    <img class="login-amico" src="login-amico0.svg" />
    <div class="enter-username">Enter Username</div>
    <div class="enter-password">Enter Password</div>
  </div>
```
frame2.css
```
.frame-2,
.frame-2 * {
  box-sizing: border-box;
}
.frame-2 {
  background: #9168c3;
  border-radius: 30px;
  height: 937px;
  position: relative;
  overflow: hidden;
}
.rectangle-4 {
  background: #d9d9d9;
  border-radius: 20px;
  width: 285px;
  height: 70px;
  position: absolute;
  left: 157px;
  top: 553px;
}
.rectangle-12 {
  background: #d9d9d9;
  border-radius: 20px;
  width: 285px;
  height: 70px;
  position: absolute;
  left: 157px;
  top: 453px;
}
.rectangle-7 {
  background: #51a1b9;
  border-radius: 25px;
  width: 150px;
  height: 75px;
  position: absolute;
  left: 220px;
  top: 654px;
}
.log-in {
  color: #ffffff;
  text-align: left;
  font-family: "Inter-Medium", sans-serif;
  font-size: 34px;
  font-weight: 500;
  position: absolute;
  left: 244px;
  top: 669px;
  width: 121px;
  height: 46px;
}
.login-amico {
  height: auto;
  position: absolute;
  left: 109px;
  top: 32px;
  overflow: visible;
}
.enter-username {
  color: #1e1e1e;
  text-align: left;
  font-family: "Inter-Regular", sans-serif;
  font-size: 28px;
  font-weight: 400;
  opacity: 0.5;
  position: absolute;
  left: 187px;
  top: 469px;
  width: 235px;
  height: 39px;
}
.enter-password {
  color: #1e1e1e;
  text-align: left;
  font-family: "Inter-Regular", sans-serif;
  font-size: 28px;
  font-weight: 400;
  opacity: 0.5;
  position: absolute;
  left: 189px;
  top: 568px;
  width: 222px;
  height: 39px;
}
```

frame3.html
```
<div class="frame-3">
    <div class="sports-event">SPORTS EVENT</div>
    <img class="grand-slam-rafiki" src="grand-slam-rafiki0.svg" />
    <div class="rectangle-9"></div>
    <div class="rectangle-10"></div>
    <div class="rectangle-16"></div>
    <div class="rectangle-15"></div>
    <div class="rectangle-14"></div>
    <div class="rectangle-13"></div>
    <div class="rectangle-12"></div>
    <div class="rectangle-11"></div>
    <div class="cricket">Cricket</div>
    <div class="football">Football</div>
    <div class="chess">Chess</div>
    <div class="running">Running</div>
    <div class="tennis">Tennis</div>
    <div class="badminton">Badminton</div>
    <div class="basketball">Basketball</div>
    <div class="ellipse-1"></div>
    <div class="ellipse-7"></div>
    <div class="ellipse-6"></div>
    <div class="ellipse-5"></div>
    <div class="ellipse-4"></div>
    <div class="ellipse-3"></div>
    <div class="ellipse-2"></div>
    <div class="rectangle-17"></div>
    <div class="rectangle-18"></div>
    <img class="polygon-1" src="polygon-10.svg" />
    <img class="polygon-2" src="polygon-20.svg" />
    <div class="rectangle-19"></div>
    <div class="register">Register</div>
    <div class="rectangle-20"></div>
    <div class="confirm">Confirm</div>
  </div>
```
frame3.css
```
.frame-3,
.frame-3 * {
  box-sizing: border-box;
}
.frame-3 {
  background: #9168c3;
  border-radius: 30px;
  height: 937px;
  position: relative;
  overflow: hidden;
}
.sports-event {
  color: #ffffff;
  text-align: left;
  font-family: "Inter-Black", sans-serif;
  font-size: 40px;
  font-weight: 900;
  position: absolute;
  left: 135px;
  top: 25px;
  width: 332px;
  height: 84px;
  display: flex;
  align-items: center;
  justify-content: flex-start;
}
.grand-slam-rafiki {
  height: auto;
  position: absolute;
  left: 131px;
  top: 101px;
  overflow: visible;
}
.rectangle-9 {
  background: #d9cde8;
  width: 423px;
  height: 478px;
  position: absolute;
  left: 98px;
  top: 423px;
}
.rectangle-10 {
  background: #6b56aa;
  width: 344px;
  height: 50px;
  position: absolute;
  left: 131px;
  top: 433px;
}
.rectangle-16 {
  background: #6b56aa;
  width: 344px;
  height: 50px;
  position: absolute;
  left: 131px;
  top: 570px;
}
.rectangle-15 {
  background: #6b56aa;
  width: 344px;
  height: 50px;
  position: absolute;
  left: 131px;
  top: 842px;
}
.rectangle-14 {
  background: #6b56aa;
  width: 344px;
  height: 50px;
  position: absolute;
  left: 131px;
  top: 773px;
}
.rectangle-13 {
  background: #6b56aa;
  width: 344px;
  height: 50px;
  position: absolute;
  left: 131px;
  top: 706px;
}
.rectangle-12 {
  background: #6b56aa;
  width: 344px;
  height: 50px;
  position: absolute;
  left: 131px;
  top: 639px;
}
.rectangle-11 {
  background: #6b56aa;
  width: 344px;
  height: 50px;
  position: absolute;
  left: 131px;
  top: 501px;
}
.cricket {
  color: #ffffff;
  text-align: left;
  font-family: "Inter-Medium", sans-serif;
  font-size: 32px;
  font-weight: 500;
  position: absolute;
  left: 149px;
  top: 439px;
  width: 153px;
  height: 38px;
  display: flex;
  align-items: center;
  justify-content: flex-start;
}
.football {
  color: #ffffff;
  text-align: left;
  font-family: "Inter-Medium", sans-serif;
  font-size: 32px;
  font-weight: 500;
  position: absolute;
  left: 150px;
  top: 509px;
  width: 153px;
  height: 38px;
  display: flex;
  align-items: center;
  justify-content: flex-start;
}
.chess {
  color: #ffffff;
  text-align: left;
  font-family: "Inter-Medium", sans-serif;
  font-size: 32px;
  font-weight: 500;
  position: absolute;
  left: 148px;
  top: 850px;
  width: 153px;
  height: 38px;
  display: flex;
  align-items: center;
  justify-content: flex-start;
}
.running {
  color: #ffffff;
  text-align: left;
  font-family: "Inter-Medium", sans-serif;
  font-size: 32px;
  font-weight: 500;
  position: absolute;
  left: 148px;
  top: 780px;
  width: 153px;
  height: 38px;
  display: flex;
  align-items: center;
  justify-content: flex-start;
}
.tennis {
  color: #ffffff;
  text-align: left;
  font-family: "Inter-Medium", sans-serif;
  font-size: 32px;
  font-weight: 500;
  position: absolute;
  left: 148px;
  top: 710px;
  width: 153px;
  height: 38px;
  display: flex;
  align-items: center;
  justify-content: flex-start;
}
.badminton {
  color: #ffffff;
  text-align: left;
  font-family: "Inter-Medium", sans-serif;
  font-size: 32px;
  font-weight: 500;
  position: absolute;
  left: 149px;
  top: 646px;
  width: 191px;
  height: 38px;
  display: flex;
  align-items: center;
  justify-content: flex-start;
}
.basketball {
  color: #ffffff;
  text-align: left;
  font-family: "Inter-Medium", sans-serif;
  font-size: 32px;
  font-weight: 500;
  position: absolute;
  left: 149px;
  top: 574px;
  width: 178px;
  height: 38px;
  display: flex;
  align-items: center;
  justify-content: flex-start;
}
.ellipse-1 {
  background: #d9d9d9;
  border-radius: 50%;
  width: 21px;
  height: 20px;
  position: absolute;
  left: 439px;
  top: 446px;
}
.ellipse-7 {
  background: #d9d9d9;
  border-radius: 50%;
  width: 21px;
  height: 20px;
  position: absolute;
  left: 439px;
  top: 517px;
}
.ellipse-6 {
  background: #d9d9d9;
  border-radius: 50%;
  width: 21px;
  height: 20px;
  position: absolute;
  left: 439px;
  top: 857px;
}
.ellipse-5 {
  background: #d9d9d9;
  border-radius: 50%;
  width: 21px;
  height: 20px;
  position: absolute;
  left: 439px;
  top: 788px;
}
.ellipse-4 {
  background: #d9d9d9;
  border-radius: 50%;
  width: 21px;
  height: 20px;
  position: absolute;
  left: 439px;
  top: 721px;
}
.ellipse-3 {
  background: #d9d9d9;
  border-radius: 50%;
  width: 21px;
  height: 20px;
  position: absolute;
  left: 439px;
  top: 654px;
}
.ellipse-2 {
  background: #d9d9d9;
  border-radius: 50%;
  width: 21px;
  height: 20px;
  position: absolute;
  left: 439px;
  top: 585px;
}
.rectangle-17 {
  background: #110f0f;
  opacity: 0.6;
  width: 20px;
  height: 478px;
  position: absolute;
  left: 521px;
  top: 423px;
}
.rectangle-18 {
  background: #676565;
  opacity: 0.8;
  width: 12px;
  height: 230px;
  position: absolute;
  left: 525px;
  top: 444px;
}
.polygon-1 {
  width: 15px;
  height: 12px;
  position: absolute;
  left: 523px;
  top: 427px;
  overflow: visible;
}
.polygon-2 {
  width: 15px;
  height: 12px;
  position: absolute;
  left: 539px;
  top: 896px;
  transform: translate(-14px, -9px);
  overflow: visible;
}
.rectangle-19 {
  background: #d9d9d9;
  width: 443px;
  height: 60px;
  position: absolute;
  left: 98px;
  top: 363px;
}
.register {
  color: #5089ad;
  text-align: left;
  font-family: "Inter-SemiBold", sans-serif;
  font-size: 32px;
  font-weight: 600;
  position: absolute;
  left: 131px;
  top: 363px;
  width: 147px;
  height: 60px;
  display: flex;
  align-items: center;
  justify-content: flex-start;
}
.rectangle-20 {
  background: #43b668;
  border-radius: 15px;
  width: 144px;
  height: 45px;
  position: absolute;
  left: 331px;
  top: 371px;
}
.confirm {
  color: #ffffff;
  text-align: left;
  font-family: "Inter-Light", sans-serif;
  font-size: 28px;
  font-weight: 300;
  position: absolute;
  left: 351px;
  top: 367px;
  width: 138px;
  height: 52px;
  display: flex;
  align-items: center;
  justify-content: flex-start;
}
```

frame4.html
```
<div class="frame-4">
    <img class="super-thank-you-rafiki" src="super-thank-you-rafiki0.svg" />
    <div class="visit-again">Visit Again !</div>
    <div class="rectangle-9"></div>
    <div class="rectangle-11"></div>
    <div class="contact-with-us">Contact with us</div>
    <div class="visit-our-website">Visit Our Website</div>
    <div class="rectangle-12"></div>
    <div class="visit-website">Visit Website</div>
    <img class="logo-1" src="logo-10.png" />
    <img class="logo-2" src="logo-20.png" />
    <img class="logo-3" src="logo-30.png" />
    <img class="logo-4" src="logo-40.png" />
    <img class="logo-5" src="logo-50.png" />
    <div
      class="your-submission-has-been-received-we-will-be-in-touch-and-contact-you-soon"
    >
      Your submission has been received.
      <br />
      <br />
      We will be in touch and contact you soon.
    </div>
  </div>
  
```
frame4.css
```
.frame-4,
.frame-4 * {
  box-sizing: border-box;
}
.frame-4 {
  background: #9168c3;
  border-radius: 30px;
  height: 937px;
  position: relative;
  overflow: hidden;
}
.super-thank-you-rafiki {
  height: auto;
  position: absolute;
  left: 106px;
  top: 98px;
  overflow: visible;
}
.visit-again {
  color: #ffffff;
  text-align: left;
  font-family: "Inter-Bold", sans-serif;
  font-size: 32px;
  font-weight: 700;
  position: absolute;
  left: 207px;
  top: 516px;
  width: 213px;
  height: 57px;
  display: flex;
  align-items: center;
  justify-content: flex-start;
}
.rectangle-9 {
  background: #d9d9d9;
  width: 231px;
  height: 190px;
  position: absolute;
  left: 60px;
  top: 601px;
}
.rectangle-11 {
  background: #d9d9d9;
  width: 231px;
  height: 190px;
  position: absolute;
  left: 319px;
  top: 601px;
}
.contact-with-us {
  color: #000000;
  text-align: left;
  font-family: "Inter-SemiBold", sans-serif;
  font-size: 28px;
  font-weight: 600;
  opacity: 0.7;
  position: absolute;
  left: 68px;
  top: 601px;
  width: 217px;
  height: 48px;
  display: flex;
  align-items: center;
  justify-content: flex-start;
}
.visit-our-website {
  color: #000000;
  text-align: center;
  font-family: "Inter-SemiBold", sans-serif;
  font-size: 28px;
  font-weight: 600;
  opacity: 0.7;
  position: absolute;
  left: 333px;
  top: 609px;
  width: 199px;
  height: 66px;
  display: flex;
  align-items: center;
  justify-content: center;
}
.rectangle-12 {
  background: #30a999;
  border-radius: 10px;
  width: 162px;
  height: 48px;
  position: absolute;
  left: 355px;
  top: 699px;
}
.visit-website {
  color: #ffffff;
  text-align: center;
  font-family: "Inter-Light", sans-serif;
  font-size: 24px;
  font-weight: 300;
  position: absolute;
  left: 359px;
  top: 702px;
  width: 156px;
  height: 41px;
  display: flex;
  align-items: center;
  justify-content: center;
}
.logo-1 {
  border-radius: 25px;
  width: 47px;
  height: 47px;
  position: absolute;
  left: 118px;
  top: 719px;
  object-fit: cover;
}
.logo-2 {
  border-radius: 25px;
  width: 47px;
  height: 47px;
  position: absolute;
  left: 150px;
  top: 655px;
  object-fit: cover;
}
.logo-3 {
  border-radius: 25px;
  width: 47px;
  height: 47px;
  position: absolute;
  left: 83px;
  top: 655px;
  object-fit: cover;
}
.logo-4 {
  border-radius: 25px;
  width: 47px;
  height: 47px;
  position: absolute;
  left: 216px;
  top: 655px;
  object-fit: cover;
}
.logo-5 {
  border-radius: 25px;
  width: 47px;
  height: 47px;
  position: absolute;
  left: 189px;
  top: 719px;
  object-fit: cover;
}
.your-submission-has-been-received-we-will-be-in-touch-and-contact-you-soon {
  color: #ffffff;
  text-align: center;
  font-family: "Inter-Medium", sans-serif;
  font-size: 26px;
  font-weight: 500;
  position: absolute;
  left: 69px;
  top: 386px;
  width: 464px;
  height: 115px;
  display: flex;
  align-items: center;
  justify-content: center;
}
```

## OUTPUT:

![alt text](<Screenshot (178).png>)

## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
