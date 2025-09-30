# Contact Form Backend Options

## Option 1: Netlify Forms (Easiest)
Add `netlify` attribute to form:
```html
<form id="contact-form" netlify>
```

## Option 2: Formspree (Free)
Change form action:
```html
<form action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
```

## Option 3: EmailJS (Client-side)
Add EmailJS script and update JavaScript:
```javascript
emailjs.send("service_id", "template_id", {
  name: document.getElementById('name').value,
  email: document.getElementById('email').value,
  message: document.getElementById('message').value
});
```

## Option 4: Custom Backend
Create API endpoint and update form submission in script.js