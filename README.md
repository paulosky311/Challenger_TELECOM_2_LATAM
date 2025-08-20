# 📊 Proyecto de Predicción de Churn - Telecom

Este proyecto tiene como objetivo analizar datos de clientes de
**Telecom**, una compañía ficticia de telecomunicaciones, y desarrollar
modelos predictivos para anticipar la probabilidad de que un cliente
cancele sus servicios (**churn**).

------------------------------------------------------------------------

## 🚀 Objetivos

1.  **Explorar y limpiar los datos** para identificar columnas
    relevantes y eliminar aquellas innecesarias.\
2.  **Transformar variables categóricas** a formato numérico mediante
    **One-Hot Encoding**, garantizando compatibilidad con algoritmos de
    Machine Learning.\
3.  **Evaluar el balance de clases (Churn vs No Churn)** y analizar el
    impacto en los modelos predictivos.\
4.  **Realizar un Análisis Exploratorio de Datos (EDA)** para entender
    tendencias, correlaciones y patrones de comportamiento de los
    clientes.\
5.  **Construir y comparar modelos de Machine Learning** para predecir
    la cancelación de clientes.\
6.  **Emitir recomendaciones estratégicas** para reducir la tasa de
    cancelación de clientes en Telecom.

------------------------------------------------------------------------

## 📂 Contenido del Proyecto

1.  **Carga y exploración inicial de los datos**

    -   Identificación de columnas irrelevantes.\
    -   Limpieza de valores faltantes y duplicados.

2.  **Codificación de variables categóricas**

    -   Se utilizó **One-Hot Encoding** debido a la naturaleza de las
        variables (categóricas nominales).\
    -   Evita asignar jerarquías artificiales y funciona bien en
        algoritmos como regresión logística y árboles de decisión.

3.  **Balance de clases (Churn vs No Churn)**

    -   Se observó un **desbalance moderado** entre clientes que
        cancelan y los que permanecen.\
    -   Esto se representó gráficamente con histogramas y gráficos de
        pastel.

4.  **EDA - Análisis Exploratorio de Datos**

    -   Se generaron estadísticas descriptivas, distribuciones y
        correlaciones.\
    -   Se analizaron variables como: tipo de contrato, tiempo de
        permanencia, gasto mensual y soporte técnico.\
    -   Los clientes con contratos mensuales y mayores gastos tenían
        mayor propensión a cancelar.

5.  **Modelos Predictivos Implementados**

    -   Regresión Logística\
    -   Random Forest\
    -   XGBoost

    ✅ El mejor desempeño lo presentó **XGBoost**, con el mayor valor de
    **ROC-AUC** y precisión balanceada entre clases.

    ⚠️ Algunos modelos simples mostraron **underfitting**, como la
    regresión logística inicial.\
    ⚠️ El **Random Forest** mostró señales leves de **overfitting**, lo
    que podría ajustarse con regularización o reducción de complejidad.

6.  **Informe y Recomendaciones**

    -   Los principales factores de churn fueron: contratos mensuales,
        altos gastos, múltiples llamadas a soporte y baja fidelización.\
    -   **Sugerencias para Telecom**:
        -   Implementar descuentos o beneficios para contratos de largo
            plazo.\
        -   Programas de fidelización y retención.\
        -   Mejorar la calidad del servicio al cliente y soporte
            técnico.\
        -   Identificar clientes con alto gasto mensual y ofrecer planes
            personalizados.

------------------------------------------------------------------------

## 📈 Resultados Clave

-   **Churn Rate**: Se identificó un desbalance en torno a la proporción
    de cancelaciones.\
-   **Modelo ganador**: XGBoost, con el mejor desempeño general en
    métricas de clasificación.\
-   **Insight de negocio**: Los contratos mensuales y costos elevados
    son los principales drivers de cancelación.

------------------------------------------------------------------------

## 🛠️ Tecnologías Usadas

-   **Python**\
-   **Google Colab**\
-   **Pandas / NumPy** (manipulación de datos)\
-   **Matplotlib / Seaborn** (visualización)\
-   **Scikit-learn** (modelado y métricas)\
-   **XGBoost** (modelo predictivo avanzado)\
-   **Statsmodels** (análisis estadístico complementario)

------------------------------------------------------------------------

## 📌 Conclusiones

Este proyecto demostró cómo el análisis de datos y el Machine Learning
pueden apoyar la toma de decisiones estratégicas en una empresa de
telecomunicaciones. El modelo de predicción desarrollado permite
identificar clientes en riesgo de cancelar y abre la puerta a
estrategias preventivas que reduzcan el **churn** y mejoren la
rentabilidad de la compañía.
