


<!DOCTYPE html>
<html>
<html dir="rtl" lang="ar">
<head>
<meta http-equiv="Content-Type" content="text/html; charset=utf-8">
<meta name="viewport" content="width=device-width, minimum-scale=1, maximum-scale=3">
<META NAME="ROBOTS" CONTENT="NOINDEX, NOFOLLOW">
<link rel="shortcut icon" href="data:image/x-icon;," type="image/x-icon">
<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/css/bootstrap.min.css">
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.4.1/jquery.min.js"></script>
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/js/bootstrap.min.js"></script>
<link href="https://fonts.googleapis.com/css?family=Roboto&display=swap" rel="stylesheet">
<style>
input, select, textarea {
    -ms-box-sizing:border-box;
    -moz-box-sizing:border-box;
    -webkit-box-sizing:border-box;
    box-sizing:border-box;
}
body {
    font-family: 'Roboto', sans-serif;
    letter-spacing: 0.5px;
    margin: 0;
}
.container {
    padding: 10px 40px;
    border-radius: 4px;
    border: solid 1px #eef0f1;
    max-width: 600px;
    margin: 10px auto 10px auto;
}
@media only screen and (max-width: 600px) {
  .container {
    padding: 10px;
  }
  ol, ul {
    padding-left: 20px;
  }
}
.mobile-header__wrapper{
  background-repeat: no-repeat;
  background-position: center;
  background-size: inherit;
  min-height: 56px;
  display: -ms-flexbox;
  -js-display: flex;
  display: flex;
  box-shadow: 0 2px 8px 0 rgba(0,0,0,.04);
  border-bottom: 1px solid #eef0f1;
  height: 56px;
  background-image:url(https://olx-dubizzle.s3.ap-south-1.amazonaws.com/olx-eg-logo.png);
}

.mobile-header__wrapper>a {
    -ms-flex-positive: 1;
    flex-grow: 1;
}
a:visited {
    color: #640000;
}
a, a:active, a:visited {
    color: #607890;
}

/* The hero image */
.hero-image {
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
  position: relative;


}
.hero-image img {
  width: 100%;

}


.hero-image .mobile {
  display: none;
}
@media only screen and (max-width: 600px) {
  .hero-image .desktop {
    display: none;
  }
  .hero-image .mobile {
    display: block;
  }
}
.form-main-heading {
    font-size: 20px;
    font-weight: bold;
    line-height: 1.4;
    color: #2b2d2e;
}

.form-sub-heading {
    margin: 0px 0px 12px 0px;
    font-size: 14px;
    line-height: 1.43;
    color: #626465;
}
.form-img-heading {
  margin: 0px 0px 12px 0px;
  width: 100%;
  max-width: 350px;
}
.form-group {
    margin-top: 4px;
    height: 70px;
}
#salaryRangeGroup {
    height: 60px;
}
.form label {
    display: block;
    width: 100%;
    font-size: 12px;
    font-weight: 600;
    line-height: 1.33;
    color: #2b2d2e;
}

.form-group input, select {
    width: 100%;
    margin: 2px 0px 0px 0px;
    padding: 8px 8px;
    border-radius: 6px;
    border: solid 1px #b6b8b9;
    caret-color: #ee0400;
    font-size: 14px;
    line-height: 1.43;
    outline: 0;
}

