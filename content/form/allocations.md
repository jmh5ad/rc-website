+++
date = "2016-12-31T23:59:16-05:00"
tags = ["search"]
categories = ["forms"]
images = [""]
author = "Staff"
description = ""
title = "Allocation Requests"
draft = false
type = "form"

+++


<ul class="nav nav-tabs" id="myTab" role="tablist">
  <li class="nav-item">
    <a class="nav-link active" id="home-tab" data-toggle="tab" href="#home" role="tab" aria-controls="home" aria-selected="true">Home</a>
  </li>
  <li class="nav-item">
    <a class="nav-link" id="profile-tab" data-toggle="tab" href="#profile" role="tab" aria-controls="profile" aria-selected="false">Profile</a>
  </li>
  <li class="nav-item">
    <a class="nav-link" id="contact-tab" data-toggle="tab" href="#contact" role="tab" aria-controls="contact" aria-selected="false">Contact</a>
  </li>
</ul>
<div class="tab-content" id="myTabContent">
  <div style="padding:2rem;border-left:1px solid #ccc;border-right:1px solid #ccc;border-bottom:1px solid #ccc;" class="tab-pane fade show active" id="home" role="tabpanel" aria-labelledby="home-tab">
    <form action="https://api.uvarc.io/rest/general-support-request/" method="post" id="allocation-form" accept-charset="UTF-8">
      <div class="form-item form-group form-item form-item-submitted-name form-type-textfield form-group">
        <label class="control-label" for="edit-submitted-name">Name <span class="form-required" title="This field is required.">*</span></label>
        <input required="required" class="form-control form-text required" type="text" id="name" name="name" value="" size="60" maxlength="128" readonly />
        <input class="form-control form-text required" type="hidden" id="category" name="category" value="Rivanna HPC">
        <input class="form-control form-text required" type="hidden" id="allocation_type" name="Allocation Type" value="Request or Renew a Standard Allocation">
      </div>
      <div class="row">
        <div class="col form-item form-group form-item form-item-submitted-e-mail form-type-webform-email form-group"> <label class="control-label" for="email">E-mail <span class="form-required" title="This field is required.">*</span></label>
          <input required="required" class="email form-control form-text form-email required" type="email" id="email" name="email" value="" size="60" readonly />
        </div>
        <div class="col form-item form-group form-item form-item-submitted-computing-id form-type-textfield form-group"> <label class="control-label" for="uid">Computing ID <span class="form-required" title="This field is required.">*</span></label>
          <input required="required" class="form-control form-text required" type="text" id="uid" name="uid" value="" size="20" maxlength="20" readonly />
        </div>
      </div>
    </div>
    <div style="padding:2rem;border-left:1px solid #ccc;border-right:1px solid #ccc;border-bottom:1px solid #ccc;" class="tab-pane fade" id="profile" role="tabpanel" aria-labelledby="profile-tab">
    <form action="https://api.uvarc.io/rest/general-support-request/" method="post" id="allocation-form" accept-charset="UTF-8">
      <div class="form-item form-group form-item form-item-submitted-name form-type-textfield form-group">
        <label class="control-label" for="edit-submitted-name">Name <span class="form-required" title="This field is required.">*</span></label>
        <input required="required" class="form-control form-text required" type="text" id="name" name="name" value="" size="60" maxlength="128" readonly />
        <input class="form-control form-text required" type="hidden" id="category" name="category" value="Rivanna HPC">
        <input class="form-control form-text required" type="hidden" id="allocation_type" name="Allocation Type" value="Request or Renew a Standard Allocation">
      </div>
      <div class="row">
        <div class="col form-item form-group form-item form-item-submitted-e-mail form-type-webform-email form-group"> <label class="control-label" for="email">E-mail$
          <input required="required" class="email form-control form-text form-email required" type="email" id="email" name="email" value="" size="60" readonly />
        </div>
        <div class="col form-item form-group form-item form-item-submitted-computing-id form-type-textfield form-group"> <label class="control-label" for="uid">Comput$
          <input required="required" class="form-control form-text required" type="text" id="uid" name="uid" value="" size="20" maxlength="20" readonly />
        </div>
      </div>
    </div>
    <div style="padding:2rem;border-left:1px solid #ccc;border-right:1px solid #ccc;border-bottom:1px solid #ccc;" class="tab-pane fade" id="contact" role="tabpanel" aria-labelledby="contact-tab">
    <form action="https://api.uvarc.io/rest/general-support-request/" method="post" id="allocation-form" accept-charset="UTF-8">
      <div class="form-item form-group form-item form-item-submitted-name form-type-textfield form-group">
        <label class="control-label" for="edit-submitted-name">Name <span class="form-required" title="This field is required.">*</span></label>
        <input required="required" class="form-control form-text required" type="text" id="name" name="name" value="" size="60" maxlength="128" readonly />
        <input class="form-control form-text required" type="hidden" id="category" name="category" value="Rivanna HPC">
        <input class="form-control form-text required" type="hidden" id="allocation_type" name="Allocation Type" value="Request or Renew a Standard Allocation">
      </div>
      <div class="row">
        <div class="col form-item form-group form-item form-item-submitted-e-mail form-type-webform-email form-group"> <label class="control-label" for="email">E-mail$
          <input required="required" class="email form-control form-text form-email required" type="email" id="email" name="email" value="" size="60" readonly />
        </div>
        <div class="col form-item form-group form-item form-item-submitted-computing-id form-type-textfield form-group"> <label class="control-label" for="uid">Comput$
          <input required="required" class="form-control form-text required" type="text" id="uid" name="uid" value="" size="20" maxlength="20" readonly />
        </div>
      </div>
    </div>
