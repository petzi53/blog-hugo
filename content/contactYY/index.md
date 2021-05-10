+++
# Contact widget.
widget = "contact"
active = true
date = 2016-04-20T00:00:00

title = "Contact"
subtitle = ""

# Order that this section will appear in.
weight = 110

# Automatically link email and phone?
autolink = true

+++

<form action="https://formspree.io/peter.baumgartner@icloud.com" method="POST">
  <label for="name">Your name: </label>
  <input type="text" name="name" required="required" placeholder="here"><br>
  <label for="email">Your email: </label>
  <input type="email" name="_replyto" required="required" placeholder="here"><br>
  <label for="message">Your message:</label><br>
  <textarea rows="4" name="message" id="message" required="required" class="form-control" placeholder="Write here your message to me!"></textarea>
  <input type="hidden" name="_next" value="/thanks" />
  <input type="submit" value="Send" name="submit" class="btn btn-primary btn-outline">
  <input type="hidden" name="_subject" value="[Educational Patterns]: Contact page" />
  <input type="text" name="_gotcha" style="display:none" />
</form>
