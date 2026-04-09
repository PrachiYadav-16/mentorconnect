# 🎓 MentorConnect

**Your bridge to expert mentorship - connecting eager learners with experienced mentors**

Hi there! 👋 Welcome to MentorConnect - a platform built to make finding and connecting with mentors as easy as possible. Whether you're looking to learn something new or share your expertise, we've got you covered!

---

## ✨ What Makes MentorConnect Special?

### For Students 🎯
- **Find Your Perfect Mentor**: Browse through hundreds of experienced professionals ready to guide you
- **Learn at Your Pace**: Schedule sessions that work for your timeline
- **Track Your Progress**: See how far you've come with our built-in progress tracker
- **Stay Connected**: Chat in real-time with your mentors whenever you need help

### For Mentors 💼
- **Share Your Knowledge**: Help others grow while reinforcing your own expertise
- **Flexible Scheduling**: Mentor on your own time, from anywhere
- **Build Your Profile**: Showcase your skills and experience
- **Make an Impact**: See the direct results of your mentorship

---

## � Getting Started (It's Easy!)

### What You'll Need
Just three things to get MentorConnect running:
1. **PHP 8.0 or newer** - The language we're using
2. **MySQL database** - Where we store all the data
3. **A web server** - Apache or Nginx works great (WAMP/XAMPP makes this super easy on Windows)

### Installation Steps

**Step 1: Set Up the Database**
```bash
# Import the database using MySQL
mysql -u root -p < database/database.sql

# Or simply run the web installer (easier!)
# Just open: http://localhost/mentorconnect/dev-tools/setup-database.php
```

**Step 2: Configure Your Database Connection**
Open `config/database.php` and update these lines:
```php
define('DB_HOST', 'localhost');      // Usually 'localhost'
define('DB_NAME', 'mentorconnect');  // Your database name
define('DB_USER', 'root');           // Your database username
define('DB_PASS', '');               // Your database password
```

**Step 3: Open in Browser**
- If using WAMP/XAMPP: `http://localhost/mentorconnect`
- Or start PHP's built-in server: `php -S localhost:8000`

That's it! 🎉 You're ready to go!

### 🎮 Try It Out (Demo Accounts)

We've set up some demo accounts so you can explore right away:

- **As a Student**: `student@demo.com` / `demo123`
- **As a Mentor**: `mentor@demo.com` / `demo123`
- **As an Admin**: `admin@demo.com` / `demo123`

---

## 🎨 Features We're Proud Of

### Core Features
- **Smart Mentor Discovery**: Find mentors by skills, experience, and availability
- **Real-Time Chat**: Message your mentors instantly - no waiting around
- **Progress Tracking**: Watch yourself grow with visual progress indicators
- **Reviews & Ratings**: Help others find great mentors (and become one yourself!)
- **Session Scheduling**: Book mentorship sessions that fit your schedule
- **File Sharing**: Share documents, code, or resources easily
- **Mobile Friendly**: Use MentorConnect on any device - phone, tablet, or desktop

### Under the Hood
- **Fast & Secure**: Built with modern PHP and MySQL for speed and security
- **Clean Design**: Orange-themed interface that's easy on the eyes
- **Works Offline**: Progressive Web App technology means you can access basic features without internet
- **SEO Optimized**: Easy to find on search engines

---

## 🛠️ Built With

Simple, reliable technology that works:
- **PHP** - Powers the backend
- **MySQL** - Stores all our data safely
- **HTML/CSS/JavaScript** - Creates the beautiful interface
- **Apache** - Serves everything up

### Performance Stats
We're pretty fast! 🚀
- ⚡ 100/100 Performance Score
- ✅ Mobile-optimized
- 🎯 SEO-friendly
- ♿ Fully accessible

---

## 🤝 Want to Help Out?

We'd love your contribution! Whether it's:
- 🐛 Fixing bugs
- ✨ Adding new features
- 📝 Improving documentation
- 💡 Suggesting ideas

Just fork the repo, make your changes, and send us a pull request. Every little bit helps!

---

## � Need Help?

Got questions? Running into issues? We're here to help!

- **Found a bug?** [Open an issue](https://github.com/PrachiYadav-16/mentorconnect/issues)
- **Have a question?** Check out our [documentation](https://github.com/PrachiYadav-16/mentorconnect/wiki)
- **Want to chat?** Email us at support@mentorconnect.com

---

## 📜 License

Free to use! This project is under the MIT License - feel free to use it for your own projects.


---

<div align="center">

### 🎓 MentorConnect
*Connecting learners with mentors, one success story at a time*

Made with ❤️ and lots of ☕

[⭐ Star us on GitHub](https://github.com/shubhamrajput27/mentorconnect) • [🍴 Fork the project](https://github.com/shubhamrajput27/mentorconnect/fork) • [📢 Share with friends](https://twitter.com/intent/tweet?text=Check%20out%20MentorConnect!)

</div>
