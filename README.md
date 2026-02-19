<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Paulo Odilon | Tecnologia & Educação</title>

<link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&display=swap" rel="stylesheet">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">

<style>
*{margin:0;padding:0;box-sizing:border-box}

body{
    font-family:'Inter',sans-serif;
    background:#0f172a;
    color:#f1f5f9;
}

header{
    padding:80px 20px;
    text-align:center;
    background:linear-gradient(135deg,#2563eb,#7c3aed);
}

header h1{
    font-size:2.8rem;
    font-weight:700;
}

header p{
    margin-top:15px;
    font-size:1.2rem;
    opacity:0.9;
}

.container{
    max-width:1100px;
    margin:auto;
    padding:60px 20px;
}

.section{
    margin-bottom:60px;
}

.section h2{
    font-size:1.8rem;
    margin-bottom:25px;
    color:#38bdf8;
}

.grid{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(280px,1fr));
    gap:20px;
}

.card{
    background:#1e293b;
    padding:25px;
    border-radius:15px;
    transition:.3s;
}

.card:hover{
    transform:translateY(-5px);
    background:#334155;
}

ul{
    list-style:none;
}

li{
    margin-bottom:10px;
}

.badge{
    display:inline-block;
    padding:6px 10px;
    background:#2563eb;
    border-radius:8px;
    margin:5px 5px 0 0;
    font-size:0.8rem;
}

footer{
    text-align:center;
    padding:30px;
    background:#020617;
    font-size:0.9rem;
    opacity:0.6;
}

a{
    color:#38bdf8;
    text-decoration:none;
}
</style>
</head>
<body>

<header>
    <h1>Paulo Odilon</h1>
    <p>Especialista em Tecnologia, Educação Profissional e Metodologias Ativas</p>
</header>

<div class="container">

    <div class="section">
        <h2><i class="fa-solid fa-user-graduate"></i> Sobre</h2>
        <p>
            Profissional com mais de 13 anos de experiência em educação profissional,
            atuando nas áreas de Tecnologia da Informação, Gestão, Turismo e Hospitalidade.
            Experiência em ensino presencial e remoto, metodologias ativas e formação técnica.
        </p>
    </div>

    <div class="section">
        <h2><i class="fa-solid fa-code"></i> Competências Técnicas</h2>
        <div>
            <span class="badge">Python</span>
            <span class="badge">Java</span>
            <span class="badge">JavaScript</span>
            <span class="badge">Flutter (Dart)</span>
            <span class="badge">C</span>
            <span class="badge">MySQL</span>
            <span class="badge">Excel Avançado</span>
            <span class="badge">Scrum & Agile</span>
            <span class="badge">AWS Cloud Foundations</span>
            <span class="badge">LGPD Foundations</span>
        </div>
    </div>

    <div class="section">
        <h2><i class="fa-solid fa-briefcase"></i> Experiência Profissional</h2>
        <div class="grid">
            <div class="card">
                <h3>Instrutor de Educação Profissional</h3>
                <p><strong>SENAC / CE</strong></p>
                <p>Atuação em cursos de Informática, Excel, Gestão e Tecnologia da Informação.</p>
            </div>

            <div class="card">
                <h3>Instrutor – Jovem Aprendiz</h3>
                <p><strong>CIEE & Instituições Parceiras</strong></p>
                <p>Formação em gestão, ética profissional, liderança e comunicação.</p>
            </div>

            <div class="card">
                <h3>Instrutor Técnico</h3>
                <p><strong>Instituições Técnicas</strong></p>
                <p>Docência em Administração, Logística, Estatística e Qualidade.</p>
            </div>
        </div>
    </div>

    <div class="section">
        <h2><i class="fa-solid fa-graduation-cap"></i> Formação</h2>
        <ul>
            <li>Especialização em Docência para Ensino Profissionalizante – SENAC</li>
            <li>Graduação em Análise e Desenvolvimento de Sistemas</li>
            <li>Graduação em Hotelaria – IFCE</li>
        </ul>
    </div>

    <div class="section">
        <h2><i class="fa-solid fa-diagram-project"></i> Áreas de Atuação</h2>
        <ul>
            <li>✔ Educação Profissional e Técnica</li>
            <li>✔ Desenvolvimento de Sistemas</li>
            <li>✔ Metodologias Ativas</li>
            <li>✔ Projetos Ágeis e Scrum</li>
            <li>✔ Cultura DevOps</li>
        </ul>
    </div>

    <div class="section">
        <h2><i class="fa-solid fa-shield-halved"></i> Conformidade & Ética</h2>
        <p>
            Formação em fundamentos da Lei Geral de Proteção de Dados (LGPD),
            aplicando boas práticas de segurança da informação e ética digital
            na educação e tecnologia.
        </p>
    </div>

</div>

<footer>
    © 2026 Paulo Odilon • Tecnologia & Educação • Portfólio Profissional
</footer>

</body>
</html>
