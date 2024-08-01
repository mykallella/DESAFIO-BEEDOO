# BEEDOO - Desafio | Analista de Qualidade de Software Júnior

![preview](./preview1.png)
 
> Teste prático para Analista de Qualidade de Software Júnior

 Projeto realizado durante o desafio para **Analista de Qualidade de Software Júnior** da **BEEDOO**.
 
## 📚 Tópicos

- Plano de teste (https://docs.google.com/document/d/1IhcEOgbB6hIxLhEH7-ENoo0GP40mMQu7XCKNcpJBsmw/edit?usp=sharing)
- Teste manual (https://docs.google.com/document/d/1W7vPXUF6gWHgGrgfL9emFWy3mO-yoIU2r6-tm_kiR78/edit?usp=sharing)
- Teste automatizado (https://github.com/mykallella/grupoMGO-teste-pratico/tree/main/teste%20automatizado)

## 🔧 Ferramentas e Tecnologias

- Python (`v3.11.5`)
- Selenium (`v4.17.2`)
- Pytest (`v8.0.0`)
- pip (`v24.0`)

## 🔧 Documentação (Motivos para criação dos cenários)

- Cenário 1: Listagem de cursos – Sem cursos cadastrados
 - `É necessário verificar se o sistema está puxando os dados corretos do banco de dados e sendo exibidos da maneira correta.`

- Cenário 2: Listagem de cursos – Com cursos cadastrados
 - É necessário verificar se o sistema está puxando os dados corretos do banco de dados e sendo exibidos da maneira correta.

- Cenário 3: Cadastro de cursos – Com todos os dados
 - É necessário verificar se o sistema está cadastrando os cursos.

- Cenário 4: Cadastro de cursos – Sem nome do curso
 - É necessário verificar se o sistema está analisando campos obrigatórios. Um curso não deve ser cadastrado sem nome, porque sem o nome do curso não é possível identificá-lo.

- Cenário 5: Cadastro de cursos – Sem descrição do curso
 - É necessário verificar se o sistema está analisando campos NÃO obrigatórios. Um curso deve ser cadastrado sem descrição, porque não interfere na usabilidade do sistema nem no aspecto visual.

- Cenário 6: Cadastro de cursos – Sem instrutor do curso
 - É necessário verificar se o sistema está analisando campos NÃO obrigatórios. Um curso deve ser cadastrado sem instrutor, porque um curso pode durar para sempre ou por muito tempo e pode ter vários instrutores ao longo do tempo e não inserir um instrutor fixo não interfere na usabilidade do sistema nem no aspecto visual.

- Cenário 7: Cadastro de cursos – Sem Url da imagem de capa
 - É necessário verificar se o sistema está analisando campos obrigatórios. Um curso não deve ser cadastrado sem imagem de capa, porque um produto sem imagem de capa fica esteticamente feio, e isso influencia na percepção de qualquer usuário ao utilizar o sistema.

- Cenário 8: Cadastro de cursos – Sem data de início
 - É necessário verificar se o sistema está analisando campos NÃO obrigatórios. Um curso deve ser cadastrado sem data de início, porque um curso pode durar para sempre ou por muito tempo e ter usuários iniciando o tempo todo e não inserir uma data de início do curso não interfere na usabilidade do sistema nem no aspecto visual.

- Cenário 9: Cadastro de cursos – Sem data de fim
 - É necessário verificar se o sistema está analisando campos NÃO obrigatórios. Um curso deve ser cadastrado sem data de fim, porque um curso pode durar para sempre e não inserir uma data de fim do curso não interfere na usabilidade do sistema nem no aspecto visual.

- Cenário 10: Cadastro de cursos – Sem número de vagas
 - É necessário verificar se o sistema está analisando campos obrigatórios. Um curso não deve ser cadastrado sem número de vagas, porque um número de vagas infinito pode ocasionar uma queda ou lentidão exagerada no sistema por sobrecarga de acessos simultâneos, dependendo da capacidade de processamento do servidor web e da infraestrutura onde está inserido.

- Cenário 11: Cadastro de cursos – Sem tipo de curso
 - É necessário verificar se o sistema está analisando campos obrigatórios. Um curso não deve ser cadastrado sem número de vagas, porque é preciso ter acesso ao endereço ou formulário de inscrição para que o usuário tenha possibilidade de acessar o curso efetivamente.

- Cenário 12: Cadastro de cursos – Com tipo de curso ‘Online’ com ‘Link de inscrição’
 - É necessário verificar se o sistema está processando o cadastro corretamente com todas as opções existentes no formulário.

- Cenário 13: Cadastro de cursos – Com tipo de curso ‘Online’ sem ‘Link de inscrição’
 - É necessário verificar se o sistema está analisando campos obrigatórios. Um curso não deve ser cadastrado sem Link de inscrição, porque é preciso ter acesso ao formulário de inscrição para que o usuário tenha possibilidade de acessar o curso efetivamente.

- Cenário 14: Cadastro de cursos – Com tipo de curso ‘Presencial’ sem ‘Endereço’
 - É necessário verificar se o sistema está analisando campos obrigatórios. Um curso não deve ser cadastrado sem Endereço, porque é preciso ter acesso ao endereço para que o usuário tenha possibilidade de acessar o curso efetivamente.


## 🔗 Contato

mykallella@gmail.com
