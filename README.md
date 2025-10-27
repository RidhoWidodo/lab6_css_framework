# lab6_css_framework

**Nama : Muhammad Ridho Hafiedz**

**Nim : 312410195**

**Matkul : Pemrograman web**

# Langkah 1 Struktur Dasar HTML dengan Bootstrap

```html
<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Praktikum 6 - CSS Framework</title>
    <!-- Bootstrap 5 CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>
    <!-- Konten akan ditambahkan di sini -->

    <!-- Bootstrap 5 JS -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
```
<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/79aacea3-022d-4160-8fc7-c773bd6465e9" />

# Tahap 2 Menambahkan Navigation Bar
```html
<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Praktikum 6 - CSS Framework</title>
    <!-- Bootstrap 5 CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>
    <!-- Navigation Bar -->
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
        <div class="container">
            <a class="navbar-brand" href="#">MyWebsite</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav">
                    <li class="nav-item">
                        <a class="nav-link active" href="#">Home</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">Artikel</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">About</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">Kontak</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>

    <!-- Bootstrap 5 JS -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
```
<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/9a65ad7a-2e58-4842-88cd-4c9403f44870" />

# Tahap 3 Menambahkan Header/Jumbotron
```html
<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Praktikum 6 - CSS Framework</title>
    <!-- Bootstrap 5 CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>
    <!-- Navigation Bar -->
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
        <div class="container">
            <a class="navbar-brand" href="#">MyWebsite</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav">
                    <li class="nav-item">
                        <a class="nav-link active" href="#">Home</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">Artikel</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">About</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">Kontak</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>

    <!-- Header/Jumbotron -->
    <div class="container mt-4">
        <div class="bg-light p-5 rounded">
            <h1 class="display-4">Hello World!</h1>
            <p class="lead">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum lorem elit, laculis innisi volutpat, malesuada tincidunt arcu. Proin in leo fringilla, vestibulum mi porta, faucibus felis. Integer pharetra est nunc, nec pretium nunc pretium ac.</p>
            <hr class="my-4">
            <a class="btn btn-primary btn-lg" href="#" role="button">Learn more ►</a>
        </div>
    </div>

    <!-- Bootstrap 5 JS -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
```
<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/7ae8c77b-9ffd-4eeb-a97e-1cfc49faa605" />

# Tahap 4: Menambahkan Konten Utama dan Sidebar
```html
<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Praktikum 6 - CSS Framework</title>
    <!-- Bootstrap 5 CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>
    <!-- Navigation Bar -->
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
        <div class="container">
            <a class="navbar-brand" href="#">MyWebsite</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav">
                    <li class="nav-item">
                        <a class="nav-link active" href="#">Home</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">Artikel</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">About</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">Kontak</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>

    <!-- Header/Jumbotron -->
    <div class="container mt-4">
        <div class="bg-light p-5 rounded">
            <h1 class="display-4">Hello World!</h1>
            <p class="lead">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum lorem elit, laculis innisi volutpat, malesuada tincidunt arcu. Proin in leo fringilla, vestibulum mi porta, faucibus felis. Integer pharetra est nunc, nec pretium nunc pretium ac.</p>
            <hr class="my-4">
            <a class="btn btn-primary btn-lg" href="#" role="button">Learn more ►</a>
        </div>
    </div>

    <!-- Konten Utama dan Sidebar -->
    <div class="container mt-4">
        <div class="row">
            <!-- Konten Utama -->
            <div class="col-md-8">
                <div class="row mb-4">
                    <div class="col-md-4">
                        <div class="card">
                            <div class="card-body">
                                <h5 class="card-title">Heading</h5>
                                <p class="card-text">Donec sed odio dui. Etiam porta sem malesuada magna mollis euismod.</p>
                                <a href="#" class="btn btn-secondary">View detail</a>
                            </div>
                        </div>
                    </div>
                    <div class="col-md-4">
                        <div class="card">
                            <div class="card-body">
                                <h5 class="card-title">Heading</h5>
                                <p class="card-text">Donec sed odio dui. Etiam porta sem malesuada magna mollis euismod.</p>
                                <a href="#" class="btn btn-secondary">View detail</a>
                            </div>
                        </div>
                    </div>
                    <div class="col-md-4">
                        <div class="card">
                            <div class="card-body">
                                <h5 class="card-title">Handling</h5>
                                <p class="card-text">Donec sed odio dui. Etiam porta sem malesuada magna mollis euismod.</p>
                                <a href="#" class="btn btn-secondary">View detail</a>
                            </div>
                        </div>
                    </div>
                </div>
            </div>

            <!-- Sidebar -->
            <div class="col-md-4">
                <div class="card mb-4">
                    <div class="card-header">
                        Widget Header
                    </div>
                    <ul class="list-group list-group-flush">
                        <li class="list-group-item">Widget Link</li>
                        <li class="list-group-item">Widget Link</li>
                        <li class="list-group-item">Widget Link</li>
                        <li class="list-group-item">Widget Link</li>
                    </ul>
                </div>
                <div class="card">
                    <div class="card-body">
                        <h5 class="card-title">Widget Text</h5>
                        <p class="card-text">Vestibulum lorem elit, laculis in nisi volutpat, malesuada tincidunt arcu. Proin in leo fringilla, vestibulum mi porta, faucibus felis. Integer pharetra est nunc, nec pretium nunc pretium ac.</p>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <!-- Bootstrap 5 JS -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
```
<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/1496bf9f-a6e5-4f8b-884d-15e15031a8c1" />

