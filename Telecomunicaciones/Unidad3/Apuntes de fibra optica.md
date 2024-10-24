
1. **Estructura de las fibras ópticas**:
    
    - Son guías de onda dieléctricas circulares que transportan energía óptica e información.
    - Tienen un núcleo central rodeado por un revestimiento con un índice de refracción ligeramente inferior (≈ 1%).
    - Están hechas de sílice con dopantes como GeO2.
    - Una capa protectora de material de amortiguación (como el acrilato) reduce la diafonía y la microflexión.
2. **Protección y cables**:
    
    - Las fibras se incorporan en cables para mayor protección ambiental.
    - Los cables tienen una cubierta de polietileno y un miembro de resistencia (hebras de acero o Kevlar).
3. **Modos de fibra**:
    
    - La luz se limita al núcleo si se cumple la condición de reflectancia interna total.
    - La geometría y composición de la fibra determinan los modos de fibra que pueden propagarse.
4. **Clasificación de modos**:
    
    - **Modos de radiación**: Transportan energía fuera del núcleo y se disipan rápidamente.
    - **Modos guiados**: Están confinados al núcleo y propagan energía e información a lo largo de la fibra.
5. **Propagación de modos**:
    
    - Si el núcleo es grande, puede admitir muchos modos guiados simultáneos.
    - Cada modo guiado tiene su propia velocidad y puede descomponerse en componentes polarizados linealmente.
    - La distribución de campo dentro de la fibra es una combinación de los modos.
6. **Ancho de banda y dispersión**:
    
    - El ancho de banda de una fibra óptica determina la velocidad de datos.
    - La dispersión es el mecanismo que limita el ancho de banda, causando que los pulsos ópticos se extiendan y los símbolos se vuelvan indistinguibles.
7. **Tipos de dispersión**:
    
    - **Dispersión intermodal**: Ocurre entre diferentes modos en una fibra multimodo, ya que cada modo tiene una velocidad de grupo diferente. Esto limita el ancho de banda y la distancia de transmisión.
    - **Dispersión intramodal**: También conocida como dispersión de material, afecta tanto a fibras monomodo como multimodo. Incluye:
        - **Dispersión cromática**: Diferentes longitudes de onda viajan a diferentes velocidades debido a variaciones en el índice de refracción.
        - **Dispersión en modo de polarización (PMD)**: Diferentes modos de polarización ortogonal viajan a diferentes velocidades debido a imperfecciones en la fibra y tensiones mecánicas.
8. **Atenuación**:
    
    - La potencia lumínica decae exponencialmente con la longitud de la fibra debido a pérdidas de absorción y dispersión.
    - La atenuación es crucial para determinar el costo de los sistemas de telecomunicaciones, ya que afecta el espaciamiento de los repetidores.
    - Las pérdidas de absorción se deben a impurezas como los iones hidroxilo y las colas de las bandas de absorción en el infrarrojo lejano y ultravioleta.
    - La dispersión de Rayleigh y las irregularidades en el diámetro y la geometría del núcleo también contribuyen a la atenuación.
9. **Apertura numérica (NA)**:
    
    - La NA se define como el seno del ángulo máximo que permite la reflectancia interna total en el núcleo de la fibra.
    - Un índice de refracción del núcleo más alto respecto al revestimiento implica una NA mayor.
    - Una mayor NA puede aumentar la pérdida de dispersión debido a mayores concentraciones de dopante.
    - La NA mide la capacidad de recolección de luz de una fibra y facilita el acoplamiento de luz en la fibra.
10. **Número V**:
    
    - El número V es el parámetro de frecuencia normalizada de una fibra.
    - Se utiliza para expresar varios parámetros de la fibra, como el número de modos y las condiciones de corte del modo.
    - Matemáticamente, ( V = \frac{2 \pi \cdot NA \cdot a}{\lambda} ), donde “a” es el radio del núcleo y “λ” la longitud de onda.
    - Una fibra multimodo de índice escalonado se convierte en monomodo cuando ( V < 2.405 ).
