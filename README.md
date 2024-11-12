
# Bisola Janet Adesola - Portfolio Website

Welcome to the repository for my personal portfolio website! This site is designed to showcase my skills, projects, achievements, and experience as a DevOps Engineer. It’s a place where you can learn more about my work, explore my projects, and get in touch with me.

---

## Overview

This static portfolio website was created to demonstrate my capabilities and experience in DevOps and cloud engineering. It provides a detailed overview of my technical skills, projects I have worked on, certifications, and links to connect with me professionally.

Through this website, I aim to highlight my expertise in deploying, automating, and managing applications on cloud platforms, along with my commitment to continuous learning and excellence in the field.

---

## Features

- **Project Showcases**: Each project includes a description, technologies used, and key contributions, giving insight into my hands-on experience.
- **Certifications**: A dedicated section lists my certifications to demonstrate my continuous learning and skill development.
- **Contact Information**: Links to my LinkedIn and GitHub profiles, allowing visitors to connect with me.
- **Responsive Design**: The website is fully responsive, ensuring an optimal viewing experience on devices of all sizes.

---

## Technologies Used

This project was built using the following tools and technologies:

- **HTML** - Provides the structure and layout for each section of the website.
- **CSS** - Adds styling and visual enhancements to improve the user experience.
- **Git, GitHub, and GitHub Pages** - Version control and deployment tools for hosting the website directly from the repository.
- **Visual Studio Code** - The primary development environment used for writing and editing the code.
- **Docker** - The website is containerized to ensure easy deployment and consistency across environments.
- **GitHub Actions** - Automates the deployment process through CI/CD pipelines, so every push to the repository triggers an automated deployment to GitHub Pages.

---

## How to Use This Repository

### Viewing the Website
You can view the live version of my portfolio website here: [Portfolio Website](https://bisola-adesola.github.io/portfolio-website/#certifications)

### Cloning and Running the Website Locally

If you’d like to clone this project and view it on your local machine, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Bisola-Adesola/portfolio-website.git
   ```

2. **Navigate to the Project Directory**:
   ```bash
   cd portfolio-website
   ```

3. **Open `index.html`** in a web browser to view the website locally.

### Running the Website with Docker

If you prefer to run the website in a Docker container, use the following steps:

1. **Build the Docker Image**:
   ```bash
   docker build -t portfolio-website .
   ```

2. **Run the Docker Container**:
   ```bash
   docker run -p 8080:80 portfolio-website
   ```

3. **Access the Website**:
   Open a web browser and navigate to `http://localhost:8080` to view the website.

---

## CI/CD Automation

This project utilizes **GitHub Actions** for continuous integration and deployment (CI/CD). Each time a change is pushed to the main branch, GitHub Actions automatically triggers a workflow that builds and deploys the latest version of the website to GitHub Pages. This ensures that the live version of the website is always up-to-date with the latest changes.

---

## Repository Structure

Here’s an overview of the key files and folders in this repository:

- **index.html** - The main HTML file that serves as the entry point for the website.
- **style.css** - The CSS file that contains all the styles and layout adjustments for the website.
- **Dockerfile** - Defines the instructions to build a Docker image for the website, ensuring consistency across environments.
- **.github/workflows/** - Contains the GitHub Actions workflow file, which handles the CI/CD pipeline for automated deployment.

---

## Links

- **Portfolio Website**: [https://bisola-adesola.github.io/portfolio-website/#certifications](https://bisola-adesola.github.io/portfolio-website/#certifications)
- **GitHub Repository**: [https://github.com/Bisola-Adesola/portfolio-website](https://github.com/Bisola-Adesola/portfolio-website)

---

## Contact

Feel free to reach out if you’d like to connect or discuss my projects!

- **Email**: adesolabisola82@gmail.com
- **LinkedIn**: [Your LinkedIn Profile](https://www.linkedin.com/in/your-linkedin)
- **GitHub**: [Bisola-Adesola](https://github.com/Bisola-Adesola)

---

Thank you for visiting my portfolio website repository! I invite you to explore the site to learn more about my DevOps journey and the projects I’ve worked on.
