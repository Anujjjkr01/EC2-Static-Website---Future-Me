# 🚀 Future Me - Personal Portfolio Website

This is a **personal static portfolio website** built using HTML, CSS, and JavaScript.
It represents my journey, goals, mindset, and future vision in the tech world.

The website is hosted on an AWS EC2 instance using an Apache2 web server.

---

## 🌟 Features

* 🌌 Animated star background & shooting stars
* ✨ Smooth scroll animations
* ⌨️ Typing effect ("Future Me 🚀")
* 📱 Fully responsive design
* 🎯 Clean UI with modern gradients
* 🚀 Hosted on AWS EC2

---

## 🛠️ Tech Stack

* HTML5
* CSS3 (Animations & Gradients)
* JavaScript (DOM Manipulation & Effects)
* AWS EC2
* Apache2 Web Server

---

## 📂 Project Structure

```
project/
│── index.html
│── README.md

---

## ⚙️ Deployment Steps (AWS EC2 + Apache2)

### 1️⃣ Launch EC2 Instance

* Go to AWS Console
* Launch an EC2 instance (Ubuntu recommended)
* Choose instance type (t2.micro for free tier)
* Configure security group:

  * Allow **HTTP (Port 80)**
  * Allow **SSH (Port 22)**

---

### 2️⃣ Connect to EC2 Instance

Use SSH to connect:

```
ssh -i your-key.pem ubuntu@your-ec2-public-ip
```

---

### 3️⃣ Install Apache2

```
sudo apt update
sudo apt install apache2 -y
```

Start Apache:

```
sudo systemctl start apache2
sudo systemctl enable apache2
```

---

### 4️⃣ Deploy Website Files

Navigate to web directory:

```
cd /var/www/html
```

Remove default file:

```
sudo rm index.html
```

Create your file:

```
sudo nano index.html
```

Paste your HTML code and save.

---

### 5️⃣ Set Permissions

```
sudo chmod -R 755 /var/www/html
```

---

### 6️⃣ Access Your Website

Open browser:

```
http://your-ec2-public-ip
```

🎉 Your website is now live!

---

## 🔗 How to Connect to Website

* Open your browser
* Enter your EC2 Public IP:

```
http://<your-public-ip of instance>

And then you can access the Static Website
