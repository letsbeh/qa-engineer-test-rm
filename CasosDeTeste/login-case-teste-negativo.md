
# Template de Caso de Teste

Arquivo: `/CasosDeTeste/login-case-teste.md`

| ID | Cenário | Pré-condições | Passos | Resultado Esperado | Resultado Obtido | Prioridade |
| TC00001 | Não logar | Login invalido | 1. Passo | Não logar | Não logar | Alta |

### Padrão BDD

Funcionalidade: Login falhar
Cenário 1: Realizar o login com e-mail invalido

```

Dado que entro no link 
Quando visualizo a tela de login
E preencho os campos de login e senha invalidos
E clico em acessar
Então apresenta a feedback de usuário não cadastrado

```

Adicionar evidência: Link, Curl ,print ou vídeo (se aplicável)
![feedback](evidencias-testes/login-invalido.png)
Link: https://qa.navega.com.vc/login
---