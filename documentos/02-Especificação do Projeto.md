# Especificação do Projeto

## Perfis de Usuários


<table>
<tbody>
<tr align=center>
<th colspan="2">Portadora da doença celíaca</th>
</tr>
<tr>
<td width="150px"><b>Descrição</b></td>
<td width="600px">Pessoas que portam a condição da doença celíaca e por ventura pessoas que convivem com ela</td>
</tr>
<tr>
<td><b>Necessidades</b></td>
<td>
• Fácil acesso a estabelecimentos que apresentam propostas de comidas sem glúten;<br>
• Fácil acesso a locais que conheçam a doença celíaca e seguem procedimentos para evitar que portadores dessa condição se alimentem com alimentos a base de glúten ou com vestígios do mesmo;<br>
• Segurança para se alimentar.
</td>
</tr>
</tbody>
</table>

<table>
<tbody>
<tr align=center>
<th colspan="2">Dono de estabelecimento alimentício</th>
</tr>
<tr>
<td width="150px"><b>Descrição</b></td>
<td width="600px">Donos de estabelecimentos alimentícios que desejam incluir seu negócio no sistema como um local seguro para portadores da doença e saber mais sobre o glúten.</td>
</tr>
<tr>
<td><b>Necessidades</b></td>
<td>
• Apresentar seu estabelecimento para portadores da doença celíaca; <br>
• Saber mais sobre a doença celíaca e como preparar seu estabelecimento para o suporte destas pessoas; <br>
• Cadastrar seu estabelecimento no sistema para fácil descoberta do mesmo.
</td>
</tr>
</tbody>
</table>


## Histórias de Usuários


|EU COMO... `QUEM`   | QUERO/PRECISO ... `O QUE` |PARA ... `PORQUE`                 |
|--------------------|---------------------------|----------------------------------|
| Paciente portadora da doença celíaca/pessoa que convive com portadores da doença                | Encontrar locais que saibam sobre a doença celíaca e ofereçam produtos alimentícios adequados para quem porta a condição                       | Comer produtos no local ou fazer encomendas para entrega em minha casa com a segurança que o produto não contém glúten e é seguro para o consumo                              |
| Dono de estabelecimento alimentício                | Cadastrar meu estabelecimento para avaliação dos responsáveis e colocá-lo no sistema de estabelecimentos seguros para celíacos                       | Oferecer meus produtos sem glúten para quem precisa e ajudar os celíacos a me localizarem. Além de conseguir captar outros públicos.                              |

## Requisitos do Projeto


### Requisitos Funcionais


|ID    | Descrição                | Prioridade |
|-------|---------------------------------|----|
| RF-01 |  A aplicação deve permitir ao usuário inicialmente selecionar cidade e estado que está localizado                    | Alta   | 
|  RF-02  |  A aplicação deve fornecer uma lista de restaurantes da cidade/estado selecionado.                    | Alta   |
|  RF-03  |  A aplicação deve disponibilizar uma filtragem para organização desta lista (popularidade do estabelecimento, ordem alfabética, data de criação do estabelecimento)                    | Média   |
|  RF-04  |  A aplicação, ao selecionar um estabelecimento, deve mostrar detalhes do cardápio, seus produtos sem glúten, localização do estabelecimento, telefone do mesmo, fotos do local e da cozinha, também devem ser incluídos os ingredientes utilizados nos produtos descritos como sem glúten                    | Alta   |
|  RF-05  |  A aplicação deve fornecer uma opção para que donos de estabelecimentos cadastrem seus negócios informando o nome, telefone, CNPJ e localização do local para o mesmo ser incluído na lista após os critérios avaliativos. O cadastro virá para o e-mail do(s) desenvolvedor(es) responsáveis.                    | Alta   |
|  RF-06  |  A aplicação deve fornecer uma filtragem para exibir locais que contém seus alimentos próprios sem glúten e alimentos industrializados que não são produzidos pelo local.                    | Média   |
|  RF-07  |  A aplicação além de fornecer o formulário para inscrição do estabelecimento, deve fornecer uma documentação de aceite contendo orientações gerais, como preparar o seu estabelecimento para celíacos, a importância de ter um ambiente bem estruturado e entre outros para que o usuário que esteja se cadastrando esteja ciente dos critérios de aprovação e que os dados deles serão utilizados no sistema web caso aprovado. | Média   |

**Prioridade: Alta / Média / Baixa. 

### Requisitos não Funcionais


|ID      | Descrição               |Prioridade |
|--------|-------------------------|----|
| RNF-01 |  A aplicação deve ser responsiva em dispositivos com diversas resoluções.                    | Alta   | 
| RNF-02 |  A aplicação deve ser extremamente simples de se utilizar, de modo que, apenas as informações contidas na tela são o bastante para o usuário conseguir o que quer (sem necessidade de FAQs ou documentações específicas).                    | Alta   | 
| RNF-03 |  A aplicação deve ter um alto desempenho em todos os dispositivos                   | Alta   | 
| RNF-04 |  As imagens dos estabelecimentos e produtos devem conter alta qualidade, de forma que seja fácil a visualização do mesmo.| Média   | 
| RNF-05 |  Devem ser colocadas fontes de fácil visualização da família sans-serif utilizando o google fonts. | Média   | 

**Prioridade: Alta / Média / Baixa. 