11. **Decapado de fibra**:
    
    - La cubierta exterior de los cables de fibra se puede quitar con herramientas específicas.
    - El recubrimiento de fibra debe eliminarse con cuidado para evitar daños, ya que los defectos y rasguños pueden causar fallas.
12. **Terminación de fibra**:
    
    - La calidad de la superficie final afecta las pérdidas en conectores y empalmes.
    - Las terminaciones de calidad se logran mediante pulido o el uso de cuchillas de fibra.
    - Los conectores populares incluyen:
        - **SMA**: Utilizado en aplicaciones de alta potencia con fibras multimodo de núcleo grande.
        - **ST**: Común en aplicaciones LAN y de campo, con férula cerámica de alta precisión.
        - **FC**: Preferido para fibras monomodo en instrumentos y enlaces de alta velocidad, con férula cerámica y llave antirrotación.
13. **Preparación de la cara final del conector**:
    
    - **Retrorreflexión**: Es la relación entre la luz que se propaga hacia adelante y la luz reflejada hacia la fuente. Minimizarla es crucial en enlaces de alta velocidad.
    - **Pulido plano**: Resulta en una retrorreflexión de aproximadamente -16 dB.
    - **Pulido de PC**: Superficie ligeramente curvada, eliminando la interfaz de fibra a aire, con reflexiones inversas de -30 a -40 dB.
    - **Pulido SPC y UPC**: Mejora la calidad de la superficie, con reflexiones inversas de -40 a -55 dB y < -55 dB, respectivamente.
    - **Pulido APC**: Agrega un ángulo de 8 grados, logrando retrorevoluciones de < -60 dB.
    - **Corte de fibra**: Método rápido para obtener un extremo plano, utilizando herramientas específicas para evitar daños.
14. **Acoplamiento de la luz en las fibras**:
    
    - **Posicionamiento preciso**: Es esencial para centrar el núcleo en el rayo láser enfocado.
    - **Fibras multimodo**: Los posicionadores de fibra óptica logran buena eficiencia de acoplamiento.
    - **Fibras monomodo**: Requieren acopladores con resolución submicrónica para máxima eficiencia.
    - **Características del haz enfocado**: Deben coincidir con los parámetros de la fibra.
        - **Punto enfocado**: Comparable al tamaño del núcleo.
        - **Ángulo del cono incidente**: No debe exceder el arcoseno del NA de la fibra.
    - **Distribución del campo incidente**: Debe coincidir con el modo de fibra para maximizar el acoplamiento en fibras monomodo.
15. **Codificación y filtrado de modos**:
    
    - **Codificación de modos**: Técnica que distribuye la potencia óptica entre todos los modos guiados de una fibra multimodo.
    - **Filtrado de modos**: Simula los efectos de longitudes kilométricas de fibra, atenuando los modos de orden superior.
    - **Técnicas de aleatorización**:
        - Empalmar fibra de índice graduado entre fibras de índice escalonado.
        - Envolver la fibra alrededor de un mandril para eliminar modos de orden superior.
        - Introducir microflexión para acoplar rápidamente todos los modos y atenuar los modos de orden superior.
16. **Eliminación del modo de revestimiento**:
    
    - La luz en el revestimiento puede interferir con las mediciones.
    - Se puede eliminar quitando el recubrimiento de la fibra y sumergiéndola en un fluido que coincida con el índice, como la glicerina.
17. **Parámetros ópticos comunes**:

- **Configuración de puertos**: Número de puertos de entrada y salida.
- **Relación de acoplamiento**: Potencia en un puerto de salida respecto a la potencia lanzada, expresada en dB.
- **Aislamiento**: Potencia en la banda de longitud de onda transmitida respecto a la extinguida, expresada en dB.
- **Directividad**: Potencia devuelta a otro puerto de entrada respecto a la potencia lanzada, expresada en dB.
- **Ancho de banda**: Rango de longitudes de onda de funcionamiento.
- **Exceso de pérdida**: Potencia total en todos los puertos de salida respecto a la potencia lanzada, expresada en dB.
- **Uniformidad**: Diferencia entre las pérdidas de inserción máximas y mínimas.
