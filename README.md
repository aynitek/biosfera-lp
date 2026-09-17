# Biosfera — propuesta de landing page

Maqueta de presentación para **Biosfera — Animales Exóticos**, museo interactivo
de fauna exótica en Av. La Encalada 969, Santiago de Surco, Lima.

Publicación **temporal** para revisión del cliente. No indexada.
El código fuente, la investigación y el sistema de construcción no forman parte
de este repositorio.

Ya no queda ningún dato marcado «por confirmar». El horario está puesto, y la
razón social y el RUC se retiraron del pie a petición de Biosfera, que los va a
cambiar.

**Las fotografías son de referencia y ninguna es de los animales de Biosfera.**
Hay que sustituirlas por fotografías propias antes de cualquier publicación real.
La procedencia, el autor y la licencia de cada una están en el diálogo
«Créditos fotográficos» de la propia página: diecisiete de Wikimedia Commons,
diez de Pexels, siete de iNaturalist y tres de Flickr; una no se pudo atribuir.

De las treinta y ocho, **once no serían publicables en un uso comercial**: tres
son de derechos reservados —la rata esfinge, el escorpión gigante asiático y el
ratón—, siete llevan cláusula «no comercial» y una es la que está sin atribuir.
Son las primeras a sustituir, y todas se resuelven de una vez con fotografía
propia.

## El fondo

La página se dibuja sobre una escena WebGL: un gecko 3D real cuya cámara gobierna
el scroll, con un ancla por sección e interpolación amortiguada entre ellas. No hay
JavaScript en el evento de scroll —el bucle de render lee un objeto mutable— y con
`prefers-reduced-motion` se pinta una pose fija y no se anima nada.

El modelo es **«Spotted Gecko» de Jeff Larson**, CC BY 3.0 vía Poly Pizza,
modificado por AYNI: fundido en una malla, sin texturas, recentrado y reescalado.
Está en los créditos de la página, que es donde lo pide la licencia. Es un gecko
genérico estilizado: **no corresponde a ninguna de las cinco especies de Biosfera**,
así que funciona como ambiente y no debe rotularse con nombre de especie.

Ver `LICENSE`.
