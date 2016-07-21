---
layout: template1
comments: false
---

有任何問題，歡迎透過以下表單聯繫我。

<div class="panel panel-default shadow1">
  <div class="panel-heading">
    <h4 class="text-primary">聯絡表單</h4>
  </div>
  <div class="panel-body">
    <form id="contactform" method="post" action="https://formspree.io/maxmilian@gmail.com" enctype="text/plain">
      <div class="form-group">
        <label for="name" class="control-label">Your name</label>
        <input id="name" type="text" name="name" class="form-control">
      </div>
      <div class="form-group">
        <label for="email" class="control-label">Your email</label>
        <input id="email" type="email" name="_replyto" class="form-control">
      </div>
      <div class="form-group">
        <label for="msg" class="control-label">Your message</label>
        <textarea id="msg" name="message" class="form-control"></textarea>
      </div>

      <input type="text" name="_gotcha" style="display:none" />
      <input type="submit" value="送出!" class="btn btn-primary">
    </form>
  </div>
</div>
