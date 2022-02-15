# TCC peak shaving
SCADA da unidade de Geração


Organização do Repositório:
--------------------------------------------------------------------------------------------
  Documentação do Protocolo ModBus do Fabricante do Inversor
        
        Inverter_Protocol.pdf
        
  Classes/
 
        Definição da classe Parametros_IO:
           Parametros_IO.py
  
  Configurations/
 
 
       Parametros de acesso ao banco de dados:
          DataBaseConfigurations.py
 
       Definição dos tópicos que serão feitos publish/subrcribe, INV_REGS e WRITE_REGS:
          Topics.py

  Controllers/
  
       Código fonte do Raspberry:
          raspberry_code.py
      
       Código fonte do visualizador:
          visualizador_code.py
