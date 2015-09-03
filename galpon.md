# Galpon de Ropa
Facundo Calcagno  




#Facturación Total del Galpon#

```
## [1] 1808534
```
#Facturación por Mes del Galpon# 

```
##     month Facturacion Cantidad PrecioporItem
## 1  201407     2035.00        1     2035.0000
## 2  201408    91887.00      347      264.8040
## 3  201409    83978.00      331      253.7100
## 4  201410    90670.00      391      231.8926
## 5  201411   103527.00      400      258.8175
## 6  201412   152870.00      552      276.9384
## 7  201501   156273.75      479      326.2500
## 8  201502   123681.50      378      327.1997
## 9  201503   193717.50      584      331.7080
## 10 201504   231189.25      611      378.3785
## 11 201505   285314.25      788      362.0739
## 12 201506   229288.50      643      356.5918
## 13 201507    64102.25      165      388.4985
```
 

#Ventas por día#

![](galpon_files/figure-html/unnamed-chunk-4-1.png) ![](galpon_files/figure-html/unnamed-chunk-4-2.png) 

#Ventas por semana#

![](galpon_files/figure-html/unnamed-chunk-5-1.png) ![](galpon_files/figure-html/unnamed-chunk-5-2.png) 





##Ganancia por Marca/tipo de prenda##

```
##               brand       type value    cost ganancia
## 7672           nike zapatillas 27855 12846.3  15008.7
## 7357     forever 21    vestido 12635  5786.3   6848.7
## 2536          levis       jean 12160  5718.5   6441.5
## 7604         adidas zapatillas  8490  3878.0   4612.0
## 2592       rapsodia       jean  8340  3746.0   4594.0
## 4058           nike     remera  8055  3590.5   4464.5
## 3886     forever 21     remera  7805  3368.0   4437.0
## 1603           nike    campera  8695  4395.0   4300.0
## 1965          prune    cartera  8010  3711.0   4299.0
## 7627       converse zapatillas  7735  3575.5   4159.5
## 5280        sabrina     tapado  6000  1860.0   4140.0
## 3832        complot     remera  6780  2654.5   4125.5
## 1405         adidas    campera  7615  3553.5   4061.5
## 1268 tommy hilfiger     camisa  7175  3587.5   3587.5
## 1563          levis    campera  6500  2998.5   3501.5
```

##Facturacion por Marca/tipo de prenda##

```
##                  brand       type value    cost ganancia
## 7672              nike zapatillas 27855 12846.3  15008.7
## 7357        forever 21    vestido 12635  5786.3   6848.7
## 2536             levis       jean 12160  5718.5   6441.5
## 1603              nike    campera  8695  4395.0   4300.0
## 7604            adidas zapatillas  8490  3878.0   4612.0
## 2592          rapsodia       jean  8340  3746.0   4594.0
## 4058              nike     remera  8055  3590.5   4464.5
## 1965             prune    cartera  8010  3711.0   4299.0
## 3886        forever 21     remera  7805  3368.0   4437.0
## 7627          converse zapatillas  7735  3575.5   4159.5
## 1405            adidas    campera  7615  3553.5   4061.5
## 1268    tommy hilfiger     camisa  7175  3587.5   3587.5
## 7727 Fratelli Rossetti     zapato  6840  3420.0   3420.0
## 3832           complot     remera  6780  2654.5   4125.5
## 1563             levis    campera  6500  2998.5   3501.5
```
##Costo por Marca/tipo de prenda##

```
##                  brand       type value    cost ganancia
## 7672              nike zapatillas 27855 12846.3  15008.7
## 7357        forever 21    vestido 12635  5786.3   6848.7
## 2536             levis       jean 12160  5718.5   6441.5
## 1603              nike    campera  8695  4395.0   4300.0
## 7604            adidas zapatillas  8490  3878.0   4612.0
## 2592          rapsodia       jean  8340  3746.0   4594.0
## 1965             prune    cartera  8010  3711.0   4299.0
## 4058              nike     remera  8055  3590.5   4464.5
## 1268    tommy hilfiger     camisa  7175  3587.5   3587.5
## 7627          converse zapatillas  7735  3575.5   4159.5
## 1405            adidas    campera  7615  3553.5   4061.5
## 7727 Fratelli Rossetti     zapato  6840  3420.0   3420.0
## 3886        forever 21     remera  7805  3368.0   4437.0
## 1563             levis    campera  6500  2998.5   3501.5
## 2521           kosiuko       jean  6060  2939.5   3120.5
```
#Tiempo promedio de venta#

#Marcas con mayor tiempo promedio para la venta#
###Dias para la venta###

#Marcas con menor tiempo promedio para la venta#
###Dias para la venta###



  
#Tipos de prenda con menor tiempo promedio para la venta
###Dias para la venta###



#Indicadores por Marca#

#Tabla de Marcas#

