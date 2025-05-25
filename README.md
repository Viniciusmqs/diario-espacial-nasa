# 🚀 Diário Espacial NASA

![Python](https://img.shields.io/badge/Python-3.8%2B-blue?style=flat&logo=python&logoColor=white)
![Flask](https://img.shields.io/badge/Framework-Flask-black?style=flat&logo=flask&logoColor=white)
![JavaScript](https://img.shields.io/badge/Frontend-JavaScript-yellow?style=flat&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/Web-HTML5-orange?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/Web-CSS3-blue?style=flat&logo=css3&logoColor=white)
![NASA APIs](https://img.shields.io/badge/API-NASA%20APIs-red?style=flat&logo=nasa&logoColor=white)
![MIT License](https://img.shields.io/badge/License-MIT-yellow.svg)

> Uma jornada visual e interativa pelo universo usando as APIs oficiais da NASA.

---

## 🌟 Sobre o Projeto

O **Diário Espacial NASA** é uma aplicação web que conecta usuários ao cosmos, trazendo imagens e vídeos fascinantes diretamente da NASA. Com uma interface moderna e intuitiva, você pode:

- Visualizar a **Imagem Astronômica do Dia (APOD)** de qualquer data.
- Explorar fotos reais capturadas pelo rover **Curiosity em Marte**.
- Mergulhar em uma experiência visual imersiva com fundo dinâmico, modais e navegação fluida.

> Ideal para curiosos, educadores, estudantes ou qualquer apaixonado pelo espaço!

---

## ✨ Principais Funcionalidades

### 🌌 APOD (Astronomy Picture of the Day)
- Consulta personalizada por data (inclusive a do seu nascimento!)
- Exibição de imagem/vídeo, título, explicação e créditos oficiais
- Fundo da página atualizado automaticamente com a mídia do dia
- Modal fullscreen para uma experiência mais envolvente

### 🪐 Galeria de Marte
- Mostra fotos do rover Curiosity com base na data escolhida
- Visualização em miniaturas e modal de destaque para imagem grande
- Aviso amigável quando não há imagens para a data selecionada

### 🎨 Interface Moderna
- Tema escuro elegante e acessível
- Layout responsivo (mobile e desktop)
- Transições suaves e design centrado na experiência do usuário

---

## 🔧 Tecnologias Utilizadas

### Backend

[![Python](https://img.shields.io/badge/Python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)](https://www.python.org/)
[![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)](https://flask.palletsprojects.com/)
[![Requests](https://img.shields.io/badge/Requests-282C34?style=for-the-badge&logo=requests&logoColor=white)](https://docs.python-requests.org/)
[![dotenv](https://img.shields.io/badge/dotenv-%23323330.svg?style=for-the-badge&logo=env&logoColor=white)](https://pypi.org/project/python-dotenv/)

- Flask: Framework web leve e poderoso
- Requests: Cliente HTTP para consumir APIs REST
- Python-dotenv: Carregamento seguro de variáveis de ambiente

### Frontend

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

- HTML/CSS/JS puro para leveza e performance
- JavaScript vanilla para requisições assíncronas e modais

### APIs Externas

[![NASA API](https://img.shields.io/badge/NASA%20API-0B3D91?style=for-the-badge&logo=nasa&logoColor=white)](https://api.nasa.gov/)

- **APOD (Astronomy Picture of the Day)**: imagens e vídeos astronômicos com explicação
- **Mars Rover Photos**: fotos tiradas em Marte pelo rover Curiosity

---

## 🚀 Deploy

O projeto pode ser facilmente hospedado em:

- **Render**
- **Heroku**
- **Railway**

Utilize o `Procfile` já incluído para facilitar o deploy em plataformas PaaS.

🔗 [Projeto online (exemplo de link)](https://diario-espacial-nasa.onrender.com)

---

## ⚙️ Como Rodar Localmente

```bash
# Clone o repositório
git clone https://github.com/Viniciusmqs/diario-espacial-nasa.git
cd diario-espacial-nasa

# Crie um ambiente virtual
python -m venv venv
.\venv\Scripts\Activate  # Windows

# Instale as dependências
pip install -r requirements.txt

# Crie o arquivo .env com sua chave da NASA
echo NASA_API_KEY=SUA_CHAVE_AQUI > .env

# Inicie o servidor Flask
python app.py
