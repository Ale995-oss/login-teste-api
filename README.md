# 🚀 Automação de Testes de API: Fluxo de Login

Validando segurança, resiliência e regras de negócio com foco em Quality Assurance (QA).

---

## 📌 Sobre o Projeto
Olá! Seja muito bem-vindo(a) ao meu repositório. 

Este projeto foi desenvolvido com um objetivo muito claro: ir além do óbvio na validação de uma API de autenticação (Login). Em vez de testar apenas se o sistema funciona quando tudo está correto, estruturei cenários completos para garantir que a aplicação seja segura, trate erros de forma elegante e mantenha a integridade dos dados sob qualquer condição.

Esse projeto reflete diretamente a minha dedicação prática à área de **Quality Assurance (QA)**, aplicando técnicas de cobertura de testes, validação de contratos de payloads e automação de requisições.

---

## 🎯 Cenários de Testes Cobertos
A collection do Postman foi planejada e estruturada para cobrir as principais regras de negócio do fluxo de login:

*   **Sucesso na Autenticação (Cenário Feliz):** Validação de login com credenciais válidas, garantindo o retorno do Status Code `200 OK` e o recebimento correto do Bearer/JWT Token de acesso.
*   **Validação de Segurança (Acesso Negado):** Testes enviando senhas incorretas ou usuários inexistentes, garantindo o retorno apropriado de `401 Unauthorized` ou `404 Not Found`, certificando de que nenhuma informação sensível do banco de dados seja exposta na mensagem de erro.
*   **Campos Obrigatórios & Contrato:** Validação do comportamento do sistema ao omitir dados obrigatórios (como enviar o e-mail vazio ou sem o campo de senha), garantindo o retorno correto de `400 Bad Request`.

---

## 🛠️ Tecnologias e Ferramentas Utilizadas
*   **Postman:** Ferramenta principal utilizada para criar, organizar e disparar as requisições HTTP.
*   **Postman JavaScript Tests:** Criação de scripts automatizados em JavaScript (na aba *Tests*) para validar asserções automáticas de Status Code, tempo de resposta (performance) e estrutura do JSON de retorno.
*   **Variables (Variáveis de Ambiente):** Configuração de ambientes dinâmicos para evitar dados estáticos (*hardcoded*), seguindo as boas práticas de manutenção de testes.
* **C# / . NET CORE :** Linguagem e framework utilizados para o desenvolvimento da API simulada / testada.
---

## 🚀 Como Executar e Validar os Testes
Se você deseja importar este projeto e rodar as validações localmente na sua máquina, o processo é muito simples:

1.  Faça o download do arquivo presente neste repositório: `programação do zero.postman_collection.json`.
2.  Abra o seu **Postman**.
3.  No canto superior esquerdo, clique no botão **Import** e selecione o arquivo baixado.
4.  Com a collection carregada, clique com o botão direito sobre ela e selecione **Run Collection** para rodar toda a esteira de testes automatizados de uma só vez.

---

## 🤝 Vamos nos conectar?
Estou em constante evolução, focado em automação de testes, qualidade de software e metodologias ágeis. Se você é recrutador, tech lead ou desenvolvedor, adoraria trocar uma ideia com você!

*   * **LinkedIn:** [Alessandro de Santana](https://www.linkedin.com/in/alessandro-desantana)
* **E-mail:** (Desantanasantosalessandro@gmail.com)
*
*