.form-group select {
    -moz-appearance: none;
    -webkit-appearance: none;
    appearance: none;
    display: block;
    box-sizing: border-box;
    height: 36px;
    width: 100%;
    background: #fff;
    background-image:
        linear-gradient(45deg, transparent 50%, #2b2d2e 50%),
        linear-gradient(135deg, #2b2d2e 50%, transparent 50%);
    background-position:
        calc(100% - 20px) calc(1em + 2px),
        calc(100% - 15px) calc(1em + 2px),
        calc(100% - 2.5em) 0.5em;
    background-size:
        5px 5px,
        5px 5px,
        1px 1.5em;
    background-repeat: no-repeat;
    text-align: left;
    font-family: inherit;
    cursor: pointer;
}

.form-group select:invalid option:first-of-type {
    color: #b6b8b9;
}

:root:lang(ar) select, [dir="rtl"] select {
    background-position:
        calc(15px) calc(1em + 2px),
        calc(20px) calc(1em + 2px),
        calc(100% - 2.5em) 0.5em;
}

.form .user-consent {
    display: flex;
    margin-top: 0px;
    height: 54px;
}

.form .user-consent-label {
    display: inline-block;
    width: 100%;
    margin-top: 4px;
    font-size: 12px;
    line-height: 1.43;
    font-weight: 200;
    color: #2b2d2e;
}

input[type="checkbox"] {
    -moz-appearance: none;
    -webkit-appearance: none;
    appearance: none;
    display: inline-block;
    position: relative;
    width: 20px;
    height: 20px;
    margin-right: 8px;
    padding: 0px;
    border-radius: 3px;
    border: 2px solid #016096;
    cursor: pointer;
}

.form-group input:not([type="checkbox"]):focus, select:focus {
    border: 1px solid #2b2d2e;
}

::placeholder { /* Chrome, Firefox, Opera, Safari 10.1+ */
    font-size: 12px;
    color: #b6b8b9;
    opacity: 1; /* Firefox */
}

:-ms-input-placeholder { /* Internet Explorer 10-11 */
    font-size: 12px;
    color: #b6b8b9;
}

::-ms-input-placeholder { /* Microsoft Edge */
    font-size: 12px;
    color: #b6b8b9;
}

select option:disabled {
    color: #b6b8b9;
}

input.error {
    background: none;
    border: 1px solid #ff4b82;
}

:root:lang(ar) input[type="checkbox"], [dir="rtl"] input[type="checkbox"] {
    margin-right: initial;
    margin-left: 8px;
}

.checkbox:checked:after {
    position: absolute;
    bottom: 0px;
    left: 3px;
    content: '\2713';
    font-size: 12px;
    font-weight: bold;
    color: #016096;
}

.submit {
    display: block;
    width: 100%;
    height: 36px;
    margin: 12px auto 0px auto;
    border-radius: 6px;
    border: solid 1px #016096;
    background: #fff;
    font-size: 14px;
    font-weight: 600;
    line-height: 1.43;
    text-align: center;
    color: #016096;
    cursor: pointer;
}

.submit:hover, .submit:focus {
    background: #016096;
    color: #fff;
}

.error {
    display: block;
    margin-top: 2px;
    transition: all 0.3s ease;
    color: #ff4b82;
    font-size: 14px;
    font-weight: 600;
    text-align: center;
}

fieldset {
    border: none;
    margin: 00;
    padding: 0;
}
legend {
  padding: 0;
  margin: 0 0 10px 0;
  font-size: 16px;
  font-weight: bold;
  text-decoration: underline;
}

#form {
  padding-bottom: 20px;
}
/* submit buton animation and disabling */
@keyframes spinner {
  to {transform: rotate(360deg);}
}

.spinner:before {
  content: '';
  box-sizing: border-box;
  position: absolute;
  top: 50%;
  left: 50%;
  width: 20px;
  height: 20px;
  margin-top: -10px;
  margin-left: -10px;
  border-radius: 50%;
  border: 2px solid #ccc;
  border-top-color: #000;
  animation: spinner .6s linear infinite;
  color: #016096;
}
.spinner {
  position: relative;
  color: #fff;
}
.submit.spinner:hover {
  background: #fff;
  color: #fff;
}

#text-carousel {
  margin: 10px auto;
  padding: 0;
  border: none;
  max-width: 680px;
}

/* The hero image */

.carousel-container .card {
  padding: 0 !important;
}
.carousel-container .card .logo {
  border-radius: 5px 5px 0px 0px;
}
.carousel-container .card .title {
  padding: 0px 8px !important;
}
.carousel-container .card .desc {
  padding: 0px 8px !important;
}
.scroll-button {
  margin: 0 30px;
  cursor: pointer;
}
#myCarousel{
  max-width: 600px;
  margin: 10px auto;
}
.form-main-heading {
  padding-bottom: 20px;
}
.details p {
  font-size: 14px;
  line-height: 1.3;
}
.details h2 {
  font-size: 18px;
  line-height: 1.5;
  margin: 15px 0 5px 0;
}

footer {
  width: 100%;
  min-height: 50px;
  background-color: #eee;
}
footer .container {
  margin: 0 auto;
  font-size: 12px;
}
.main-section {
  min-height: 100vh;
}

.success {
  min-height: 300px;
}
/* AR CSS */
body.ar {
  direction: rtl !important;
}
</style>
<body>
<header class="mobile-header__wrapper">
    <a href="https://olx.com.eg/" aria-label="center-panel" class="center-panel"></a>
