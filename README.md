# 🚀 Future Me - Personal Portfolio Website

This is a personal **static portfolio website** built using HTML, CSS, and JavaScript. It represents my journey, goals, mindset, and future vision in the tech world.

The website is deployed on an AWS EC2 instance using the Apache2 web server, making it accessible over the internet.

---

## 🌟 Features

* 🌌 Animated star background & shooting stars
* ✨ Smooth scroll animations
* ⌨️ Typing effect ("Future Me 🚀")
* 📱 Fully responsive design
* 🎯 Clean UI with modern gradients
* 🚀 Deployed on AWS EC2

---

## 🛠️ Tech Stack

* **HTML5**
* **CSS3** (Animations & Gradients)
* **JavaScript** (DOM Manipulation & Effects)
* **AWS EC2**
* **Apache2 Web Server**

---

## 📂 Project Structure

```
project/
│── index.html
│── README.md
```

---

## ⚙️ Deployment Steps

### 1. Launch EC2 Instance

* Created an EC2 instance using Ubuntu
* Enabled HTTP access (Port 80) for public connectivity

---

### 2. Connect to EC2

* Connected to the server using SSH from a Linux environment
* Used the terminal to configure and manage the instance

---

### 3. Install Apache2

* Updated system packages
* Installed Apache2 web server
* Started and enabled the service

---

### 4. Create Website File

* Navigated to the home directory
* Created `index.html` and added the complete website code

---

### 5. Deploy Website

* Moved the file to the Apache root directory:

  ```
  /var/www/html
  ```
* This allows Apache to serve the website

---

### 6. Restart Apache

* Restarted the Apache service to apply changes

---

### 7. Access Website

* Opened the EC2 public IP in a browser
* Website is now live and accessible globally 🌍

---

## 🧠 Key Learnings

* Difference between **localhost vs cloud hosting**
* How **EC2 acts as a virtual server**
* How **Apache serves static files**
* Importance of **public IP & security groups**

---

## 🚀 Future Improvements

* Add custom domain (Route 53)
* Enable HTTPS (SSL Certificate)
* Implement CI/CD pipeline
* Enhance UI/UX further

---

* 💼 Aspiring Cloud & DevOps Engineer
* 🔗 LinkedIn: https://www.linkedin.com/in/kranuj

---

⭐ If you like this project, feel free to star the repository!
