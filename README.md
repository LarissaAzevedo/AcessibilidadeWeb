# Talk Precisamos falar sobre acessibilidade web
Conteúdo da apresentação sobre Acessibilidade Web para o TDC 2022

[Breves apresentações minhas e sobre porquê desse tema]

## Benefícios de uma web acessiva
Contar a história da charge da rampa e da escada com neve da escola

[Imagem de exemplo](https://miro.medium.com/max/1400/1*sX9jROr2qU4XyWKO2BaHGg.jpeg)

## Dados
No Brasil cerca de 24% da população (45 milhões de brasileiros) possui algum tipo de deficiência(IBGE).

## Vantagens na Web Inclusiva
Para empresas
- Responsabilidade social
- Melhoria da imagem da empresa, com o consequente fortalecimento da marca
- Aumento da visibilidade do site pelos sistemas de busca
- Fidelização de usuários e clientes
- Crescimento da audiência do site web
- Vantagem competitiva
- Canal aberto de comunicação com usuários e clientes
- Diminuição dos custos com manutenção
- Melhoria do desempenho
- Aumento da interoperabilidade

Para as pessoas
- Pessoas cegas que utilizam programas leitores de tela no computador navegam sem dificuldade pelos sítios web, preenchem formulários, acionam botões por meio de comandos do teclado e conseguem acessar, inclusive, as informações que estão em imagens, por meio de textos alternativos.

- Pessoas com baixa visão, usando ou não programas ampliadores de tela, não têm dificuldade com o contraste, nem para identificar e clicar em hiperlinks, barras e botões, nem para aumentar o tamanho das letras.

- Pessoas que não conseguem identificar algumas cores não se confundem nem perdem informações, porque todas as informações apresentadas por meio de cores são transmitidas também de outras formas.
- Pessoas surdas ou com deficiência auditiva acessam informações em áudio e vídeo com legendas, transcrições e traduções em LIBRAS (Língua Brasileira de Sinais).
- Pessoas com deficiência motora e mobilidade reduzida que utilizam apenas o teclado para acessar os conteúdos dos sítios web navegam com facilidade por todos os menus e seus subitens, formulários, serviços e informações disponíveis.
- Pessoas com deficiência intelectual ajustam a velocidade das animações e têm acesso a conteúdos em texto, áudio e vídeo para aprimorarem seus estudos.
- Pessoas com baixa experiência computacional aprendem com facilidade a utilizar serviços fundamentais para seu dia a dia e encontram com rapidez todas as informações de que necessitam.
- Pessoas com idade avançada conseguem encontrar todas as informações de que necessitam devido ao bom contraste, assim como pelo tamanho dos textos, navegabilidade e baixa complexidade das interações.
- Pessoas com problemas de conexão com a Internet acessam as páginas web com facilidade e navegam com ótimo desempenho.
- Pessoas com dispositivos móveis acessam serviços e informações na Web, mesmo utilizando telas e teclados muito pequenos e com velocidade de conexão e capacidade de processamento e armazenamento reduzidas.


[Preciso mencionar as vantagens para as empresas também, atende ao público que não desenvolve mas gerencia]

Tornando o seu projeto acessível fará com que essas pessoas sejam incluídas e consigam ter acesso ao seu conteúdo/produto.

## Leis de Acessibilidade Web
Após a promulgação da Constituição, a Lei nº 10.098 foi o primeiro avanço efetivo na legislação brasileira em relação à acessibilidade. Ela estabelece normas gerais e critérios básicos para a promoção da acessibilidade das pessoas com deficiência ou com mobilidade reduzida e dá outras providências.

Essa lei foi regulamentada pelo Decreto nº 5.296, de 2 de dezembro de 2004. Este decreto representou um grande avanço, pois estabelece, no seu conceito de acessibilidade, a “utilização, com segurança e autonomia, […] dos dispositivos, sistemas e meios de comunicação e informação”.

O acesso às tecnologias de informação e comunicação também foi definido como um direito humano básico na Convenção das Nações Unidas sobre os Direitos das Pessoas com Deficiência (UN CRPD).


## Construindo uma Web Acessível

O	Web	Content	Accessibility	Guidelines	pode	ser	considerado o	 principal	 documento	 de	 acessibilidade	 na	 Web	 no	 qual	 o desenvolvedor	 se	 baseia	 para	 tornar	 o	 conteúdo	 acessível.

### Princípios - pilares que constroem a base da acessibilidade web
- Perceptível

As	 informações	 e	 os	 componentes	 da interface	do	usuário	devem	ser	apresentados	em	formas que	 possam	 ser	 percebidas	 pelo	 usuário.	 Isso	 significa que	 o	 conteúdo	 não	 pode	 ser	 invisível	 para	 mais	 de um	 sentido	 do	 usuário.	 Um	 bom	 exemplo	 para	 este princípio	 é	 considerar	 que	 qualquer	 conteúdo	 não textual	 precisa	 ter	 uma	 alternativa	 em	 texto,	 seja	 ele uma	imagem,	um	campo	de	formulário	etc.

| Princípio  |  Diretrizes  |
| ------------------- | ------------------- |
| Perceptível | <strong>Alternativas em Texto:</strong> Fornecer alternativas em texto para todo o conteúdo não textual de modo a que o mesmo possa ser apresentado de outras formas, de acordo com as necessidades dos utilizadores, como por exemplo: caracteres ampliados, braille, fala, símbolos ou uma linguagem mais simples. <br><br>  Mídia Dinâmica ou Contínua: Fornecer alternativas para conteúdo em multimídia dinâmica ou temporal.<br><br>Adaptável: Criar conteúdo que possa ser apresentado de diferentes formas (por ex., um esquema de página mais simples) sem perder informação ou estrutura.<br><br>  Distinguível: Facilitar aos utilizadores a audição e a visão dos conteúdos nomeadamente através da separação do primeiro plano do plano de fundo. |
| Operável | Acessível por Teclado: Fazer com que toda a funcionalidade fique disponível a partir do teclado. <br><br> Tempo Suficiente: Proporcionar aos utilizadores tempo suficiente para lerem e utilizarem o conteúdo. <br><br> Diretriz 2.3 Convulsões: Não criar conteúdo de uma forma que se sabe que pode causar convulsões. <br><br> Navegável: Fornecer formas de ajudar os utilizadores a navegar, localizar conteúdos e determinar o local onde estão. |
| Compreensível | Legível: Tornar o conteúdo textual legível e compreensível. <br><br> Previsível: Fazer com que as páginas Web apareçam e funcionem de forma previsível. <br><br> Assistência na Inserção de Dados: Ajudar os utilizadores a evitar e a corrigir os erros.|
| Robusto | Compatível: Maximizar a compatibilidade com os agentes de utilizador atuais e futuros, incluindo as tecnologias de apoio. |
|  |


- Operável

Os	componentes	de	interface	de	usuário	e	a navegação	 devem	 ser	 operáveis.	 Para	 tanto,	 o	 usuário não	 deve	 ter	 impedimentos	 para	 utilizar	 a	 interface, seja	 ele	 por	 um	 computador,	 smartphone	 ou	 tablet. Para	exemplificar	esse	princípio,	as	diretrizes	apontam a	 importância	 da	 navegação	 por	 teclado,	 já	 que	 nem todas	as pessoas	têm	facilidade	com	o	uso	do	mouse.

- Compreensível

A	 informação	 e a	operação	da interface	de	usuário devem	ser	 compreensíveis. Este princípio	 toca	 em	 aspectos	que não são
necessariamente	 técnicos,	 já	 que	 está	 relacionado à compreensão	 do	 usuário. Uso adequado	 de	 cores, abreviaturas	 e	 outras	 diretrizes	 relacionadas	a conteúdo	fazem	parte	deste	princípio
- Robusto

O	conteúdo	deve	ser	robusto	o	suficiente	para
poder	 ser	 interpretado	 de	 forma	 confiável	 por	 uma
ampla	 variedade	 de	 agentes	 de	 usuário,	 incluindo
tecnologias	assistivas.	Basicamente,	isso	representa	que
a	 aplicação	 deve	 ser	 bem	 construída,	 de	 forma	 a	 ser
acessível	 para	 uma	 gama	 maior	 de	 navegadores	 e
tecnologia	assistiva.	O	uso	correto	dos	padrões	Web	já
ajuda	bastante	a	atingir	este	princípio








### Diretrizes - objetivos básicos a serem atingidos dentro de cada princípio
- Diretriz	 1.1	 Alternativas	 em	 texto

Fornecer alternativas	 textuais	 para	 qualquer	 conteúdo	 não
textual,	 para	 que	 possa	 ser	 transformado	 em	 outras
formas	de	acordo	com	as	necessidades	dos	usuários,	tais
como	 impressão	 com	 tamanho	 de	 fontes	 maiores,
braille,	fala,	símbolos	ou	linguagem	mais	simples.

- Diretriz	 2.1	 Acessível	 por	 teclado

Fazer	 com	 que toda	 funcionalidade	 fique	 disponível	 a	 partir	 de	 um
teclado

- Diretriz	 3.1	 Legível

Tornar	 o	 conteúdo	 do	 texto legível	e	compreensível.

- Diretriz	 4.1	 Compatível

Maximizar	 a compatibilidade	 entre	 os	 atuais	 e	 futuros	 agentes	 de
usuário,	incluindo	tecnologias	assistivas.



### Critérios	de	sucesso ou níveis de conformidade	- detalhes de	como	obter	sucesso	em	cada diretriz

- Nível	 A

Nível	 mínimo	 de	 conformidade. Atingindo este	nível	um	grande	conjunto	de	barreiras	de	acesso são	eliminadas,	possibilitando	que	pessoas	com	certos tipos	de	deficiência	consigam	acessar	de	forma	plena.

- Nível	 AA	 

Com	 os	 critérios	 de	 sucesso	 de	 níveis	 A	 e AA,	sua	aplicação	consegue	eliminar	mais	barreiras	de acesso,	 atingindo	 um	 público	maior	 do	 que	 somente os	contemplados	pelo	nível	A.
- Nível	AAA

Satisfaz	os	critérios	dos	níveis	anteriores, possibilitando	 que	 mais	 pessoas	 sejam	 contempladas com	 a	 acessibilidade	 da	 aplicação,	 porém	 é	 o	 mais difícil	de	se	atingir.	Não	se	recomenda	utilizar	o	nível AAA	 como	 política	 de	 acessibilidade	 para	 sites inteiros,	 mas	 em	 algumas	 áreas,	 quando	 necessário, pode	ser	bastante	útil.

### Técnicas - Código

## Considerações finais

- Acessibilidade	 não	 é	 filantropia.	 É	 garantia	 de	 direitos iguais.
- Eliminar	 barreiras	 de	 acesso	 é	 mais	 simples	 do	 que parece.
- Uma	 Web	 acessível	 beneficia	 todas	 as	 pessoas. Defenda-a o quanto possível.

[último slide]
Estou	à	disposição	para	tirar	dúvidas.	Fiquem	à	vontade	para	entrar em	contato	comigo	quando	quiserem	pelos	canais	disponíveis [redes]
Obrigada e até a próxima.
