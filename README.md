# 💻 Desafio DIO - Criando e Conectando uma Máquina Virtual na Azure

Este repositório documenta minha experiência prática no laboratório da DIO, onde aprendi a criar e acessar uma máquina virtual (VM) na plataforma Microsoft Azure.

---

## 📌 Objetivo do Projeto

- Criar uma máquina virtual no Microsoft Azure
- Configurar o acesso remoto via SSH
- Registrar o processo em um repositório público como material de apoio para estudos

---

## 🧠 Conceitos Praticados

- Criação de VM no Azure
- Escolha de sistema operacional adequado (Linux ou Windows)
- Conexão via SSH
- Uso do terminal remoto (Linux)

---

## 🛠️ Etapas Realizadas

### 1. Acesso ao Portal da Azure
- Acesse: [https://portal.azure.com](https://portal.azure.com)

### 2. Criação da Máquina Virtual
- **Sistema Operacional**: Ubuntu 24.04 LTS
- **Tamanho da VM**: Standard B1s (1 vCPU, 1 GB RAM)
- **Usuário**: `Atila-2025`
- **Método de Autenticação**: Senha
- **Portas liberadas**: 22 (SSH)

### 3. Conexão à VM via Terminal (SSH)

No PowerShell (Windows), usei o seguinte comando:

```bash
ssh Atila-2025@<IP_PÚ20.226.172.164>

Ao conectar, digitei a senha cadastrada

A conexão foi bem-sucedida ✅

4. Resultado da Conexão

🧪 Comandos Testados
bash
Copiar
Editar
# Verificar diretório atual
pwd

# Listar arquivos
ls

# Criar um arquivo de teste
echo "Olá, Azure!" > teste.txt

# Ver conteúdo do arquivo
cat teste.txt

# Ver uso de sistema
top
📂 Estrutura do Repositório
markdown
Copiar
Editar
📁 azure-vm-lab
├── README.md
└── images
    └── conexao-ssh.png


📸 Capturas de Tela
As imagens estão disponíveis na pasta /images deste repositório.

🚀 Aprendizados
Entendi na prática como criar e acessar VMs na Azure

Pratiquei comandos básicos no Linux remoto

Aprendi a usar o GitHub para documentar um projeto técnico

📚 Recursos
Documentação Azure - Criar VM

Guia SSH no Azure

Guia Markdown GitHub

🧑‍💻 Desenvolvido por: Atila Almeida Santana
🔗 Perfil DIO: https://www.dio.me/users/inov9midia
🔗 GitHub: https://github.com/atila-source