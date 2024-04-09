# Análise Diabetes

# Problema a ser resolvido

O time de negócios está interessado em descobrir padrões e insights que os ajudem a entender melhor o controle do diabetes e os fatores de risco associados. Eles querem identificar relações entre os diferentes atributos do dataset e a ocorrência de diabetes, a fim de desenvolver estratégias de prevenção mais eficazes, melhorar o tratamento dos pacientes e otimizar os recursos médicos disponíveis.
Descrição do dataset:

Pregnancies: Número de gestações.
Glucose: Nível de glicose no sangue.
BloodPressure: Medição da pressão arterial.
SkinThickness: Espessura da pele.
Insulin: Nível de insulina no sangue.
BMI: Índice de massa corporal.
DiabetesPedigreeFunction: Probabilidade de diabetes com base no histórico familiar.
Age: Idade
Outcome: Diabético ou não (1 para sim e 0 para não)



# Conclusões finais a partir das consultas anteriores:

As idade de 25 e 29 anos foram as idades que mais registraram casos para diabetes.
As idades 67 e 34 anos foram as idades que menos registraram casos para diabetes.
Com base nas consultas, nota-se uma tendência clara: quanto maior o número de gestações, maior a prevalência de diabetes. Com 100% das mulheres com mais de 14 gestações apresentando diabetes, essa proporção diminui para 84% com 11 gestações e para 62% com 8 gestações. Portanto, fica evidente que o aumento do número de gestações está associado a um maior risco de desenvolver diabetes.
Fora constatado que não há uma correlação entre os níveis de glicose no sangue e a pressão arterial de pacientes diabéticos, onde o resultado do coeficiente de Pearson é 0.03.
Fora observado uma correlação positiva moderada entre a espessura da pele e os indíces de IMC, onde o resultado do coeficiente de Pearson é 0.30. Isso significa que, em geral, à medida que o IMC aumenta, a espessura da pele tende a aumentar também, e vice-versa, mas não de forma muito forte.
Observa-se um maior nível de insulina no sangue para usuários que possuem obesidade de grau 1, grau 2 e grau 3. Essa conexão entre obesidade e hiperinsulinemia exibe a importância de estratégias de prevenção e manejo da obesidade para informar os riscos associados, como o desenvolvimento de diabetes tipo 2 e outras complicações metabólicas.
Observou-se que não existe correlação entre a idade dos pacientes e a espessura da pele.
Nos dados da amostra, usuários diabéticos possuem uma espessura da pele maior comparado a usuários não diabéticos.
Observou-se que não existe correlação entre a idade dos pacientes e níveis de insulina no sangue.
Conclui-se que existe uma associação entre diabetes e índice de massa corporal (IMC), independente da faixa etária, com os diabéticos tendendo a ter um IMC maior em comparação com os não diabéticos. Além disso, observa-se uma tendência de redução do IMC à medida que as faixas etárias avançam. Essas informações mostram a importância do controle do peso corporal e da prevenção da obesidade como medidas essenciais na gestão e na prevenção do diabetes, independente da idade.


# Estratégias de prevenção com base nas conclusões da análise:

Educação e conscientização pública: Implementar programas educacionais sobre os fatores de risco para diabetes, incluindo obesidade, número de gestações, e índice de massa corporal. Esses programas podem incluir informações sobre dieta saudável, exercícios físicos regulares e controle do peso corporal.

Rastreamento e diagnóstico precoce: Estabelecer protocolos de rastreamento regulares para diabetes, especialmente em faixas etárias com maior incidência, como entre 25 e 29 anos. Isso pode incluir exames de glicose no sangue, medições de pressão arterial e avaliação do IMC. Quanto mais cedo o diagnóstico for feito, mais cedo o tratamento pode começar, o que pode reduzir complicações a longo prazo.

Avaliação regular da espessura da pele e IMC: Introduzir protocolos para avaliação regular da espessura da pele e do IMC em pacientes diabéticos, como parte de exames de rotina. Isso pode ajudar a identificar indivíduos com maior risco de complicações e direcionar intervenções preventivas específicas.

Integração de cuidados de saúde: Promover uma abordagem multidisciplinar e integrada no cuidado de pacientes diabéticos, envolvendo médicos de várias especialidades, enfermeiros, nutricionistas, e outros profissionais de saúde. Isso pode melhorar a coordenação do tratamento, a adesão do paciente e os resultados de saúde a longo prazo.
