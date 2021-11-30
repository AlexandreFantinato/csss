.pricing-table {
  display: block;

}
.pricing-table .card {
  font-size: 16px;
  width: 400px;
  height: 450px;
  padding: 30px;
  border-radius: 1.5rem;
  display: -webkit-box;
  display: flex;
  -webkit-box-orient: vertical;
  -webkit-box-direction: normal;
  flex-direction: column;
  -webkit-box-align: center;
  align-items: center;
  position: relative;
  overflow: hidden;
  box-shadow: 2px 2px 10px -4px rgba(0, 0, 0, 0.6);
  -webkit-transition: all 0.2s ease-in-out;
  transition: all 0.2s ease-in-out;
  background: #333745;
  color: #fff;
  font-family: "Open Sans", sans-serif;
  font-weight: bold;
  text-transform: uppercase;
  text-shadow: 2px 2px 2px rgba(51, 55, 69, 0.6);
}

.pricing-table .card:nth-child(1) {
  background: #7f7fd5;
  background: -webkit-gradient(linear, right top, left top, from(#076c93), color-stop(#86a8e7), to(#7f7fd5));
  background: #03bcd8;
}

.pricing-table .card:nth-child(1) .price::before {
  content: "";

}
.pricing-table .card:nth-child(2) {
  margin: 0 20px;
  width: 250px;
  height: 400px;
  background: #ff416c;
  background: -webkit-gradient(linear, left top, right top, from(#ff4b2b), to(#ff416c));
  background: linear-gradient(to right, #ff4b2b, #ff416c);

}

}
.pricing-table .card:nth-child(1) .buy-button h3, .pricing-table .card:nth-child(3) .buy-button h3 {
  font-size: 1rem;
}


.pricing-table .card .type {
  font-size: 18px;
  font-weight: bold;
  margin-top: 10px;
  margin-bottom: 10px;
  text-align: center;
  border-bottom: 3px solid rgba(255, 255, 255, 0.2)


}
.pricing-table .card .price {
  font-size: 7.5rem;
  position: relative;
  margin: 15px 0px 20px;

}

.pricing-table .card .price::before {
  position: absolute;
  content: "";
  color: rgba(255, 255, 255, 0.06);
  font-size: 9.5rem;
  right: -30%;
  bottom: 15%;
  text-shadow: 0 0 0px rgba(51, 55, 69, 0);
  -webkit-transition: all 1s ease-in-out;
  transition: all 1s ease-in-out;


}
.pricing-table .card .plan {
  position: relative;
  font-weight: bold;
  font-size: 16px;
  margin-bottom: 25px;

}
.pricing-table .card .plan::before, .pricing-table .card .plan::after {
  position: absolute;
  content: "➥";
  width: 15px;
  height: 8.5px;
 
  bottom: 30%;
  -webkit-transition: all 0.5s ease-out;
  transition: all 0.2s ease-out;

}
.pricing-table .card .plan::before {
  right: 100%;
  -webkit-transform: translate(-90%, -90%);
          transform: translate(-90%, -90%);

}
.pricing-table .card .plan::after {
  display: none;

}

.pricing-table .card .details li {
  margin: 25px 0px;

}


.pricing-table .card .buy-button {
  cursor: pointer;
  position: absolute;
  width: 280px;
  height: 175px;
  background: white;
  border-radius: 10%;
  right: -30%;
  bottom: -27%;
  -webkit-transition: all 0.5s ease-in-out;
  transition: all 0.5s ease-in-out;

}
.pricing-table .card .buy-button h3 {
  text-shadow: 0 0 0;
  text-decoration: none;
  color: black;
  position: absolute;
  left: 7%;
  top: 10%;
  color: #333745;
  font-size: 14px;
  -webkit-transition: all 0.5s ease-in-out;
  transition: all 0.5s ease-in-out;

}
.pricing-table .card:hover {
  -webkit-transform: scale(1.02);
          transform: scale(1.02);

}
.pricing-table .card:hover .price::before {
  -webkit-animation: text-hover 1s ease-in-out infinite normal;
  animation: text-hover 1s ease-in-out infinite normal;

}
.pricing-table .card:hover .plan::before {
  right: 95%;

}

.pricing-table .card:hover .buy-button {
  width: 100%;
  right: 0%;
  border-radius: 0%;

}

.squad{
border-radius: 5px;
border: 1px solid rgba(255, 255, 255, 0.5);
padding: 2px;
margin: 1px;
}

