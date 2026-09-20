<main>
  <div align="center" id="top"> 
    <a href="https://vcnafacul.com.br" target="_blank">
      <img src="/assets/Logo-transparente.png" alt="Logo">
    </a>
  </div>

  <h1 align="center">📚 Você na Facul - Democratizando o Acesso à Educação! 🎓</h1>

  <p align="center">
    <strong>Uma plataforma de estudos pré-vestibular acessível e gratuita, feita para transformar vidas!</strong>
  </p>

  <p align="justify">
    O <strong>Você na Facul</strong> é um projeto social sem fins lucrativos, criado para ampliar o acesso à educação 
    de qualidade para estudantes de baixa renda. Nossa plataforma é desenvolvida exclusivamente para cursinhos populares, 
    oferecendo conteúdos e ferramentas que ajudam na preparação para o vestibular e o ENEM.
  </p>

  <p align="justify">
    Acreditamos que a educação pode mudar destinos, e para isso contamos com uma equipe apaixonada de voluntários e 
    colaboradores das áreas de <strong>desenvolvimento de software, design, planejamento pedagógico e gestão de projetos</strong>. 
    Trabalhamos juntos para garantir que milhares de jovens tenham a oportunidade de entrar no ensino superior.
  </p>

  <h2>🧩 Nossos projetos</h2>

A plataforma é dividida em serviços independentes, cada um no seu repositório:

| Repositório | O que faz | Stack |
|---|---|---|
| 🚀 [client-vcnafacul](https://github.com/vcnafacul/client-vcnafacul) | Interface que estudantes, cursinhos e a equipe usam no dia a dia | React + Vite + Tailwind |
| 📚 [api-vcnafacul](https://github.com/vcnafacul/api-vcnafacul) | Gateway da plataforma: autenticação, cursinhos, estudantes e permissões | NestJS + TypeORM + MySQL |
| 🧪 [ms-simulado](https://github.com/vcnafacul/ms-simulado) | Banco de questões, montagem de simulados, correção e relatórios | NestJS + MongoDB |
| 🖨️ [ms-omr](https://github.com/vcnafacul/ms-omr) | Lê por foto o cartão-resposta preenchido à mão e devolve as marcações | Python + FastAPI + OpenCV |
| 📝 [vcnafacul-form](https://github.com/vcnafacul/vcnafacul-form) | Formulários e regras de pontuação do processo seletivo dos cursinhos | NestJS + MongoDB |

Como eles conversam entre si:

```
client-vcnafacul  →  api-vcnafacul  →  ms-simulado  →  ms-omr
   (React SPA)      (NestJS gateway)    (provas)      (leitura do cartão)
                           ↓
                     vcnafacul-form
                (formulários e seleção)
```

O frontend fala **apenas** com a `api-vcnafacul`. Os microsserviços não são expostos ao público.

  <h2>🤝 Como você pode ajudar?</h2>
  

O **Você na Facul** é um projeto social movido por voluntários apaixonados pela educação. Se você acredita que todos devem ter acesso a um ensino de qualidade, há diversas formas de ajudar essa causa!  

### 💻 Desenvolvedores  
Nosso projeto é open-source e sempre há espaço para melhorias. Escolha um dos repositórios acima, dê uma olhada nas *issues* e envie um PR! Cada repositório tem no próprio README o passo a passo para rodar o serviço localmente.

Não sabe por onde começar? Procure issues marcadas como `good first issue` ou fale com a gente pelo e-mail abaixo.

### 📖 Educadores  
Se você é professor ou educador e quer ajudar na criação de materiais, revisão de conteúdos ou sugestões pedagógicas, entre em contato conosco pelo e-mail: [contato@vcnafacul.com.br](mailto:contato@vcnafacul.com.br).  

### 📢 Divulgadores  
Acredita na nossa missão? Então ajude divulgando o **Você na Facul**! Compartilhe nas redes sociais, fale sobre o projeto com amigos, cursinhos populares e estudantes que possam se beneficiar da plataforma.  

### 💙 Apoie financeiramente  
Doações ajudam a manter a infraestrutura que atende os cursinhos parceiros. Para apoiar ou entender como sua empresa pode patrocinar o projeto, fale com a gente em [contato@vcnafacul.com.br](mailto:contato@vcnafacul.com.br).  

### 🙌 Junte-se a nós!  
Toda ajuda é bem-vinda. Independentemente de sua área de atuação, se você quer transformar vidas através da educação, venha fazer parte do **Você na Facul**!  

Juntos, podemos abrir portas para um futuro com mais oportunidades para todos. 🚀  

  <h2>📬 Contato</h2>
  <div>✉️ <strong>Email:</strong> <a href="mailto:contato@vcnafacul.com.br">contato@vcnafacul.com.br</a></div>
  <div>
    🌐 <strong>Site:</strong> 
    <a href="https://vcnafacul.com.br">vcnafacul.com.br</a>
  </div>

  <h2>🛠️ Tecnologias Utilizadas</h2>

 [![React](https://img.shields.io/badge/-React-61DAFB?style=flat&logo=react&logoColor=white)](https://react.dev/)
 [![Typescript](https://img.shields.io/badge/-Typescript-3178C6?style=flat&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
 [![Vite](https://img.shields.io/badge/-Vite-646CFF?style=flat&logo=vite&logoColor=white)](https://vite.dev/)
 [![Tailwind](https://img.shields.io/badge/-Tailwind-38B2AC?style=flat&logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)
 [![Zustand](https://img.shields.io/badge/-Zustand-000?style=flat&logo=zustand&logoColor=white)](https://zustand-demo.pmnd.rs/)
 [![Nest JS](https://img.shields.io/badge/-NestJS-E0234E?style=flat&logo=nestjs&logoColor=white)](https://nestjs.com/)
 [![Node](https://img.shields.io/badge/-Node-339933?style=flat&logo=node.js&logoColor=white)](https://nodejs.org/en)
 [![Mysql](https://img.shields.io/badge/-Mysql-4479A1?style=flat&logo=mysql&logoColor=white)](https://www.mysql.com/)
 [![Mongo](https://img.shields.io/badge/-Mongo-47A248?style=flat&logo=mongodb&logoColor=white)](https://www.mongodb.com/)
 [![Redis](https://img.shields.io/badge/-Redis-FF4438?style=flat&logo=redis&logoColor=white)](https://redis.io/)
 [![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white)](https://www.python.org/)
 [![FastAPI](https://img.shields.io/badge/-FastAPI-009688?style=flat&logo=fastapi&logoColor=white)](https://fastapi.tiangolo.com/)
 [![OpenCV](https://img.shields.io/badge/-OpenCV-5C3EE8?style=flat&logo=opencv&logoColor=white)](https://opencv.org/)
 [![Swagger](https://img.shields.io/badge/-Swagger-85EA2D?style=flat&logo=swagger&logoColor=black)](https://swagger.io/)
 [![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat&logo=docker&logoColor=white)](https://www.docker.com/)
 [![Nginx](https://img.shields.io/badge/-Nginx-269539?style=flat&logo=nginx&logoColor=white)](https://nginx.org/en/)
 [![Figma](https://img.shields.io/badge/-Figma-F24E1E?style=flat&logo=figma&logoColor=white)](https://www.figma.com/)

</main>