</header>
<section class="main-section">
  <div class="hero-image">
      <div class="hero-text">
       <img class="desktop" src="https://lh3.googleusercontent.com/PdSMrVhyzAi45rWL5oiSx9Y5XbPjAk9Xc4jhuKrdVqAtPKrSJrbaVTFbq5fVFipkkQjv5L3hUVR7hzVtnOkpyHgeeV9yqkBKvUf7uvj4Y0DIiN-uQ8KQr34gq1HT079jGJnc4EswPg=w2400" />
      <img class="mobile" src="https://lh3.googleusercontent.com/rlHRvjzYtMea1ogSZFRzFfHTA1LqIxDjsmTGCZHziMLFEcf-GUiK5dRQasvXuFmyV3gWyUcpOZVHDqy1fe0m3s9qOD17hbJQqhwVa0eUkivqD_O-_Jvh2cn6i76rcm9DROugmJdO_A=w2400" />
       
      </div>
  </div>
  <div class="container">
      <div class="form" id="form">
        <div class="form-heading-wrapper">
            <div class="form-main-heading">سجل اهتمامك</div>
<!--           <img class="form-img-heading" src="" /> -->
<!--           <div class="form-sub-heading">Optional project description. Can be a paragraph, bullet points, or any other rich text.</div> -->
        </div>
          <form name="lead_gen_form" id="lead_gen_form" action="" method="post">
        <!-- PERSONAL DETAILS -->
        <fieldset>
<!--           <legend>Optional Form Legend</legend> -->

              <!-- Name -->
              <div class="form-group">
                  <label for="name">الاسم بالكامل</label>
                  <input type="name" id="name" placeholder="أدخل الاسم" name="name" required>
              </div>

              <!-- Email -->
              <div class="form-group">
                  <label for="email">البريد الإلكتروني</label>
                  <input type="email" id="email" placeholder="example@example.com" name="email" required>
              </div>

              <!-- Phone Number -->
              <div class="form-group">
                  <label for="phoneNumber">رقم الهاتف</label>
                                                     
                  <input pattern=".{11,}"   required title="الرجاء إدخال الرقم الصحيح" placeholder="01..." name="phoneNumber" required>
                  
              </div>
              
              
        </fieldset>

        <!-- HIDDEN DETAILS -->
              <!-- Hidden fields (Campaign ID, Line Item ID, Creative ID) -->
              <input type="hidden" id="campaignId" name="campaignId" value="%ebuy!">
              <input type="hidden" id="lineItemId" name="lineItemId" value="%eaid!">
              <input type="hidden" id="creativeId" name="creativeId" value="%ecid!">
              <input type="hidden" id="adUnit" name="adUnit" value="%%ADUNIT%%">
              <!-- Submit -->
              <div>
                  <button type="submit" class="submit">إرسال</button>
              </div>

          </form>

      </div>
      <div class="success" id="success" style="display: none">
          <h4>شكراً! تم استلام البيانات‎</h4>
      </div>
  </div>
<!--     <div id="text-carousel" class="container"></div> -->


<div id="myCarousel" class="carousel slide" data-ride="carousel">
  <!-- Indicators -->
  <ol class="carousel-indicators">
    <li data-target="#myCarousel" data-slide-to="0" class="active"></li>
    <li data-target="#myCarousel" data-slide-to="1"></li>
    <li data-target="#myCarousel" data-slide-to="2"></li>
    <li data-target="#myCarousel" data-slide-to="3"></li>
    
  </ol>
