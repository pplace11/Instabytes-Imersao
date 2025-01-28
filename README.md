# Instabytes-Imersao

Instabytes é uma aplicação inovadora em JavaScript e Shell, criada pela Alura. Ela oferece análise e visualização de dados em tempo real com eficiência e rapidez.

📋 **Funcionalidades**

### Gestão de Posts
- **Criação de Posts**: Permite aos usuários criar novos posts com fotos e descrições.
- **Consulta de Posts**: Exibe os posts criados pelos usuários em um feed dinâmico.
- **Atualização de Posts**: Permite que os usuários editem as descrições dos seus posts.
- **Eliminação de Posts**: Permite que os usuários removam seus posts.

### Gestão de Usuários
- **Registo de Usuários**: Permite que novos usuários se registrem com nome, e-mail e senha.
- **Consulta de Usuários**: Exibe informações dos perfis dos usuários, incluindo posts e seguidores.
- **Atualização de Usuários**: Permite que os usuários atualizem suas informações de perfil.
- **Eliminação de Usuários**: Permite que os usuários desativem ou excluam suas contas.

### Interações Sociais
- **Curtidas**: Permite que os usuários curtam os posts de outros usuários.
- **Comentários**: Permite que os usuários comentem nos posts.
- **Seguir/Deixar de Seguir**: Permite que os usuários sigam ou deixem de seguir outros usuários.
- **Mensagens Diretas**: Permite que os usuários enviem mensagens privadas uns aos outros.

### Visualização de Dados
- **Feed de Notícias**: Exibe os posts dos usuários seguidos em uma linha do tempo.
- **Explorar**: Apresenta posts populares e recomendados.
- **Notificações**: Informa os usuários sobre novas curtidas, comentários e seguidores.

🛠️ **Tecnologias Utilizadas**
- **JavaScript** 📜 — Linguagem de programação principal para lógica do frontend.
- **Shell** 🐚 — Utilizado para scripts de automação e tarefas do backend.
- **HTML5 + CSS3** 🎨 — Templates estilizados para a interface da aplicação.

⚙️ **Como Executar o Projeto**

### Pré-requisitos
Certifique-se de ter o Node.js e o npm instalados.

1. **Clone o repositório:**
   ```bash
   git clone https://github.com/pplace11/Instabytes-Imersao.git
   cd Instabytes-Imersao
   ```
2. **Instale as dependências:**
```bash
npm install
```

3. **Execute a aplicação:**
```bash
npm start
```

4. **Acesse a aplicação em seu navegador:**
```bash
http://localhost:3000
```
🗂️ Estrutura do Projeto
```plaintext
Instabytes-Imersao/
├── 📂 imersao-backend-gemini-2024-front-main/  # Parte do HTML e CSS
├── 📂 src/
│   ├── 📂 config/          # Configurações da aplicação
│   ├── 📂 controllers/     # Controladores para lidar com as requisições
│   ├── 📂 models/          # Modelos de dados
│   ├── 📂 routes/          # Definição das rotas da aplicação
│   └── 📂 services/        # Lógica de negócio organizada em serviços
├── 📂 uploads/             # Diretório para armazenamento de uploads de imagens
├── 📄 package.json         # Dependências do projeto
├── 📄 package-lock.json    # Arquivo de bloqueio de dependências do NPM
├── 📄 server.js            # Ponto de entrada principal da aplicação
└── 📄 services.sh          # Script de serviços
```
