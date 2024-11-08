<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Meu Site</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/css/bootstrap.min.css" rel="stylesheet">
  <link rel="stylesheet" href="style.css">
</head>
<body>

  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
    <div class="container">
      <a class="navbar-brand" href="#">Meu Site</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item"><a class="nav-link" href="#home">Home</a></li>
          <li class="nav-item"><a class="nav-link" href="#sobre">Sobre</a></li>
          <li class="nav-item"><a class="nav-link" href="#contato">Contato</a></li>
        </ul>
      </div>
    </div>
  </nav>

  <!-- Seção Principal -->
  <header id="home" class="bg-primary text-white text-center py-5">
    <div class="container">
      <h1>Bem-vindo ao Meu Site</h1>
      <p class="lead">Aqui você encontra as melhores informações</p>
    </div>
  </header>

  <!-- Conteúdo Principal -->
  <section id="sobre" class="py-5">
    <div class="container">
      <h2 class="text-center mb-4">Sobre Nós</h2>
      <p class="text-center">Somos uma empresa dedicada a fornecer as melhores informações e serviços. Nossa equipe é composta de especialistas em diversas áreas para atender a todas as suas necessidades.</p>
    </div>
  </section>

  <!-- Contato -->
  <section id="contato" class="bg-light py-5">
    <div class="container">
      <h2 class="text-center mb-4">Contato</h2>
      <form class="row g-3">
        <div class="col-md-6">
          <label for="nome" class="form-label">Nome</label>
          <input type="text" class="form-control" id="nome" required>
        </div>
        <div class="col-md-6">
          <label for="email" class="form-label">Email</label>
          <input type="email" class="form-control" id="email" required>
        </div>
        <div class="col-12">
          <label for="mensagem" class="form-label">Mensagem</label>
          <textarea class="form-control" id="mensagem" rows="4" required></textarea>
        </div>
        <div class="col-12 text-center">
          <button type="submit" class="btn btn-primary">Enviar</button>
        </div>
      </form>
    </div>
  </section>

  <!-- Rodapé -->
  <footer class="bg-dark text-white text-center py-3">
    <p>&copy; 2023 Meu Site. Todos os direitos reservados.</p>
  </footer>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
