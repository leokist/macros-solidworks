# macros-solidworks
Macros in VBA for SolidWorks

MACRO - CONGELAR MONTAGEM - (FREEZE ALL PARTS INSIDE OF A ASSEMBLY)
 - Arrasta a Barra de Congelar em todas as peças dentro de uma montagem
   (Freeze all parts wich are inside of an assembly)
 - Peças somente leitura são ignoradas
   (Read only parts are ignored)
 - Gera um Log em txt com o nome dos arquivos que foram congelados, ou que estavam somente leitura
   (Creates a txt with error log, showing the name of read only parts)

MACRO - PROPRIEDADES DO DOCUMENTO - QUALIDADE DE IMAGEM - CONGELAR (CHANGE SOME DOCUMENT PROPERTIES AND FREEZE PARTS)
 - Percorre todos os arquivos de uma determinada pasta
   (Run thrugh all files inside of a fodler)
 - Altera algumas propriedades do documento
   (Change some document properties)
 - Congela as peças
   (Freeze parts)
   
MACRO - PROPRIEDADES PERSONALIZADAS E CONGELAR (CREATE CUSTOM PROPERTIES AND FREEZE PARTS)
 - Percorre todos os arquivos de uma determinada pasta
   (Run thrugh all files inside of a fodler)
 - Cria algumas propriedades personalizadas em cada configuração
   (Create some custom properties in all configurations)
 - Congela a peça
   (Freeze parts)
 
 MACRO - CONGELAR - 5 SUBPASTAS
  - Percorre todos os arquivos de uma determinada estrutura de pastas (com até 5 subpastas)
  - Abre cada peça e arrasta a barra de congelar
  - Abre as montagens e somente salva elas
  - Ignora arquivos somente leitura
  - Gera rquivo .txt informando quais arquivos estavam somente leitura e quais foram executados com sucesso

MACRO GRAVAR SOLIDWORKS
  - Obtem informações de células do excel
  - Grava as informações nas Propriedades Personalizadas do 3D que estiver ativo no SolidWorks
