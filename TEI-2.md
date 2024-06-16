# Título do trabalho

1. Alexandre Munaier 
1. Luis Henrique Fantini
2. Henrique Lobo

* Lesandro Ponciano

## Introdução

1. A área da Engenharia de Software tratada neste trabalho é: Geração de código automático com inteligência artificial e seu uso no desenvolvimento de software.
1. O problema que este trabalho busca resolver nessa área é: Como a utilização de inteligências artificiais para geração de código impacta a taxa de acerto e a qualidade do software desenvolvido? Quais são as principais dificuldades e limitações enfrentadas na geração de código por IAs, tanto pelas próprias IAs quanto pelos desenvolvedores que utilizam essas ferramentas? De que maneira diferentes abordagens de IA (ex.: GPT-4, Codex) se comparam em termos de precisão e eficiência na geração de código?
1. Resolver este problema é relevante por que porque a crescente adoção de inteligências artificiais para tarefas de desenvolvimento de software traz à tona a necessidade de entender a eficácia dessas ferramentas em termos de precisão e qualidade do código gerado. Este estudo visa preencher a lacuna existente na literatura ao fornecer uma análise detalhada das capacidades e limitações das IAs na geração de código, contribuindo para a melhoria contínua dessas tecnologias e sua integração eficaz na indústria de software.
1. O objetivo geral deste trabalho é : Investigar e analisar a eficácia das inteligências artificiais na geração de código, com foco na taxa de acerto e na qualidade do software produzido.
1. Os *três* objetivos específicos deste trabalho são:
   - Avaliar a precisão da geração de código por diferentes ferramentas de IA (ex.: GPT-4, Codex).
   - Identificar as principais limitações e desafios enfrentados pelas IAs na geração de código.
   - Comparar a eficiência e a qualidade do código gerado por IAs com o código produzido por desenvolvedores humanos.

## Fundamentação Teórica

