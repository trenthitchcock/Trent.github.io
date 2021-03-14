html
<div class="mobile">
    <div class="phone">
       <div class="phone-mirror">
           <div class="topWrapper">
               <div class="camera"></div>
               <div class="line-rec"></div>
           </div>
           <img src="../images/oppo.png" alt="oppo" height="535" width="312">
        </div>
    </div>
  </div>

css 
html, body {     width: 100%;
    font-size: 16px;
    box-sizing: border-box;
}
body {
    margin: 0;
    padding: 0;
    line-height: 1.6;
    background-color: white;
}
.mobile {
    height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
}
.phone {
    display: flex;
    justify-content: center;
    align-items: center;
    width: 331px;
    height: 616px;
    background: blue;
    border-radius: 30px;
    padding: 10px;
}
.phone-mirror {
    position: relative;
    width: 328px;
    height: 600px;
    background-color: rgb(26, 25, 25);
    border-radius: 30px;
}
.topWrapper {
    position: relative;
    width: 130px;
    height: 20px;
    margin: 0px auto 0 auto;
    float: left;
    left: 30%;
    background-color: black;
    border-radius: 0 0 45px 45px;
}
.line-rec {
    position: relative;
    width: 60px;
    height: 6px;
    margin: 0px auto 0 auto;
    float: left;
    left: 20%;
    top: 4px;
    background-color: rgb(83, 83, 82);
    border-radius: 5px;
    border: 1px solid rgb(214, 214, 214);
}
.camera {
    position: relative;
    float: left;
    margin-right: 8px;
    left: 18%;
    width: 11px;
    height: 11px;
    top: 1px;
    background-color: rgb(83, 83, 82);
    border-radius: 30px;
    border: 1px solid rgb(214, 214, 214);
}
.buttons {
    background-color: black;
    width: 100%;
    height: 30px;
    border-radius: 0 0 45px 45px;
}
