## Projeto 20 - Botão de Compartilhar Interativo


### 🚀 Sobre o Projeto

O projeto consiste em um botão central que, ao ser clicado, se expande e revela ícones de redes sociais para compartilhamento. O botão "Compartilhar" se transforma em "Fechar", e os ícones deslizam para a tela com um efeito de pop-up animado.

### 🛠️ Tecnologias e Conceitos Abordados

#### HTML5

O HTML usa uma estrutura simples, mas inteligente. A tag input com type="checkbox" e a tag <label> associada são a espinha dorsal da funcionalidade. A pseudoclasse :checked no CSS controla o estado visual de todos os outros elementos, fazendo a animação de abrir e fechar. Eu usei a biblioteca Font Awesome para os ícones, o que me permitiu adicionar ícones estilizados de forma fácil e eficiente.

#### CSS3
Eu usei várias técnicas avançadas de CSS para criar a animação. O uso de position: absolute com transform: translate() foi fundamental para centralizar o botão e os ícones na tela, independentemente do tamanho da janela. A pseudoclasse :checked em conjunto com o seletor de irmão geral (~) foi usada para mudar o estado visual do botão e do menu de ícones. O ::before, um pseudoelemento, foi usado de forma criativa para dois propósitos: primeiro, para alterar o texto do botão de "Compartilhar" para "Fechar" quando o menu está aberto, e segundo, para criar a pequena "seta" que conecta o menu ao botão. Finalmente, usei transições suaves (transition) nas propriedades de opacidade (opacity), posição (top) e no pointer-events para animar a abertura e o fechamento do menu. O pointer-events foi crucial para que os ícones ficassem invisíveis e não pudessem ser clicados quando o menu estava fechado.

### 💻 Como Executar:

Instale o arquivo no seu computador, e abra no seu navegador de preferencia.
