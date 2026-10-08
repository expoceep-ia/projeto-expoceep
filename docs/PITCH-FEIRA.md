# Pitch da feira, uma ideia

Isso aqui é como eu acho que a gente poderia contar esse projeto em dois minutos e meio. Não é
roteiro fechado e não é regra, é uma proposta pra vocês discordarem e trocar o que não
combinar com a voz de vocês. Se acharem um caminho melhor, melhor ainda. A única coisa que
eu não faria é decorar palavra por palavra, porque o avaliador interrompe no meio e quem
decorou trava.

O objetivo é um só: o avaliador sair do estande querendo que esse radar esteja na escola
dele.

## O produto

Um radar de evasão escolar. A escola coloca os dados que ela já tem de um aluno, frequência,
notas, reprovações, idade em relação à série, e o sistema diz qual o risco desse aluno largar
a escola e, principalmente, por quê.

A ideia que sustenta ele é simples: quando a escola percebe que o aluno vai sair, ele já
saiu. Os sinais estavam lá meses antes, espalhados em planilha, diário e boletim, e ninguém
juntou.

É isso que eu apresentaria, e não "vamos fazer uma IA que prevê evasão". IA prevendo coisa
todo mundo já ouviu. Professor chegando antes do aluno desistir, não.

## A ordem que eu seguiria

Pra mim a ordem importa mais que as palavras exatas.

Eu começaria por uma pessoa, não por número. Aquele colega que começou o ano com a gente e em
algum momento parou de aparecer. Todo mundo na feira conhece um, então pega. O que eu
evitaria é abrir com estatística ou com "machine learning", porque aí o avaliador vira
espectador.

Depois eu mostraria que o problema não é falta de informação, a escola tem informação de
sobra. O problema é que ela está espalhada e só é olhada quando já é tarde. Esse é o pedaço
que tira vocês do "fizemos uma IA" e põe no "entendemos um problema".

Só então eu diria a proposta, em uma frase: juntar o que a escola já sabe e avisar antes. E
logo em seguida o diferencial, que é o sistema explicar o porquê. Eu acho que é nesse
segundo que o avaliador decide se vale a pena continuar ouvindo.

A tecnologia e o cuidado com os dados eu deixaria pro fim, entrando como prova de que vocês
pensaram direito, nunca como lista de ferramenta. E eu terminaria com ele fazendo algo, não
só ouvindo: olhando a tela do aluno no banner e respondendo qual fator ele acha que mais
pesa.

Resumindo o que vale pra tudo isso: vender o problema e deixar ele chegar na solução.
Abrindo com "usamos regressão logística e SHAP", vocês são avaliados como código. Abrindo com "a gente perdeu um colega e ninguém viu chegando", são avaliados
como ideia, e aí o plano técnico aparece no fim e vale o dobro.

## Como eu contaria

Escrevi do jeito que sairia da minha boca, pra vocês passarem pra voz de vocês. Dividi um
pedaço por pessoa porque eu desconfio de projeto que só um sabe explicar, e o avaliador
também.

### Pessoa 1, uns 45 segundos

Todo mundo aqui já teve um colega que começou o ano junto e em algum momento simplesmente
parou de vir. Ninguém avisou, ninguém percebeu o dia exato. Quando a escola foi atrás, ele
já tinha ido.

E aí a gente foi olhar e percebeu que os sinais estavam lá. A frequência caindo, a nota
caindo, uma reprovação no ano anterior, a idade já atrasada em relação à série. A escola
tinha tudo isso anotado. O problema não é falta de informação, é que ela fica espalhada em
diário, boletim e planilha, e ninguém junta as peças a tempo.

### Pessoa 2, uns 75 segundos

Então a nossa proposta é juntar essas peças. É um radar, e ele olha em dois níveis. De cima,
um mapa das escolas do NRE de Cascavel, mostrando onde o risco está mais alto, com dado
público do Censo Escolar e do QEdu. E de perto, o aluno: a escola coloca os dados que já tem
e o sistema mostra a chance dele largar a escola. Esse aqui no banner, por exemplo, deu 82%,
risco alto.

