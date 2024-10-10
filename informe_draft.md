# Abstract

Bla bla bla

## Introduccion

## Teoria

El modelo de Hodgkin & Huxley es un modelo matematico que describe la dinamica de la membrana de una neurona... TODO

Las ecuaciones diferenciales que describen el modelo son:

$$
\begin{align}
\dot{n}&=&\alpha_n(v)(1-n)-\beta_n(v) n\\
\dot{m}&=&\alpha_m(v)(1-m)-\beta_m(v) m\\
\dot{h}&=&\alpha_h(v)(1-h)-\beta_h(v) h \\
\dot{v}&=&c^{-1}(i-\bar{g}_{\mathrm{Na}}m^3h(v-v_{\mathrm{Na}})-\bar{g}_{\mathrm{K}}n^4(v-v_{\mathrm{K}})-g_{l}(v-v_{l}))
\end{align}
$$

Donde los coeficientes $\alpha$ y $\beta$ (dependientes del valor del potencial de membrana) representan las tasas de activacion e inactivacion para cada tipo de compuerta ...

(Explicar cada uno de los terminos de las ecuaciones ???)

(Explicar los valores de los parametros y valores de equilibrio???)

Para este trabajo buscamos analizar la dinamica del modelo de Hodgkin & Huxley en respuesta a diferentes estimulos electricos, simulando diferentes corrientes inyectadas en la neurona. Para ello, implementamos un modelo de integracion numerica de las ecuaciones diferenciales del modelo de Hodgkin & Huxley, y analizamos la respuesta de la neurona a las siguientes corrientes:

1. Estimulo debil y estimulo fuerte
2. Ráfaga de estimulos
3. Período refractario
4. Estimulos espontaneos

## Resultados

### Estimulo debil y estimulo fuerte


## Discusion

## Conclusiones

## Agradecimientos
