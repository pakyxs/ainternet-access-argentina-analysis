# **Análisis del acceso a internet en Argentina**

## **`Introducción:`**

La relación entre el acceso a Internet en Argentina y el PBI per cápita (Producto Bruto Interno per cápita) puede ser compleja y multifacética. Aunque no existe una relación directa de causa y efecto entre estos dos indicadores, el acceso a Internet puede tener un impacto positivo en el desarrollo económico y el bienestar de un país. A continuación, exploraré algunos puntos relevantes sobre esta relación:

1. Acceso a la información: Internet brinda acceso a una amplia gama de información y conocimiento, lo que puede promover la educación, la innovación y la productividad. Un mayor acceso a la información puede facilitar el desarrollo de habilidades y conocimientos necesarios para el crecimiento económico.

2. Oportunidades comerciales: Internet proporciona un canal para la expansión de negocios y el comercio electrónico. Las empresas pueden aprovechar el alcance global de Internet para llegar a nuevos mercados, aumentar sus ventas y generar empleo. Un mayor acceso a Internet puede facilitar el desarrollo de emprendimientos y fomentar la creación de empleo.

3. Inclusión financiera: Internet también puede promover la inclusión financiera al facilitar el acceso a servicios bancarios y financieros. La disponibilidad de servicios en línea puede ayudar a las personas a administrar sus finanzas, acceder a crédito y participar en actividades económicas formales.

4. Conectividad rural: En muchos casos, las áreas rurales tienen acceso limitado a servicios básicos y oportunidades económicas. La expansión de la infraestructura de Internet en estas áreas puede mejorar la conectividad y abrir nuevas posibilidades en sectores como la agricultura, el turismo y los servicios en línea.

5. Brecha digital: Sin embargo, es importante tener en cuenta que la falta de acceso a Internet puede agravar la brecha digital y la desigualdad económica. Aquellos que no pueden acceder a Internet o carecen de habilidades digitales pueden quedarse rezagados en términos de oportunidades económicas y acceso a servicios básicos.

Es importante destacar que estos puntos son generales y que cada país y contexto específico pueden tener variaciones en la relación entre el acceso a Internet y el PBI per cápita. Además, otros factores, como la infraestructura, la educación, las políticas gubernamentales y la estabilidad económica, también influyen en el desarrollo económico de un país.

En resumen, aunque el acceso a Internet no es la única variable determinante en el PBI per cápita de Argentina, puede desempeñar un papel significativo al promover la educación, la innovación, el comercio electrónico y la inclusión financiera. Sin embargo, es necesario abordar la brecha digital para garantizar que todos los sectores de la sociedad se beneficien de las oportunidades que brinda la conectividad en línea.

## **`Contenido del repositorio:`**
- Dashboard.pbix: informe de gráficos del análisis realizado.
- Carpeta datasets: contiene los archivos de datos en formato .csv.
- EDA.ipynb: análisis de datos en lenguaje python.

## **`Fuente de información:`**

- Datos del acceso a internet: Fuente primaria: Ente Nacional de Comunicaciones (ENACOM), URL: https://datosabiertos.enacom.gob.ar/dashboards/20000/acceso-a-internet/
- Datos de PBI per cápita en dólares y pesos: Fuente primaria: Instituto Nacional de Estadística y Censos (INDEC), URL: https://datos.gob.ar/dataset/sspm-producto-interno-bruto-dolares-producto-interno-bruto-per-capita-poblacion.

## **`Análisis de datos:`**

- Del dataset de PBI per cápita realizamos unas transformaciones para crear las columnas Año y Trimestre y eliminar las columnas que no vamos a utilizar, todo esto con lenguaje Python, y así poder comparar el nivel de acceso a internet por habitantes con el PBI.

- Realizamos la visualización del contenido y tipo de datos de todos los datasets para saber con cuáles trabajar.

- En PowerQuery de PowerBi podemos observar información de los datos que contienen la tablas, por ejemplo: valores con error, vacíos, valores únicos, etc.
