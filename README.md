# Email-Sender
<hr>
<p>This is a simple Email sending Project.</p>
<p>You need to enter receiver's email id, email's subject (optional) and main content in input fields which appear when we first load out project.</p>
<p>When send button is pressed email is sent to desired person. It has nice, responsive UI.</p>

<hr>
<hr>
<h3>For security purpose I have not pushed settings.py file in project but I will tell you changes to be made at the end of the file (no change in default content) </h3>
<p>Add these lines at the end </p>
<hr>
EMAIL_BACKEND = 'django.core.mail.backends.smtp.EmailBackend'
EMAIL_HOST = 'smtp.gmail.com'
EMAIL_USE_TLS = True
EMAIL_PORT = 587
EMAIL_HOST_USER = #sender's email-id
EMAIL_HOST_PASSWORD = #password associated with above email-id
<hr>
<p>Hope you like it. Thank you.</p>