</div>


<div style="width:100%;height:40px;"></div>

<ul class="nav nav-tabs">
  <li class="nav-item">
    <a class="nav-link active" href="">Standard</a>
  </li>
  <li class="nav-item">
    <a class="nav-link" href="">Purchase</a>
  </li>
  <li class="nav-item">
    <a class="nav-link" href="">Dean's</a>
  </li>
  <li class="nav-item">
    <a class="nav-link" href="">Instructional</a>
  </li>
</ul>

<form action="https://api.uvarc.io/rest/general-support-request/" method="post" id="allocation-form" accept-charset="UTF-8">
<p id="form_post_response"></p>

<div style="padding:2rem;margin-top:-1rem;border-left:1px solid #ccc;border-right:1px solid #ccc;border-bottom:1px solid #ccc;">
  <div class="form-item form-group form-item form-item-submitted-name form-type-textfield form-group">
    <label class="control-label" for="edit-submitted-name">Name <span class="form-required" title="This field is required.">*</span></label>
    <input required="required" class="form-control form-text required" type="text" id="name" name="name" value="" size="60" maxlength="128" readonly />
    <input class="form-control form-text required" type="hidden" id="category" name="category" value="Rivanna HPC">
    <input class="form-control form-text required" type="hidden" id="allocation_type" name="Allocation Type" value="Request or Renew a Standard Allocation">
  </div>

  <div class="row">
    <div class="col form-item form-group form-item form-item-submitted-e-mail form-type-webform-email form-group"> <label class="control-label" for="email">E-mail <span class="form-required" title="This field is required.">*</span></label>
      <input required="required" class="email form-control form-text form-email required" type="email" id="email" name="email" value="" size="60" readonly />
    </div>
    <div class="col form-item form-group form-item form-item-submitted-computing-id form-type-textfield form-group"> <label class="control-label" for="uid">Computing ID <span class="form-required" title="This field is required.">*</span></label>
      <input required="required" class="form-control form-text required" type="text" id="uid" name="uid" value="" size="20" maxlength="20" readonly />
    </div>
  </div>

  <div class="form-item form-group form-item form-type-select form-group"> <label class="control-label" for="classification">Classification <span class="form-required" title="This field is required.">*</span></label>
    <select required="required" class="form-control form-select required" title="Faculty, postdoctoral associates, and full-time research staff are eligible to request allocations.  " data-toggle="tooltip" id="classification" name="classification"><option value="" selected="selected">- Select -</option><option value="faculty">Faculty</option><option value="staff">Staff</option><option value="postdoc">Postdoctoral Associate</option><option value="other">Other</option></select>
  </div>

  <div class="form-item form-group form-item form-type-textfield form-group"> <label class="control-label" for="department">Department <span class="form-required" title="This field is required.">*</span></label>
    <input required="required" class="form-control form-text required" type="text" id="department" name="department" value="" size="60" maxlength="128" />
  </div>

  <div class="form-item form-group form-item form-type-textfield form-group"> <label class="control-label" for="mygroups-group">Name of MyGroups Account (lowercase only, no spaces) <span class="form-required" title="This field is required.">*</span></label>
    <input required="required" class="form-control form-text required" type="text" id="mygroups-group" name="mygroups-group" value="" size="60" maxlength="128" />
  </div>

  <div class="form-item form-group form-item add-uids form-type-textarea form-group"> <label class="control-label" for="add-uids">Others to be Added to MyGroups Account (UVA computing IDs separated by commas)</label>
    <div class="form-textarea-wrapper resizable"><textarea class="form-control form-textarea" id="add-uids" name="add-uids" cols="60" rows="3"></textarea>
    </div>
  </div>

  <div class="form-item form-group form-type-radios form-group"> <label class="control-label" for="new-or-renewal">New or Renewal <span class="form-required" title="This field is required.">*</span></label>
    <div class="row">
      <div id="new-or-renewal" class="form-radios col">
        <div class="form-item form-type-radio radio"> <label class="control-label" for="new-or-renewal-1">
          <input required="required" type="radio" id="new-or-renewal-1" name="new-or-renewal" value="new" checked="checked" class="form-radio" />&nbsp;New</label>
        </div>
        <div class="form-item form-type-radio radio"> <label class="control-label" for="new-or-renewal-2">
          <input required="required" type="radio" id="new-or-renewal-2" name="new-or-renewal" value="renewal" class="form-radio" />&nbsp;Renewal</label>
        </div>
      </div>
      <div class="help-block col">If this is your first request, select New.  Otherwise select Renewal.</div>
    </div>
  </div>

  <div class="form-item project-description form-type-textarea form-group"> <label class="control-label" for="project-description">Description of Research Project <span class="form-required" title="This field is required.">*</span></label>
    <div class="form-textarea-wrapper resizable"><textarea required="required" class="form-control form-textarea required" id="project-description" name="project-description" cols="60" rows="8"></textarea>
    </div>
  </div>
  <div class="form-item form-type-textarea form-group"> <label class="control-label" for="renewal-description">For Renewals: Description of Results from Previous Allocation</label>
    <div class="form-textarea-wrapper resizable"><textarea class="form-control form-textarea" id="renewal-description" name="renewal-description" cols="60" rows="8"></textarea>
    </div>
  </div>

  <div class=""> <label class="control-label">Are you a human? <span class="form-required" title="This field is required.">*</span></label>
    <div class="row"">
      <div class="form-item form-group col" id="captcha" style="pointer-events:none;margin:1.4rem;width:12rem;">
      </div>
      <div class="form-item form-group col">
        <input type="text" placeholder="Captcha" id="cpatchaTextBox" style="margin-top:1rem;padding:6px;font-family:monospace; width:8rem;" />
        <button class="btn btn-success" id="captcha-submit" type="button" onclick="validateCaptcha()"><i class="fas fa-check fa-1x"></i></button>
        <button class="btn btn-default" id="captcha-refresh" type="button" onclick="createCaptcha()"><i class="fas fa-sync fa-1x"></i></button>
      </div>
    </div>
  </div>

  <div class="form-actions" id="submit-div" style="margin-top:1rem;">
    <hr size="1" style="" />
    <button class="button-primary btn btn-primary form-submit" id="submit" type="submit" name="op" value="Submit">Submit</button>
  </div>

