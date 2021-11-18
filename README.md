# Jump 2 Digital 💻
## Data Challenge - Akadelivers
By Juan Sirai



## Summary
Akadelivers es una empresa de reparto a domicilio especializada en la entrega de paquetes en menos de 1 hora, lo que se denomina (Q-commerce = Quick commerce) Esta empresa tiene una aplicación móvil con la que sus usuarios pueden elegir entre un catálogo de productos de tiendas locales de su ciudad y que les sean entregados en menos de 10 minutos a la dirección que deseen. Cuando un usuario pide un pedido a través de Akadelivers se le cobra directamente el coste del producto + gastos de servicio + gastos de envío. Una vez el usuario ha pagado un producto, el repartidor que se encuentre más próximo a la tienda que tiene el producto se acerca a esta, paga el producto, lo recoge y lo lleva a la dirección que el usuario ha elegido. Akadelivers se lo llevara a la dirección indicada.

## Dataset
Feature	Meaning
order_id	Número de identificación del pedido
local_time	Hora local a la que se realiza el pedidon
country_code	Código del pais en el que se realiza el pedido
store_address	Número de tienda en a la que se realiza el pedido
payment_status	Estado del pedido
n_of_products	Número de productos que se han comprado en ese pedido
products_total	Cantidad en Euros que el usuario ha comprado en la app
purchase_total_price	Costo total incluyendo envío + servicio
final_status	Estado final del pedido, este puede ser si se ha entregado o si se ha cancelado
Objetivos
1) ¿Cuáles son los 3 paises en los que más pedidos se realizan?
2) ¿Cuáles son las horas en las que se realizan más pedidos en España?
3) ¿Cuál es el precio medio por pedido en la tienda con ID 12513?
4) Teniendo en cuenta los picos de demanda en España, si los repartidores trabajan en turnos de 8horas. Turno 1 (00:00-08:00) Turno 2 (08:00-16:00) Turno 3 (16:00-00:00) Qué porcentaje de repartidores pondrías por cada turno para que sean capaces de hacer frente a los picos de demanda. (ej: Turno 1 el 30%, Turno 2 el 10% y Turno 3 el 60%).

5) Realiza un modelo predictivo de machine learning a partir del dataset 'train.csv' en el cual a partir de las variables predictoras que se entregan en el dataset 'test_X' se pueda predecir si el pedido se cancelará o no. Siendo: 0 = CanceledStatus 1 = DeliveredStatus
