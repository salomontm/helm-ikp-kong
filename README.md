# helm-ikp-kongagregar repositorio



Orden de Carga de valores

1.- Fichero Values
2.- Un fichero de valores pasado en el install o upgrade con la opcion -f
3.- Parametros pasados con un --Set





######
helm get manifest NOMBRE-RELEASE
helm get values 
helm show chart

helm env 


helm create nombre_chart ->crea directorio con el nombre del chart
helm create chart1 -> crear archivos template
                      File chart -> version     -> version de instalacion del deploy
                                    appVersion  -> version del producto




helm upgrade -f ARCHIVO_CON_VALORES nombre_chart
helm upgrade nombre_chart . -> comando a ejecutar si estas dentro del directorio del chart (toma la config fel archivo values)

helm install -f ARCHIVO_CON_VALORES nombre_chart
helm install APP-NAME .  -> comando a ejecutar si estas dentro del directorio del chart (toma la config fel archivo values)

