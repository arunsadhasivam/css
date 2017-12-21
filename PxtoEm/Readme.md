
when chaning the <p> property   
  
  root tag like in case h2 or p (implicit  root tag). since in css it default pick up px . 
Even I added margin-bottom-15px or 0.9375em it is not picking up.it default pickup px default property.
Only if in override this my class section h2 to px it works. 



p {
		font-size: 16px;
	}
  
  body {
    font-size: 18px;
    max-width: 1440px;
    margin-left: auto;
    margin-right: auto;

}


h2 {
  font-size: 24px;

  font-weight: 700; }


section h2 {
      margin-bottom: 0.9375em; }

}
  
  Above it is not working since p is default implicit tag which default picking px . 