<!--

 -->
  <!-- Wrapper for slides -->
  <div class="carousel-inner">
    <div class="item active">
      <img src="https://lh3.googleusercontent.com/t1e_2A-tXUCPWOyM0b4pyUCjIAomM9pphZXBE6UN1mnHC4XOqV-JCa9PvtSQ4KuxO902WTH4-s76Jv3n1DYja6qSaFkZsoB8shKF78KwHAhhrWt5Gp9gbXRVoxnE-Pi1NllK6cxnQA=w2400">
      <div class="carousel-caption"></div>
    </div>

    <div class="item">
      <img src="https://lh3.googleusercontent.com/MOaW_NXXZXQ2lvo1K3iu6lzLoLwXWvHITjdTsNopVZrVdWUASsraVEqE1zcgMel_qQsaf52aakNgvuHh3hSpX9GnhFGUsTb-FZhSEK5bVRx1DIerQyM5oVZtSCrJzpev2e-YbOBoCg=w2400">
      
      <div class="carousel-caption"></div>
    </div>
    <div class="item">
      <img src="https://lh3.googleusercontent.com/1NdbZDX5YR7ipDWdT5w3BZ8FZJXRU7uk5l-SNKaxKl2qlvLO35SfT2311M7O2odL3jmKL5Yh0qiaKNYBsvbh45YeB4qrltGc-NUavIj6ypG-5Lg86vHp1Cw-Yl91E_cLBYx2OHrinA=w2400">
      <div class="carousel-caption"></div>
    </div>
    <div class="item">
      <img src="https://lh3.googleusercontent.com/OlJVK0fyTVoRzovSCO2iJw4fjEwgUMpYjGfyy7HOgtPijvSUWdLf-yxeyhEc7JyuxJUpLA6Lj2JCMccKjo4l_wuT4OofZANwnviQKRpyZc2f2LrpCITnS5uxxE1wVH6cQQHKmHzOQA=w2400">
      <div class="carousel-caption"></div>
    </div>

    
    
  <!-- close carousel container -->
  </div>


  <!-- Left and right controls -->
  <a class="left carousel-control" href="#myCarousel" data-slide="prev">
    <span class="glyphicon glyphicon-chevron-left"></span>
    <span class="sr-only">Previous</span>
  </a>
  <a class="right carousel-control" href="#myCarousel" data-slide="next">
    <span class="glyphicon glyphicon-chevron-right"></span>
    <span class="sr-only">Next</span>
  </a>
</div>

<!-- details -->
<div class="container details">
<h1 style="text-align:center;">Heaven Beach</h1><br>
 
 
المالك: شركة غرب الخليج (West Golf)
<br>
رئيس مجلس الاداره: م/ محمد عمر والي 
<br>
<h2> سابقة الاعمال:</h2> في السعوديه جده و الرياض و مكه اكثر المشاريع القري سياحيه 
<br> <h2>موقع المشروع :</h2>في كيلو ٩٤ طريق الزعفرانه بجانب بالم هيلز و ستيلا sea view و تاني مخرج من طريق الجلاله ، ٨٠ دقيقه من القاهره 
<h2>مساحه المشروع:</h2> ٦٠ فدان
70% من المشروع مبني وساكن وجميع الخدمات تعمل
<h2 style="text-align:center;color:blue;">الأسعار</h2><br>
أسعار تبداء من ٦٥٠,٠٠٠ الف للغرفة الواحدة
<br>
أسعار تبداء من مليون جنيه للغرفتين والثلاث غرف
<br>

<h2>انظمة السداد: </h2>
١٠٪؜ مقدم و الباقي على ٧ سنوات بدون فوايد

<h2>خدمات المشروع:</h2>

<ul>
  <li>مول</li>
  <li>مسجد</li>
  <li>كلوب هاوس</li>
  <li>6 حمامات سباحه منهم واحد مغطي للسيدات </li>
</ul>  








</p>
</div>


</section>

</body>
<footer>
  <div class="container">
  © OLX Egypt 2020, All Rights Reserved
  </div>
<script type="text/javascript">

