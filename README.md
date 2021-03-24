## Practico de Aprendizaje Profundo

### Informe de Entrenamiento

Se realizaron entrenamientos con MLP y CNN.

Con __MLP__ se entrenaron modelos modificando los hiperparamatros epoch, embeding-size y freeze , sabiendo que 
colocando en false este ultimo el modelo puede overfitear. No se notaron cambios drasticos al modificar estos valores, 
se puede notar que aumenta el accuracy y disminuye las medidas de perdida.

![newplot](https://user-images.githubusercontent.com/47707311/112336712-1466cb80-8c9c-11eb-8640-cc020123d61b.png)


![newplot (1)](https://user-images.githubusercontent.com/47707311/112337471-b2f32c80-8c9c-11eb-8d15-deee5a30f790.png)


Con __CNN__ se entrenaron modelos modificando distinto paramentros estos son epochs, fc_size, filters_count, filter_lenght en 
el cual se agrego una capa. Igual que el modelo anterior el accuracy disminuye y y las de perdida aumentan.

![Captura de Pantalla 2021-03-24 a la(s) 15 45 57](https://user-images.githubusercontent.com/47707311/112367095-438b3600-8cb8-11eb-9183-23da41ee2feb.png)


