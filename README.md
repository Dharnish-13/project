# Ex.09 Project Responsive Web Design using Bootstrap
# Date:19/12/2025
# AIM:
To create a simplified clone of Dribbble (https://dribbble.com/) landing page.

# DESIGN STEPS:
## Step 1:
Clone the repository from GitHub.

## Step 2:
Create Django Admin project.

## Step 3:
Create a New App under the Django Admin project.

## Step 4:
Insert the necessary CSS and JavaScript files as external in order to use Bootstrap.

## Step 5:
Create a HTML file and include the needed Bootstrap components.

## Step 6:
Publish the website in the LocalHost.

# PROGRAM :
```
<!DOCTYPE html>
<html lang="en">

<head>
    <title>DHARNEESH PHARMACY</title>

    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">

    <style>
        body {
            background-color: #e0f2fe; 
            font-family: Arial, Helvetica, sans-serif;
        }

        .top-nav {
            background-color: #0369a1; 
            padding: 10px 0;
        }

        .top-nav a {
            color: #ffffff;
            font-size: 14px;
            text-decoration: none;
            margin: 0 15px;
        }

        .page-header h1 {
            font-size: 28px;
            letter-spacing: 2px;
            color: #0f172a;
        }

        .page-header p {
            font-size: 14px;
            color: #334155;
        }

        .item-card {
            background-color: #ffffff;
            border: 1px solid #38bdf8;
            border-radius: 10px;
            padding: 10px;
            height: 100%;
            box-shadow: 0 4px 8px rgba(0,0,0,0.08);
        }

        .item-card img {
            width: 100%;
            height: 160px;
            object-fit: contain;
            margin-bottom: 8px;
        }

        .item-card h6 {
            font-size: 15px;
            color: #075985;
        }

        .item-card p {
            font-size: 13px;
            color: #0c4a6e;
        }

        .grid-item {
            width: 20%;
            padding: 10px;
        }

        @media (max-width: 992px) {
            .grid-item {
                width: 33.33%;
            }
        }

        @media (max-width: 576px) {
            .grid-item {
                width: 100%;
            }
        }
    </style>
</head>

<body>

    <nav class="navbar top-nav">
        <div class="container justify-content-center">
            <a href="#">Home</a>
            <a href="#">Medicines</a>
            <a href="#">Contact</a>
        </div>
    </nav>

    <div class="page-header text-center my-4">
        <h1>DHARNEESH PHARMACY</h1>
        <p>Caring for your health every day</p>
    </div>

    <section class="pb-5">
        <div class="container">

            <div class="row justify-content-center">
                <div class="grid-item">
                    <div class="item-card">
                        <img src="mediflox.jpg">
                        <h6>Mediflox</h6>
                        <p>Used to treat bacterial infections.</p>
                    </div>
                </div>

                <div class="grid-item">
                    <div class="item-card">
                        <img src="azicure.jpg">
                        <h6>Azicure</h6>
                        <p>Effective for respiratory infections.</p>
                    </div>
                </div>

                <div class="grid-item">
                    <div class="item-card">
                        <img src="cough.jpg">
                        <h6>Cough syrup</h6>
                        <p>Relief from cough and throat irritation.</p>
                    </div>
                </div>

                <div class="grid-item">
                    <div class="item-card">
                        <img src="relaxon.jpg">
                        <h6>Relaxon</h6>
                        <p>Helps reduce muscle pain.</p>
                    </div>
                </div>

                <div class="grid-item">
                    <div class="item-card">
                        <img src="fevernil.jpg">
                        <h6>Fevernil</h6>
                        <p>Fast relief from fever.</p>
                    </div>
                </div>
            </div>

            <div class="row justify-content-center">
                <div class="grid-item">
                    <div class="item-card">
                        <img src="Headrelief.jpg">
                        <h6>Headrelief</h6>
                        <p>Effective for headaches.</p>
                    </div>
                </div>

                <div class="grid-item">
                    <div class="item-card">
                        <img src="Electrolife ORS.jpg">
                        <h6>Electrolife ORS</h6>
                        <p>Prevents dehydration.</p>
                    </div>
                </div>

                <div class="grid-item">
                    <div class="item-card">
                        <img src="Painfree.jpg">
                        <h6>Painfree</h6>
                        <p>Reduces pain and fever.</p>
                    </div>
                </div>

                <div class="grid-item">
                    <div class="item-card">
                        <img src="Coldcare Plus.jpg">
                        <h6>Coldcare Plus</h6>
                        <p>Relieves cold and nasal congestion.</p>
                    </div>
                </div>
            </div>

        </div>
    </section>

</body>
</html>
```
# OUTPUT:
PHARMACY
<img width="1899" height="984" alt="Screenshot 2025-12-26 101722" src="https://github.com/user-attachments/assets/5b99820a-c582-481d-893d-2920fd306c8f" />

# RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
