# **Modelo de predicción de Fuga de Clientes en una compañía de telecomunicaciones**

#### **Contexto del problema**

Una compañía de telecomunicaciones pretende identificar posibles clientes con alto riesgo de cancelar sus servicios con la compañía a favor de la información que se tiene de estos. Con base en esto, se busca implementar un plan de acción con el objetivo de **retener** estos clientes y diseñar estrategias para aumentar la satisfacción de estos con los servicios.

#### **Objetivo**

Haciendo uso de técnicas de *Aprendizaje supervisado* se buscará el mejor modelo de clasificación posible para predecir los clientes con alto riesgo de cancelar sus productos con la compañia. Se seleccionarán los mejores modelos de los principales algoritmos usados en este tipo de casos y finalmente se evaluarán con un conjunto de datos totalmente desconocidos para, de esta forma, elegir el modelo con mayor precisión.

#### **Variables del dataset**

**Variables predictoras**

-------------------------------------------------------

**Customerid:** Id. del Cliente

**Gender:** Género del cliente

**Seniorcitizen:** Si el cliente es una persona jubilada o no

**Partner:** Si el cliente es socio o no

**Dependents:** Si el cliente tiene dependientes o no

**Tenure:** Cantidad de meses con servicios en la compañía

**Phoneservice:** Si el cliente tiene servicio telefónico

**Multiplelines:** Si el cliente cuenta con múltiples líneas telefónicas o no

**Internetservice:** Si el cliente cuenta con servicio de Internet

**Onlinesecurity:** Si el cliente cuenta con servicio de seguridad online

**Onlinebackup:** Si el servicio cuenta con servicios de backup

**Deviceprotection:** Si el cliente cuenta con servicios de protección para sus dispositivos

**Techsupport:** Si el cliente ha utilizado o no el servicio de soporte

**Streamingtv:** Si el cliente tiene servicio de televisión

**Streamingmovies:** Si el cliente cuenta con el servicio de streaming de películas y series de la compañía

**Contract:** Si el cliente tiene contrato mensual, anual o bimensual

**Paperlessbilling:** Si el cliente tiene factura electrónica

**Paymentmethod:** Tipo de pago utilizado por el cliente

**Monthlycharges:** Promedio de facturación mensual

**Totalcharges:** Total facturado para el cliente


**Variable a predecir**

--------------------------------------

**Churn:** Si el cliente canceló o no sus servicios con la compañía
