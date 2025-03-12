# DS_BetaBank

Tipo de proyecto: DS - Data Science

Sector: Banca

Tecnologías implementadas: Pandas | Numnpy | Seaborn | Matplotlib | Sklearn <DecisionTreeClassifier> <RandomForestClassifier> <LogisticRegression>

Introducción:

Los clientes de Beta Bank se van poco a poco cada mes. Los banqueros han descubierto que es más económico retener a los clientes existentes que atraer nuevos. Necesitamos predecir si un cliente dejará el banco pronto. Disponemos de datos sobre el comportamiento histórico de los clientes y las rescisiones de contratos con el banco.

- Crear un modelo para predecir si un cliente dejará el banco pronto.

Conclusiones:

En conclusión, tras ajustar y compensar las clases, se determinó que el mejor modelo de aprendizaje automático (ML) obtenido es el Bosque Aleatorio con los siguientes parámetros: RandomForestClassifier(class_weight='balanced', max_depth=10, n_estimators=51, random_state=1996), con repeat = 4.

Aunque este conjunto de ajustes no produce la puntuación F1 más alta, al probarlo con el subconjunto de datos de prueba, muestra la menor diferencia entre el modelo de validación y el modelo de prueba. Además, su valor de AUC-ROC es muy similar en ambos modelos.
