# 🧪 Testes E2E — Interface Web com Selenium + Python

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Selenium](https://img.shields.io/badge/Selenium-43B02A?style=for-the-badge&logo=selenium&logoColor=white)
![Pytest](https://img.shields.io/badge/Pytest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white)

Automação de fluxos completos de usuário no site de e-commerce [Automation Exercise](https://automationexercise.com), um site público para prática de QA, usando **Page Object Model**.

## 🧪 Testes Implementados

| Fluxo | Teste | Resultado |
|---|---|---|
| Login | `test_login_com_credenciais_validas` | ✅ Passou |
| Login | `test_login_com_credenciais_invalidas` | ✅ Passou |
| Cadastro | `test_criar_nova_conta_com_sucesso` | ✅ Passou |
| Checkout | `test_finalizar_compra_com_sucesso` | ✅ Passou |

## 🛠️ Tecnologias

| Ferramenta | Uso |
|---|---|
| Python | Linguagem dos testes |
| Selenium | Automação do navegador |
| Pytest | Framework de testes |
| pytest-html | Relatório HTML |
| webdriver-manager | Gerencia o driver do Chrome |

## 📁 Estrutura do Projeto


## ▶️ Como Executar

```bash
pip install -r requirements.txt
pytest
```

Em `tests/test_login.py` e `tests/test_checkout.py`, troque `VALID_EMAIL`, `EMAIL` e `PASSWORD` por uma conta real do site (rode `test_cadastro.py` primeiro para criar uma).

Ao rodar, são gerados localmente um relatório HTML em `reports/` e prints de cada teste em `screenshots/`.

## 📸 Evidências

**Login com credenciais válidas**

![Login válido](evidencias%20projeto/test_login_com_credenciais_validas_PASSOU.png)

**Login com credenciais inválidas**

![Login inválido](evidencias%20projeto/test_login_com_credenciais_invalidas_PASSOU.png)

**Cadastro de nova conta**

![Cadastro](evidencias%20projeto/test_criar_nova_conta_com_sucesso_PASSOU.png)

**Checkout**

![Checkout](evidencias%20projeto/test_finalizar_compra_com_sucesso_PASSOU.png)

## 🚀 Próximos Passos

- Testes de recuperação de senha e edição de perfil
- Integração com GitHub Actions
- Testes de responsividade (mobile/desktop)

## 👩‍💻 Autora

**Idna Reis**

QA | Analista de Qualidade | Automação de Testes

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/idna-reis)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/IdnaReis)