# Tahap 5: Menambahkan Featurette dan Footer
```html
<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Praktikum 6 - CSS Framework</title>
    <!-- Bootstrap 5 CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>
    <!-- Navigation Bar -->
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
        <div class="container">
            <a class="navbar-brand" href="#">MyWebsite</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav">
                    <li class="nav-item">
                        <a class="nav-link active" href="#">Home</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">Artikel</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">About</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">Kontak</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>

    <!-- Header/Jumbotron -->
    <div class="container mt-4">
        <div class="bg-light p-5 rounded">
            <h1 class="display-4">Hello World!</h1>
            <p class="lead">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum lorem elit, laculis innisi volutpat, malesuada tincidunt arcu. Proin in leo fringilla, vestibulum mi porta, faucibus felis. Integer pharetra est nunc, nec pretium nunc pretium ac.</p>
            <hr class="my-4">
            <a class="btn btn-primary btn-lg" href="#" role="button">Learn more ►</a>
        </div>
    </div>

    <!-- Konten Utama dan Sidebar -->
    <div class="container mt-4">
        <div class="row">
            <!-- Konten Utama -->
            <div class="col-md-8">
                <div class="row mb-4">
                    <div class="col-md-4">
                        <div class="card">
                            <div class="card-body">
                                <h5 class="card-title">Heading</h5>
                                <p class="card-text">Donec sed odio dui. Etiam porta sem malesuada magna mollis euismod.</p>
                                <a href="#" class="btn btn-secondary">View detail</a>
                            </div>
                        </div>
                    </div>
                    <div class="col-md-4">
                        <div class="card">
                            <div class="card-body">
                                <h5 class="card-title">Heading</h5>
                                <p class="card-text">Donec sed odio dui. Etiam porta sem malesuada magna mollis euismod.</p>
                                <a href="#" class="btn btn-secondary">View detail</a>
                            </div>
                        </div>
                    </div>
                    <div class="col-md-4">
                        <div class="card">
                            <div class="card-body">
                                <h5 class="card-title">Handling</h5>
                                <p class="card-text">Donec sed odio dui. Etiam porta sem malesuada magna mollis euismod.</p>
                                <a href="#" class="btn btn-secondary">View detail</a>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Featurette -->
                <hr class="my-5">
                <div class="row featurette mb-5">
                    <div class="col-md-12">
                        <h2 class="featurette-heading">First featurette heading.</h2>
                        <p class="lead">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum lorem elit, laculis in nisi volutpat, malesuada tincidunt arcu. Proin in leo fringilla, vestibulum mi porta, faucibus felis. Integer pharetra est nunc, nec pretium nunc pretium ac.</p>
                    </div>
                </div>

                <hr class="my-5">
                <div class="row featurette mb-5">
                    <div class="col-md-12">
                        <h2 class="featurette-heading">First featurette heading.</h2>
                        <p class="lead">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum lorem elit, laculis in nisi volutpat, malesuada tincidunt arcu. Proin in leo fringilla, vestibulum mi porta, faucibus felis. Integer pharetra est nunc, nec pretium nunc pretium ac.</p>
                    </div>
                </div>
            </div>

            <!-- Sidebar -->
            <div class="col-md-4">
                <div class="card mb-4">
                    <div class="card-header">
                        Widget Header
                    </div>
                    <ul class="list-group list-group-flush">
                        <li class="list-group-item">Widget Link</li>
                        <li class="list-group-item">Widget Link</li>
                        <li class="list-group-item">Widget Link</li>
                        <li class="list-group-item">Widget Link</li>
                    </ul>
                </div>
                <div class="card">
                    <div class="card-body">
                        <h5 class="card-title">Widget Text</h5>
                        <p class="card-text">Vestibulum lorem elit, laculis in nisi volutpat, malesuada tincidunt arcu. Proin in leo fringilla, vestibulum mi porta, faucibus felis. Integer pharetra est nunc, nec pretium nunc pretium ac.</p>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <!-- Footer -->
    <footer class="bg-dark text-light mt-5 py-3">
        <div class="container">
            <p class="text-center mb-0">© 2021 - Universitas Pelita Bangsa</p>
        </div>
    </footer>

    <!-- Bootstrap 5 JS -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
```
<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/fd836eba-9ba8-457c-8a75-b07fd8d1002b" />

**Penjelasan Setiap Tahap:**
  - Tahap 1: Struktur dasar HTML dengan impor Bootstrap 5
  - Tahap 2: Menambahkan navigation bar dengan menu Home, Artikel, About, dan Kontak
  - Tahap 3: Menambahkan header/jumbotron dengan judul "Hello World!" dan tombol "Learn more"
  - Tahap 4: Menambahkan konten utama (kartu-kartu) dan sidebar dengan widget
  - Tahap 5: Menambahkan featurette dan footer
