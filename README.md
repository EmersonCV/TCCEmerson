# TCCEmerson

[![total downloads](https://img.shields.io/github/downloads/EmersonCV/TCCEmerson/total)](https://github.com/EmersonCV/TCCEmerson/releases) ![](https://img.shields.io/badge/Email-emerson.voltarelli62%40gmail.com-green) ![](https://img.shields.io/badge/Versão-0.9.0_Beta-yellow)

Olá, me chamo Emerson Castelhano Voltarelli, sou estudante do ultimo ano de Engenharia de Controle e Automação do IFSP de São João da Boa Vista e aqui estão todos os arquivos e informações sobre meu projeto de TCC. O projeto tem como base criar um software funcional de programação de microcontroladores pela lógica de máquina de estados, através de uma interface gráfica para programar a lógica do projeto que gera um código pronto para rodar na IDE do microcontrolador, afim de facilitar a etapa de implementação da solução. A ideia inicial era usar uma gama alta de microcontroladores, mas para os primeiros testes será desenvolvido apenas uma versão para o Arduino. Para qualquer dúvida, estou disponibilizando um [formulário](#formulário) para reporte de bugs, erros e sugestões, mas também é possivel entrar em contato pelo email: emerson.voltarelli62@gmail.com.

Professor Orientador: Daniel Espanhol Razera. (lattes: http://buscatextual.cnpq.br/buscatextual/visualizacv.do?id=K4761668T7)

**IMPORTANTE 1**: *Não necessita de instalação, basta rodar o executável.*

**IMPORTANTE 2**: *Se possível, após usar o programa e encontrar algum bug, por favor reporte pelo link do [formulário](#formulário) disponível abaixo, é simples e rápido e me ajudará com as futuras versões.*

**IMPORTANTE 3**: *Todas as versões também estão disponíveis no [Google Drive](https://drive.google.com/drive/folders/1UCouTdIfPdof5EfPR2Y5R4nd5PCfJvNz?usp=sharing).*

# Sumário

<!--toc-start-->
* [Formulário](#formulário)
* [Versões](#versões)
  * [Atual](#atual)
  * [Anteriores](#anteriores)
  * [Histórico de lançamentos](#histórico-de-lançamentos)
* [Tutoriais](#tutoriais)
  * [Video Tutoriais](#vídeo-tutoriais)
  * [Interface e navegação](#interface-e-navegação)
* [Copyright](https://github.com/EmersonCV/TCCEmerson/blob/master/LICENSE)
<!--toc-end-->

## Formulário

Com intuito de coletar dados para o TCC e aprimoramento do programa, criei esse formulário para reportarem possíveis bugs, erros ou sugestões, agradeço a todos que entrarem no link: [FORMULÁRIO](https://forms.gle/rHGeHskT5XBgKVj29)

## Versões

### Atual

* [TCC 0.9.0 (pt-br)](https://github.com/EmersonCV/TCCEmerson/releases/tag/v0.9.0-beta-(ptBR))

Nota: O projeto dessa versão está disponível na respectiva * [Release](https://github.com/EmersonCV/TCCEmerson/releases/tag/v0.9.0-beta-(ptBR)) e no [Google Drive](https://drive.google.com/drive/folders/1UCouTdIfPdof5EfPR2Y5R4nd5PCfJvNz?usp=sharing).*

* [Vídeo detalhando a versão](https://youtu.be/BN-fXTJBF3o)

### Anteriores

* [TCC 0.8.1 (pt-br)](https://github.com/EmersonCV/TCCEmerson/releases/tag/v0.8.1-beta-(ptBR))

* [TCC 0.8.0 (pt-br)](https://github.com/EmersonCV/TCCEmerson/releases/tag/v0.8.0-beta-(ptBR))

* [TCC 0.7.0 (pt-br)](https://github.com/EmersonCV/TCCEmerson/releases/tag/v0.7.0-beta-(ptBR))

### Histórico de lançamentos

#### 0.9.0: Integração com Arduino Command Line (09/01/2021):

     * Inserido opção de configuração de novas placas para o Arduino CLI;
     
     * Inserido opção de acesso as configurações gerais e das placas no menu superior;
     
     * Adicionado novas etapas de verificação na Pré-Compilação (pinos, avisos, etc);
     
     * Integrado Arduino CLI as etapas de compilação e envio do código.
     
#### 0.8.1: Funções e interrupções (23/12/2020):

     * Adicionado opção para criar e editar funções do usuário;
     
     * Adicionado configuração de interrupções externas;
     
     * Adicionado variáveis voláteis (para uso nas interrupções);
     
     * Inserido blocos dividindo o código fonte (facilitação de leitura);
     
     * Inserido eventos em alguns controles criados dinamicamente.

#### 0.8.0: Correções e novas features (02/12/2020):

     * Adicionado variáveis do tipo 'Tempo' (contadores, timers e clocks);
     
     * Inserido os tutoriais no programa;
     
     * Corrigido alguns textos errados;
     
     * Corrigido pinos E e R/W invertidos no LCD;;
     
     * Corrigido problema ao editar LCD;
     
     * Corrigido pino ENABLE na lista de LCD;
     
     * Ajustado posição de filtros e debounces nas configurações.

#### 0.7.0: Primeiro lançamento de testes beta (15/11/2020):

    * Layout definido;
  
    * Entradas, saídas e estados inseridos;
  
    * LCD Implementado;
  
    * Variáveis Inteiras, Float e Booleanas implementadas;
  
    * Pré-Compilação: Formulários, componentes, nomes, avisos.
  
    * Código gerado:
  
         -Entradas: Debounces e Filtros Analógicos;
       
         -Saídas: Definir valor e PID;
       
         -Ciclo de varredura;
       
         -Transição e lógica dos estados;
       
         -Frases no LCD.
         
         
## Tutoriais

### Vídeo-Tutoriais

*Aqui estão disponíveis os vídeo-tutoriais que postei no Youtube para auxiliar no uso do software.*

* [Playlist Youtube](https://www.youtube.com/playlist?list=PL3qKEtYRgLbeH7AN0ey96xThbChCQA10R)
    * [Introdução](https://youtu.be/DZ-aSdm23UY)
    * [Máquina de estados](https://www.youtube.com/watch?v=a5DeDrkABXk&t)
    * [Entradas digitais e analógicas](https://youtu.be/d337311d_B0)
    * [Saídas digitais e analógicas](https://www.youtube.com/watch?v=x7HS153erTk)
    * [Display LCD](https://www.youtube.com/watch?v=UwaOMptXVWg)
    * [Variáveis](https://www.youtube.com/watch?v=LftITC0HxAc&t)
    * [Funções e Interrupções](https://youtu.be/lHoSV9D4sUU)
    
 