</div>
</form>

<script type="text/javascript" src="/js/captcha.js"></script>

<script>
function getParams() {
  var vars = {};
  var parts = window.location.href.replace(/[?&]+([^=&]+)=([^&]*)/gi, function(m,key,value) {
    vars[key] = value;
  });
  return vars;
}

function decode64(str) {
  var e={},i,b=0,c,x,l=0,a,r='',w=String.fromCharCode,L=str.length;
  var A="ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz0123456789+/";
  for(i=0;i<64;i++){e[A.charAt(i)]=i;}
  for(x=0;x<L;x++){
    c=e[str.charAt(x)];b=(b<<6)+c;l+=6;
    while(l>=8){((a=(b>>>(l-=8))&0xff)||(x<(L-2)))&&(r+=w(a));}
  }
  return r;
};

var form = document.getElementById('allocation-form');

var name_enc = getParams()["name"];
if (name_enc) {
  // do nothing
} else {
  $('#name').val('');
  $('#email').val('');
  $('#uid').val('');
  window.location.replace( "https://auth.uvasomrc.io/site/allocation-standard.php" );
}

// name
var name_enc = getParams()["name"];
var name_esc = decodeURI(name_enc);
var form_name = decode64(name_esc);
var name_field = document.getElementById('name');
name_field.value = form_name;
//var name_field = document.querySelectorAll('name');
//name_field[0].value = form_name;
//name_field[1].value = form_name;
//name_field[2].value = form_name;

// uid
var uid_enc = getParams()["uid"];
var uid_esc = decodeURI(uid_enc);
var form_uid = decode64(uid_esc);
var uid_field = document.getElementById('uid');
uid_field.value = form_uid;

// email
var email_enc = getParams()["email"];
var email_esc = decodeURI(email_enc);
var form_email = decode64(email_esc);
var email_field = document.getElementById('email');
email_field.value = form_email;

let message = decodeURI(getParams()["message"]);
let status = decodeURI(getParams()["status"]);
if(message == "undefined" || message == undefined) {
  message="";
}

document.getElementById("form_post_response").innerHTML = message;
if(status == "error" || status == undefined) {
  document.getElementById("form_post_response").style.color = "red";
  document.getElementById("form_post_response").style.fontWeight = "500"
} else {
  document.getElementById("form_post_response").style.color = "green";
  document.getElementById("form_post_response").style.fontWeight = "500"
}
</script>
