# 🤝 Como Contribuir para o Open Prompts BR

Ficamos muito felizes com o seu interesse em contribuir! Este é um espaço colaborativo criado para democratizar o acesso a comandos de IA estruturados e de alta qualidade. 

Para mantermos o repositório organizado e útil para todos, pedimos que você siga as diretrizes abaixo ao enviar o seu prompt.

## 📝 Regras de Submissão

### 1. Nomenclatura Clara e Direta
O nome do arquivo deve deixar óbvio o que o prompt faz, preferencialmente usando letras minúsculas e hífens.
* **❌ Evite:** `prompt1.md`, `meu_prompt_de_estudos.md`, `teste.md`
* **✅ Use:** `entrevista-de-emprego-star.md`, `simulador-de-negocios.md`, `revisao-de-codigo-python.md`

### 2. Variáveis em Colchetes `[ ]`
Para que qualquer pessoa possa reutilizar o seu prompt, todas as informações de contexto pessoal devem ser substituídas por variáveis genéricas entre colchetes.
* **Exemplo:** *"Atue como um especialista em `[Área de Atuação]` e me ajude a criar um plano de estudos para `[Tema ou Ferramenta]`."*

### 3. Apenas Formato Markdown (`.md`)
**Não aceitamos PDFs, arquivos do Word ou outros formatos.** Todos os prompts devem ser enviados estritamente em formato `.md` (Markdown). Isso garante que o repositório seja leve, que o controle de versão funcione perfeitamente e que qualquer pessoa consiga ler e copiar o código direto pelo navegador ou celular.
* No topo do arquivo, inclua uma breve descrição (1 a 2 linhas) explicando qual é o objetivo daquele prompt.
* Sinta-se à vontade para assinar a autoria do prompt no final do arquivo (ex: *Criado por @seugithub*).

### 4. Categorização Correta
Coloque o seu arquivo dentro da pasta que melhor representa o uso daquele prompt (ex: `/carreira_e_entrevistas`, `/programacao_e_tecnologia`). Se o seu prompt for muito específico e não se encaixar em nenhuma, sugira uma nova categoria no seu *Pull Request*.

### 5. Teste Antes de Enviar
Garanta que o seu prompt realmente funciona. Ele deve ter sido testado em alguma das principais IAs (Gemini, ChatGPT, Claude) e deve gerar respostas consistentes.

## 🛠️ Passo a Passo para o Pull Request

1. Faça um **Fork** deste repositório.
2. Crie uma branch para o seu prompt: `git checkout -b meu-novo-prompt`
3. Adicione e faça o commit das suas alterações: `git commit -m "feat: adiciona prompt para [objetivo]"`
4. Envie para o seu Fork: `git push origin meu-novo-prompt`
5. Abra um **Pull Request** detalhando rapidamente o que o prompt faz.
