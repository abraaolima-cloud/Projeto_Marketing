

<img width="1314" height="832" alt="image" src="https://github.com/user-attachments/assets/b0211cbb-b0e8-4ffd-9b70-7721ce865fe5" />



# Processo de Analise

Analise bivariada - duas variáveis (salario anual com gasto com alimentos) - utilizando grafico de dispersão

<img width="1299" height="733" alt="image" src="https://github.com/user-attachments/assets/a003dd5f-54f6-4a8c-8529-b29e690e266d" />

Analise bivariada - relação entre gasto e filhos

<img width="543" height="347" alt="image" src="https://github.com/user-attachments/assets/6e27f201-21ba-456d-91de-547b5fb60750" />

Analise de relação de tres variáveis diferentes(Total de gasto explicar por - escolaridade e estado civil)

<img width="610" height="366" alt="image" src="https://github.com/user-attachments/assets/f62cfe21-e256-46e1-9357-8ca687a0b27c" />






# Processo de Limpeza

Identifiquei um outlier

<img width="1182" height="672" alt="image" src="https://github.com/user-attachments/assets/430d1da9-7dc3-4088-ade1-804c29f375a4" />

Aplicando a escala logarítmica

<img width="1693" height="851" alt="image" src="https://github.com/user-attachments/assets/15bf54ac-e59a-402f-baa1-6f407cfeee7a" />

Removendo outlier 

<img width="1037" height="218" alt="image" src="https://github.com/user-attachments/assets/aaa52dfa-6c25-4466-8f64-216cce2b37b5" />
<img width="1618" height="636" alt="image" src="https://github.com/user-attachments/assets/198e8a8a-0935-43ea-85ec-bbfdaccc568c" />

# DAX

Dax para soma de total 

TotalGasto = sumx(DadosMarketing,DadosMarketing[Gasto com Alimentos]+DadosMarketing[Gasto com Brinquedos]+DadosMarketing[Gasto com Eletronicos]+DadosMarketing[Gasto com Moveis]+DadosMarketing[Gasto com Utilidades]+DadosMarketing[Gasto com Vestuario]) 

