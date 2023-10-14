# Dogs-vs-Cats
Red para clasificacion entre perros y gatos, a partir de esto poder familiarizarse con DagsHub y Wandb
---

La primera red convolucional que se realizo a partir del repositorio dado [Gatos-y-Perros](https://dagshub.com/jorgevc/Gatos-y-Perros.git) de donde también se tomó la base de datos, esto con el fin de probar la red que se realizo en Colab y se puede ver mejor en Wandb.ia la comparación de las metricas.

<center>
  <h4>Código de la red:</h4>
  <a href="https://github.com/Jeremy-22/Dogs-vs-Cats/blob/main/RedConv2.ipynb" target="_blank">
    <img width="20%" src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
  </a>
</center>
<br>

<center>
  <h4>Comparación de las metricas:</h4>
  <a href="https://wandb.ai/jeryrangmart/Dogs-cats?workspace=user-jeryrangmart" target="_blank">
    <img width="20%" src="https://import.cdn.thinkific.com/cdn-cgi/image/width=384,dpr=2,onerror=redirect/705742%2Fcustom_site_themes%2Fid%2FxVbf2a4QI6LMRQywVIhA_Group%2022406.png" alt="Open In Colab"/>
  </a>
</center>
<br>


En base con la primera red pero con ciertos parametros diferentes, también se implemento el regularizador L1-L2 y se obtuvieron los resultados de relizar 4 pruebas y un experimento, por otro lado se obtuvo una prueba con una metrica accuracy de 0.859 y un val_accuracy de 0.807, la cual nombre como mejor prueba, la cual se puede visualizar en Wandb.ia, y en el experimento se implemento en las dos primeras capas el regularizador L1-L2 y se aumentaron el número de filtros, algo en lo que se pudo notar una mejora es la función de costo (Loss) la cual estuvo con mejor equilibrio con val_loss.

<center>
  <h4>Código de la red:</h4>
  <a href="https://github.com/Jeremy-22/Dogs-vs-Cats/blob/main/RedConv2D.ipynb" target="_blank">
    <img width="20%" src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
  </a>
</center>
<br>

<center>
  <h4>Comparación de las metricas:</h4>
  <a href="https://wandb.ai/jeryrangmart/DogsvsCats?workspace=user-jeryrangmart" target="_blank">
    <img width="20%" src="https://import.cdn.thinkific.com/cdn-cgi/image/width=384,dpr=2,onerror=redirect/705742%2Fcustom_site_themes%2Fid%2FxVbf2a4QI6LMRQywVIhA_Group%2022406.png" alt="Open In Colab"/>
  </a>
</center>
<br>

---

### Atribuciones

- Este repositorio cuenta con una  [GNU License](https://github.com/Jeremy-22/RN/blob/main/LICENSE).
