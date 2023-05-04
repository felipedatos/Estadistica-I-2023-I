Tablas de frecuencia paquete base
================
Felipe Andres Martínez Vera

- <a href="#crear-un-cuaderno-nuevo" id="toc-crear-un-cuaderno-nuevo">1.
  Crear un cuaderno nuevo</a>
- <a href="#cargar-el-archivo-que-contiene-los-datos-a-colab"
  id="toc-cargar-el-archivo-que-contiene-los-datos-a-colab">2. Cargar el
  archivo que contiene los datos a <strong>Colab</strong></a>
- <a href="#cargar-las-librerias-que-se-van-a-utilizar"
  id="toc-cargar-las-librerias-que-se-van-a-utilizar">3. Cargar las
  librerias que se van a utilizar</a>
- <a href="#importar-los-datos-a-r" id="toc-importar-los-datos-a-r">4.
  Importar los datos a R</a>

# 1. Crear un cuaderno nuevo

Para crear un nuevo cuaderno de **Colab** basado en R use el este link:
<https://colab.research.google.com/#create=true&language=r>

# 2. Cargar el archivo que contiene los datos a **Colab**

<figure>
<img src="Cargar_archivo.png" style="width:80.0%"
alt="Cargar el archivo a Colab" />
<figcaption aria-hidden="true">Cargar el archivo a Colab</figcaption>
</figure>

# 3. Cargar las librerias que se van a utilizar

En este caso la idea es trabajar con el paquete “base” de R. Por lo
tanto no se cargará ninguna librería.

# 4. Importar los datos a R

El archivo que contiene los datos ya fue cargado a **Colab**, pero aún
no ha sido importado a R. Usaremos la funcion *read.csv* para importar
los datos a R.

      customerID gender SeniorCitizen Partner Dependents tenure PhoneService
    1 7590-VHVEG Female             0     Yes         No      1           No
    2 5575-GNVDE   Male             0      No         No     34          Yes
    3 3668-QPYBK   Male             0      No         No      2          Yes
    4 7795-CFOCW   Male             0      No         No     45           No
    5 9237-HQITU Female             0      No         No      2          Yes
    6 9305-CDSKC Female             0      No         No      8          Yes
         MultipleLines InternetService OnlineSecurity OnlineBackup DeviceProtection
    1 No phone service             DSL             No          Yes               No
    2               No             DSL            Yes           No              Yes
    3               No             DSL            Yes          Yes               No
    4 No phone service             DSL            Yes           No              Yes
    5               No     Fiber optic             No           No               No
    6              Yes     Fiber optic             No           No              Yes
      TechSupport StreamingTV StreamingMovies       Contract PaperlessBilling
    1          No          No              No Month-to-month              Yes
    2          No          No              No       One year               No
    3          No          No              No Month-to-month              Yes
    4         Yes          No              No       One year               No
    5          No          No              No Month-to-month              Yes
    6          No         Yes             Yes Month-to-month              Yes
                  PaymentMethod MonthlyCharges TotalCharges Churn
    1          Electronic check          29.85        29.85    No
    2              Mailed check          56.95      1889.50    No
    3              Mailed check          53.85       108.15   Yes
    4 Bank transfer (automatic)          42.30      1840.75    No
    5          Electronic check          70.70       151.65   Yes
    6          Electronic check          99.65       820.50   Yes
