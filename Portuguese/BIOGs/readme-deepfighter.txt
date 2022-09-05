DFBIOGFIX v1.2 - Correcção da Biografia da Queda da Adaga

	por Frank 'Deepfighter' Schwalb
	traduzido por Ms. Invicible
	- deepfighter@tamriel-almanach.de -

 ~ Uma correcção para os ficheiros de biografia em The Elder Scrolls II: Daggerfall. ~

==============================================================================
                             C O N T E N T E S
==============================================================================

    1. Introdução
    2. Changelog
    3. Instalação
    4. Agradecimentos e Exoneração de responsabilidade
    5. Resumo das alterações

==============================================================================
  1. Introdução                                                            
==============================================================================

A ideia de corrigir os erros nos ficheiros BIOGXXT0 do Daggerfall surgiu durante
 o processo de tradução em alemão. Ao traduzir os ficheiros, encontrei alguns
 erros estranhos que variavam desde erros ortográficos, a valores errados, até
 resultado diferente do equipamento escolhido. Ao longo dos anos ninguém parecia verificar
 todos os ficheiros para erros. Houve uma pequena correcção para o ficheiro BIOG00TO.TXT,
 por Uniblab, mas ele perdeu o mesmo erro noutra questão do mesmo
 ficheiro. No fim de contas, estava incompleto.
 
 Essa foi a principal razão para verificar todas as 216 perguntas e encontrar erros.
 Encontrei mais inconsistências do que as que corrigi, porque algumas são intencionais e outras
 mudanças significariam algumas mudanças profundas de equilíbrio. Por esse motivo, fiz algumas
 directrizes para esta (primeira) fixação (v1.0):
 
  * Alterar 'apenas' os erros óbvios.
  * Tentar manter o mais original possível.
 
 E fiz como verão na minha lista de alterações abaixo. 
 
 Nesta base, há muitas possibilidades. Podemos corrigir mais ou menos outras
 questões de equilíbrio e inconsistências, que de outra forma não seriam como
 original o mais original possível (como por exemplo a habilidade "Orcish" em falta no
 "[...] mais amigável do que a maioria [...]" pergunta ou algum resultado enganoso
 com "Critical Strike" e "Hand-to-Hand", que deixei de fora devido ao meu
 directrizes). Tudo já está relatado e pode ser facilmente alterado.
 
 Para a v1.2 incluí mais correcções especialmente, onde se escolhe "Tiro com Arco".
 como resposta e não obter um arco correspondente para disparar as setas associadas.
 Também mudei um ficheiro onde poderia adquirir duas (redundantes) setas de Katana
 ou onde uma arma apropriada tenha estado em falta.
 
 Sinta-se à vontade para discutir comigo sobre as alterações ou simplesmente escrever se encontrou
 outros erros no Daggerfall, ou nos meus ficheiros. Todos serão creditados
 é claro. Isto deve ser mais ou menos um reparo comunitário da adaga.
 
 Cumprimentos
 Frank Schwalb t.c.p. Deepfighter
 
==============================================================================
  2. Changelog                                                            
==============================================================================

 (11/10/15) - v1.0 - Lançamento das versões em inglês e alemão
 (23/10/15) - v1.1 - Adição da versão francesa
 (12/05/20) - v1.2 - Alterou algumas outras inconsistências

==============================================================================
  3. Instalação                                                            
