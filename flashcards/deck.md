[
  {
    "id": 1,
    "front": "Qual a diferença entre grupo ATRIBUÍDO e DINÂMICO?",
    "back": "Atribuído: você adiciona pessoas manualmente (1 por 1). Dinâmico: Azure adiciona automaticamente por regra (ex: dept=RH). Dinâmico precisa licença Business Premium.",
    "topic": "Grupos & Entra ID",
    "created": "2026-07-09",
    "due": "2026-07-10",
    "interval": 1,
    "ease": 2.3,
    "reps": 0,
    "lapses": 0
  },
  {
    "id": 2,
    "front": "O que é Acesso Condicional (Conditional Access)?",
    "back": "Regras que controlam 'quem acessa quando'. Exemplo: 'Se grupo=RH E dispositivo=Android E hora=19h-7h ENTÃO bloqueie'. Configurado em entra.microsoft.com. Primeira regra que bate é aplicada (ordem importa).",
    "topic": "Segurança & Entra ID",
    "created": "2026-07-09",
    "due": "2026-07-11",
    "interval": 3,
    "ease": 2.3,
    "reps": 0,
    "lapses": 0
  },
  {
    "id": 3,
    "front": "Como validar um custom domain no Azure (ex: empresa.com.br)?",
    "back": "1. Entra ID → Custom Domains → Adicionar 'empresa.com.br'. 2. Azure gera código (MS=xxx). 3. Você vai no DNS externo (Registro.br, GoDaddy) e cria registro TXT com o código. 4. Volta ao Entra ID e clica 'Verificar'. 5. Azure valida automaticamente.",
    "topic": "Custom Domains & Validação",
    "created": "2026-07-09",
    "due": "2026-07-12",
    "interval": 4,
    "ease": 2.3,
    "reps": 0,
    "lapses": 0
  },
  {
    "id": 4,
    "front": "Por que precisa atribuir LICENÇA antes de Intune instalar Office 365?",
    "back": "Licença = autorização legal + funcional. Sem licença, Intune não pode instalar (usuário não pagou). Fluxo: admin.microsoft.com (compra & atribui licença) → Intune verifica → libera instalação se usuário tem licença E5 ou superior.",
    "topic": "Intune & Licenças",
    "created": "2026-07-09",
    "due": "2026-07-13",
    "interval": 5,
    "ease": 2.3,
    "reps": 0,
    "lapses": 0
  }
]