# Webs de la hostelería andaluza, 2026: datos por provincia

Resumen por provincia de la revisión de 1.537 webs de bares, restaurantes y cafeterías de Andalucía, hecha por Facilo el 13 de noviembre de 2026. Mide si la web funciona, si se ve bien en el móvil, si muestra la carta con precios en texto, si tiene un teléfono que se pueda pulsar, reservas y versión en inglés.

Estudio completo, método y margen de error: https://webs.facilo.es/estudios/webs-hosteleria-andalucia-2026/

Origen de los datos: OpenStreetMap, © colaboradores de OpenStreetMap. Este resumen se publica con la licencia ODbL. Solo incluye cifras agregadas: no hay ningún dato de negocios concretos.

## Archivo

[`datos/datos-por-provincia.csv`](datos/datos-por-provincia.csv): una fila para toda Andalucía y una por provincia. Los porcentajes llevan un decimal.

| Columna | Qué es | Sobre cuántas webs |
|---|---|---|
| `provincia` | Andalucía o la provincia | |
| `medidas` | Webs que pudimos medir | |
| `pct_no_funcionan` | % que ya no funciona: dominio que no existe, error, no carga o página aparcada | `medidas` |
| `funcionan` | Webs que funcionan | |
| `pct_sin_candado` | % sin conexión segura (HTTPS) | `funcionan` |
| `pct_sin_movil` | % no adaptada al móvil | `funcionan` |
| `con_texto` | Webs que funcionan con texto legible en la página de inicio | |
| `pct_sin_aviso_legal` | % sin enlace a aviso legal | `con_texto` |
| `pct_sin_privacidad` | % sin enlace a política de privacidad | `con_texto` |
| `pct_sin_cookies` | % sin enlace a política de cookies | `con_texto` |
| `pct_precios_texto` | % que muestra la carta con precios en texto | `con_texto` |
| `pct_sin_tel` | % sin un teléfono que se pueda pulsar | `con_texto` |
| `pct_sin_reserva_enlace` | % sin forma de reservar en la web | `con_texto` |
| `pct_sin_ingles` | % sin versión en inglés | `con_texto` |
| `pct_algun_fallo_basico` | % con al menos un fallo básico: no funciona, sin candado o no adaptada al móvil | `medidas` |

Las muestras provinciales son pequeñas y su margen de error es amplio: el dato fiable es el de Andalucía, no una clasificación entre provincias.

## Cómo citar

Facilo (2026). *Webs de la hostelería andaluza, 2026: datos por provincia* [Conjunto de datos]. https://webs.facilo.es/estudios/webs-hosteleria-andalucia-2026/

En un texto basta con «Estudio de Facilo sobre las webs de la hostelería andaluza, noviembre de 2026», con un enlace al [estudio completo](https://webs.facilo.es/estudios/webs-hosteleria-andalucia-2026/). Para otros formatos (APA, BibTeX), usa el botón «Cite this repository» de esta página, que GitHub genera a partir de [`CITATION.cff`](CITATION.cff).

## Licencia

Open Database License (ODbL) 1.0, en [`LICENSE`](LICENSE). Si reutilizas los datos, cita a Facilo y a los colaboradores de OpenStreetMap.
