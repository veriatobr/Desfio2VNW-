GLEICIANE MEU AMOR



# Projeto de Interface Responsiva - Logística Portuária

Este repositório contém a implementação de uma página web responsiva para um projeto de logística portuária, com o objetivo de simular o layout fornecido no Figma de forma fiel, utilizando boas práticas de design e desenvolvimento web.

## 🎯 **Objetivo do Projeto**

O desafio consiste em criar uma interface responsiva que se adapte a diferentes tamanhos de tela, aplicando técnicas modernas de design e desenvolvimento. O layout deve ser estruturado e funcional, garantindo uma boa experiência para o usuário.

---

## 📋 **Requisitos Técnicos**

### Implementações realizadas:

1. **Unidades de Medida Relativas**:

   - Foram utilizadas unidades como `vw` (largura da viewport), `vh` (altura da viewport) e `em` para garantir que o layout seja dinâmico e responsivo.

2. **Estrutura com Flexbox**:

   - O layout foi organizado utilizando o **Flexbox**, proporcionando alinhamento e distribuição eficiente dos elementos em diferentes resoluções de tela.

3. **Tags de Formulário**:

   - Foram implementadas tags como:
     - `<form>`: Para criar um formulário funcional.
     - `<input>`: Para campos de entrada de dados.
     - `<textarea>`: Para campos de texto.

4. **Imagem de Fundo**:

   - A propriedade CSS `background-image` foi utilizada para adicionar imagens de fundo e melhorar a estética da página.

5. **Uso de Tags Semânticas**:
   - Foram usadas tags semânticas como `<header>`, `<main>`, `<footer>`, `<section>`, e outras para estruturar o conteúdo de maneira organizada e acessível.

---

## 💡 **Diferenciais**

- **Responsividade:** A página foi projetada para funcionar perfeitamente em diferentes dispositivos, como desktops, tablets e smartphones.
- **Acessibilidade:** O uso de tags semânticas melhora a acessibilidade, facilitando a leitura por ferramentas como leitores de tela.
- **Design Modular:** O uso do Flexbox permite uma adaptação natural do layout, sem quebra de elementos.

---

## 🚀 **Tecnologias Utilizadas**

- **HTML5**: Para a estrutura da página e marcação semântica.
- **CSS3**: Para estilização, incluindo o uso de Flexbox, imagens de fundo e unidades de medida relativas.

---

---

## 🛠️ **Como Executar o Projeto**

1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/projeto-logistica-portuaria.git
   ```
2. Navegue até o diretório do projeto:
   ```bash
   cd projeto-logistica-portuaria
   ```
3. Abra o arquivo index.html em seu navegador.

---
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        <main>
            <section class="secao1">
                <img alt class="imgsecao1"
                    src="./img/6ba567ef9e94f172c378e6b2c5e3d205.jpg">
                <a class="buttonsecao1" href="#"><button>serviços</button></a>
            </section>

            <section class="secao2">
                <div>
                    <article class="artigosecao2">
                        <h2 class="titulosecao2">Gestão portuária integrada</h2>
                        <p class="psecao2">Simplificando suas operações
                            portuarias</p>
                        A PortoLogistica é um sistema de gestão integrado de
                        ultima
                        geração desenvolvido para aumentar a eficiência e a
                        segurança das operações portuárias no Brasil. Nossa
                        plataforma oferece monitoramento em tempo real,
                        automação de
                        processos e análise de dados, garantindo que suas
                        necessidades de movimentação, descarga e armazenamento
                        de
                        carga sejam atendidas com precisão. Faça parceria
                        conosco
                        para obter uma solução robusta e confiável para agilizar
                        seus fluxos logísitcos.
                        <p>Entre em contato</p>
                    </article></div>
                <div>
                    <img class="imgsecao2" alt
                        src="./img/117c39b6c00b7560757b915b831ac770.jpg">
                </div>
            </section>

            <section>
                <h3>Nossas soluções</h3>
                <p>O que esperar do nosso sistema</p>
                <div>
                    <img alt src="./img/Containersatodomomento.jpg">
                </div>
                <div>
                    <img alt src="./img/+1000navios.jpg">
                </div>
                <div>
                    <img alt src="./img/monitoramento.png">
                </div>
            </section>
            <section id="secao4">
                <div id="atendimentocomercial">
                    <h4>Atendimento e Comercial</h4>
                    <p>Entre em contato com a unidade:</p>
                    <div>
                        <figure class>
                            <img alt id="img1" src="./img/niteroi.png">
                            <figcaption>niteroi</figcaption>
                        </figure>
                    </div>
                    <div>
                        <figure class>
                            <img alt id="img2"
                                src="./img/ilha da conceicao.png">
                            <figcaption>ilha da conceicao</figcaption>
                        </figure>
                    </div>
                    <div>
                        <figure>
                            <img alt id="img3" src="./img/santos.png">
                            <figcaption>santos</figcaption>
                        </figure>
                    </div>
                    <div>
                        <figure>
                            <img alt id="img4" src="./img/caju.png">
                            <figcaption>caju</figcaption>
                        </figure>
                    </div>
                </div>
                <div id="faleconosco">
                    <h5 id="faleconosco">Fale conosco</h5>
                    <p>Se conecte com nossos colaboradores</p>
                    <form action="processar_formulario.php" method="POST">
                        <label for="nome">Nome:</label><br>
                        <input type="text" id="nome" name="nome"
                            placeholder="Digite seu nome" required>
                        <br><br>

                        <label for="email">E-mail:</label><br>
                        <small>Informe um e-mail válido para
                            contato.</small><br>
                        <input type="email" id="email" name="email" required>
                        <br><br>

                        <label for="telefone">Telefone:</label><br>
                        <br>
                        <input type="tel" id="telefone" name="telefone"
                            <br><br>

                        <label for="mensagem">MENSAGEM:</label><br>
                        <textarea id="mensagem" name="mensagem" rows="4"
                            placeholder="Digite sua mensagem"></textarea>
                        <br><br>

                        <button type="submit">Enviar</button>

                    </form>
                </div>
            </section>
        </main>
        <footer>
            <p>[2024 Desafio produzido para fins educativos, Escola VAI NA WEB ]
                criado por @VERIATOBR</p>
        </footer>















        .headercontent {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 10px 20px;
    font-family: Arial, sans-serif;
    background-color: white;
    height: 130px;
    font-family: 'Oswald';
}

.logocontent{
    font-size: 20px;
    font-weight: bold;
}

.menucontent a {
    
    margin: 0 10px;
    text-decoration: none;
    color: gray;
    font-size: 14px;
    transition: color 0.3s;
}

.menucontent a:hover {
    color: black;
}

.contatocontent .contatobotao{
    
    padding: 5px 15px;
    border: 2px solid black;
    text-decoration: none;
    color: black;
    font-size: 14px;
    transition: background-color 0.3s, color 0.3s;

}
.contatocontent .contatobotao:hover{
    background-color: black;
    color: white;
}
}
.secao1{
    .imgsecao1{
        width: 1440px;
        height: 634px;
        top: 155px;
        border: 1px;

    }

    .buttonsecao1{
    :hover{
        background-color:solid black;
    }
    padding: 5px 15px;
    border: 2px solid black;
    text-decoration: none;
    color: black;
    font-size: 14px;
    transition: background-color 0.3s, color 0.3s;
    }
}
