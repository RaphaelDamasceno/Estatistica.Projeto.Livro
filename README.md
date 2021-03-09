Estatistica.Projeto
Projeto para matéria de Estatistica Alunos:

Pedro Raphael
João Marques
Bruna Carvalho
Como jogar
O projeto consiste em recriar a história da chapéuzinho vermelho, o narrador dita a história e no momento que você precisar tomar uma decisão. Ex.: A chapéuzinho andava pela rua quando um alquimista chega claramente assustado.

Você não vai naquela direção, certo? Perguntou o alquímico.
Sim, eu vou sim. | Não, vou pela estrada.

(as duas opções acima estarão com um hyperlink que dependendo da escolha ele vai para uma página X ou Y) Esse tipo de situação influenciará no resultado final da história, podendo ocorrer um bad ending ou good ending.

Pacote Bookdown
O Bookdown será o pacote que auxiliará no desenvolvimento do projeto. Ele gerará um livro em PDF que permite ir ou não. 

Instalação:
install.packages("bookdown") 
Lembrando que se você quiser usar a versão de desenvolvedor, pode instalar o pacote pelo GitHub através do remotes :: install_github ( ' rstudio / bookdown ' )

Usabilidade:
Para criar o projeto, você precisa ir em New Project > New Directory > Book project using Bookdown
Para construir apenas a versão HTML, vá no Build Pane > Build Book > bookdown::gitbook (lembrando que o bookdown::render_book() também pode ser usado) 
Depois de criado o projeto, entre no arquivo index.Rmd e depois clique em Knit
O Knit apenas renderiza o arquivo que você está editando no seu livro, para visualizar seu livro vá em Build > Build Book (Se quiser que seu projeto abra em PDF, precisa do LaTeX)

Dúvidas:
Para dúvidas, você pode usar dois forúns: https://stackoverflow.com/questions/tagged/bookdown+r e https://community.rstudio.com/tags/c/R-Markdown/10/bookdown

Comandos Necessários:
- bookdown::render_book() (Inícia um novo projeto bookdown)
- _text_ou *text* (Digita em Negrito)
- __text__ ou **text** (Digita em negrito)

# First-level header

## Second-level header  (Usados para criar cabeçalhos)

### Third-level header



