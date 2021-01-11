<h1 align="center">Aplicando Design Patterns na Prática com C#</h1>

<h5 align="left">Definição</h5>

<p align="left">
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Design Patterns são soluções reutilizáveis para problemas comumente ocorridos (no contexto do design de software). Estes padrões foram iniciados como melhores práticas que foram aplicadas repetidamente a problemas semelhantes encontrados em diferentes contextos. Eles se tornaram populares depois que foram apresentados, de forma estruturada, no livro "Design Patterns - Elements of Reusable Object-Oriented Software" (Gang of Four) em 1994.
</p>

<p align="center">
  O "Gang of Four" representa apenas uma de muitas coleções.
</p>

<hr />

<h5 align="left">Enquete</h5>

<p align="left">
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="www.menti.com/iq57cex4f5">Quais padrões de projeto você conhece?</a>
</p>

<hr />

<h5 align="left">Gang Of Four</h5>

<p align="left">
  <img src="https://github.com/lucasrmagalhaes/aplicandoDesignPatternsNaPraticaComDotNet-DIO/blob/main/img/GoF.jpg" alt="Gang Of Four">
</p>

<hr />

<h5 align="left">Porque eu devo usar?</h5>

<ul>
  <li><strong>Produtividade:</strong> Estes padrões são modelos de resolução de problemas que já foram utilizados e testados inúmeras vezes;</li>
  <li><strong>Manutenção:</strong> Os padrões são baseados em soluções de baixo acoplamento e padronização de soluções;</li>
  <li><strong>Temos Universais:</strong> Os projetos são amplamente conhecidos desta forma as discussões técnicas são facilitadas, é mais simples falar o nome de um "design pattern" do que toda vez ter que explicar o seu comportamente.</li>
</ul>

<hr />

<h5 align="left">ATENÇÃO!!!</h5>

<p align="left">
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Antes de começar a apicar padrões de projetos precisamos entender algumas coisas...
</p>

<h5 align="left">Desuso</h5>

<p align="left">
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Alguns padrões surgiram para solucionar limitações de linguagens de programação com menos recursos no que diz respeito à abstração, nestes casos os padrões era como "gambiarras" que proporcionavam à linguagem a possibilidade de fazer implementações que não eram possíveis nativamente.<br />
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Linguagens mais recentes trazem alguns destes recursos nativamente, em alguns outros casos os padrões foram substituídos por padrões mais recentes.<br />
  
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;O padrão Strategy, por exemplo, pode ser substituído pelo o uso de uma função anônima.
</p>

<h5 align="left">Soluções "Prontas"</h5>

<p align="left">
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Os padrões não são soluções prontas, códigos que podemos pegar prontos e "jogar" dentro do projeto, em alguns casos é necessário ajustar o padrão ao contexto em que o projeto necessita, e isso costuma demandar um conhecimento mais profundo por parte da equipe de desenvolvimento.
</p>

<h5 align="left">A "bala de prata"</h5>

<p align="left">
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;É comum ver desenvolvedores que ao conhecer um novo padrão/técnica, tentam encaixar ele em todos os cenários, inclusive em situações onde uma abordagem mais simples seria suficiente para resolver o problema.<br />
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Um martelo é ótimo para colocar um prego na parede, mas não funciona tão bem se você tiver um parafuso.
</p>

<p align="center">
  Lembre-se: Não é uma competição para ver quem usa mais padrões.
</p>

<hr />

<h5 align="left">S.O.L.I.D.</h5>

<p align="left">
  <img src="https://github.com/lucasrmagalhaes/aplicandoDesignPatternsNaPraticaComDotNet-DIO/blob/main/img/OsPrincipiosDoS.O.L.I.D.jpg" alt="Os Princípios do S.O.L.I.D.">
</p>

<h5 align="left">Problemas comuns em aplicações que NÃO usam o S.O.L.I.D.</h5>

<ul>
  <li>Duplicidade de Código;</li>
  <li>Código sem estrutura coesa;</li>
  <li>Dificuldade de manter/evoluir;</li>
  <li>Pequenos ajustes podem quebrar o código, inclusive em outras partes do sistema;</li>
  <li>Dificuldade para executar e criar testes unitários; e</li>
  <li>Dificuldade de reaproveitar código para outras aplicações.</li>
</ul>

<h5 align="left">Principais benefícios</h5>

<ul>
  <li>Fácil manutenção;</li>
  <li>Fácil entendimento;</li>
  <li>Organização;</li>
  <li>Aberta a receber novas funcionalidades sem danos colaterais;</li>
  <li>Reaproveitamento de código; e</li>
  <li>Fácil adaptação a mudanças no escopo do projeto.</li>
</ul>

<hr />

<h5 align="left">Exemplos Práticos (WebAPI REST .NET Core)</h5>

<p align="left">
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="https://github.com/fructuoso/DesignPatternSamples">DesignPatternSamples</a>
</p>

<hr />

<h5 align="left">Estudos Complementares</h5>

<p align="left">
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="https://docs.microsoft.com/en-us/azure/architecture/patterns/">Cloud Design Patterns:</a> Apresenta os principais desafios do desenvolvimento na nuvem e padrões difundidos no mercado para supera-los.
</p>

<hr />

<h5 align="left">Referências:</h5>

<ul>
  <li>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="https://www.oodesign.com/">OODesign</a></li><br />
  <li>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="https://www.dofactory.com/net/design-patterns/">dofactory</a></li><br />
  <li>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="https://refactoring.guru/design-patterns">Refactoring Guru</a></li>
</ul>
