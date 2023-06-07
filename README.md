# HSE-BI-ProjectIndividualPart

## Общая информация
**Ген:** SUV39H1
<br>**Эпигенетическая функция:** Histone modification write
<br>**Эпигенетическая группа:** H3K9me


**Статьи:** 
<br>[SUV39H1 and SUV39H2 were the first protein lysine methyltransferases that were identified more than 20 years ago. Both enzymes introduce di- and trimethylation at histone H3 lysine 9 (H3K9) and have important roles in the maintenance of heterochromatin and gene repression. They consist of a catalytically active SET domain and a chromodomain, which binds H3K9me2/3 and has roles in enzyme targeting and regulation. The heterochromatic targeting of SUV39H enzymes is further enhanced by the interaction with HP1 proteins and repeat-associated RNA](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8303541/)

[The histone methyltransferases (HMTs) that methylate H3K9 — in mammals Suppressor of variegation 3–9 homologue 1 (SUV39H1), SUV39H2, SET domain bifurcated 1 (SETDB1), SETDB2, G9A and G9A-like protein (GLP) — and the ‘readers’ of H3K9me2 or H3K9me3 are highly conserved and show considerable redundancy.](https://www.nature.com/articles/s41580-022-00483-w)


## Выравнивание гистонов
|Название | Скрин | Вывод |
|:-:|:-:|:-|
|H2A|![image](https://github.com/avakhunova/HSE-BI-ProjectIndividualPart/blob/main/files/H2A.png)|Между последовательностями есть не особо сильные различия,что, скорее всего, указывает на полиморфизм, различные мутации. Эти различия могли быть результатом эволюционных процессов или факторов окружающей среды, которые по-разному воздействовали на каждый гистон и ген. Наблюдаемые вариации могут иметь значение для функции и регуляции генов внутри гистонов, а также могут способствовать фенотипической изменчивости среди индивидуумов или популяций, обладающих этими гистонами.|
|H2B|![image](https://github.com/avakhunova/HSE-BI-ProjectIndividualPart/blob/main/files/h2b.png)|Между последовательностями есть не особо сильные различия,что, скорее всего, указывает на полиморфизм, различные мутации. Эти различия могли быть результатом эволюционных процессов или факторов окружающей среды, которые по-разному воздействовали на каждый гистон. Наблюдаемые вариации могут иметь значение для функции и регуляции генов внутри гистонов, а также могут способствовать фенотипической изменчивости среди индивидуумов или популяций, обладающих этими гистонами.|
|H3|![image](https://github.com/avakhunova/HSE-BI-ProjectIndividualPart/blob/main/files/H3.png)|Последовательности крайне похожи между собой, наблюдаются очень редкие и незначительные различия. Можно сказать, что гены являются копиями|
|H4|![image](https://github.com/avakhunova/HSE-BI-ProjectIndividualPart/blob/main/files/H4.png)|Последовательности крайне похожи между собой, наблюдаются очень редкие и незначительные различия. Можно сказать, что гены являются копиями|

## e-value, количество хитов, -log(e-value)
![image](https://github.com/avakhunova/HSE-BI-ProjectIndividualPart/blob/main/files/Снимок%20экрана%202023-06-07%20в%2017.02.46.png)

## HEAT MAP
![image](https://github.com/avakhunova/HSE-BI-ProjectIndividualPart/blob/main/files/Снимок%20экрана%202023-06-07%20в%2017.11.36.png)

## Код

** В терминале для выравнивания был использован следующий код :** blastp -query *protein*.fasta -db /mnt/storage/project_2023/proteomes/*proteome*.faa -out *proteome*.blast -outfmt 7


## Вывод 

Выбранный белок гена SUV39H1 эволюционно впервые появился у одноклеточных эукариотических организмов (Yeast). В дальнейшем, после дрожжей, белок был выражен у всех организмов (и у многоклеточных позвоночных, и у беспозвоночных). Данные выводы были сделаны на основании тепловой карты с условием наличия значения логарифма выше 10. 
<br>Для выбранного белка так же абсолютно очевидна связь с гистоном H3, что подтверждается более ярким цветом и более высокии значениями логарифмов соответственно по сравнению с другими гистонами. 
