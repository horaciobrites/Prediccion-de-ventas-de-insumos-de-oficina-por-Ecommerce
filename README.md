# Sobre el proyecto
Proyecto desarrollado en el marco del trabajo final de la carrera de Data Science dictado por CoderHouse, aborda el desafío de prever la cantidad de ítems que una empresa venderá en los proximos meses a través de su plataforma de comercio electrónico.
comprende varias etapas fundamentales en el proceso de analisis de datos, incluyendo limpieza y exploración de los datos, ingenieria de atributos y la implementación y comparación de diversos modelos predictivos para series temporales.
El repositorio incluye la notebook con información de meta data, explicación de cada uno de los pasos y el proceso metodológico. Además se incluye el conjunto de datos utilizados.
# Contexto de negocio
En la actualidad, la empresa se encuentra inmersa en la planificación estratégica de sus próximas inversiones y operaciones. En este contexto, la comprensión profunda del comportamiento de las ventas y la capacidad de prever su dirección a corto y mediano plazo se erigen como elementos críticos. La obtención de datos precisos y relevantes se convierte, por lo tanto, es una prioridad estratégica para orientar la toma de decisiones de manera informada y eficaz. Este informe está diseñado para satisfacer las necesidades de los altos, el departamento de ventas y principalmente a los equipos de logística y distribución.

En este exhaustivo análisis, exploraremos el rendimiento de las ventas de productos durante los últimos cuatro años, resaltando las tendencias y patrones clave en las ventas. Nuestra intención es proponer modelos de predicción de ventas que permitan anticipar los futuros patrones y tendencias. Es importante señalar que la empresa opera en el mercado estadounidense y se especializa en la venta de mobiliario, suministros y accesorios tecnológicos para oficinas. Este enfoque sectorial nos brinda una visión detallada del comportamiento del mercado y nos permite ofrecer soluciones más precisas y adaptadas a las necesidades específicas de nuestros clientes en el ámbito empresarial.

Este estudio se concentra en generar un pronóstico de la cantidad de productos vendidos semanalmente y proyectar las ventas para las próximas 4 semanas a partir de la última fecha conocida. Esta información resulta de suma relevancia para la planificación logística y distribución de los productos. Por ejemplo, permite definir la capacidad de procesamiento en el almacén logístico y establecer la capacidad de contratación del agente distribuidor de última milla, entre otros aspectos cruciales. Con este enfoque predictivo, se busca optimizar la gestión de inventario y recursos, garantizando una distribución eficiente y oportuna de los productos, lo que a su vez potencia la satisfacción del cliente y la eficacia operativa de la empresa.
# Objetivo y metodología
Nuestra principal meta es desarrollar un modelo predictivo capaz de estimar con precisión la cantidad de productos que se venderán. El conjunto de datos que emplearemos comprende información detallada sobre las ventas de los últimos cuatro años de una destacada compañía de comercio electrónico. Enfrentaremos este desafío como un problema de serie temporal, donde la fecha de la orden se presenta como la única variable de entrada, siendo la variable objetivo la cantidad de ítems que se comercializarán en un horizonte temporal de un mes, partiendo desde la última fecha registrada en el conjunto de datos.
