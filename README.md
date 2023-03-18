<a name="readme-top"></a>

<div align="center">
  <h3 align="center">Background remover</h3>

  <p align="center">
    Remove background from images using pre-trained AI model.
    <br />
    <a href="#" target="_blank"><strong>View Demo »</strong></a>
    <br />
  </p>
</div>

<!-- ABOUT THE PROJECT -->
## About The Project

[![Screenshot](static/images/screenshot.png?raw=true "Tomar")](#)

A web app built with Python/Django that enables users to remove image background using pre-trained AI model. It allows users to download the final result image with a transparent background. 

It does well for most images that doesn't have messy background but I'm sure you won't expect photoshop like results :) 

### Features
- Download the final result
- Transparent background (PNG format)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Built With
- Python/Django
- Bootstrap
- Rembg

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- GETTING STARTED -->
## Getting Started

To get a local copy up and running follow these simple steps.

### Prerequisites

* Django

### Installation

1. Clone the repo
   ```
   git clone https://github.com/balewgize/background-remover.git
   ```
2. Install required packages (virtual environments recommended)
   ```
   pip install -r requirements.txt
   ```
3. Provide credentials in *.env*  (create a file named .env inside **background_remover** folder - project root directory)
   ```
    DJANGO_SECRET_KEY=
    DJANGO_DEBUG=True
   ```
4. Apply migrations
    ```
    python manage.py migrate
    ```
5. Start the server
    ```
    python manage.py runserver
    ```
6. Goto http://127.0.0.1:8000 on your browser

<p align="right">(<a href="#readme-top">back to top</a>)</p>

Loved the project? Consider giving a star ★

Thanks!