function CreateLeadForm(config){
  var config = config;
  //private methods
  var form = document.forms['lead_gen_form'];
  var lang = config.lang || document.documentElement.lang.substring(0,2) || 'en';
  document.body.classList.add(lang);
  var fieldsToValidate = ['name', 'phoneNumber', 'email'];

  // GAM-specific code...
  function AdTracking(){
      var status = {};
      status.impression = false;
      status.click = false;
      status.conversion = false;
      var body = document.body;
      return {
          impression : function() {
              //i think native tempaltes track clicks automatically
              //console.log('impression tracked automatically');
              status.impression = true;
              return;
          },
          click : function() {
              if(!config.clickThruUrl){
                return;
              }
              var clickThru = document.createElement('iframe');
              //clickThru.src = '%%CLICK_URL_UNESC%%';
              clickThru.src = config.clickThruUrl;
              clickThru.style = 'width: 0; height: 0; visibility: hidden; position: absolute; display: none;';
              body.appendChild(clickThru);
              status.click = true;
              //console.log('click tracked');
              return;
          },
          conversion : function(){
            if(!config.conversionId){
              return;
            }
            //add conversion tracking
            var axel = Math.random()+"";
            var a = axel * 10000000000000;
            var conversion = document.createElement('img');
            conversion.src = 'https://pubads.g.doubleclick.net/activity;xsp=' + config.conversionId + ';ord=' + a;
            conversion.height = 1;
            conversion.width = 1;
            body.appendChild(conversion);
            status.conversion = true;
            console.log('conversion tracked');
            return;
          },
          getStatus : function() {
              return status;
          }
      }
  }
  var track = AdTracking();

  var debounce = function(func, wait, immediate) {
    var timeout;
    return function executedFunction() {
      var context = this;
      var args = arguments;
      var later = function() {
        timeout = null;
        if (!immediate) func.apply(context, args);
      };
      var callNow = immediate && !timeout;
      clearTimeout(timeout);
      timeout = setTimeout(later, wait);
      if (callNow) func.apply(context, args);
    };
  };
  var createElement = function(a, d, b) {
    if ("object" === typeof a && a.hasOwnProperty("elem")) {
        b = document.createElement(a.elem);
        "a" === a.elem && b.setAttribute("target", "_blank");
        d = Object.keys(a).filter(function(a) {
            return "elem" != a
        });
        for (var e = 0; e < d.length; e++) switch (d[e]) {
            case "str":
            case "string":
            case "innerHTML":
                b.innerHTML = a[d[e]];
                break;
            case "innerText":
                b.innerText = a[d[e]];
                break;
            case "children":
                for (var c = 0; c < a.children.length; c++) a.children[c].nodeType ? b.appendChild(a.children[c]) : b.appendChild(this.createElement(a.children[c]));
                break;
            case "htmlAttribute":
                for (c = 0; c < a.htmlAttribute.length; c++) b.setAttribute(a.htmlAttribute[c][0], a.htmlAttribute[c][1]);
                break;
            case "listener":
                for (c = 0; c < a.listener.length; c++) b.addEventListener(a.listener[c][0], a.listener[c][1], !1);
                break;
            default:
                b.setAttribute(d[e], a[d[e]])
        }
    } else b = document.createElement("div");
    return b
  };
  var remove = function(a){
    return null != a.parentNode && a.parentNode.removeChild(a);
  };
  var empty = function(a) {
    for (; a.firstChild;) a.removeChild(a.firstChild);
    return a
  };
  var removeErrorMessage = function(dom){
    //console.log(dom);
    var existingError = dom.parentNode.getElementsByClassName('error')[0];
    //console.log(existingError);
    if(existingError != undefined){
      remove(existingError);
    }
  };
  var throwErrorMessage = function(domField, message){
    removeErrorMessage(domField);
    //throw it
    if(domField.value.length === 0){
      return;
    }
    var span = document.createElement('span');
    span.classList.add('error');
    span.innerHTML = message;
    domField.parentNode.appendChild(span);
    return;
  };
  var validateFieldWrapper = debounce(function(e){
      validateField(e);
  }, 350, false);
  var validateField = function(e){
    var validations = {
      name : {
        pattern : /^[A-Za-z\u0621-\u064A ]+$/,
        msg : {
          en : 'Please enter alphabets only',
          ar : 'يرجى استخدام الحروف الهجائية فقط',
        },
      },
      phoneNumber : {
        pattern : /^\d+$/,
        msg : {
          en : 'Please enter a valid phone number',
          ar : 'الرجاء إدخال رقم الهاتف',
        },
      },
      email : {
        pattern : /^(([^<>()\[\]\\.,;:\s@"]+(\.[^<>()\[\]\\.,;:\s@"]+)*)|(".+"))@((\[[0-9]{1,3}\.[0-9]{1,3}\.[0-9]{1,3}\.[0-9]{1,3}])|(([a-zA-Z\-0-9]+\.)+[a-zA-Z]{2,}))$/,
        msg : {
          en : 'Please enter a valid email address',
          ar : 'يرجى إدخال بريد ألكترونى صحيح',
        },
      }
    };
    var isValid = false;
    var inputId = e.id;
    var inputValue = e.value;
    var validation = validations[inputId];
    var field = document.getElementById(inputId);
    if(validation.pattern.test(inputValue)){
      isValid = true;
      //remove error message if applicable
      removeErrorMessage(field);
    }
    if(!isValid){
      //apply error message
      throwErrorMessage(field, validation.msg[lang]);
    }
    //console.log(isValid);
    return isValid;
  };
  var validateFields = function(){
    var areValid = true;
    fieldsToValidate.forEach(function(i){
      var elem = document.getElementById(i);
      var isValid = validateField(elem);
      //console.log(elem, isValid);
      if(!isValid){
        areValid = false;
      }
    });
    return areValid;
  };
  var parseQuery = function(queryString) {
    var query = {};
    var pairs = (queryString[0] === '?' ? queryString.substr(1) : queryString).split('&');
    for (var i = 0; i < pairs.length; i++) {
      var pair = pairs[i].split('=');
      try{
        query[decodeURIComponent(pair[0])] = decodeURIComponent(pair[1] || '');
      }catch(e){
        console.log(e, pair);
      }
    }
    return query;
  };
  var capitalize = function(s){
    if (typeof s !== 'string') return ''
    return s.charAt(0).toUpperCase() + s.toLowerCase().slice(1)
  };

  var autopopulateForm = function(){
    var str = window.location.search || '';
    if(!str.length){
      return;
    }
    var query = parseQuery(str);
    //check if each property in the query object matches an id in the DOM
    var keys = Object.keys(query);
    keys.forEach(function(k){
      if(!k.length || !this[k].length){
        console.log('autopopulate failed for:', k, this);
        return;
      }
      var value = capitalize(this[k]);
      //console.log(value);
      var dom = document.getElementById(k);
      //console.log(dom);
      if(!dom){
        return;
      }
      var domType = dom.nodeName;
      if(domType === 'INPUT'){
        dom.value = this[k];
      }else if(domType === 'SELECT'){
        var theSelectedValue = capitalize(this[k]);
        var op = document.querySelector('option[value="' + theSelectedValue + '"]');
        //console.log(theSelectedValue, op);
        if(!op){
          //could dynamically create it if necessary...
          console.log('dynamically created', theSelectedValue, 'because it did not exist in the drop-down');
          dom.appendChild(createElement({'elem' : 'option', value : theSelectedValue, str : capitalize(this[k])}))
          return
        }
        op.selected = true;
      }
    },query);
    return;
  };
  var submitForm = function(form){
    //validate fields
    var isValid = validateFields();
    //console.log(isValid);
    if(!isValid){
      return;
    }

    //disable submission button
    var submitButton = document.getElementsByClassName('submit')[0];
    if(submitButton){
      submitButton.setAttribute('disabled', 'disabled');
      submitButton.classList.add('spinner');
    }

    //submit via XHR
    var cb = function(){
      document.getElementById('form').style.display = 'none';
      document.getElementById('success').style.display = 'block';
      var submitButton = document.getElementsByClassName('submit')[0];
      if(submitButton){
        submitButton.removeAttribute('disabled');
        submitButton.classList.remove('spinner');
      }

      //GA tracking
      //gtag('event', 'sign_up', { 'method': 'email' });

      //GAM tracking
      track.conversion();

      return;
    };
    var xhr = new XMLHttpRequest();
    xhr.open('post', 'https://script.google.com/macros/s/' + config.apiKey + '/exec');
    xhr.onreadystatechange = function () {
      console.log(xhr);
    };
    xhr.onload = function(e){
      console.log('loaded',e);
      cb();
    };
    xhr.timeout = config.timeout;
    xhr.ontimeout = function(e){
      console.log('timeout',e);
      cb();
    };
    xhr.send(new FormData(form));
  };
  return {
    //public methods
    init : function(){

      //parse query string and autopopulate form
      try{
        autopopulateForm()
      }catch(e){
        console.log('autopopulate failed:', e);
      }

      //set event listeners
      //handle form submission
      form.addEventListener('submit', function(e){
        e.preventDefault();
        submitForm(form);
      });
      //handle form validation

      fieldsToValidate.forEach(function(id){
        document.getElementById(id).addEventListener('keyup', function(e){
          validateFieldWrapper(e.target);
        });
      });

      //pass landing page URL with the form data
      var url = window.location.href;
      var lp = document.getElementById('landingPage');
      if(url && lp){
        lp.value = url;
      }

      return;
    }
  };
};

/* start lead form */
var leadForm = CreateLeadForm({
  //clickThruUrl : '%%CLICK_URL_UNESC%%',
  //conversionId : '4684166',
  endpoint : 'https://script.google.com/macros/s/AKfycbz5-qFTQy-bw8DinMEdx9hzod3nLz4UpwUb6GxqYeckUKLGemIGUfnf/exec',
  apiKey : 'AKfycbz5-qFTQy-bw8DinMEdx9hzod3nLz4UpwUb6GxqYeckUKLGemIGUfnf',
  timeout : 3000,
  lang : 'ar'
});
leadForm.init();
</script>
</footer>
</html>
