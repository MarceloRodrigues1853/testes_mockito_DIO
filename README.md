<h1 align="center">Projeto de Testes de API e Serviços com Mockito</h1>
<p align="center">
Sejam bem-vindos ao projeto de testes de APIs e serviços, utilizando o framework Mockito para mockar dependências. Neste projeto, abordamos diversas práticas e estratégias para a criação de testes automatizados eficientes e confiáveis em um ambiente Java.
</p>
<h2>📚 Sobre o Projeto</h2>
<p>
<strong>Projeto replicado do curso Java da plataforma <a href="https://web.digitalinnovation.one/">Digital Innovation One (DIO)</a></strong>, que tem como objetivo fornecer exemplos práticos de como testar diferentes funcionalidades de APIs e serviços, garantindo a qualidade e a robustez das integrações e funcionalidades implementadas.
</p>
<p>Utilizando Mockito, conseguimos simular o comportamento de objetos complexos, permitindo que nossos testes se concentrem apenas nas funcionalidades específicas que estamos validando, sem a necessidade de interagir com dependências externas reais.</p>
<p>Com este projeto, você aprenderá a:
<ul>
  <li>Configurar o Mockito em um projeto Java.</li>
  <li>Criar mocks e stubs para simular comportamentos de dependências.</li>
  <li>Escrever testes unitários para serviços e APIs utilizando Mockito.</li>
  <li>Verificar interações e comportamentos de métodos mockados.</li>
  <li>Integrar testes unitários com uma pipeline de CI/CD utilizando Maven.</li>
</ul>
</p>
<p>Além disso, o projeto está estruturado para cobrir diversos cenários comuns em aplicações reais, desde o envio de mensagens e emails até a integração com APIs externas, como a dos Correios. Cada classe de teste demonstra diferentes técnicas e boas práticas para garantir que seu código seja testável e mantenha um alto padrão de qualidade.</p>
<h2>🛑 Pré-Requisitos</h2>
<p>
✅ Conhecer a sintaxe do Java<br>
✅ Java JDK 11 ou superior<br>
✅ IDE para desenvolvimento Java (usei IntelliJ, mas pode ser utilizado outro de sua preferência)<br>
✅ Maven 3.6.0 ou superior<br>
✅ Mockito<br>
✅ Git<br>
✅ Conta no GitHub<br>
</p>
<h2>📂 Estrutura do Projeto</h2>
<p>
O projeto está organizado da seguinte forma:
<ul>
  <li><code>ApiDosCorreiosTeste.java</code>: Testes para a API dos Correios.</li>
  <li><code>CadastrarPessoaTeste.java</code>: Testes para o cadastro de pessoas.</li>
  <li><code>ContaTeste.java</code>: Testes relacionados a contas.</li>
  <li><code>EnviarMensagemTeste.java</code>: Testes para envio de mensagens.</li>
  <li><code>GeradorDeNumerosTeste.java</code>: Testes para o gerador de números.</li>
  <li><code>PessoaTeste.java</code>: Testes gerais para a entidade Pessoa.</li>
  <li><code>PlataformaDeEnvioTeste.java</code>: Testes para a plataforma de envio de mensagens.</li>
  <li><code>ServicoEnvioEmailTeste.java</code>: Testes para o serviço de envio de emails.</li>
</ul>
</p>
<h2>👣 Passo-a-Passo</h2>
<p>
<strong>1.</strong> Clone o repositório:
<pre><code>git clone https://github.com/MarceloRodrigues1853/testes_mockito_DIO.git
cd testes_mockito_DIO</code></pre>
<strong>2.</strong> Compile o projeto e execute os testes:

<pre><code>mvn clean install</code></pre>
</p>
