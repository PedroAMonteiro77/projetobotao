REQUISITOS GERAIS DO PROJETO

1 - Requisitos gerais
  . Projeto contara com 5 botões;
  . Os botões devem ascender em 5 cores diferetes;
  . Os botões devem ascender em tempos independetes ou simultaneos;
  . Os botões serão independetes fisicamente;
  . Terá 2 modos de funcionamento;
  . A unidade de processamento sera um notebook;
  . As informações serão armazenadas na unidade de processamento (notebook);
  . Cada botão sera encapsulado;
  . Cada botão deve possuir um microcontrolador da familia ARM (modelo STM32F103C8T6); 
  . Cada botão deve possuir uma modulo BLE;
  . Ser leve e robusto;
  . Facil manuseio;

2 - Requisitos de usuario
  . Será utilizado por pacientes tratando lezão de ligamento cruzado anterior;
  . Pode ser usado para:
    - Teste de reflexo;
    - Teste de memória;
  . Start via notebook;
  . O botão devera ser preciosado com o pé ou com a mão;
  . Ao fim do seção sera gerado um relatorio de desempenho;
  . O usuario que ira manusiar;

3 - Requisitos mecanicos
  . Deve ser robusto uma vez que sera utilizado com o peso/força;
  . tem o seu tamanho limitado;
  . Deve ser facil deslocamento;
  . A sua base deve ser antiderrapante;
  . O seu topo deve ser translucido;
  . O sensor de toque deve ter um range de acionamento limitado
  . Botão de automação;
  . Os 5 botões devem se acoplar;
  . Deve ser feito um suporte de proteção para a bateria;
  . O projeto não é a prova dagua;
  . O projeto não permite quedas de grandes alturas;
  
4 - Requisitos elétricos
  . Comunicação:
    - Cada botão deve ter um modulo ble;
    - Os botões irão trocar informações com o notebook pelo bluetooh;
    - Notebook deve funcionar como uma central;
    - O notebook deve mandar e receber informações dos botões simultaneamentes; 
  . Micro:
    - O microcontrolador deve ser classificado como uma máquina de 16 bits ou maior;
    - O microcontrolador deve ser alimentado com uma tensão não superior a 3.3V;
    - O microcontrolador deve possuir pelo menos um periférico do tipo USART;
    - O microcontrolador deve possuir pelo menos um periférico do tipo I2C;
    - O microcontrolador deve possuir, pelo menos, um periférico do tipo SPI ;
    - O microcontrolador deve possuir, pelo menos, 8 portas GPIO livres;
    - O microcontrolador deve possuir suporte a interrupções;
    - O microcontrolador deve possuir memórias do tipo FLASH e SRAM;
    - O microcontrolador deve possuir suporte a gravação e debugação;    
    - É desejável que o microcontrolador possua um periférico DMA;
    - Ferramentas, IDE, Toolchain e Bibliotecas;
    - Suporte do Fabricante e Documentação;
    - Deve ser utilizado cristal externo;
  . Alimentação:
    - Cada botão tera uma bateria;
    - A bateria deve ser carrecado por um cabo USB - C;
    - Cada botão sera carregado independentemente;
    - Cada botão tera um modulo de carregamento;
    - Deve haver reguladores para as diferentes tensões dos componentes;
    - O modulo deve conter um monitorador de bateria;
    - Cada botão deve conter um led indicador de bateria;
  . Cada botão tera um ou mais led RGB de alta potencia;
  . Cada led sera alimentado por x volts;
  . Led deve ser anodo comum;
  . Botão funcionara como push-pull
  
5 - Requisito de software
  . O software sera de facil uso;
  . O software tera que dar inicio aos modos de operação;
  . Após o inicio do modo de operação o software tera que acionar um timer para contabilizar o tempo da seção;
  . O software tera que guardar os dados recebidos dos botões;
  . O software tera que amazenar os tempos das seções;
  . Após um periodo determinado pelo usuario o sofware tera que gerar uma planilha de desempenho;
  
  
