# ClinicaVeterinaria

Clínica Veterinária Crie o Diagrama de Classes para um sistema de clínica veterinária, levando em consideração as seguintes características: 

Um cliente pode possuir muitos animais, mas um animal pertence única e exclusivamente a um único cliente. 

A clínica precisa de informações a respeito de cada cliente, como nome endereço e telefone; 

Um animal pertence a uma única espécie, porém podem haver diversos animais cadastrados de uma determinada espécie; 

É preciso manter informações a respeito de cada animal já tratado, como nome, sexo, idade e espécie a qual pertence;

Um animal pode realizar muitos tratamentos, mas um tratamento é realizado exclusivamente para um animal;

Cada tratamento possui ao menos uma consulta, mas pode possuir muitas consultas.
Uma determinada consulta refere-se exclusivamente a um determinado tratamento. 

Cada consulta deve armazenar informações como a data em que foi realizada, o veterinário que atendeu o animal e o resumo da consulta;

Um veterinário pode realizar muitas consultas, porém um consulta deve ser realizada por somente um veterinário; 

Em uma consulta podem ser marcados exames para o animal, o número de exames possíveis em uma consulta é indeterminado, mas precisam ser registrados.