```
##                      sales buys avg_price avg_cost avg_win timetosell
## gap                    270  305     124.2     55.3    68.9       17.5
## prune                   95  108     163.1     74.5    88.6       25.6
## hollister               84   96     124.4     57.9    66.5        8.2
## rapsodia               405  465     122.5     55.6    66.9       17.6
## zara man                81   93     162.9     74.7    88.2       29.1
## adidas                 254  293     160.5     74.0    86.5       13.0
## tommy hilfiger         174  201     149.8     68.7    81.1       11.5
## lacoste                 83   96     129.5     58.8    70.7       13.8
## paula cahen d anvers   104  121     137.1     65.6    71.6       22.8
## ralph lauren            61   71     140.5     66.8    73.6       18.0
## nike                   428  504     170.9     80.2    90.7       16.2
## lucuma                  72   85     118.0     51.7    66.3       18.6
## desiderata              61   73     109.2     46.6    62.6       25.8
## de la ostia             60   72     133.3     59.1    74.1       25.6
## forever 21             503  606     135.5     62.0    73.5       16.1
## abercrombie            234  282     145.6     67.9    77.7       11.5
## jazmin chebar          139  168     131.7     61.4    70.3       18.6
## banana republic        132  160     122.1     54.9    67.2       16.9
## converse                66   80     153.9     71.4    82.5       22.3
## maria cher             130  158     126.2     59.0    67.2       15.6
## cuesta blanca          114  139      98.7     43.4    55.3       19.7
## soho                    63   77      99.6     45.2    54.4       39.3
## hym                    167  205     136.6     62.5    74.1       21.1
## undefined               92  113     111.4     50.6    60.8       25.2
## divided                140  172     138.7     63.3    75.4       14.1
## akiabara               260  322     106.4     49.2    57.2       14.5
## american eagle          62   77     141.1     65.7    75.4       -3.7
## vitamina               106  132     121.8     55.6    66.2       20.2
## levis                  258  322     131.5     59.5    72.1       16.4
## ona saez               148  185     117.1     52.1    65.0       17.0
## complot                369  462     103.5     44.6    58.9       14.3
## wanama                 158  199     122.6     56.7    66.0       22.4
## bensimon                77   97     147.0     61.6    85.4       18.0
## paula cahen danvers    142  179      99.3     45.0    54.2       15.1
## 47 street               63   81     108.5     49.5    59.0       16.1
## ay not dead            115  150     128.8     53.8    74.9       26.2
## koxis                   69   91     104.7     46.2    58.5       20.2
## las pepas               61   81     165.2     77.2    88.1       15.5
## zara                   464  617     112.7     51.1    61.6       20.5
## ayres                  235  313     109.0     49.4    59.6       20.4
## zara basic             100  134     124.8     56.6    68.1       24.9
##                         76  102     120.9     72.7    48.2       25.1
## kosiuko                251  338     127.1     58.7    68.4       12.7
## yagmour                 60   81      94.5     41.7    52.8       27.2
## trafaluc               103  140     131.0     54.5    76.5       20.5
## chocolate               97  133     113.2     54.4    58.8       17.5
## materia                 74  103      96.4     42.5    53.8       15.7
## tucci                   51   72     112.2     50.9    61.3       29.9
## uma                     64   92     132.9     62.1    70.8       28.1
## ossira                  67  101     103.2     45.9    57.4       31.2
##                      efectivity
## gap                        0.89
## prune                      0.88
## hollister                  0.88
## rapsodia                   0.87
## zara man                   0.87
## adidas                     0.87
## tommy hilfiger             0.87
## lacoste                    0.86
## paula cahen d anvers       0.86
## ralph lauren               0.86
## nike                       0.85
## lucuma                     0.85
## desiderata                 0.84
## de la ostia                0.83
## forever 21                 0.83
## abercrombie                0.83
## jazmin chebar              0.83
## banana republic            0.82
## converse                   0.82
## maria cher                 0.82
## cuesta blanca              0.82
## soho                       0.82
## hym                        0.81
## undefined                  0.81
## divided                    0.81
## akiabara                   0.81
## american eagle             0.81
## vitamina                   0.80
## levis                      0.80
## ona saez                   0.80
## complot                    0.80
## wanama                     0.79
## bensimon                   0.79
## paula cahen danvers        0.79
## 47 street                  0.78
## ay not dead                0.77
## koxis                      0.76
## las pepas                  0.75
## zara                       0.75
## ayres                      0.75
## zara basic                 0.75
##                            0.75
## kosiuko                    0.74
## yagmour                    0.74
## trafaluc                   0.74
## chocolate                  0.73
## materia                    0.72
## tucci                      0.71
## uma                        0.70
## ossira                     0.66
```
#Cluster de Marcas#
![](galpon_files/figure-html/unnamed-chunk-18-1.png) ![](galpon_files/figure-html/unnamed-chunk-18-2.png) ![](galpon_files/figure-html/unnamed-chunk-18-3.png) 


