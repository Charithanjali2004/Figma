# Ex09 Event Registration Web Application
# Date:25/11/2024
# AIM:
To design, develop and deploy a web application for event registration.

# DESIGN STEPS:
## Step 1:
Create a new frame.

## Step 2:
Select any one preset size of your choice.

## Step 3:
Select the shapes you need.

## Step 4:
Import images as needed.

## Step 5:
Create pages based on your need and link them.

## Step 6:
Validate the HTML and CSS code.

## Step 6:
Publish the website in the given URL.

# DESIGN TOOL:
Figma

# CODE:



    <div class="frame-1">
    <img class="sec-logo-1" src="sec-logo-10.png" />
    <img class="sec-logo-2-1" src="sec-logo-2-10.png" />
    <div class="rectangle-2"></div>
    <div class="rectangle-3"></div>
    <div class="login">LOGIN</div>
    <div class="register">REGISTER</div>
    <div class="sports-day-events">SPORTS DAY EVENTS</div>
    </div>




    .frame-1,
    .frame-1 * {
    box-sizing: border-box;
    }
    .frame-1 {
    background: #e3bbe0;
    width: 221px;
    height: 411px;
    position: relative;
    overflow: hidden;
    }
    .sec-logo-1 {
    width: 220px;
    height: 33px;
    position: absolute;
    left: 0px;
    top: 9px;
    object-fit: cover;
    }
    .sec-logo-2-1 {
    width: 72px;
    height: 72px;
    position: absolute;
    left: 79px;
    top: 99px;
    object-fit: cover;
    }
    .rectangle-2 {
    background: #77f8fa;
    width: 104px;
    height: 34px;
    position: absolute;
    left: 60px;
    top: 254px;
    }
    .rectangle-3 {
    background: #72f8ec;
    width: 104px;
    height: 34px;
    position: absolute;
    left: 58px;
    top: 312px;
    }
    .login {
    color: #000000;
    text-align: left;
    font-family: "Inter-Regular", sans-serif;
    font-size: 12px;
    font-weight: 400;
    position: absolute;
    left: 91px;
    top: 265px;
    width: 79px;
    height: 23px;
    }
    .register {
    color: #000000;
    text-align: left;
    font-family: "Inter-Regular", sans-serif;
    font-size: 12px;
    font-weight: 400;
    position: absolute;
    left: 79px;
    top: 318px;
    width: 72px;
    height: 28px;
    }
    .sports-day-events {
    color: #4a3bf2;
    text-align: left;
    font-family: "Inter-Regular", sans-serif;
    font-size: 12px;
    font-weight: 400;
    position: absolute;
    left: 50px;
    top: 182px;
    width: 137px;
    height: 15px;
    }



    <div class="frame-2">
        <div class="frame-5"></div>
        <div class="sports-day-events">SPORTS DAY EVENTS</div>
        <div class="cricket">
        <ul class="cricket-span">
            <li>CRICKET</li>
        </ul>
        </div>
        <div class="volley-boll">
        <ul class="volley-boll-span">
            <li>VOLLEY BOLL</li>
        </ul>
        </div>
        <div class="badminton">
        <ul class="badminton-span">
            <li>BADMINTON</li>
        </ul>
        </div>
        <div class="_100-mts">
        <ul class="_100-mts-span">
            <li>100 MTS</li>
        </ul>
        </div>
        <div class="_200-mts">
        <ul class="_200-mts-span">
            <li>200 MTS</li>
        </ul>
        </div>
        <div class="_400-mts">
        <ul class="_400-mts-span">
            <li>400 MTS</li>
        </ul>
        </div>
        <div class="_4-100-relay">
        <ul class="_4-100-relay-span">
            <li>4-100 RELAY</li>
        </ul>
        </div>
    </div>

  


    .frame-2,
    .frame-2 * {
    box-sizing: border-box;
    }
    .frame-2 {
    background: #f9c1f6;
    width: 196px;
    height: 411px;
    position: relative;
    overflow: hidden;
    }
    .frame-5 {
    width: 1px;
    height: 7px;
    position: absolute;
    left: 196px;
    top: 198px;
    overflow: hidden;
    }
    .sports-day-events {
    color: #1d12e8;
    text-align: left;
    font-family: "Inter-Regular", sans-serif;
    font-size: 12px;
    font-weight: 400;
    position: absolute;
    left: 27px;
    top: 37px;
    width: 142px;
    height: 25px;
    }
    .cricket {
    color: #13aeb6;
    text-align: left;
    font-family: "Inter-Regular", sans-serif;
    font-size: 16px;
    font-weight: 400;
    position: absolute;
    left: 27px;
    top: 94px;
    width: 142px;
    height: 25px;
    }
    .volley-boll {
    color: #13aeb6;
    text-align: left;
    font-family: "Inter-Regular", sans-serif;
    font-size: 16px;
    font-weight: 400;
    position: absolute;
    left: 32px;
    top: 190px;
    width: 142px;
    height: 25px;
    }
    .badminton {
    color: #13aeb6;
    text-align: left;
    font-family: "Inter-Regular", sans-serif;
    font-size: 16px;
    font-weight: 400;
    position: absolute;
    left: 27px;
    top: 142px;
    width: 142px;
    height: 25px;
    }
    ._100-mts {
    color: #13aeb6;
    text-align: left;
    font-family: "Inter-Regular", sans-serif;
    font-size: 16px;
    font-weight: 400;
    position: absolute;
    left: 27px;
    top: 233px;
    width: 142px;
    height: 25px;
    }
    ._200-mts {
    color: #13aeb6;
    text-align: left;
    font-family: "Inter-Regular", sans-serif;
    font-size: 16px;
    font-weight: 400;
    position: absolute;
    left: 27px;
    top: 276px;
    width: 142px;
    height: 25px;
    }
    ._400-mts {
    color: #13aeb6;
    text-align: left;
    font-family: "Inter-Regular", sans-serif;
    font-size: 16px;
    font-weight: 400;
    position: absolute;
    left: 27px;
    top: 319px;
    width: 142px;
    height: 25px;
    }
    ._4-100-relay {
    color: #13aeb6;
    text-align: left;
    font-family: "Inter-Regular", sans-serif;
    font-size: 16px;
    font-weight: 400;
    position: absolute;
    left: 27px;
    top: 362px;
    width: 142px;
    height: 25px;
    }



    <div class="frame-3">
        <div class="event-registration-form">
        <span>
            <span class="event-registration-form-span">
            EVENT REGISTRATION
            <br />
            </span>
            <span class="event-registration-form-span2">FORM</span>
        </span>
        </div>
        <div class="fill-the-details">FILL THE DETAILS</div>
        <div class="rectangle-4"></div>
        <div class="rectangle-5"></div>
        <div class="rectangle-6"></div>
        <div class="rectangle-7"></div>
        <div class="rectangle-8"></div>
        <div class="full-name">FULL NAME</div>
        <div class="gender">GENDER</div>
        <div class="register-no">REGISTER NO</div>
        <div class="department">DEPARTMENT</div>
        <div class="rectangle-9"></div>
        <div class="register">REGISTER</div>
    </div>

  
    .frame-3,
    .frame-3 * {
    box-sizing: border-box;
    }
    .frame-3 {
    background: #ffdefd;
    width: 182px;
    height: 402px;
    position: relative;
    overflow: hidden;
    }
    .event-registration-form {
    text-align: left;
    font-family: "Inter-Regular", sans-serif;
    font-size: 15px;
    font-weight: 400;
    position: absolute;
    left: 10px;
    top: 21px;
    width: 172px;
    height: 18px;
    }
    .event-registration-form-span {
    color: #7e77fc;
    font-family: "Inter-Regular", sans-serif;
    font-size: 15px;
    font-weight: 400;
    }
    .event-registration-form-span2 {
    color: #746df9;
    font-family: "Inter-Regular", sans-serif;
    font-size: 15px;
    font-weight: 400;
    }
    .fill-the-details {
    color: #f92fe5;
    text-align: left;
    font-family: "Inter-Regular", sans-serif;
    font-size: 12px;
    font-weight: 400;
    position: absolute;
    left: 20px;
    top: 66px;
    width: 105px;
    height: 16px;
    }
    .rectangle-4 {
    background: #d9d9d9;
    width: 98px;
    height: 30px;
    position: absolute;
    left: 42px;
    top: 112px;
    }
    .rectangle-5 {
    background: #d9d9d9;
    width: 98px;
    height: 30px;
    position: absolute;
    left: 42px;
    top: 112px;
    }
    .rectangle-6 {
    background: #d9d9d9;
    width: 98px;
    height: 30px;
    position: absolute;
    left: 41px;
    top: 172px;
    }
    .rectangle-7 {
    background: #d9d9d9;
    width: 98px;
    height: 30px;
    position: absolute;
    left: 41px;
    top: 221px;
    }
    .rectangle-8 {
    background: #d9d9d9;
    width: 98px;
    height: 30px;
    position: absolute;
    left: 42px;
    top: 270px;
    }
    .full-name {
    color: #000000;
    text-align: left;
    font-family: "Inter-Regular", sans-serif;
    font-size: 11px;
    font-weight: 400;
    position: absolute;
    left: 55px;
    top: 118px;
    width: 70px;
    height: 19px;
    }
    .gender {
    color: #000000;
    text-align: left;
    font-family: "Inter-Regular", sans-serif;
    font-size: 11px;
    font-weight: 400;
    position: absolute;
    left: 58px;
    top: 181px;
    width: 67px;
    height: 15px;
    }
    .register-no {
    color: #000000;
    text-align: left;
    font-family: "Inter-Regular", sans-serif;
    font-size: 11px;
    font-weight: 400;
    position: absolute;
    left: 47px;
    top: 230px;
    width: 84px;
    height: 13px;
    }
    .department {
    color: #000000;
    text-align: left;
    font-family: "Inter-Regular", sans-serif;
    font-size: 11px;
    font-weight: 400;
    position: absolute;
    left: 51px;
    top: 275px;
    width: 80px;
    height: 18px;
    }
    .rectangle-9 {
    background: #d9d9d9;
    width: 102px;
    height: 29px;
    position: absolute;
    left: 45px;
    top: 335px;
    }
    .register {
    color: #f21518;
    text-align: left;
    font-family: "Inter-Regular", sans-serif;
    font-size: 11px;
    font-weight: 400;
    position: absolute;
    left: 60px;
    top: 344px;
    width: 71px;
    height: 13px;
    }


    <div class="frame-4">
        <div class="ellipse-1"></div>
        <div class="thank-you">THANK YOU</div>
        <div
        class="we-are-all-eagerly-waiting-for-your-participation-in-the-sports-event"
        >
        WE ARE ALL EAGERLY WAITING FOR YOUR PARTICIPATION IN THE SPORTS EVENT
        </div>
        <img class="sec-logo-3" src="sec-logo-30.png" />
    </div>

  



    .frame-4,
    .frame-4 * {
    box-sizing: border-box;
    }
    .frame-4 {
    background: #fec0ed;
    width: 192px;
    height: 397px;
    position: relative;
    overflow: hidden;
    }
    .ellipse-1 {
    background: #f8d9d9;
    border-radius: 50%;
    width: 131px;
    height: 130px;
    position: absolute;
    left: 30px;
    top: 89px;
    }
    .thank-you {
    color: #6b9cff;
    text-align: left;
    font-family: "Inter-Regular", sans-serif;
    font-size: 12px;
    font-weight: 400;
    position: absolute;
    left: 60px;
    top: 147px;
    }
    .we-are-all-eagerly-waiting-for-your-participation-in-the-sports-event {
    color: #ec103c;
    text-align: left;
    font-family: "Inter-Regular", sans-serif;
    font-size: 12px;
    font-weight: 400;
    position: absolute;
    left: 22px;
    top: 224px;
    width: 159px;
    height: 81px;
    }
    .sec-logo-3 {
    width: 200px;
    height: 29px;
    position: absolute;
    left: 0px;
    top: 13px;
    object-fit: cover;
    }

# OUTPUT:

![alt text](<web ex-9.png>)
# RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
