# Proyecto-1

El propósito del proyecto 1 fue la predicción de las ventas de un minorista a partir del entendimiento de sus variables y la manipulación de data.

# Data

Item_Identifier: Unique Item Identifier

Item_Weight: Item Weight

Item_Fat_Content: If the item was low fat or regular

Item_Visibility: Percentage of the area of all products in the store that contains this item

Item_Type: Item category

Item_MRP: Maximum Retail Price

Outlet_Identifier ID: ID of Store/Outlet

Outlet_Establishment_Year: Year the outlet was established

Outlet_Size: Categorized physical size of the outlet

Outlet_Location_Type: Categorized location type of the outlet

Outlet_Type: Categorized type of outlet (supermarket or grocery store)

Item_Outlet_Sales: Sales of the item, this is the target variable

En total tenemos 8523 atributos de data, repartido en 12 variables.

# Data Insights

En el análisis previo a la elaboración del trabajo, encontramos 2 variables con datos nulos:

-Outlet_Size
-Item_Weight

Para la primer variable mencionada, se tuvo que eliminar los nulos. Para la segunda, se pudo reemplazar con data de otras variables que contenian el mismo identificador.

# Plots

<img width="351" alt="image" src="https://user-images.githubusercontent.com/106395993/197909662-81aa0aa6-d43d-4596-9cd1-c50040d23d82.png">

Matriz de correlación, para comprender mejor la relación entre las variables. Gran correlación principalmente entre Item Outlet Sales y Item MRP.

![image](https://user-images.githubusercontent.com/106395993/197909897-7f25d900-ca6a-47bf-97a4-c3c40a715db7.png)

Gráfico que muestra la venta dependiendo el tipo de producto. Frutas y vegetales lideran la tabla.

![image](https://user-images.githubusercontent.com/106395993/197909998-35ebc79d-1f20-442f-964e-e3678b559fef.png)

Ventas por tipo de supermercado, en donde el supermercado del tipo 1 presenta los mejores resultados.

Existen más gráficos que pueden ser visualizados dentro del proyecto.

# Models and Results

Los modelos que se realizaron en el proyecto fueron KNN y Random Forest, y luego del desarrollo de los mismos podemos visualizar los siguientes resultados:

![image](https://user-images.githubusercontent.com/106395993/197911002-f1495621-a04f-486a-b74e-4387b377913c.png)

# Conclusions

El modelo que obtuvo los mejores resultados fue el KNN. Sin embargo, ningún modelo tuvo un gran nivel de rendimiento en el proyecto. Dicho esto, no sería recomendable basarse en este tipo de modelos para la predicción de las ventas con la base que se presentó.

























