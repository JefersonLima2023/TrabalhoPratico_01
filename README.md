# TrabalhoPratico_01
 Repositório para trabalhos da disciplina teoria da informação e da codificação do curso de engenharia de telecomunicações da universidade federal de São João Del Rei. Disciplina do Oitavo período ministrada pelo professor Leonardo.

Tema do trabalho:
Comparação de Métodos de Criptografia: Cifra de César, Cifra da Espartilho (Scytale Cipher) e Cifra de Vigenère
O objetivo desta tarefa é comparar o desempenho e a segurança de diferentes métodos de criptografia, incluindo a Cifra de César, a Cifra da Espartilho (Scytale Cipher) e a Cifra de Vigenère. Ao implementar e analisar esses métodos, os alunos ganharão uma compreensão prática da criptografia clássica e suas características.

Instruções:
Redija um texto contemplando os seguintes aspectos:

Introdução:
Forneça uma breve introdução sobre criptografia e sua importância na segurança da informação.
Explique o conceito de criptografia simétrica e a diferença entre cifração e decifração.
Discuta a importância da segurança dos métodos de criptografia e as limitações dos métodos clássicos.

Cifra de César:
Apresente o método da Cifra de César, que é um método de substituição simples.
Explique o processo de cifração e decifração utilizando um deslocamento fixo do alfabeto.
Discuta as limitações da Cifra de César e sua vulnerabilidade a ataques de força bruta.

Cifra da Espartilho (Scytale Cipher):
Apresente a Cifra da Espartilho, um método de criptografia transposicional.
Explique o processo de cifração e decifração usando um cilindro com uma fita enrolada nele.
Discuta as características únicas da Cifra da Espartilho e sua resistência a ataques de força bruta.

Cifra de Vigenère:
Introduza a Cifra de Vigenère, um método de criptografia polialfabética.
Explique o conceito de palavra-chave e seu uso para gerar uma série de deslocamentos do alfabeto.
Destaque as vantagens da Cifra de Vigenère em relação à Cifra de César e discuta suas limitações.

Cálculo de Medidas de Teoria da Informação:
Explique o conceito de entropia e como ela quantifica a incerteza ou aleatoriedade de uma mensagem.
Calcule a entropia das mensagens originais em texto simples e dos textos cifrados obtidos por ambas as cifras.
Calcule a informação mútua entre o texto simples e o texto cifrado para cada cifra, destacando sua relevância na mensuração do vazamento de informação.
Para realizar os cálculos anteriores, utilize como base uma mensagem de texto suficientemente longa para que tais análises sejam significativas.

Técnicas de Criptoanálise:
Apresente técnicas básicas de criptoanálise, como análise de frequência e métodos estatísticos aplicáveis às cifras deste trabalho.
Analise as mensagens cifradas pelas três cifras usando análise de frequência para identificar padrões ou vulnerabilidades.
Realize ataques de texto escolhido para avaliar a resistência de cada cifra. Tente desvendar o texto cifrado conhecendo uma parte do texto original. Explore padrões, características linguísticas ou outras informações disponíveis para quebrar a cifra e recuperar o texto original.

Prática
Implementação e Testes:
Implementem os algoritmos da Cifra de César, Cifra da Espartilho e Cifra de Vigenère usando MATLAB/Octave.
Testem os algoritmos com diferentes mensagens e chaves para verificar a corretude das implementações.
Realize a cifração e decifração de mensagens utilizando cada método e comparem os resultados obtidos.
Façam testes trocando mensagens cifradas com os colegas, certificando assim a interoperabilidade possíveis diferentes implementações realizadas por cada um dos alunos.

Análise Comparativa:
Compararem os três métodos de criptografia com base em critérios como segurança, facilidade de implementação e desempenho.
Analise as vantagens e desvantagens de cada método em termos de resistência a ataques e praticidade de uso.
Discutam os resultados obtidos, comparando a eficácia dos métodos em diferentes cenários e contextos de aplicação.

Conclusão:
Resuma as conclusões da análise comparativa dos métodos de criptografia.
Destaque as principais características de cada método e sua relevância na segurança da informação.
Reflitam sobre a importância de selecionar o método de criptografia adequado com base nos requisitos de segurança e praticidade.

Observação: Para as implementações dos métodos, considere apenas textos e chaves com caracteres maiúsculos A-Z, remova todos espaços, sinais pontuação ou qualquer outro caractere diferente dos caracteres A-Z. Converta os caracteres minúsculos em caracteres maiúsculos. Documente o código de implementação, análises, resultados e observações ao longo da tarefa. Apresentem suas descobertas por meio de tabelas, gráficos e explicações claras. A citação adequada de quaisquer fontes externas utilizadas na tarefa é essencial.