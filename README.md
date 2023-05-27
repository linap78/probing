# Пробинг языковых моделей на данных с ошибками  
В этом репозитории находятся датасеты и программы, с помощью которых был проведён пробинг моделей *bert-base-uncased* и *xml-roberta-base* на данных с ошибками  
## Описание датасетов  
В папке 2014-2020 находятся датасеты, собранные на первом наборе данных (тесты из корпуса REALEC за 2014-2020 годы), в папке 2020 находятся датасеты, собранные на втором наборе данных (тесты из корпуса REALEC за 2020 годы, включая новые тексты за этот период)  
Каждый датасет представляет собой коллекцию минимальных пар с одной из следующих ошибок:  
### морфология:
- “Agreement error” — ошибки в согласовании (подлежащего и сказуемого, указательного местоимения и существительного и т. д.);
- “Noun number” — ошибки, связанные с выбором числа существительного;
### семантика:  
- “Verb pattern” — нарушения глагольного управления;
- "Choice of lexical item" — ошибки, связанные с подбором слов
### синтаксис:
- “Absence of component in a clause or sentence” — отсутствие элемента в конструкции, из-за которого фраза становится синтаксически дефектной или бессмысленной;
- “Redundant component in a clause or sentence” — случаи, когда из-за лишнего элемента в предложении возникает синтаксический или семантический дефекты;
### дискурс:
- “Redundant component in a clause or sentence” — случаи, когда из-за лишнего элемента в предложении возникает синтаксический или семантический дефекты;
- “Absence of component in a clause or sentence” — отсутствие элемента в конструкции, из-за которого фраза становится синтаксически дефектной или бессмысленной.
## Описание программы  