Mas o que a gente acha mais importante não é o número, é o porquê. Do lado do risco aparecem
os fatores que mais pesaram, frequência, nota, faltas, reprovação. Não adianta falar pro
professor que o aluno tem risco alto e parar aí. Ele precisa saber o motivo, porque cada um
pede uma conversa diferente. Por isso a tela já sugere um plano de ação: conversar com a
família, acompanhamento pedagógico, busca ativa.

E foi isso que guiou a escolha do modelo. A gente comparou modelos e escolheu pela
explicação, não só pelo acerto. Se a IA não consegue dizer por que acha uma coisa, o
professor não tem motivo pra confiar nela, e nem deveria.

E tem o cuidado com os dados. Dado de aluno é dado de menor de idade, então pra treinar o
modelo a gente usa uma base pública e anonimizada, só com as informações que uma escola
brasileira também registra. Os dados de Cascavel entram no nível da escola, nunca do aluno.
O sistema não decide nada sozinho, ele avisa. Quem decide é o professor, o pedagogo, a
família.

### Pessoa 3, uns 30 segundos

Imagina isso na mão da coordenação de cada escola do NRE. Em vez de descobrir no fim do
bimestre que o aluno sumiu, ela recebe o aviso enquanto ainda dá tempo de conversar. O
próximo passo é validar o radar com dados reais das escolas daqui, com autorização e
dentro da LGPD.

E pra isso a gente quer saber uma coisa de você. Olha essa tela do aluno aqui. Se você fosse
professor, qual desses sinais você acha que mais pesa pra um aluno desistir? Guarda sua
resposta, porque é exatamente isso que o modelo responde.

### Se sobrar tempo e se precisar cortar

Sobrando tempo, eu mostraria o mapa antes do convite. É a tela que a secretaria e o núcleo
usariam: quais escolas precisam de atenção primeiro e como a taxa de evasão vem mudando ao
longo dos anos. Mostra que o radar serve pro aluno e serve pra gestão.

Se tivesse que cortar, eu cortaria o parágrafo da escolha do modelo, da Pessoa 2, e deixaria
só a frase "o sistema mostra o porquê". A ideia sobrevive sem a justificativa técnica, e o
avaliador pergunta se quiser.

## A versão de 30 segundos

Pra quem só passa no estande, ou pra quando o avaliador está com pressa:

Quando a escola percebe que um aluno vai desistir, ele já desistiu. Os sinais estavam lá,
frequência, nota, faltas, reprovação, mas espalhados. O radar junta o que a escola já sabe,
mostra o risco do aluno sair e explica por quê, pra o professor chegar antes. Esse aluno aqui
no banner deu 82%, e do lado está o motivo.

## Usando o banner

O banner é o roteiro. Cada pessoa aponta pra sua parte enquanto fala:

A Pessoa 1 não precisa de tela, é a história.

A Pessoa 2 aponta pro mapa de risco quando fala das escolas e pra tela do aluno quando fala
do 82%, dos fatores e do plano de ação.

A Pessoa 3 aponta pro banner inteiro quando fala da coordenação de cada escola, e volta
pra tela do aluno na pergunta final.

## As perguntas que eu aposto que vão fazer

Escrevi como eu responderia. A resposta de vocês pode ser melhor, desde que seja verdade.

**De onde vêm os dados do aluno?** De uma base pública e anonimizada de uma instituição de
Portugal, porque dado real de aluno não pode ser público. A gente usa só as variáveis que uma
escola daqui também tem. Ela espelha o mecanismo da evasão, não os números de Cascavel, e
por isso validar com dado local é o trabalho futuro. Dado inventado foi descartado de
propósito: um modelo treinado em dado inventado só devolve o que quem inventou já achava.

**E se o sistema errar e marcar um aluno injustamente?** Por isso ele não decide nada, só
avisa, e mostra o porquê. Se o motivo não fizer sentido pro professor, ele ignora. Um aviso a
mais custa uma conversa. Um aviso a menos pode custar um aluno.

**Isso não é rotular o aluno?** Essa eu ensaiaria bastante. O risco não fica com o aluno, fica
com a escola, como um lembrete de quem precisa de atenção agora. E o dado não sai da escola.

**O que o professor fez e o que vocês fizeram?** Aparece sempre. Eu respondo que escrevo as
tarefas e reviso o trabalho, e que a ideia, o estudo do problema e a construção são de
vocês, com o histórico do GitHub mostrando quem fez cada parte.
