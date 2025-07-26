# 🌐 Homade Site - Dashboard Administrativo

Este é o repositório oficial do projeto **Homade**, uma plataforma de acompanhamento e administração de indicações com integração via Supabase.

> ✅ Totalmente responsivo  
> 🚀 Pronto para deploy no Netlify ou Vercel  
> 🧩 HTML + CSS + JavaScript puro  
> 🔐 Backend via Supabase  

---

## 📁 Estrutura do Projeto

```
/
├── index.html                # Página principal do dashboard
├── admin.html               # Página administrativa
├── acompanhamento.html      # Página de acompanhamento
├── style.css                # Estilos globais
├── admin.css                # Estilos da área admin
├── acompanhamento.css       # Estilos da área de acompanhamento
├── script.js                # Scripts da dashboard
├── admin.js                 # Scripts da área admin
├── acompanhamento.js        # Scripts da área de acompanhamento
├── supabaseClient.js        # Conexão com Supabase
└── /assets                  # Imagens e ícones
```

---

## 🚀 Deploy com Netlify (recomendado)

### 1. Crie uma conta em [netlify.com](https://netlify.com)  
### 2. Clique em **"Import from GitHub"**
### 3. Selecione este repositório (`homade-site`)
### 4. Configurações:

- Build Command: *(deixe vazio)*
- Publish directory: `./`

### 5. Clique em **Deploy**

Seu site ficará disponível em:  
`https://nomedosite.netlify.app`

---

## 🌐 Domínio personalizado (opcional)

No painel da Netlify:
- Vá em **Site Settings > Domain Management**
- Clique em **Add custom domain**
- Configure seu próprio domínio ou registre um grátis com `.netlify.app`

---

## 🧑‍💻 Contribuição e Manutenção

- Edite os arquivos HTML, CSS ou JS localmente
- Faça push no GitHub
- O Netlify atualiza automaticamente o site

---

## 🛠️ Tecnologias utilizadas

- HTML5 + CSS3 + JavaScript ES6
- Supabase (Auth + Banco de Dados)
- Netlify (deploy)

---

## 🔒 Credenciais e Variáveis

As credenciais do Supabase devem ser colocadas no arquivo `supabaseClient.js`.  
⚠️ **Não suba credenciais sensíveis em repositórios públicos.**

---

## 🧾 Licença

Este projeto é livre para uso e modificação.  
Consulte os termos da licença na pasta `/LICENSE` (se aplicável).
