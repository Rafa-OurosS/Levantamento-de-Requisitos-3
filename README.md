# Levantamento-de-Requisitos-3

# **:large_blue_diamond: Nome: Rafael Augusto Moreira dos Ouros :small_blue_diamond: RA: 2039975**


## :memo: Cenário: Sistema de Gestão de Estoque para uma Loja de Eletrônicos

## :telephone_receiver: Descrição do Escopo: 

Uma loja de eletrônicos está procurando um sistema de gestão de estoque para controlar o inventário de produtos em suas lojas físicas e online.

## :small_red_triangle: Necessidades do Software:
* Registro de Produtos: O sistema deve permitir o registro de novos produtos,
incluindo informações como nome, descrição, preço e quantidade em
estoque.
* Monitoramento de Estoque: O sistema deve monitorar os níveis de estoque
de cada produto e emitir alertas quando os estoques estiverem baixos.
* Vendas e Pedidos: O sistema deve registrar vendas e pedidos de produtos,
atualizando automaticamente os níveis de estoque.
* Gestão de Fornecedores: O sistema deve manter registros de fornecedores
de produtos, incluindo informações de contato e histórico de pedidos.
* Relatórios de Desempenho: O sistema deve gerar relatórios sobre o
desempenho de vendas e o movimento de estoque para ajudar na tomada
de decisões

## :milky_way: REQUISITOS FUNCIONAIS:
* O botão no canto superior esquerdo, entitulado (manutenção) permite o usuário cadastrar e remover itens no estoque da loja;
* Possível cadastrar usuários e fazer login toda vez que o sistema é lançado, afim de registrar quem fez a venda e aplicar comissão (caso a empresa o faça);
* Ao lançar o cadastro o usuário deve informar nome do produto, valor, e quantidade disponível. Também pode inserir informações opcionais como descrições e imagens do produto para facilitar a visualização;
* Nas preferências de usuário é possível ativar o modo escuro;
* Função de abrir pedidos para clientes: abre uma janela dentro do sistema onde o usuário pode inserir produtos de acordo com o pedido, no rodapé o valor total e quantidade de itens é mostrado e atualizado em tempo real;
* Cadastro e consulta de fornecedores: O sistema possibilita cadastrar novos fornecedores, também é possível consultar e atualizar as informações de cada fornecedor;
* Possibilidade de contatar fornecedores simplesmente clicando em "contatar", o sistema abre uma tela de e-mail para o fornecedor;
* O sistema gera relatórios de movimento de produtos, quanto a empresa faturou (permitindo selecionar o período e intervalo de tempo através de calendário interativo, ou digitando a data);
* Caso seja selecionada a opção de relatório detalhado, também é possível visualizar os métodos de pagamentos selecionados, bem como o valor total geral e o valor total de cada método de pagamento, ex. Cartão de Crédito: R$7000,00;
* Permitida diversas formas de pagamento ao finalziar pedido, bem como opção de aplicação de desconto e juros de acordo com o tipo de método selecionado;
* O sistema é capaz de emitir nota fiscal;


## :mag: REQUISITOS NAO-FUNCIONAIS: 
* Contador de mercadorias que é atualizado em tempo real toda vez que um pedido é finalizado, emitindo um alerta quando determinado produto está próximo de esgotar;
* O tempo de processamento de cada ação do sistema (lançar cadastro de produto/fornecedor, abertura e finalização de pedido, emissão de NF) deve ser inferiro à 3sec;
* As informações de cada produto cadastrado ficam armazenadas no banco de dados;
* Os dados de cada fornecedor cadastrado ficam armazenados no banco de dados do sistema;
* À cada venda, os dados de produto, valor, método de pagamento e data são armazenados no banco de dados para serem levantados no relatório;


## :memo: Cenário: Aplicativo de Saúde e Bem-Estar

## :telephone_receiver: Descrição do escopo: 
Vocês estão desenvolvendo um aplicativo de saúde e bem-estar para ajudar os usuários a acompanharem sua atividade física, dieta e bem-estar geral.

## :small_red_triangle: Necessidades do Software:
* Registro de Atividades: O aplicativo deve permitir que os usuários registrem
atividades físicas, como corrida, caminhada, ciclismo, etc.
* Acompanhamento de Dieta: Os usuários devem poder registrar sua
ingestão diária de alimentos e monitorar a qualidade de sua dieta.
* Monitoramento de Saúde: O aplicativo deve permitir que os usuários
registrem dados de saúde, como pressão arterial, níveis de glicose e peso
corporal.
* Definição de Metas: Os usuários devem poder definir metas pessoais para
atividade física, dieta e outros aspectos de saúde e bem-estar.
* Feedback Personalizado: O aplicativo deve fornecer feedback
personalizado e dicas para ajudar os usuários a alcançarem suas metas de
saúde e bem-estar.

## :milky_way: REQUISITOS FUNCIONAIS:
* Registro de atividade física praticada: corrida, caminhada, musculação, ciclismo, etc. Bem como a duração de cada atividade;
* Definir uma refeição do dia ex. Almoço, nela ele pode inserir os alimentos consumidos e obter uma relação geral de quantas calorias, gorduras, proteínas e fibras foram ingeridas na refeição como um todo, e em cada alimento;
* Saúde: é possível inserir informações de saúde como pressão arterial, nível de glicose e peso;
* Criação de perfil na aplicação, o usuário pode digitar seu nome, apelido, idade(data de nascimento) foto de perfil;
* Meta: o usuário pode selecionar de uma lista de metas predefenidas na aplicação, tais como: perder peso, hipertrofia, melhorar condicionamento físico, bem como customizar a sua própria;
* O usuário pode selecionar o tipo de dieta: Perda de peso, ganho de peso,ganho de massa muscular;
* O aplicativo mostra a quantidade de calorias ingeridas até agora no dia através de uma barra;
* Ao final de cada semana é mostrado um resumo da semana, onde demonstra o tempo total de atividades físicas praticadas, o tempo individual de cada atividade (se praticou mais de uma) bem como o total de calorias consumidas e compara com a semana anterior;
* Também é possível acessar o consumo total de calorias e tempo de atividades físicas praticadas sempre que quiser;
* Aparência: o aplicativo permite utilizar modo escuro ou modo claro;



## :mag: REQUISITOS NAO-FUNCIONAIS: 
* O app deve carregar cada tela em menos de 2sec
* O app deve realizar cada registro em menos até 3sec
* Registra cada atividade praticada, e sua duração
* back-end contém milhares de alimentos cadastrados, com informações nutricionais como calorias, proteínas, gorduras e etc;
* calcula a quantidade de cada valor da tabela nutricional do alimento de acordo com a quantidade informada pelo usuário, em gramas ou porções;
* registra a quantidade de calorias, proteínas, gorduras e etc, para demonstrar na barra de calorias do dia;





















