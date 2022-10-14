# Desafio DATA_Viking - Detector de Fumaca
## 3° Bootcamp - Data Viking
### Objetivo
**Criar um Modelo de Classificação (aprendizado supervisionado) usando a base de dados**

**Dicionário de dados**
- Temperatura do ar
- Umidade do ar
- TVOC: Compostos Orgânicos Voláteis Totais; medido em partes por bilhão ( Fonte )
- eCO2: concentração equivalente de co2; calculado a partir de valores diferentes como TVCO
- H2 bruto: hidrogênio molecular bruto; não compensado (Viés, temperatura, etc.)
- Etanol bruto: gás etanol bruto ( Fonte )
- Pressão do ar 
- PM 1,0 e PM 2,5: tamanho do material particulado < 1,0 µm (PM1,0). 1,0 µm < 2,5 µm (PM2,5)
- Alarme de incêndio: a verdade do solo é "1" se houver um incêndio
- CNT: contador de amostra
- UTC: timestamp UTC segundos
- NC0.5/NC1.0 e NC2.5: Concentração numérica de material particulado. Isso difere de PM porque NC fornece o número real de partículas no ar. O NC bruto também é classificado pelo tamanho de partícula: < 0,5 µm (NC0,5); 0,5 µm < 1,0 µm (NC1,0); 1,0 µm < 2,5 µm (NC2,5);
**A coluna 'Fire Alarm' é a que consta se era Incendio ou não [ 0 = não, 1 = sim ]**
