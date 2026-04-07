<!DOCTYPE html>
<html lang="pt-BR">
</head>
<body>
    <div class="container">
        <div class="header">
            <h1>📚 Lógica de Programação & Algoritmos</h1>
            <p>Fundamentos essenciais para o desenvolvimento de software</p>
            <div>
                <span class="badge badge-python">Python</span>
                <span class="badge badge-git">Git</span>
                <span class="badge">GitHub</span>
            </div>
        </div>

  <div class="content">
  <!-- Linguagem de Programação -->
            <div class="section">
                <h2 class="section-title">💻 O que é uma Linguagem de Programação?</h2>
                <p>Uma linguagem de programação é uma linguagem escrita e formal que especifica um conjunto de instruções e regras usadas para gerar programas.</p>
                <ul class="info-list">
                    <li>Está presente em todos os aparelhos eletroeletrônicos funcionais</li>
                    <li>Existem várias linguagens, cada uma com propósitos específicos</li>
                </ul>
                
  <div class="concept-grid">
                    <div class="concept-card">
                        <h3>🔧 Sistema Embarcado</h3>
                        <p>Um sistema mais completo, com maior inteligência. Exemplo: geladeira com tela, sistema de refrigeração completo.</p>
                        <p><strong>Arduino</strong> é um exemplo de sistema embarcado.</p>
                    </div>
                    <div class="concept-card">
                        <h3>📝 Sintaxe</h3>
                        <p>Define as regras estruturais da linguagem: organização de palavras-chave, operadores e delimitadores.</p>
                    </div>
                    <div class="concept-card">
                        <h3>🎯 Semântica</h3>
                        <p>Refere-se ao significado das instruções escritas de acordo com a sintaxe da linguagem.</p>
                    </div>
                </div>
            </div>

