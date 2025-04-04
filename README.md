/* Estilos gerais */
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f8f8f8;
}

/* Cabeçalho */
header {
    background-color: #d32f2f;
    color: white;
    text-align: center;
    padding: 20px;
    font-size: 24px;
    font-weight: bold;
}

/* Menu de navegação */
nav {
    background-color: #b71c1c;
    padding: 10px;
    text-align: center;
}

nav a {
    color: white;
    text-decoration: none;
    margin: 0 15px;
    font-size: 18px;
}

/* Cardápio */
.container {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    padding: 20px;
}

.card {
    background: white;
    margin: 10px;
    padding: 15px;
    border-radius: 8px;
    box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
    text-align: center;
    width: 250px;
}

.card img {
    max-width: 100%;
    border-radius: 8px;
}

/* Rodapé */
footer {
    background-color: #d32f2f;
    color: white;
    text-align: center;
    padding: 15px;
    margin-top: 20px;
    font-size: 16px;
}

/* Informações de contato */
.contact-info {
    margin-top: 10px;
    font-size: 14px;
}

/* Responsividade */
@media (max-width: 768px) {
    .container {
        flex-direction: column;
        align-items: center;
    }
}
