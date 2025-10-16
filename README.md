<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Currículo - Davyd Molina</title>
    <style>
        *{
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body {
            font-family: 'Arial', 'Helvetica', sans-serif;
            line-height: 1.6;
            color: #333;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            padding: 20px;
        }
        .container {
            max-width: 900px;
            margin: 0 auto;
            background: white;
            box-shadow: 0 10px 40px rgba(0, 0, 0, 0.2);
            border-radius: 10px;
            overflow: hidden;
        }
        header {
            background: linear-gradient(135deg, #2c3e50 0%, #34495e 100%);
            color: white;
            padding: 40px 30px;
            text-align: center;
        }
        header h1 {
            font-size: 2.5em;
            margin-bottom: 20px;
            font-weight: bold;
            letter-spacing: 2px;
        }
        .contact-info {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 20px;
            margin-top: 20px;
        }
        .contact-item {
            display: flex;
            align-items: center;
            gap: 8px;
            font-size: 0.95em;
        }
        .contact-item::before {
            content: "●";
            color: #3498db;
            font-size: 1.2em;
        }
        .contact-item a {
            color: #3498db;
            text-decoration: none;
            transition: color 0.3s;
        }
        .contact-item a:hover {
            color: #5dade2;
        }
        main {
            padding: 40px 30px;
        }
        section {
            margin-bottom: 40px;
        }
        section h2 {
            color: #2c3e50;
            font-size: 1.8em;
            margin-bottom: 15px;
            padding-bottom: 10px;
            border-bottom: 3px solid #3498db;
            position: relative;
        }
        section h2::after {
            content: '';
            position: absolute;
            bottom: -3px;
            left: 0;
            width: 60px;
            height: 3px;
            background: #667eea;
        }
        .objetivo p {
            text-align: justify;
            font-size: 1.05em;
            color: #555;
            line-height: 1.8;
        }
        ul {
            list-style: none;
            padding-left: 0;
        }
        ul li {
            padding: 10px 0 10px 30px;
            position: relative;
            color: #555;
        }
        ul li::before {
            content: "▸";
            position: absolute;
            left: 0;
            color: #3498db;
            font-size: 1.3em;
            font-weight: bold;
        }
        .job, .education-item {
            margin-bottom: 20px;
            padding: 15px;
            background: #f8f9fa;
            border-left: 4px solid #3498db;
            border-radius: 5px;
        }
        .job h3, .education-item h3 {
            color: #2c3e50;
            font-size: 1.2em;
            margin-bottom: 5px;
        }
        .job p, .education-item p {
            color: #666;
            font-size: 0.95em;
        }
        .cursos ul li {
            background: #f8f9fa;
            margin: 8px 0;
            padding: 12px 12px 12px 35px;
            border-radius: 5px;
            transition: transform 0.2s, background 0.2s;
        }
        .cursos ul li:hover {
            background: #e3f2fd;
            transform: translateX(5px);
        }
        .habilidades ul li {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            margin: 10px 0;
            padding: 15px 15px 15px 40px;
            border-radius: 8px;
            font-weight: 500;
            box-shadow: 0 3px 10px rgba(102, 126, 234, 0.3);
        }
        .habilidades ul li::before {
            color: white;
        }
        footer {
            background: #2c3e50;
            color: white;
            text-align: center;
            padding: 30px;
        }
        footer p {
            margin-bottom: 10px;
            font-size: 1.1em;
        }
        footer a {
            color: #3498db;
            text-decoration: none;
            font-weight: bold;
            transition: color 0.3s;
        }
        footer a:hover {
            color: #5dade2;
        }
        @media (max-width: 768px) {
            body {
                padding: 10px;
            }
            header h1 {
                font-size: 2em;
            }
            .contact-info {
                flex-direction: column;
                gap: 10px;
            }
            main {
                padding: 30px 20px;
            }
            section h2 {
                font-size: 1.5em;
            }
        }
        @media (max-width: 480px) {
            header h1 {
                font-size: 1.6em;
            }
            header {
                padding: 30px 20px;
            }
            main {
                padding: 20px 15px;
            }
            section {
                margin-bottom: 30px;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <h1>DAVYD MOLINA</h1>
            <div class="contact-info">
                <div class="contact-item">
                    <span>📍 Bairro Sítio Cercado - Curitiba, PR</span>
                </div>
                <div class="contact-item">
                    <span>📧 <a href="mailto:davydeduardo97@gmail.com">davydeduardo97@gmail.com</a></span>
                </div>
                <div class="contact-item">
                    <span>📱 (41) 99813-0514</span>
                </div>
                <div class="contact-item">
                    <span>💼 <a href="https://www.linkedin.com/in/davyd-eduardo" target="_blank">LinkedIn</a></span>
                </div>
            </div>
        </header>
        <main>
            <section class="objetivo">
                <h2>Objetivo</h2>
                <p>Desejo integrar-me à equipe, aplicando dedicação e atenção em atividades de atualização de sistemas, análise e resolução de problemas, sejam de qualquer tipo, procuro soluções que tornam os processos mais rápidos e inteligentes. Busco constantemente aprender novas habilidades e contribuir para o alcance dos objetivos da empresa.</p>
            </section>
            <section class="qualificacao">
                <h2>Qualificação Profissional</h2>
                <ul>
                    <li>Conhecimento aprofundado em formas de uso de Inteligência Artificial (mais de 3 anos de estudo)</li>
                    <li>Conhecimento básico em Programação e Desenvolvimento Web (HTML, CSS, JavaScript)</li>
                </ul>
            </section>
            <section class="experiencia">
                <h2>Experiência Profissional</h2>
                <div class="job">
                    <h3>Estagiário de TI</h3>
                    <p><strong>COPEL</strong> | Atual</p>
                </div>
                <div class="job">
                    <h3>Operador de Teleatendimento</h3>
                    <p><strong>Concentrix</strong> | 10/03/2025 até 19/09/2025</p>
                </div>
            </section>
            <section class="educacao">
                <h2>Educação</h2>
                <div class="education-item">
                    <h3>Análise e Desenvolvimento de Sistemas</h3>
                    <p><strong>Faculdade Positivo</strong> | Cursando</p>
                </div>
                <div class="education-item">
                    <h3>Ensino Médio Completo</h3>
                    <p><strong>Colégio Estadual Hasdruball Bellegard</strong></p>
                </div>
            </section>
            <section class="cursos">
                <h2>Cursos e Formações Complementares</h2>
                <ul>
                    <li>Curso de Informática (2024)</li>
                    <li>Cursos de Programação Alura (2021 a 2024)</li>
                    <li>Curso de Programação em Java básico (2025)</li>
                    <li>Curso de Programação HTML básico (2025)</li>
                    <li>Curso de Programação APIs e Serviços Web (2025)</li>
                    <li>Curso de Programação SQL básico (2025)</li>
                    <li>Curso de Programação Arquitetura de TI (2025)</li>
                    <li>Curso de Programação - Visualização de Dados para Análise e Análise de Dados (2025)</li>
                </ul>
            </section>
            <section class="habilidades">
                <h2>Habilidades</h2>
                <ul>
                    <li>Facilidade em trabalhar em equipe, boa comunicação, organização e flexibilidade para cumprir metas</li>
                    <li>Dedicado, disciplinado, aprendo rápido e possuo iniciativa para lidar com desafios</li>
                </ul>
            </section>
        </main>
        <footer>
            <p><strong>Davyd Molina</strong></p>
            <p>Conecte-se comigo: <a href="https://www.linkedin.com/in/davyd-eduardo" target="_blank">LinkedIn</a></p>
        </footer>
    </div>
</body>
</html>
