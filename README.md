
![Team Logo](/logo-vertical.png)

# Zonguldak Bülent Ecevit University Un-Defined Team

Welcome to the forefront of change! We are the Un-Defined team from Zonguldak Bülent Ecevit University, driven by the relentless pursuit of a fairer world for women. In a society where equality remains a distant dream for many, we stand as advocates, catalysts, and architects of empowerment.

## Our Mission

At the core of our project lies a commitment to addressing the multifaceted challenges hindering gender equality. Through a lens of social justice and empowerment, we aim to tackle issues spanning Gender Equality, Inequality Reduction, Quality Education, Business Partnerships, Peace, Justice, and Strong Institutions. Our primary focus is on supporting and uplifting women, fostering an environment where they can thrive and contribute meaningfully to all aspects of society.

## Project Overview

### Gender Equality and Empowerment

One of the paramount issues we're tackling is the disparity in female employment rates. Despite strides made in various sectors, women still face barriers in job selection and career advancement. Our project seeks to dismantle these barriers by empowering women to make informed choices, challenging societal norms, and creating opportunities for meaningful employment.

### Installation Guide

To embark on this journey with us, follow these steps to set up Un-Defined:

1. **Clone the Repository:** Begin by cloning our repository using the following command:
    
    bashCopy code
    
    ```bash
    git clone https://github.com/un-defined-gsc/un-defined
	```
    
2. **Build Docker Image:** Navigate to the project directory and build the Docker image:
    
    bashCopy code
    
    ```bash
    docker compose -f "deployment\docker\un-defined\dev.docker-compose.yaml" build
	```
    
3. **Launch the Application:** Start the Docker containers to bring the application online:
    
    bashCopy code
    
    ```bash
    docker compose -f "deployment\docker\un-defined\dev.docker-compose.yaml" up
	```
    
4. **Access the Application:** Finally, access Un-Defined by visiting [http://localhost:80](http://localhost/) in your web browser.
    

## Project Features

### Social Network

- **Create Posts:** Users can create posts categorized by various topics, facilitating meaningful discussions.
- **Interactivity:** Engage with posts through features like comments, likes, and unlikes, fostering a vibrant online community.
- **User Profiles:** Explore user profiles to get insights into their contributions and interests.

### Roadmap System

- **Plan and Execute:** Create roadmaps to outline strategies and milestones in tackling societal challenges.
- **Streamlined Management:** Easily manage and update roadmaps to adapt to evolving needs and priorities.

## Embrace the Change

Join us in reshaping the narrative and building a world where women are not just included but empowered to lead. Together, we can redefine norms, challenge inequalities, and pave the way for a brighter, fairer future. Let's make every voice heard, every step count, and every success shared as we journey towards a more equitable tomorrow.
