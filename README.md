## O que é o teste?
- O teste é a etapa em que são verificadas as falhas, que a aplicação pode ter!

Testes são tão importantes que é necessário um profissional dedicado apenas à isto!
Chamado como QA (Quality Assurance), também pode ser entendido como 'Garantia de Qualidade'.

## Por que testar?
- O objetivo do teste é identificar possíveis falhas, ou vúlnerabilidades que um sistema pode apresentar. Ainda quanto antes o incidente for identificado menor o retrabalho ou dor de cabeça que o cliente poderia ter.

## Pirâmide de testes
- A Ideia da pirâmide de testes é ilustrar o relacionamento de tempo e complexidade para cada etapa e tipo de testes!


                      /\
                     /  \
                    /    \
                   /  UI  \
                  /        \
                 /          \
                / Testes de  \
               /  integração  \
              /                \
             /                  \
            /                    \
           /   Testes Unitários   \
          /                        \
         ----------------------------


Nestas três divisões podemos entender de cima para baixo a pirâmide como VELOCIDADE, de baixo para cima como CUSTO e horizontalmente como QUANTIDADE DE TESTES.

De acordo com a pirâmide, a quantidade de testes que desenvolvemos está sempre relacionada à tempo e valores. Sendo os testes unitários os testes mais baratos, por este motivo compõe a base. Já os testes de E2E (UI), costumam ser os testes mais custosos, em tempo e velocidade de entrega.


## Front end
-> Normalmente o teste mais utilizado é o teste unitário, visto que testa pequenas unidades do sistema, podemos chamar de componentes. Nos auxiliarão à realizar testes em funções, por exemplo.

Um próximo passo à ser executado são os testes de integração, como o próprio nome já diz, são rotinas com responsabilidades de interagir entre as duas camadas do sistema (Front e Back end).

Em uma tela de Login por exemplo, quando clicar em um botão 'Entrar' esperamos receber uma mensagem de confirmação, ou informativa com erro. Neste caso, poderíamos inserir um teste de integração, já que estamos interagindo entre o front end (ao clicar no botão) e com back end (ao enviar e aguardar uma requisição).

Ao topo da nossa pirâmide, o mais custoso em tempo E2E. Este teste realizará toda jornada no front end que o usuário faria para executar determinada rotina. Para esta estapa são utilizadas ferramentas de automação como Cypress.

## Back end

Além do front end, também é importante testar outra camada do sistema, o back end! Mesmo não sendo algo visível em interfaces gráficas como no caso do front, os testes em back end pode adiantar bastante o desenvolvimento, e auxiliar a squad antecipando os testes e documentação das requisições. 

Assim como no front end, podemos desfrutar de ferramentas para nos auxiliar no desenvolvimento destes testes como postman, insomnia, SwaggerUi.

## Mobile

Vamos pular dos monitores para algumas telas menores. Se você achou que os aplicativos mobile não estariam nesta lista, está enganado! Aqui exploraremos algumas dificuldades que no desenvolvimento WEB não são tão críticas. Neste pequeno grande mundo, precisamos estar atentos à testes de compatiblidade, testes de conectividade e testes de performance.

É claro que existem outros testes também muito importantes no dia a dia, mas pontuei estes especificamente por se tratarem do CORE do mobile. Precisamos garantir que o usuários estará navegando no seu sistema operacional correto, logo teste de compatibilidade.

Ahhh, quase me esqueci de ligar o Wi-fi do meu aparelho. Acho que encontramos o teste de conectividade aqui!
Apesar de parecer simples, este se faz muito importante visto que o usuário também precisa ser notificado sobre qualquer inatividade ou dificuldade de conexão.

O teste de performance nos trará informações que permitirão observar o uso do preocessador, memória e bateria, além de outros componentes, e assim podemos melhorar nosso aplicativo para que o usuário tenha a melhor imersão!

Vejam como cada peça se encaixa, não deixando passar nenhum ponto para fora.
Aqui listei apenas alguns dos tipos de testes para mobile, mas existem muitos mais, desafio você pesquisar e se aprofundar mais sobre eles!

Test IO, é uma das frameworks que colabora com os testes mobiles.

## Segurança

Não podemos esquecer que todos registros e conjuntos de dados carregados em nossos sistemas são informações importantes. E com estas não podemos permitir que sejam expostas ou que fiquem vulneráveis para consumo indevido ou malicioso.

Para evitar estas situações, existem os testes de segurança, onde por meio dele verificamos o comportamento do software mediante tentativas incorretas de uso. No teste de vulnerabilidade é feita uma varredura de falhas, como erros de armazenamento das informações e configurações.

Outro teste que pode ser realizado é o teste de intrusão, é um teste manual onde o objetivo é buscar até onde um hacker pode oferecer risco à aplicação.