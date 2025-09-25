# My Portfolio Website

Welcome to my personal portfolio website! This site showcases my projects, skills, and achievements. It is hosted on an **AWS EC2 instance**.

## 🌐 Live Site
You can access my portfolio here: `http://<your-ec2-public-ip>`

## 🛠 Technologies Used
- **Frontend:** HTML, CSS, JavaScript
- **Hosting:** AWS EC2 (Linux instance)
- **Web Server:** Apache/Nginx

## 📁 Project Structure
/var/www/html/
├── index.html # Homepage
├── about.html # About Me section
├── projects.html # Projects showcase
├── contact.html # Contact form
├── css/ # Stylesheets
└── js/ # JavaScript files

## 🚀 Deployment on EC2
1. Launch an EC2 instance (Amazon Linux/Ubuntu).
2. Install a web server (Apache or Nginx):
   ```bash
   sudo yum install httpd -y   # For Amazon Linux
   sudo systemctl start httpd
   sudo systemctl enable httpd

