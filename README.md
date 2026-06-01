# Atividade Prática - Semana 13

Nesta atividade, você vai migrar a estrutura de dados que estava dentro do arquivo JavaScript para um arquivo db.json e utilizar o JSON Server como um “backend” simples para o seu projeto. Para este ambiente local de desenvolvimento, utilizamos além do JSONServer, o Node.js. A sua aplicação ficará com uma estrutura similar à ilustração na imagem a seguir.

## Informações Gerais

- **Nome:** Iale Leles de Almeida
- **Matrícula:** 927707

## Print da página principal mostrando os cards (home):
![alt text](<public/images/Captura de tela 2026-05-31 212343.png>)

## Print da página detalhes:
![alt text](<public/images/Captura de tela 2026-05-31 212353.png>)

- **Resumo da estrutura do db.json:**

```json
{
  "id": 1,
  "nome": "Ollie",
  "categoria": "Iniciante",
  "descricaoCurta": "O salto básico e fundamental do skate.",
  "descricaoCompleta": "O Ollie é a manobra base de todo o skate moderno. Consiste em bater o tail no chão...",
  "imagem": "https://images.unsplash.com/photo-1617034840325-b10d81550042",
  "dificuldade_num": 1,
  "tags": ["solo", "fundamental", "salto"],
  "destaque": true,
  "base": "Regular ou Goofy",
  "dica_mestre": "Bata o tail com força e arraste o pé da frente totalmente para cima."
}

