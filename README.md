
<body>

<h1>Análise de Exercícios de Programação em Python</h1>
<p>Os exercícios abordam conceitos fundamentais como estruturas de repetição (<code>for</code>, <code>while</code>), manipulação de strings, listas, dicionários e validação de dados.</p>

 <h3>Exercício 1: Média Bimestral</h3>
 <img width="576" height="801" alt="Captura de tela 2026-05-06 143202" src="https://github.com/user-attachments/assets/6a3a8aa9-35d3-49d2-8431-72e999808a95" />
<p>Trabalha a captura de múltiplas entradas e a conversão de <code>string</code> para <code>float</code>. A lógica baseia-se na média aritmética simples aplicada ao contexto escolar.</p>
        </div>

 

    
 <h3>Exercício 2: Conversor de Medidas</h3>
 <img width="532" height="431" alt="Captura de tela 2026-05-06 143308" src="https://github.com/user-attachments/assets/f742087b-53f4-44b3-acc5-3792f283a897" />
            <p>Focado em cálculos de conversão. Demonstra a habilidade de transformar requisitos do mundo real (conversão métrica) em uma expressão matemática simples no código.</p>
        </div>
       


<h2>Exercício 3: Nome em Escada</h2>
<img width="533" height="325" alt="Captura de tela 2026-05-06 143343" src="https://github.com/user-attachments/assets/532f9b37-6ce9-4188-8bf7-a70b74638f05" />

<p>O objetivo é imprimir o nome de forma progressiva. O código utiliza <span class="concept">fatiamento de strings (slicing)</span> dentro de um laço <code>for</code>.</p>
<div class="code-box">print(nome[:i])</div>
<p>A cada iteração, o índice <code>i</code> aumenta, mostrando uma letra a mais do nome até completá-lo.</p>

<h2>Exercício 4: Sequência de Fibonacci</h2>
<img width="560" height="379" alt="Captura de tela 2026-05-06 143524" src="https://github.com/user-attachments/assets/04d0580b-b4b3-43cc-8627-ea87c091e525" />

<p>Gera a sequência onde o próximo número é a soma dos dois anteriores. O algoritmo utiliza a técnica de <span class="concept">atualização de variáveis</span> simultânea:</p>
<ul>
    <li><code>a</code> começa em 1, <code>b</code> em 1.</li>
    <li>O próximo valor é calculado e as variáveis "andam" para a frente na sequência.</li>
</ul>

<h2>Exercício 5: Validação de Dados</h2>


<p>Este exercício foca em <span class="concept">estruturas de controle e persistência</span>. Utiliza-se <code>while True</code> para criar loops infinitos que só são interrompidos pelo comando <code>break</code> quando o usuário insere um dado que satisfaz os critérios (ex: idade entre 0 e 150).</p>

<h2>Exercício 6: Números Primos</h2>
<img width="1044" height="373" alt="Captura de tela 2026-05-06 143615" src="https://github.com/user-attachments/assets/44003107-2b4a-42f7-bb85-e028ac0d01ff" />

<p>Verifica se um número é primo testando sua divisibilidade. O ponto chave é o uso do operador <span class="concept">módulo (%)</span> para verificar se o resto da divisão por qualquer número entre 2 e o próprio número é zero.</p>

<h2>Exercício 7: Cálculo de Fatorial</h2>
<img width="856" height="234" alt="Captura de tela 2026-05-06 143622" src="https://github.com/user-attachments/assets/ec0a7a2b-0ef9-4971-8c43-aeeab4bf2df7" />

<p>Demonstra o uso de um <span class="concept">acumulador multiplicativo</span>. A variável <code>fatorial</code> começa em 1 e é multiplicada por cada número no intervalo de 1 até <code>n</code>.</p>

<h2>Exercício 8: Manipulação de Listas</h2>
<img width="591" height="421" alt="Captura de tela 2026-05-06 143628" src="https://github.com/user-attachments/assets/10ebfa8f-c8f5-4411-b9ef-f0386cb9d9da" />

<p>Explora funções integradas (built-in) do Python para análise de dados em listas:</p>
<ul>
    <li><code>len()</code>: Tamanho; <code>max()</code>: Maior valor; <code>min()</code>: Menor valor.</li>
    <li><code>sum()</code>: Soma total.</li>
    <li><code>sorted()</code>: Ordenação crescente e decrescente (usando <code>reverse=True</code>).</li>
</ul>

<h2>Exercício 9: Dicionários</h2>
<img width="533" height="250" alt="Captura de tela 2026-05-06 143633" src="https://github.com/user-attachments/assets/9792c609-aa6b-4c59-827d-1f1286c28197" />

<p>Introduz a estrutura de <span class="concept">chave-valor</span>. É a forma ideal para representar tabelas ou cardápios, onde cada item (chave) possui um preço associado (valor).</p>

<h2>Exercício 10: Verificação de Senha</h2>
<img width="1234" height="279" alt="Captura de tela 2026-05-06 143642" src="https://github.com/user-attachments/assets/fd7ad92c-c98e-436f-86cb-4fc2455f1f95" />

<p>Um exemplo clássico de <span class="concept">loop condicional</span>. O programa continua solicitando a entrada enquanto a condição <code>senha != senha_correta</code> for verdadeira.</p>

<h2>Exercício 11: Tabuada</h2>
<img width="554" height="311" alt="Captura de tela 2026-05-06 143648" src="https://github.com/user-attachments/assets/e5fc6564-007a-4eb5-911a-772db5852807" />

<p>Utiliza um laço <code>for</code> simples para iterar de 1 a 10, realizando cálculos aritméticos básicos e formatando a saída para o usuário.</p>

