<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>rimusic | Portfólio</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
    <style>
        * { margin: 0; padding: 0; box-sizing: border-box; font-family: 'Poppins', sans-serif; }
        body { background: #000; color: #fff; overflow-x: hidden; display: flex; flex-direction: column; align-items: center; min-height: 100vh; }
        body::before { content: ""; position: fixed; inset: 0; background: radial-gradient(circle at 5% 50%, rgba(0,162,255,0.15), transparent 35%), radial-gradient(circle at 95% 50%, rgba(0,162,255,0.15), transparent 35%); z-index: -1; }
        .container { max-width: 500px; width: 90%; padding: 40px 0; }
        .profile-container { margin-bottom: 25px; text-align: center; }
        
        /* Círculo de perfil seguro (sem imagem externa para não dar 404) */
        .profile-img { 
            width: 115px; height: 115px; border-radius: 50%; border: 2px solid #00a2ff; 
            box-shadow: 0 0 25px rgba(0,162,255,0.5); background: #222; margin: 0 auto;
            display: flex; align-items: center; justify-content: center; font-size: 2rem; color: #00a2ff;
        }

        .username { font-size: 1.8rem; font-weight: bold; margin-top: 10px; }
        .bio { color: #888; font-size: .95rem; margin-bottom: 20px; }
        .about-section { background: rgba(0,162,255,0.05); border: 1px solid #00a2ff; border-radius: 12px; padding: 20px; margin-bottom: 30px; }
        .about-section h2 { color: #00a2ff; font-size: 1.1rem; margin-bottom: 10px; }
        .about-section p { font-size: .85rem; line-height: 1.6; color: #ddd; }
        h2 { font-size: .85rem; color: #00a2ff; margin: 25px 0 12px 5px; text-transform: uppercase; letter-spacing: 2px; align-self: flex-start; }
        .card { background: rgba(255,255,255,0.03); border: 1px solid #1a1a1a; border-radius: 12px; padding: 18px; margin-bottom: 12px; text-decoration: none; color: #fff; display: flex; align-items: center; justify-content: space-between; transition: .3s; cursor: pointer; }
        .card:hover { border-color: #00a2ff; background: rgba(0,162,255,0.08); transform: translateX(8px); }
        .card-content h3 { font-size: 1rem; }
        .card-content p { font-size: .75rem; color: #666; }
        .version-warning { font-size: .65rem; color: rgba(255,255,255,0.2); margin-top: 5px; display: block; }
    </style>
</head>
<body>
    <div class="container">
        <div class="profile-container">
            <div class="profile-img"><i class="fas fa-user"></i></div>
            <div class="username">rimusic</div>
            <div class="bio">Sorry Noob</div>
        </div>

        <div class="about-section">
            <h2><i class="fas fa-user"></i> Sobre Mim</h2>
            <p>Sou <b>Game Dev</b> e <b>Roblox Developer</b> há 6 anos. Especialista em <b>Luau</b> e <b>JavaScript</b>.</p>
        </div>

        <h2>Perfis Oficiais</h2>
        <a href="https://discord.com/users/rimusic._" class="card" target="_blank">
            <div class="card-content"><h3>Discord</h3><p>rimusic._</p></div>
            <i class="fab fa-discord" style="color:#5865F2"></i>
        </a>
        <a href="https://www.roblox.com/users/profile?username=raymen7102" class="card" target="_blank">
            <div class="card-content"><h3>Roblox</h3><p>raymen7102</p></div>
            <i class="fas fa-cube"></i>
        </a>

        <h2>Trabalhos</h2>
        <div class="card">
            <div class="card-content"><h3>Sites Criados</h3><p>Veja meus projetos web.</p></div>
            <i class="fas fa-code"></i>
        </div>

        <h2>Contato</h2>
        <a href="https://discord.com/users/rimusic._" class="card" style="border-color:rgba(255,68,68,0.4)" target="_blank">
            <div class="card-content"><h3>Reportar Bugs</h3><p>Algo quebrou? Me avise.</p></div>
            <i class="fas fa-bug" style="color:#ff4444"></i>
        </a>

        <h2>Sessão</h2>
        <div class="card" style="cursor:default">
            <div class="card-content"><h3>V.00.01</h3><span class="version-warning">Pode cometer bugs por conta da versão do site</span></div>
            <i class="fas fa-code-branch" style="color:#444"></i>
        </div>
    </div>
</body>
</html>

