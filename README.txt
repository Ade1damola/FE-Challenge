 <div class="container bottom">
        <div class="row">
            <div class="column">
                <div class="logo">
                    <img src="images/Logo.svg" alt="logo"><span >TechFin<span>
                </div>
                <br><br>
                <p>
                    Lorem ipsum dolor sit amet, <br> consectetur adipiscing elit. <br> Posuere viverra nec, sit est, <br> tellus habitant. 
                </p>
            </div>
            <div class="column">
                <h6>COMPANY</h6>
                <ul>
                    <li><a href="#">About</a></li>
                    <li><a href="#">FAQ</a></li>
                    <li><a href="#">Contact Us</a></li>
                    <li><a href="#">Careers</a></li>
                    <li><a href="#">Privacy Policy</a></li>
                </ul>
            </div>
            <div class="column">
                <h6>PRODUCTS</h6>
                <ul>
                    <li><a href="#">Features</a></li>
                    <li><a href="#">Connect</a></li>
                    <li><a href="#">Pricing</a></li>
                    <li><a href="#">Download</a></li>
                </ul>
            </div>
            <div class="column">
                <h6>NEED HELP</h6>
                <ul>
                    <li><a href="#">+234 81 333 0965</a></li>
                </ul>
    
                <h6>NEED SUPPORT</h6>
                <ul><li><a href="#">hi@mosessmax.com</a></li></ul>
            </div>
            <div class="column">
                <h6>FOLLOW US</h6>
                <ul class="social">
                    <li><a href="#"><img src="images/twitter.svg" alt=""></a></li>
                    <li><a href="#"><img src="images/insta.svg" alt=""></a></li>
                    <li><a href="#"><img src="images/linkedin.svg" alt=""></a></li>
                </ul>
    
                <label class="form">
                    <input type="text" placeholder="Enter your email address"><button><a href="#">GO</a></button>
                </label>
            </div>
        </div>




        .bottom{
 
  margin-top: 50px;
}
 
.row{
  display: flex;
  /* flex-wrap: wrap; */
}

/* .column{
  width: 20%;
} */

.bottom a{
  text-decoration: none;
  color: #fff;
}

.bottom a:hover{
  color: #6D6D6D;
}

.column ul{
  list-style: none;
  font-weight: 500;
  font-size: 14px;
  text-align: left;
  padding: 0;
  margin: 20px 0px;
}

.column ul li{
  padding: 15px;
}

.logo span{
  font-weight: 700;
  font-size: 24px;
}



.social{
  display: flex;
  justify-content: space-evenly;
  align-items: center;
}

label{
  position: relative;
  width: 100%;
}

input{
  background-color: #26262B;
  height: 50px;
  width: 100%;
  font-size: 12px;
  font-weight: 500;
  text-align: center;
  border: none;
  border: none;
  box-shadow: #495057;
}

.form button{
  position: absolute;
  top: 0;
  bottom: 0;
  right: 0;
  width: 80px;
  background-color: #6D6D6D;
  border: #6D6D6D;
  font-size: 12px;
}
