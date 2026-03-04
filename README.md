# codestar_blog



A full-featured blog web application built with Django.  
This project includes a homepage, blog system, about page, and user authentication system.

---

## 🚀 Live Project

🌍 Live Site (Heroku): https://dashboard.heroku.com/apps/kassem 
📂 GitHub Repository: https://github.com/Kassem79/codestar_blog

---

## 🚀 Features

- 🏠 Homepage
- 📝 Blog post list page
- 📄 Blog detail page
- ℹ️ About page
- 🔐 User Signup
- 🔑 Login / Logout system
- 💬 Comment system
- 🎨 Custom static files (CSS & JavaScript)

---

## 🛠️ Technologies Used

- Python
- Django
- HTML5
- CSS3
- JavaScript
- (development)
- (production – Heroku)

---

## 📂 Project Structure

```
codestar/
│
├── blog/
│   ├── models.py
│   ├── views.py
│   ├── urls.py
│
├── templates/
│   ├── base.html
│   ├── index.html
│   ├── about.html
│   ├── blog_detail.html
│   └── registration/
│       ├── login.html
│       └── signup.html
│
├── static/
│   ├── css/
│   │   └── style.css
│   ├── js/
│   │   ├── script.js
│   │   └── comments.js
│   └── images/
│
├── manage.py
└── README.md

## Testing blog
Django automatically discovers tests inside files named tests.py or test_*.py within installed apps. If no tests are defined, the command will return Found 0 test(s), which simply means that no test cases have been created yet.

Django performed the following steps:

1️⃣ Found 1 test(s)
Django discovered one test case in your project.

2️⃣ Creating test database for alias 'default'...
Django created a temporary test database so your real project data is not affected during testing.

3️⃣ System check identified no issues
Django checked your project configuration and found no problems.

4️⃣ Ran 1 test in 0.001s
The test executed successfully and completed very quickly.

5️⃣ OK
This means the test passed with no errors or failures. ✅

6️⃣ Destroying test database for alias 'default'...
After the tests finished, Django deleted the temporary test database to clean up.

✅ In summary: Django successfully ran your test in an isolated environment and everything worked correctly.




