# Projeto Equipa Vértice - Sistema de Gestão Clínica de Estética

<p align="center">
  <img src="https://github.com/claudiamachado27/apresentacaofinalfe/blob/main/images/logo-ve%CC%81rtice.png" alt="Logo Vértice" width="200">
</p>

## 📋 Sobre o Projeto

Este projeto é o **Trabalho Final do Curso de Front-End**, desenvolvido pela **Equipa Vértice** para o cliente **Templo de Gaya** (Aveiro).

Não se trata apenas de uma aplicação, mas de um **Ecossistema Digital de Gestão Operacional** desenhado para otimizar os processos administrativos e operacionais de uma clínica de estética. O foco principal é a automação de processos e a inteligência de dados, apresentados através de uma interface "Clean & Professional" que transmite higiene, bem-estar e profissionalismo.

## 🚀 Funcionalidades Principais

- **Gestão Operacional**: Controle total sobre as atividades diárias da clínica.
- **Ecossistema de Dados**: Inteligência aplicada para otimização de eficiência.
- **Interface Moderna**: UI intuitiva focada em usabilidade e experiência do utilizador.
- **Design Responsivo**: Adaptado para diversos dispositivos.

## 🛠️ Stacks Utilizadas

O projeto utiliza tecnologias de ponta para garantir performance e escalabilidade:

### Frontend
- **React**: Biblioteca principal para construção da UI.
- **Inertia.js**: A ponte perfeita entre o backend clássico e o frontend moderno.
- **Vite**: Build tool extremamente rápida.
- **Bootstrap 5**: Framework CSS para layout responsivo e componentes.

### Backend
- **Laravel (PHP)**: Framework robusto para lógica de negócio e segurança.
- **Breeze**: Starter kit para autenticação mínima e simples.

### Base de Dados
- **MySQL**: Armazenamento de dados relacional fiável.

## 👥 A Equipa

O projeto foi desenvolvido pela tríade da **Equipa Vértice**:

- **Anthony Mendoza** - Front-end Developer - [GitHub Profile](https://github.com/Anthonydcm1)
- **Claudia Machado** - Front-end Developer - [GitHub Profile](https://github.com/claudiamachado27)
- **Taís Pestana** - Front-end Developer - [GitHub Profile](https://github.com/taispestana/)

## ⚙️ Instalação e Configuração

Para rodar este projeto localmente, siga os passos abaixo:

### Pré-requisitos
- PHP 8.2+
- Composer
- Node.js & NPM
- MySQL

### Passos
1. **Clonar o repositório:**
   git clone [url-do-repositorio]
   cd apresentacao

2. **Instalar dependências de Backend:**
   composer install

3. **Instalar dependências de Frontend:**
   npm install

4. **Configurar o Ambiente:**
   - Copie o ficheiro `.env.example` para `.env`
   - Configure os dados da sua base de dados MySQL no `.env`.
   - Gere a chave da aplicação:
     php artisan key:generate

5. **Executar Migrações:**
   php artisan migrate
   

6. **Iniciar os Servidores:**
   - No terminal 1 (Laravel):
     php artisan serve

   - No terminal 2 (Vite):
     npm run dev

## 📄 Licença

Esta apresentação foi desenvolvida para fins académicos como parte do Projeto Final de Curso de Front-End Developer.

---
*Design e Desenvolvimento com ❤️ por Claudia Machado | Todos os direitos reservados © 2026*
