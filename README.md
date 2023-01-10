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