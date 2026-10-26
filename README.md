# Express Demo

Projeto básico em Node.js usando o framework **Express**.

## Estrutura
```
express-demo/
├─ package.json   # dependências e script de start
├─ index.js       # código do servidor
└─ README.md      # este arquivo
```

## Como rodar
1. Abra um terminal na pasta `express-demo`:
   ```bash
   cd C:\Users\alunoifal\.gemini\antigravity\scratch\express-demo
   ```
2. Instale as dependências (já feito, mas caso precise):
   ```bash
   npm install
   ```
3. Inicie o servidor:
   ```bash
   npm start
   ```
   O servidor ficará escutando na porta **3000**.
4. Acesse no navegador ou via `curl`:
   ```bash
   curl http://localhost:3000
   ```
   Você deverá ver a mensagem `Hello, world!`.

## Observações
- O script de start está definido em `package.json` como `node index.js`.
- Não há necessidade de instalar `body-parser` para este exemplo simples, pois o Express já lida com respostas de texto.
- Caso queira mudar a porta, edite a constante `port` em `index.js`.
