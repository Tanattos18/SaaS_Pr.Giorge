# Estrutura da plataforma

Protótipo navegável em `index.html`. Abra o arquivo no navegador; não precisa instalar nada.
Nome da escola, cursos, preços e números do painel são exemplos. Nenhum pagamento é real.

## Páginas

| Página | Endereço | O que faz |
|---|---|---|
| Início | `#inicio` | Apresenta a escola, o catálogo, o passo a passo, o professor e as dúvidas |
| Curso | `#c-<curso>` | Descrição, sumário, preço e botão de compra |
| Entrar | `#entrar` | Login do aluno, exigido antes de pagar |
| Pagamento | `#pagar-<curso>` | Pix ou cartão, com a liberação automática simulada |
| Minha biblioteca | `#biblioteca` | PDFs comprados e cursos ainda bloqueados |
| Painel do pastor | `#painel` | Vendas, alunos, cursos mais vendidos e publicação de cursos |

## Seções da página inicial

1. Abertura com a estante de cursos
2. Catálogo com filtro por área (Bíblia, Doutrina, Ministério)
3. Como funciona, em três passos
4. Professor e depoimentos
5. Perguntas frequentes

## Caminho do aluno

Início → Curso → Entrar → Pagamento → Confirmação do banco → Minha biblioteca → Baixar PDF

## O que o pastor precisa enviar

- Nome da escola e logo
- Foto, história e formação
- Lista real de cursos, com descrição, sumário e preço
- PDFs das apostilas
- Depoimentos reais de alunos, com autorização

## O que é simulado neste protótipo

- Login: usa uma conta de demonstração fixa
- Pagamento: um botão imita o aviso de confirmação do banco
- Download: mostra uma prévia da página com a marca d'água
- Painel: números de exemplo, somados às compras simuladas
- Compras simuladas ficam guardadas só no navegador de quem testa
