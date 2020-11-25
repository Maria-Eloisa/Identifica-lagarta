**Universidade do Vale do Rio dos Sinos - UNISINOS**

**Programa de Pós-graduação em Computação Aplicada – PPGCA**

**Disciplina: Técnicas de Programação**

**Relatório do Trabalho de Implementação de uma rede que identificasse
se era ou não uma lagarta**

**Prof. Rodolfo Stoffel Antunes**

**Aluna: Maria Eloisa Mignoni**

**Novembro 2020**

Resumo

O ataque de pragas nas lavouras deixa um rastro de destruição e
prejuízos enormes aos agricultores. Nas lavouras de soja, a grande vilã,
são as lagartas, que atacam desde a folha até a vagem. Os diversos tipos
de lagarta que atacam a soja dificultam a sua identificação, dependendo
do conhecimento técnico do responsável pela lavoura, que faz a
identificação e o diagnóstico de forma manual. Os atuais sistemas de
identificação, classificação e diagnóstico ainda são carentes, e para a
soja, são praticamente inexistentes. A identificação de lagartas na soja
por imagem, será um grande avanço para a agricultura, evitará perdas e
prejuízos tanto econômicos quanto em produção.

**Apresentação**

A região centro-oeste é muito rica na produção de grãos, mas sofre com
as infestações de diferentes pragas, entre elas, a lagarta. Os prejuízos
causados por essas pragas afetam diversos segmentos, como a economia,
meio ambiente, recursos humanos, entre outros.

A proposta visa desenvolver um modelo e treiná-lo para Reconhecimento de
Padrões e Imagens para o controle de pragas na Agricultura –
reconhecimento de lagartas na soja, a fim de ajudar na prevenção e
combate as pragas, diminuindo assim os impactos na produção de grãos.

A proposta inicial era desenvolver e treinar um modelo de um Sistema de
Reconhecimento de Padrões e Imagens para o controle de pragas na
Agricultura – reconhecimento de danos nas folhas causadas pela da
lagarta na soja. Porém como os conjuntos de imagens de soja não
apresentaram danos nas folhas, pois todas são de lindas plantações, sem
pragas, não foi possível utilizá-las neste momento. Diante desse fato,
optou-se por fazer a identificação se era ou não uma lagarta na folha de
soja.

Com esse projeto, objetivou-se identificar padrões de imagens e aumentar
o controle de pragas na agricultura, o sistema foi treinado para
detectar lagartas nas folhas de plantações de soja.

O desenvolvimento desse sistema visa atender a alta demanda do controle
de pragas nas lavouras de soja. Portanto, o sistema de reconhecimento de
padrões em imagens tende a colaborar na identificação de características
da praga-lagarta na soja.

**Descrição:**

A ideia inicial é que o sistema, após treinado, utilizando um base de
dados, identificar se a praga existente na imagem é uma lagarta ou não.
Uma vez identificadas, o sistema será capaz de identificar e retornará
por meio de técnicas e algoritmos de Inteligência Artificial se existe
ou não lagarta na plantação.

Para o desenvolvimento e treinamento do modelo, usou-se a Linguagem
Python, ambiente Jupyter, Redes Neurais Convolucionais – CNN, algoritmo
Adam e imagem.

Linguagem python: Python é uma linguagem de programação de alto nível,
interpretada, multi-paradigma, de script, imperativa, orientada a
objetos, funcional (Reamat, 2020).

Ambiente Jupyter: ambiente para desenvolvimento utilizando a linguagem
python, mas pode ser utilizadas outras linguagens.

Redes Neurais Convolucionais – CNN: algoritmo de Aprendizado Profundo
que pode captar uma imagem de entrada, atribuir pesos e vieses que podem
ser aprendidos objetos da imagem e ser capaz de diferenciar um do outro.

Algoritmo Adam: é um algoritmo de otimização de funções objetivos
estocásticas a partir de gradientes de primeira ordem (Romaguera, 2017).

Imagens: foi utilizado dois conjuntos de 100 imagens cada para treinar,
sendo cem imagens positivas e cem negativas. Para teste pode-se usar
qualquer imagem, neste caso, ousou-se imagens de lagartas que não
estavam no rol das 100 imagens e outras imagens aleatórias.

Maiores informações, entrar em contato com eloisa@unemat.br
