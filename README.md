# Project Responsive Web Design using Bootstrap
## Date: 14/5/25
## Name:Sharon Steffani

## AIM:
To create a simplified clone of Dribbble (https://dribbble.com/) landing page.


## DESIGN STEPS:

### Step 1:
Clone the repository from GitHub.

### Step 2:
Create Django Admin project.

### Step 3:
Create a New App under the Django Admin project.

### Step 4:
Insert the necessary CSS and JavaScript files as external in order to use Bootstrap.

### Step 5:
Create a HTML file and include the needed Bootstrap components.

### Step 6:
Publish the website in the LocalHost.

## PROGRAM :
### HTML Code
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Dribble Christmas Fest</title>

  <!-- Bootstrap CSS -->
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">

  <!-- Font Awesome -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css" />

  <style>
    body {
      background-image: url('https://images.unsplash.com/photo-1543852786-1cf6624b9987?auto=format&fit=crop&w=1950&q=80');
      background-size: cover;
      background-position: center;
      background-attachment: fixed;
      color: #fff;
    }

    .navbar, .sorting-navbar, footer {
      background-color: rgba(0, 0, 0, 0.7);
    }

    .navbar-brand, .nav-link {
      color: #fff !important;
    }

    .nav-link.active {
      font-weight: bold;
      color: #ffc107 !important;
    }

    .card {
      background-color: rgba(255, 255, 255, 0.9);
      border: none;
      border-radius: 12px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.2);
    }

    .card-title {
      color: #d32f2f;
      font-weight: bold;
    }

    .contact-section {
      background-color: rgba(0, 0, 0, 0.7);
      padding: 40px;
      border-radius: 12px;
      margin-bottom: 50px;
    }

    h2 {
      color: #ffe082;
    }

    footer {
      color: #ccc;
    }
  </style>
</head>
<body>

  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg">
    <div class="container">
      <a class="navbar-brand" href="#"><i class="fa-solid fa-tree me-2"></i>Dribble Fest</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item"><a class="nav-link" href="#"><i class="fa-solid fa-house"></i> Home</a></li>
          <li class="nav-item"><a class="nav-link" href="#"><i class="fa-solid fa-circle-info"></i> About</a></li>
          <li class="nav-item"><a class="nav-link" href="#"><i class="fa-solid fa-snowman"></i> Services</a></li>
          <li class="nav-item"><a class="nav-link" href="#"><i class="fa-solid fa-envelope"></i> Contact</a></li>
        </ul>
      </div>
    </div>
  </nav>

  <!-- Sorting Nav -->
  <nav class="sorting-navbar py-2">
    <div class="container d-flex justify-content-center">
      <ul class="nav">
        <li class="nav-item">
          <a class="nav-link active" href="#">Popular</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Newest</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Random</a>
        </li>
      </ul>
    </div>
  </nav>

  <!-- Cards -->
  <div class="container my-5">
    <div class="row g-4">
      <div class="col-6 col-md-3">
        <div class="card">
          <img src="https://images.unsplash.com/photo-1608889179192-9dc33f1f1df0?auto=format&fit=crop&w=600&q=80" class="card-img-top" alt="Christmas">
          <div class="card-body">
            <h6 class="card-title">Tree Decoration</h6>
          </div>
        </div>
      </div>
      <!-- Duplicate the card block for more cards -->
    </div>
  </div>

  <!-- Contact Section -->
  <section id="contact" class="contact-section container">
    <h2><i class="fa-solid fa-envelope-open-text me-2"></i>Contact Us</h2>
    <form>
      <div class="mb-3">
        <label for="name" class="form-label">Your Name</label>
        <input type="text" class="form-control" id="name" placeholder="Enter your name">
      </div>
      <div class="mb-3">
        <label for="email" class="form-label">Your Email</label>
        <input type="email" class="form-control" id="email" placeholder="Enter your email">
      </div>
      <div class="mb-3">
        <label for="message" class="form-label">Message</label>
        <textarea class="form-control" id="message" rows="3" placeholder="Your message"></textarea>
      </div>
      <button type="submit" class="btn btn-warning"><i class="fa-solid fa-paper-plane me-1"></i>Send</button>
    </form>
  </section>

  <!-- Footer -->
  <footer class="text-center py-3">
    <p>&copy; 2024 <i class="fa-solid fa-snowflake"></i> Dribble Fest. All rights reserved.</p>
  </footer>

  <!-- Bootstrap JS -->
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
```
## OUTPUT:
![image](https://github.com/user-attachments/assets/76c65d84-0054-4c3f-8efa-85ffcdd98264)


## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
