<h1>
  <b>Comprobación del diseño de una tubería</b>
</h1>

<h2>
  <b>Descripción:</b>
  <i>App para calcular el gasto de una tubería.</i>
</h2>

<img src="/src_appCDT/esquema0.png">

<h2>
  <i>Diagráma de flujo.</i>
</h2>

<img src="/src_appCDT/DDF.png">

<h3>
  <i>Datos de entrada:</i>
  <ul>
    <li>$H$: Altura del nivel de la superficie del tanque con respecto al datum, en metros.</li>
    <li>$z_{2}$: Altura del punto 2 con respecto al datum, en metros.</li>
    <li>$L$: Longitud de la tubería, en metros.</li>
    <li>$d$: Diámetro interior de la tubería, en metros.</li>
    <li>$k_{s}$: Rugosidad de la tubería, en metros.</li>
    <li>$k_{m}$: Coeficiente de pérdidas menores, adimencional.</li>
    <li>$v$: Viscosidad dinámica del agua.</li>
  </ul>
  <i>Datos de salida:</i>
  <ul>
    <li>$A$: Area de la sección transversal de la tubería, en m2.</li>
    <li>$V$: Velocidad del fluido, en m/s.</li>
    <li>$Q$: Gasto de la tubería, en L/s.</li>
    <li>$R_{e}$: Número de reynolds, adimencional.</li>
    <li>$f$: Factor de fricción, adimencional.</li>
    <li>$h_{f}$: Pérdida por fricción, en metros.</li>
    <li>$h_{m}$: Pérdidas por accesorios, en metros.</li>
    <li>$J$:  Pérdida unitaria, en m/m.</li>
   </ul>
</h3>
  
<h2>
  <i>Diseño de la App.</i>
</h2>

<img src="/src_appCDT/App.png">

<h3>
  <p>
    En caso de que el usuario no haya capturado algún dato (en este caso suponemos que ha olvidado capturar la Longitud) se desplega una alarma indicando el dato
    faltante:
  </p>
</h3>

<img src="/src_appCDT/App2.png" width=400>

<h3>
  <p>
    Si el problema no converge, se muestra la siguiente salida:
  </p>
</h3>
  
  <img src="/src_appCDT/App3error.png" width=300>

## _Tecnologías usadas:_
![Kotlin](https://img.shields.io/badge/Kotlin-0095D5?&style=for-the-badge&logo=kotlin&logoColor=white)
![Android_Studio](https://img.shields.io/badge/Android_Studio-3DDC84?style=for-the-badge&logo=android-studio&logoColor=white)
![Canva](https://img.shields.io/badge/Canva-%2300C4CC.svg?&style=for-the-badge&logo=Canva&logoColor=white)
  
<h3>
  <i>Puedes descargar la app dando click en la imagen:</i>
</h3>

<a href="https://drive.google.com/file/d/1CuPBBlZAnMhgA1tXEcK87w22ixgCVxI-/view?usp=sharing">
          <img src="/src_appCDT/icono_fondo.png" width=200>
</a>
