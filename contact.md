---
layout: page
title: Contact
permalink: /contact/
img: ducngocapple-logo.jpg
---


Gửi thắc mắc cho cửa hàng


<form id="contact-form" class="form-horizontal" action="//formspree.io/chaudanghuy@gmail.com" method="POST" enctype="multipart/form-data">
       <fieldset>
       
            <div class="form-group">
                <label class="col-lg-2 control-label" for="name">Tên:</label>
                <div class="col-lg-10">
                <input type="text" placeholder="Your name" id="name" class="form-control" name="name" tabindex="1"/>
                </div>
            </div>
            <div class="form-group">
                <label class="col-lg-2 control-label" for="email">Email:</label>
                <div class="col-lg-10">
                <input type="email" placeholder="Your email" id="email" class="form-control" name="email" tabindex="2"/>
                </div>
            </div>
            <div class="form-group">
                <label class="col-lg-2 control-label" for="message">Nội dung:</label>
                <div class="col-lg-10">
                <textarea class="contact-textarea" placeholder="Your message" class="form-control" rows="4" id="message" name="message" tabindex="3"></textarea>
                </div>
            </div>
            
           <div class="form-group"> 
           <div class="col-lg-10 col-lg-offset-2">  
         <input type="submit" class="btn btn-primary" value="Send" id="submit"/>
         </div>
         </div>
        <input type="hidden" name='redirect_to' value="http://ducngoco2.com/thank-you/" />
    </fieldset>  
</form>