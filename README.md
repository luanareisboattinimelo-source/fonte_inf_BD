# fonte_inf_BD
Atividade da disciplina fonte de dados 

<img width="1198" height="737" alt="Screenshot_20260814-224818-display-0 png" src="https://github.com/user-attachments/assets/90791e9a-4cb4-4764-80bf-d3f9a4b0fe3a" />

         DADOS ABERTOS-HABILITAÇÃO MULTIMODAL

Pergunta 1

Qual é a quantidade de empresas com habilitação multimodal em cada estado (UF)?

Resultado: o estado com maior quantidade é SP, com 569 empresas.

      Fórmula utilizada: =CONT.SE(operador_transporte_multimodal!F:F;Gráficos!A5)
Pergunta 2

Quantas empresas possuem habilitação multimodal em cada estado da região Sudeste?

R: SP-569, RJ-110, MG-71, ES-22. Total=772

 Fórmula utilizada: =SOMA(B5;B8;B25;B26)

 https://centropaulasouza-my.sharepoint.com/:x:/r/personal/luana_melo7_aluno_cps_sp_gov_br/Documents/operador_transporte_multimodal%20lulu.xlsx?d=wfdbcec19c5db4438aa2d433bb48e9a79&csf=1&web=1&e=B5gksL
<img width="1229" height="391" alt="Capturar3" src="https://github.com/user-attachments/assets/21ea052f-f466-47a9-9685-7b6a893c25ba" />

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

       Dados Abertos- Analise de Dados Abertos da Receita Federal Faixa de Renda e Gênero

  *Pergunta 1*

Como evoluiu a quantidade de declarantes entre 2015 e 2020?

R: A quantidade de declarantes passou de 27.512.126 em 2015 para 31.632.151 em 2020, representando um aumento de aproximadamente 14,98%.

Fórmula :=SOMA(intervalo_declarantes)

=(Declarantes_2020-Declarantes_2015)/Declarantes_2015

<img width="1053" height="490" alt="Capturar" src="https://github.com/user-attachments/assets/57cfa89a-e288-474f-a262-cc3bbbf472a0" />



*Pergunta 2*

Em 2020, qual gênero teve a maior quantidade de declarantes?

R:O gênero Masculino, com 17.870.120 declarantes.

Fórmula =SOMASE(intervalo_gênero;"Masculino";intervalo_declarantes)

<img width="1024" height="422" alt="Capturar" src="https://github.com/user-attachments/assets/a8cc4be8-addd-4db4-838f-83ec999205f5" />


*Pergunta 3*

Em 2020, quantos declarantes estavam nas faixas de até 5 salários mínimos?

R: 25.461.913 declarantes estavam nas faixas de até 5 salários mínimos.

Fórmula:=SOMA(B2:B6)

<img width="1223" height="453" alt="Capturar" src="https://github.com/user-attachments/assets/f461a8b5-9cb8-4874-bde6-6589c82a70dd" />



*Pergunta 4*

Em 2020, qual gênero apresentou o maior total de rendimentos tributáveis?

R:O gênero Masculino, com 1.148.602,28 em rendimentos tributáveis.

Fórmula:=SOMASE(intervalo_gênero;"Masculino";intervalo_rendimentos)

<img width="1012" height="447" alt="Capturar" src="https://github.com/user-attachments/assets/07b71adb-8aeb-474e-ad97-b8627b77e778" />


*Pergunta 5*

Entre 2015 e 2020, qual foi a média de declarantes por gênero?

R:Feminino: 12.765.677 e Masculino: 17.001.602.

Fórmula:=MÉDIA(B2:B7) / =MÉDIA(C2:C7)

<img width="1516" height="239" alt="Capturar" src="https://github.com/user-attachments/assets/b6ae82ef-00bb-4269-ad44-3ef2567451bc" />