==============================================================================

 Basta copiar os ficheiros da sua língua para a pasta ARENA2. Se lhe for pedido
 para substituir os ficheiros antigos, faça isso. Se necessário, faça uma cópia de segurança dos seus ficheiros antigos
 antes de os substituir, caso contrário os ficheiros originais devem estar no arquivo
 que descarregou. Basta levá-los e substituí-los da mesma forma para obter o
 ficheiros originais na sua língua de volta.
 
 Unidade Daggerfall
 ----------------
 Está previsto que esta correcção seja implementada como uma característica central (Github
 Edição #1468). Até que isto esteja em vigor, a Daggerfall Unity recebe a informação
 a partir destes ficheiros directamente a partir da pasta ARENA2 do jogo associado
 o que significa que deve remendá-los como indicado acima.

==============================================================================
  4. Agradecimentos e Exoneração de responsabilidade
==============================================================================

 * Ted Peterson e Julien LeFay, as verdadeiras mentes por detrás dos Pergaminhos dos Anciãos.
 * Graças a Gavin Clayton (Interkarma) e à Comunidade de Oficinas do DF.
 * Graças a Numenorean por ter feito tanto na tradução alemã, que eu
   Tenho tempo para fazer os meus projectos de Daggerfall lateral, sempre que for necessário.
 * Agradecimentos especiais a Uniblab e PLRDLF pelo seu incrível trabalho na UESP
   páginas para Daggerfall.
 * A todos os outros que amam e contribuem para Daggerfall (in)directamente e
   a grande e deslumbrante comunidade Daggerfall. Teremos um óptimo momento para
   trabalho sobre o jogo.

 Contacto: deepfighter@tamriel-almanach.de

==============================================================================
  5. Visão geral das mudanças
==============================================================================

 Uma visão geral de todas as mudanças, e uma visão geral de todas as
 perguntas + um lugar para acrescentar comentários:
 https://docs.google.com/spreadsheets/d/1MyDLmIMQ1G20QWbkGWQg7Pxl07TAJGM_
 VsLN-b025_o/edit

 -----------------
 
# BIOG00T0.TXT {Mages}

#3 c) A resposta "praticar acrobacia" está incorrectamente associada com a
  habilidade 'Orcish'.
**Modificou-a para a habilidade apropriada 'Saltar'.

* #5 a) Para a resposta "Mais de 200 peças de ouro" receberá apenas 200 peças de ouro
  e não como indicado 200+.
**Modificou-o para 250 peças de ouro.

* #7 a) A resposta "Coelho" está incorrectamente associada com a habilidade
  "Orcish", mesmo que seja indicativo de atletismo.
**Modificou-o para a habilidade apropriada 'Saltar', tal como na outra
  ficheiros originais com a mesma pergunta; faz mais sentido.

* #7 c) A resposta "Quicksilver" está incorrectamente associada à habilidade
  Resoration", mesmo que seja indicativo de rapidez.
**Modificou-a para a habilidade apropriada 'Running', como na outra
  ficheiros originais com a mesma pergunta; faz mais sentido.


# BIOG01T0.TXT {Spellword}

#3 c) A resposta "praticar acrobacia" está ao lado de "Saltar" e "Esquivar-se".
  inconsistente associada à habilidade 'Running'.
**Modificou-a para a habilidade apropriada 'Escalada' como em BIOG00T0.TXT.

* #5 a) Para a resposta "Mais de 200 peças de ouro" receberá apenas 200 peças de ouro
  e não como indicado 200+.
**Modificou-o para 250 peças de ouro.

* #7 f) Se seleccionar "Longblade" obtém seis pontos de habilidade, mas não
  arma, enquanto que para todas as outras respostas (a-e) é adicionada uma arma correspondente.
**Modificou-a para adicionar uma 'Espada Longa de Ferro' extra.


# BIOG02T0.TXT {Battlemage}

#3 c) A resposta "praticar acrobacia" está ao lado de "Saltar" e "Esquivar-se".
  inconsistente associada à habilidade 'Running'.
**Modificou-a para a habilidade apropriada 'Escalada' como em BIOG00T0.TXT.

* #5 a) Para a resposta "Mais de 200 peças de ouro" receberá apenas 200 peças de ouro
  e não como indicado 200+.
**Modificou-o para 250 peças de ouro.


# BIOG03T0.TXT {Sorcerer}

#3 c) A resposta "praticar acrobacia" está ao lado de "Saltar" e "Esquivar-se".
  inconsistente associada à habilidade 'Running'.
**Modificou-a para a habilidade apropriada 'Escalada' como em BIOG00T0.TXT.

* #5 a) Para a resposta "Mais de 200 peças de ouro" receberá apenas 200 peças de ouro
  e não como indicado 200+.
**Modificou-o para 250 peças de ouro.


# BIOG04T0.TXT {Healer}

#3 c) A resposta "praticar acrobacia" está ao lado de "Saltar" e "Esquivar-se".
  inconsistente associada à habilidade 'Running'.
**Modificou-a para a habilidade apropriada 'Escalada' como em BIOG00T0.TXT.

* #5 a) Para a resposta "Mais de 200 peças de ouro" receberá apenas 200 peças de ouro
  e não como indicado 200+.
**Modificou-o para 250 peças de ouro.


# BIOG05T0.TXT {Nightblade}

* #3 e) A pergunta "Onde está a sua perícia em combate?" tem a resposta
  "Tiro com Arco" que lhe dá "Pauldron de Ferro Esquerdo" em vez de uma arma de arco.
**Mudou o resultado para "arco curto de ferro" e 6x "flecha de ferro".

#7 c) A resposta "praticar acrobacias" é ao lado de "Saltar" e "Esquivar-se".
  inconsistente associada à habilidade 'Running'.
**Modificou-a para a habilidade apropriada 'Escalada' como em BIOG00T0.TXT.


# BIOG06T0.TXT {Bard}

#4 c) A resposta "praticar acrobacia" está ao lado de "Saltar" e "Esquivar-se".
  inconsistente associada à habilidade 'Running'.
**Modificou-a para a habilidade apropriada 'Escalada' como em BIOG00T0.TXT.

* #6 a) Para a resposta "Mais de 200 peças de ouro" receberá apenas 200 peças de ouro
  e não como indicado 200+.
**Modificou-o para 250 peças de ouro.


# BIOG07T0.TXT {Burglar}

* #5 a) Para a resposta "Mais de 200 peças de ouro" receberá apenas 200 peças de ouro
  e não como indicado 200+.
**Modificou-o para 250 peças de ouro.

* #7 a) A pergunta "Onde está a sua perícia em combate?" tem a resposta
  "Armas de lâmina curta" que lhe dá "Luvas de Ferro" em vez de um curto
  arma com lâminas.
**Mudou o resultado para "Espada Curta de Ferro".

#7 b) A pergunta "Onde está a sua perícia em combate?" tem a resposta
  "Combate corpo-a-corpo" que lhe dá "Cuirass de Aço" em vez de ajuda para
  Combate corpo a corpo.
**Mudou o resultado para 'Iron Gauntlets'.

* #7 e) A pergunta "Onde está a sua perícia em combate?" tem a resposta
  "Tiro com Arco" que lhe dá "Pauldron de Ferro Esquerdo" em vez de uma arma de arco.
**Mudou o resultado para "arco curto de ferro" e 6x "flecha de ferro".


# BIOG08T0.TXT {Rogue}

#1 b) A pergunta "Tem um certo grau de formação com ___" tem
  a resposta "combate corpo-a-corpo" que lhe dá "Cuirass de Prata" em vez disso
  de ajuda para o combate corpo a corpo.
**Mudou o resultado para 'Gauntlets de Prata'.

* #1 e) A pergunta "Tem um certo grau de treino com ___." tem
  a resposta "Tiro com Arco" que lhe dá "Pauldron de Ferro Esquerdo" em vez de
  uma arma correspondente, como as outras respostas.
**Mudou o resultado para "Arco Curto de Ferro" e 6x "Seta de Ferro".


# BIOG10T0.TXT {Ladrão}

* #3 e) A pergunta "Onde está a sua perícia em combate?" tem a resposta
  "Tiro com Arco" que lhe dá "Pauldron de Ferro Esquerdo" em vez de uma arma de arco.
**Mudou o resultado para "arco curto de ferro" e 6x "flecha de ferro".

* #4 a) Para a resposta "Mais de 200 peças de ouro" receberá apenas 200 peças de ouro
  e não como indicado 200+.
**Modificou-o para 250 peças de ouro.

#8 c) A resposta "praticar acrobacias" está ao lado de "Saltar" e "Esquivar-se".
  inconsistente associada à habilidade 'Running'.
**Modificou-a para a habilidade apropriada 'Escalada' como em BIOG00T0.TXT.


# BIOG14T0.TXT {Ranger}

#1 c) A resposta "Luta com machado" está associada a "Luvas de Ferro" em vez de "Luvas de Ferro".
  de uma arma adequada que se adapte à habilidade.
**Modificou-a para "Machado de Ferro".

#1 f) A resposta "Lâmina Longa" está associada a 'Katana de Ferro'. Como
  ter a oportunidade de obter uma Dai-Katana em #5 e), parece ser redundante
  adquirindo duas Katana's.
**Modificou-a para 'Espada Longa de Ferro'.

# BIOG16T0.TXT {Warrior}

* #1 f) A resposta "Longblade" está associada a "Iron Kite Shield" em vez de
  de uma arma adequada que se adapte à habilidade.
**Modificou-a para 'Iron Claymore' como em BIOG15T0.TXT.

#9 As respostas são desvirtuadas como os valores associados dos diferentes
  as competências são estranhamente [-2]. Isso significa que, por exemplo, a resposta g) "os primitivos
  Centauros" está associado com a habilidade "Daedric" e responde e) "o infernal
  Daedra" com a habilidade "Dragonish", etc.
**Modificou cada resposta à sua respectiva perícia; acrescentou a cada uma a perícia apropriada
  valor [+2].

______________________________________________________________________________
THE UNDERKING FINDS DFBIOGFIX © F. Schwalb (Deepfighter) 2015-2020
VOCÊ E TRAZ VOCÊ OS ROLAMENTOS DE ANTIGUARDADADEIOS nomeiam © respectivos donos
LONGE, LONGE, MUITO LONGE...                            E N D O D O C U M E N T

