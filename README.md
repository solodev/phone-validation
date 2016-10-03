# phone-validation
Forms are only as good as the integrity of the data they accept and that's where validation comes in. There are various kinds of validation. In one case, you may just want to make sure the email input was filled out. In another, you want it filled out and to make sure it is valid and contains an @ symbol. 

What you don't see often is telephone number validation because it's difficult. Not anymore. In this tutorial, [Solodev](https://www.solodev.com/) will teach you how to add validation to your phone number input fields using jQuery.

## Tutorial

View detailed instructions in Solodev's [Validating Phone Numbers with JavaScript](https://www.solodev.com/blog/web-design/validating-phone-numbers-with-javascript.stml) article.

## Demo

Try out a working example on [JSFiddle](https://jsfiddle.net/solodev/5fn1owy9/).

## HTML

The form for phone number validation contains the following basic HTML markup.

```
<div class="container">
<div class="well">
   <div class="row">
      <div class="col-md-3">
         <label class="control-label">Country:</label>
         <div class="country"></div>
      </div>
      <div class="col-md-3">
         <input type="tel" class="tel form-control" pattern="\d*" x-autocompletetype="tel" placeholder="Mobile Phone Number" autofocus>
      </div>
      <div class="col-md-6">
      </div>
   </div>
   </div>
</div>
```

## CSS

All required CSS is in phone-validate.css

## External Includes

This tutorial requires the following third party resources.

```
<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Open+Sans+Condensed:300">
<link rel="stylesheet" href="phone-validate.css">

<script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"></script>
<script src="https://ajax.googleapis.com/ajax/libs/jquery/1.12.4/jquery.min.js"></script>
<script src="https://cdn.jsdelivr.net/jquery.caret/0.1/jquery.caret.js"></script>
<script src="https://www.solodev.com/assets/phone/jquery.mobilePhoneNumber.js"></script>
```