1. O conceito/teoria principal associado a este trabalho é Engenharia de Software Assistida por Inteligência Artificial (AI-SE). A sua definição neste trabalho é “AI-SE é um campo emergente que visa integrar técnicas de IA em ferramentas e metodologias de engenharia de software para auxiliar no desenvolvimento, testes, manutenção e evolução de software." conforme definido no trabalho "Incorporation of Autonomous Model Analytics for Avionic System Design into Standard Framework for Integrated Engineering"  (https://ieeexplore.ieee.org/document/9594432) pelo autor Carlos C. Insaurralde (2020).
1. O conceito/teoria secundária associado a este trabalho é a Geração de Código Automático com IA. A sua definição neste trabalho é "A geração de código automático com IA visa criar código fonte de software de alta qualidade a partir de descrições naturais ou modelos de software, utilizando técnicas de aprendizado de máquina, processamento de linguagem natural e outras áreas da IA para otimizar a eficiência, legibilidade e correção do código gerado." conforme definido no trabalho "CamBench -- Cryptographic API Misuse Detection Tool Benchmark Suite" (https://arxiv.org/abs/2204.06447) pelos autores: Michael Schlichtig, Anna-Katharina Wickert, Stefan Krüger, Eric Bodden, Mira Mezini (2022).
1. O conceito/teoria terciário associado a este trabalho é a Avaliação de Ferramentas de Geração de Código Automático. A sua definição neste trabalho é "A avaliação de ferramentas de geração de código automático envolve a análise do desempenho e da precisão dessas ferramentas em gerar código fonte correto e legível a partir de diferentes tipos de entradas, utilizando métricas quantitativas e qualitativas." conforme definido no trabalho "Towards Greener Yet Powerful Code Generation via Quantization: An Empirical Study"  (https://dl.acm.org/doi/10.1145/3611643.3616302) pelos autores: Xiaokai Wei, Sujan Kumar Gonugondla, Shiqi Wang, Wasi Ahmad, Baishakhi Ray, Haifeng Qian, Xiaopeng, Zijian Wang, Li, Varun Kumar, Qing Sun, Ben Athiwaratkun, Yuchen Tian, Mingyue Shang, Murali Krishna Ramanathan, Parminder Bhatia, Bing Xiang (2023).

## Trabalhos Relacionados

1. O trabalho mais relacionado é "Artificial Intelligence For Software Testing-Perspectives And Practices", publicado no ano de 2021 na IEEE(https://ieeexplore.ieee.org/document/9514942). Este trabalho revisa o estado da arte na aplicação de IA em testes de software, destacando como a IA e o aprendizado de máquina têm o potencial de avançar significativamente as capacidades de teste de software. Este estudo é relevante para a nossa pesquisa porque explora a integração da IA em processos críticos de desenvolvimento de software, fornecendo insights valiosos sobre os desafios e inovações necessárias para a adoção de IA em atividades de teste, o que pode ser comparável à geração de código automático com IA.
2. O segundo trabalho mais relacionado é "Factors Involved in Artificial Intelligence-based Automated HTML Code Generation Tool", publicado no ano de 2020 na IEEE(https://ieeexplore.ieee.org/document/9299609). Este artigo examina os fatores críticos envolvidos na geração automática de código HTML com base em IA. Ele aborda o processo de geração automática de código, que inclui a construção de máquinas que podem escrever código autonomamente. Este estudo é essencial para a nossa pesquisa, pois analisa a eficácia e os desafios das ferramentas de geração de código, alinhando-se diretamente com nossos objetivos de avaliar a precisão e a qualidade do código gerado por IA.
3. O terceiro trabalho mais relacionado é "Automatic Generation of Comments Based on Code Structure Enhancements", publicado no ano de 2022 na IEEE(https://ieeexplore.ieee.org/document/9862730/authors#authors). Este artigo propõe um método baseado em aprendizado profundo para gerar automaticamente comentários de código para métodos Java, utilizando informações estruturais do código. Os resultados mostram que o método proposto tem um desempenho superior em comparação com os modelos de última geração. Este trabalho oferece uma perspectiva sobre como as técnicas de IA podem ser utilizadas para melhorar a documentação do código, complementando assim a geração de código automático e contribuindo para a melhoria da legibilidade e manutenção do software.

## Materiais e Métodos

1. O tipo de pesquisa adotado neste trabalho é experimental e descritiva, porque envolve a realização de experimentos controlados para avaliar a eficácia das ferramentas de IA na geração de código, bem como a descrição detalhada dos processos e resultados observados.
2. Os materiais utilizados neste trabalho são ferramentas de IA para geração de código (ex.: GPT-4, Codex), repositórios de código para análise comparativa, e ferramentas de análise de código como SonarQube.
3. Os métodos empregados neste trabalho são:
   - Método de amostragem: Seleção de 10 projetos de software representativos de diferentes domínios (ex.: e-commerce, saúde, finanças) a partir de repositórios públicos como GitHub. Os projetos serão escolhidos com base em critérios como popularidade (número de estrelas e forks) e documentação disponível, garantindo que alguns foram gerados com auxílio de IA e outros não.
   - Método de análise de correlação: Para avaliar a relação entre as variáveis de precisão, qualidade e eficiência do código gerado.
   - Método de estudo de caso: Análise detalhada de três empresas que adotaram ferramentas de IA para geração de código, observando o impacto na produtividade e qualidade do software.
4. As métricas de avaliação são: precisão, legibilidade do código, eficiência (tempo de geração de código), e taxa de erros.
5. As etapas de execução do trabalho são:
 - Definição dos projetos de software e dados a serem utilizados nos experimentos.
 - Coleta de dados qualitativos através de questionários e entrevistas com desenvolvedores.
 - Realização dos experimentos de geração de código utilizando as ferramentas de IA.
 - Análise comparativa dos resultados utilizando métricas definidas.
 - Discussão dos resultados e identificação das principais limitações e desafios.
 - Conclusão e recomendações para futuras pesquisas.
