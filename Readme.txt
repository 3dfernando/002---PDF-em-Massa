Para instalar a �ltima vers�o compilada, � necess�rio copiar 
os dois *.dll dentro de "00 - Instalar" para a pasta \Arquivos de Programas\Autodesk\Inventor 20XX\bin

Al�m disso, � preciso registrar as dlls. A rotina "00 - Register.cmd" foi escrita com essa
finalidade, mas ela est� programada para o Inventor 2014. Se voc� quiser programar para outra vers�o,
abra-a no bloco de notas e edite o caminho da pasta do Inventor.

Abaixo o que deve ser feito para instalar, caso desconfie ou n�o queira usar o *.cmd:

1. Abra o command prompt (Iniciar, pesquise por "cmd", execute como administrador)
2. digite:
C:\Windows\Microsoft.NET\Framework64\v4.0.30319\RegAsm.exe /codebase "C:\Program Files\Autodesk\Inventor 2014\bin\PDFemMassa.dll"

<Para isto voc� ter� que ter o Microsoft .NET Framework v4.0.30319 ou superior.>

3. Deve aparecer uma mensagem "Registro de tipos efetuado com sucesso". Caso n�o apare�a, verifique se executou como admin. Tamb�m tem que estar com o Inventor fechado nesta etapa.
4. Abra o Inventor e verifique se os novos bot�es da ferramenta aparecem nas barras de ferramentas Ribbon e no menu principal.

D�vidas enviar para fzigunov@gmail.com

***N�O ME RESPONSABILIZO POR NENHUMA PERDA DE DADOS DEVIDO AO USO DESTA FERRAMENTA!!! USE-A COM CAUTELA E CONSCI�NCIA!****


Autor: Fernando Zigunov - Licen�a Creative Commons 3.0