<!-- Sintaxe vs Semântica -->
  <div class="section">
                <h2 class="section-title">⚠️ Sintaxe vs Semântica - Exemplos</h2>
                
  <h3>Sintaxe Incorreta (Erro):</h3>
                <div class="code-block code-error">
                    if x == 10 <br>
                    &nbsp;&nbsp;&nbsp;&nbsp;console.log("X é 10); // Erro de sintaxe (falta de parênteses)
                </div>
                
  <h3>Sintaxe Correta:</h3>
                <div class="code-block code-correct">
                    if (x == 10) {<br>
                    &nbsp;&nbsp;&nbsp;&nbsp;console.log("x é 10");<br>
                    }
                </div>
                
  <h3>Semântica Incorreta (Erro Lógico):</h3>
                <div class="code-block code-error">
                    let x = Number("10") + 5  // Resulta em "105" (concatenação)<br>
                    console.log(x)
                </div>
                
  <h3>Semântica Correta:</h3>
                <div class="code-block code-correct">
                    let x = Number("10") + 5  // Resulta em 15 (soma numérica)<br>
                    console.log(x)
                </div>
            </div>

<!-- Tipos de Linguagem -->
  <div class="section">
                <h2 class="section-title">📊 Classificação das Linguagens</h2>
                
  <div class="concept-grid">
                    <div class="concept-card">
                        <h3>🔄 Interpretado vs Compilado</h3>
                        <p><strong>Compilado:</strong> C, C++, Fortran - Código é traduzido antes da execução</p>
                        <p><strong>Interpretado:</strong> JavaScript, Python - Código é executado linha por linha</p>
                    </div>
                    
  <div class="concept-card">
                        <h3>📐 Tipagem Estática vs Dinâmica</h3>
                        <p><strong>Estática (Compiladas):</strong> <code>int numero = 10;</code> (Java) - Previne erros em tempo de compilação</p>
                        <p><strong>Dinâmica (Interpretadas):</strong> <code>numero = 10</code> (JavaScript) - Tipo é definido em tempo de execução</p>
                    </div>
                    
  <div class="concept-card">
                        <h3>⚡ Tipagem Forte vs Fraca</h3>
                        <p><strong>Forte:</strong> Operações entre tipos incompatíveis são proibidas (Java, C#)</p>
                        <p><strong>Fraca:</strong> Conversão implícita entre tipos (JavaScript)</p>
                    </div>
                </div>
                
  <h3>Modularidade e Reutilização:</h3>
                <ul class="info-list">
                    <li><strong>Funções e Métodos:</strong> Permitem dividir o código em partes reutilizáveis</li>
                    <li><strong>Bibliotecas e Frameworks:</strong> Conjuntos de funções pré-definidas para facilitar o desenvolvimento</li>
                </ul>
                
  <h3>Nível de Linguagem:</h3>
                <ul class="info-list">
                    <li><strong>Baixo Nível (Assembly):</strong> Linguagens mais próximas da máquina</li>
                    <li><strong>Alto Nível (Python):</strong> Linguagens mais próximas do ser humano</li>
                </ul>
            </div>

<!-- Estrutura do Projeto -->
  <div class="section">
                <h2 class="section-title">📁 Estrutura do Projeto</h2>
                <div class="file-structure">
                    <div class="folder">📂 main/</div>
                    <div class="file">├── 📄 Aula_0704.txt</div>
                    <div class="file">├── 📄 Aula_1003.txt</div>
                    <div class="file">├── 📄 Aula_2402.txt</div>
                    <div class="file">├── 📄 Aula_3103.txt</div>
                    <div class="file">├── 📄 README.md</div>
                    <div class="file">├── 🐍 operacoes_math.py</div>
                    <div class="file">└── 🐍 teste.py</div>
                </div>
            </div>

<!-- Exemplo de Código Python -->
  <div class="section">
                <h2 class="section-title">🐍 Exemplo Prático - Python</h2>
                <div class="code-block">
                    # Operações Matemáticas em Python<br><br>
                    # soma = 10 + 10<br>
                    # sub = 50 - 50<br>
                    # mult = 10 * 2<br>
                    # div = 100 / 10<br><br>
                    rest_div = 5 % 3<br>
                    div_int = 5 // 3<br><br>
                    print(f"O resto da divisão é: {rest_div}")<br>
                    print(f"O resultado da divisão inteira é: {div_int}")<br>
                    print(f"O resultado da divisão em fração é: {div_int/3}")<br><br>
                    # Input do usuário<br>
                    nome = input("Digite seu nome: ")<br>
                    print(f"Olá {nome}")
                </div>
                
  <div class="code-block">
                    print("Hello World!")  # Programa inicial
                </div>
            </div>

<!-- Git e GitHub -->
  <div class="section">
                <h2 class="section-title">🐙 Git & GitHub - Controle de Versão</h2>
                
  <h3>Conceitos Básicos do Git:</h3>
                <ul class="info-list">
                    <li><strong>Repositórios:</strong> Local onde fica o histórico do seu projeto</li>
                    <li><strong>Branch (Ramificação):</strong> Linha do tempo paralela</li>
                    <li><strong>Commit:</strong> Pontos na história do projeto</li>
                    <li><strong>Stage:</strong> Preparação do que será enviado para o ponto na história</li>
                </ul>
                
  <h3>Comandos Essenciais:</h3>
                <table class="commands-table">
                    <tr><td>git init</td><td>Inicia o Git (repositório) no seu projeto</td></tr>
                    <tr><td>git add .</td><td>Adiciona todos os arquivos modificados ao stage</td></tr>
                    <tr><td>git commit -m "mensagem"</td><td>Cria e descreve um ponto na história</td></tr>
                    <tr><td>git push</td><td>Envia alterações para o repositório remoto</td></tr>
                    <tr><td>git pull</td><td>Puxa alterações do repositório remoto</td></tr>
                </table>
                
  <h3>GitHub:</h3>
                <ul class="info-list">
                    <li>Plataforma online para hospedar seus códigos (através do Git)</li>
                    <li>Trabalhar em diversos projetos profissionalmente ou em time</li>
                    <li>Perfil para mostrar seu trabalho (Portfólio)</li>
  </ul>
                
  <h3>Comandos Linux Úteis:</h3>
  <div class="code-block">
  pwd      # Mostra o diretório atual<br>
  ls -La   # Lista todos os arquivos (incluindo ocultos)<br>
  ls       # Lista arquivos do diretório atual
  </div>
  </div>

  !-- Resumo -->
  <div class="section">
  <h2 class="section-title">🎯 Resumo dos Conceitos Aprendidos</h2>
  <div class="concept-grid">
   <div class="concept-card">
  <h3>📅 24/02 - Git & GitHub</h3>
  <p>Introdução ao controle de versão, comandos básicos e criação de conta no GitHub.</p>
  </div>
  <div class="concept-card">
  <h3>📅 31/03 - Linguagens de Programação</h3>
  <p>Conceitos fundamentais: sintaxe, semântica, tipagem, modularidade e níveis de linguagem.</p>
  </div>
  <div class="concept-card">
  <h3>🐍 Prática em Python</h3>
  <p>Operações matemáticas, entrada de dados, formatação de strings e lógica de programação.</p>
  </div>
   </div>
  </div>
   </div>

  <div class="footer">
  <p>📚 Portfólio de Estudos - Lógica de Programação, Algoritmos, Git e GitHub</p>
   <p>Desenvolvido por AliciaEPFlor | Atualizado em Abril de 2026</p>
  </div>
  </div>
</body>
</html>
