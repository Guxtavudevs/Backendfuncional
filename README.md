meu-projeto-backend/ 
├── package.json (criado automaticamente) 
├── package-lock.json (criado automaticamente) 
├── node_modules/ (criado automaticamente) 
├── app.js (você vai criar) 
├── database.js (você vai criar) 
├── meuapp.db (criado automaticamente pelo SQLite) 
└── README.md (opcional)


🔧 Como Usar:
// SEMPRE coloque esta linha no seu app.js
app.use(express.json());

// Agora sua API pode receber dados assim:
// { "nome": "João", "idade": 25 }