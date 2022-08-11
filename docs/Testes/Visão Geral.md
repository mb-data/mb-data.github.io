## Teste de Software

Teste de software é um método para checar se o seu software cumpre os requisitos e está livre de Defeitos. Envolve a execução de componentes do sistema usando ferramentas manuais ou automatizadas para avaliar uma ou mais partes de interesse. O intuito do teste de software é identificar erros, lacunas ou requisitos faltantes em contraste aos requisitos de fato.

A área de teste de software é bastante extensa, tendo profissionais dedicados à essa parte do processo de desenvolvimento de software. Geralmente, esse tipo de processo é realizado por um time de QA (Quality Assurance ou Controle de Qualidade).

Dois fundamentos para esse segmento são:

- Não é possível atingir 100% de automação.
- Não é possível testar 100% da aplicação. Mesmo nas aplicações mais triviais podem ocorrer entradas e erros inesperados.

### O Mito

Mito: Testar requer tempo! Eu não tenho tempo, preciso entregar tudo pra ontem. Eu sou o mestre, meu código é perfeito, eu não preciso de testes.

A verdade é que criar testes automatizados aumentam a velocidade de desenvolvimento. Veja o seguinte ciclo:

<img src="https://www.guru99.com/images/unit-testing.png" alt="Piramide Teste" style="height: 50%; width:50%;"/>

Programadores acreditam que os Testes Manuais vão capturar todos os erros e não executam Testes Unitários. Assim que as unidades/componentes são integrados, erros simples que poderiam ter sido facilmente encontrados e consertados em Testes Unitários levam mais tempo para serem identificados e consertados.

## Benefícios e Importância

Testes são importantes porque bugs e erros podem ser identificados de forma precoce e solucionados antes da entrega/lançamento do produto. Um software testado de forma apropriada garante alguns benefícios:

- Eficiência de Custo: uma das maiores vantagens. Testar qualquer projeto de TI ajuda o time a economizar dinheiro no longo prazo. No caso de bugs serem detectados em estágios iniciais de desenvolvimento, eles custam menos para serem consertados.
- Segurança: pessoas buscam produtos confiáveis. Testes ajudam a remover riscos e problemas mais cedo, trazendo mais credibilidade.
- Qualidade de Produto: testes garantem a qualidade do produto que será lançado aos clientes.
- Satisfação do Cliente: o objetivo primário de qualquer produto é dar satisfação aos clientes. Testes garantem a melhor experiência do usuário (livre de bugs e crashes), ainda, podendo ser potencializado por testes de UI/UX.

## Tipos de Teste de Software

<img src="https://www.guru99.com/images/2/061920_1310_Whatissoftwaretesting1.png" alt="Piramide Teste" style="height: 60%; width:60%;"/>

### Testes Funcionais

- Teste Unitário
- Teste de Integração
- Teste de Fumaça
- UAT (User Acceptance Testing)
- Teste de Globalização (tradução)
- Teste de Interoperabilidade
- Entre outros

### Testes não-funcionais

- Performance
- Resiliência
- Carga
- Escalabilidade
- Usabilidade
- Entre outros

## Testes de Manutenção

- Manutenção
- Regressão

## Principais testes

### Teste Unitário

Testes unitários visam testar componentes individuais de uma aplicação. O intuito é validar se cada unidade de um código funciona como esperado, isolando uma parte do código e verificando sua corretude. Esses testes são realizados na etapa de desenvolvimento da aplicação pelos desenvolvedores. Uma unidade ou componente de código pode ser uma função, método, procedimento, módulo ou objeto.

### Teste de Integração

Testes de integração visam testar dois ou mais componentes como um grupo. Um projeto de software usual possui diversos módulos, codificados por diferentes programadores. O intuito desses testes são expor defeitos de interação entre os módulos quando eles estão integrados.

### Teste End-to-end

Testes End-to-End (E2E ou ponta-a-ponta) buscam replicar o comportamento do usuário em um ambiente completo da aplicação. Ele verifica os vários fluxos que o usuário usa. Podem ser simples como carregar uma página da web, fazer login ou ser tão complexos quanto verificar notificações de email, pagamentos online, etc... Esses testes são bastante úteis, mas são custosos para executar e difíceis de manter quanto automatizados. É recomendado ter alguns testes end-to-end chaves e recorrer mais aos testes de menor nível para verificar mudanças de quebra.

## Teste Manual

Por fim, o bom e velho teste manual acaba sendo uma importante arma no arsenal. Como não é possível chegar em 100% de automação e nem inteligente, testes manuais visam reproduzir o que os testes end-to-end buscam. Verificar se os fluxos do usuário funcionam como esperado e não quebram quando houveram novas features ou refatorações. Esses testes acabam tomando tempo e podem ser cansativos de serem feitos, mas não podem ser negligenciados. Geralmente testes manuais são testes exploratórios, ou seja, visam buscar erros não-óbvios na aplicação.

## Pirâmide de Teste

A Pirâmide de Teste é um framework que pode ajudar tanto desenvolvedores quanto QAs para criar softwares de alta qualidade. Isso reduz o tempo necessário para desenvolvedores identificarem se uma mudança introduzida quebrou o código. Também é útil para construir uma suíte de teste mais consistente.

<img src="https://3fxtqy18kygf3on3bu39kh93-wpengine.netdna-ssl.com/wp-content/uploads/2020/01/test-automation-pyramid.jpg" alt="Piramide Teste" style="height: 50%; width:50%;"/>

A ideia da pirâmide é que os testes unitários sejam a base da suíte de testes, pois tomam menos tempo para serem escritos e rodam com mais frequência, além de proverem feedback ao desenvolvedor com mais rapidez. Os testes de integração ficam num nível superior, pois precisam testar duas ou mais unidades, tomando mais tempo para serem escritos, precisam de um ambiente para serem rodados, podem comunicar com aplicações externas e, por fim, tomam mais tempo do que testes unitários para rodar. Por último, no topo da pirâmide, os testes End-to-End tomam mais tempo para rodar, serem escritos e possuem dependências, além de serem complexos de serem executados. Geralmente os testes End-to-End são substituídos por testes manuais, portanto acabam sendo o último passo da suíte de testes.

## Fontes

- https://www.guru99.com/software-testing-introduction-importance.html#5
- https://www.guru99.com/application-testing.html
- https://www.guru99.com/frontend-testing-vs-backend-testing.html
- https://www.browserstack.com/guide/testing-pyramid-for-test-automation
- https://www.guru99.com/functional-testing.html
- https://www.guru99.com/manual-testing.html
- https://www.guru99.com/unit-testing-guide.html#9
- https://medium.com/aperto-an-ibm-company/unit-testing-in-agile-web-projects-4db5547a733b
- https://www.digite.com/agile/unit-testing/
- https://www.browserstack.com/guide/front-end-testing
- https://www.guru99.com/integration-testing.html
- https://www.atlassian.com/continuous-delivery/software-testing/types-of-software-testing
