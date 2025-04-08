@import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@100;400;600;700&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Gloock&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Pacifico&display=swap');

:root {
    --verde-claro: #6C9A8B;
    --amarelo-mpb: #F9A825;
    --azul-mpb: #039BE5;
    --marrom-claro: #9E7B3E;
}

body {
    font-size: 1rem;
    font-family: 'Montserrat', sans-serif;
}

header {
    background-color: #ffffff;
}

section {
    padding-bottom: 5rem;
}

.nav-link {
    color: var(--marrom-claro);
    font-weight: 600;
}

.inicio-fundo {
    background-image: url('img/mpb-background.jpg'); /* Imagem com tema MPB */
    background-size: cover;
    background-position: center;
    border-radius: 80px;
    width: 100%;
    height: 606px;
    padding: 40px;
    margin: 0 auto;
}

.img-inicio {
    position: absolute;
    right: 0;
    top: 18rem;
    width: 45rem;
    height: auto;
}

.esquerda-conteudo {
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    gap: 1rem;
}

.botao-inicio {
    background-color: var(--amarelo-mpb);
    border-radius: 30px;
    border: none;
    width: 14em;
    height: 3em;
    align-content: center;
    font-family: 'Pacifico', cursive;
    font-weight: bold;
    text-transform: uppercase;
    letter-spacing: 1px;
    transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.botao-inicio:hover {
    transform: scale(1.05);
    box-shadow: 0 4px 12px rgba(0, 0, 0, 0.2);
}

.display-4 {
    text-shadow: -5px 5px var(--azul-mpb);
}

#tropicalia {
    position: relative;
    padding-top: 5rem;
    margin-top: 3rem;
    margin-bottom: 3rem;
    background: url('img/violao-mpb.png') top right no-repeat, url('img/musica-vintage.png') bottom left no-repeat;
    background-size: 180px 180px;
}

#tropicalia::before {
    content: '';
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background: rgba(0, 0, 0, 0.5);
    z-index: 0;
}

#tropicalia .container {
    display: flex;
    align-items: center;
    justify-content: center;
    position: relative;
    z-index: 1;
}

h2 {
    font-family: 'Gloock', serif;
    font-size: 2.5em;
    color: var(--azul-mpb);
}

#galeria {
    background-color: #f3e0c2; /* Um tom claro, que remete à madeira e ao vintage */
}

.fundo-galeria {
    background: url('img/vintage-mpb.png') bottom right no-repeat;
    background-size: 180px 180px;
}

#contato {
    background-image: url('img/contato-mpb.jpg');
    background-size: cover;
    padding: 4rem 0;
}

#contato .formulario {
    background-color: rgba(255, 255, 255, 0.9);
    padding: 2rem;
    border-radius: 10px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    font-weight: bold;
}

.form-control {
    background-color: #F1EDEF;
    border-radius: 5px;
    padding: 0.8rem;
    font-size: 1rem;
}

.form-control:focus {
    border-color: var(--amarelo-mpb);
    box-shadow: 0 0 5px rgba(255, 170, 0, 0.5); /* Destaque com amarelo MPB */
}

/* Modificação do estilo dos botões e links */
.btn, .nav-link {
    font-family: 'Pacifico', cursive;
    text-transform: uppercase;
    letter-spacing: 1px;
}

footer {
    background-color: #F9A825;
    padding: 1rem;
    color: white;
    font-family: 'Gloock', serif;
    text-align: center;
}

footer i {
    margin: 0 1rem;
    font-size: 2rem;
    color: white;
}

footer p {
    font-size: 1rem;
    font-weight: 300;
}

