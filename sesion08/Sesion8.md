------------------------------------------------------------------------

editor_options: markdown: wrap: 72 ---

# Sesión08

Brisa Gutierrez 2026-10-09

### 2. Tabla de salida de `./top5.sh referencias_lgr5.faa proteoma_dlaeve` en Markdown

| qseqid | sseqid | pident | length | evalue | bitscore | qcovs |
|----|----|----|----|----|----|----|
| LGR5\|human\|NP_003658.1 | dlaeveM00000441839 | 33.908 | 870 | 1.11e-143 | 466 | 89 |
| LGR5\|human\|NP_003658.1 | dlaeveM00000727719 | 31.597 | 883 | 9.29e-138 | 434 | 90 |
| LGR5\|human\|NP_003658.1 | dlaeveM00000308285 | 28.094 | 299 | 2.04e-39 | 158 | 33 |
| LGR5\|human\|NP_003658.1 | dlaeveM00000612275 | 29.167 | 432 | 7.98e-33 | 137 | 46 |
| LGR5\|human\|NP_003658.1 | dlaeveM00000132191 | 25.440 | 511 | 2.03e-29 | 126 | 83 |
| LGR5\|mollusc\|Bradybaena_similaris\|BFZ05148.1 | dlaeveM00000727719 | 83.243 | 925 | 0.0 | 1621 | 67 |
| LGR5\|mollusc\|Bradybaena_similaris\|BFZ05148.1 | dlaeveM00000441839 | 56.643 | 1400 | 0.0 | 1444 | 99 |
| LGR5\|mollusc\|Bradybaena_similaris\|BFZ05148.1 | dlaeveM00000308285 | 32.873 | 724 | 5.18e-100 | 346 | 46 |
| LGR5\|mollusc\|Bradybaena_similaris\|BFZ05148.1 | dlaeveM00000132191 | 28.877 | 561 | 7.55e-57 | 216 | 61 |
| LGR5\|mollusc\|Bradybaena_similaris\|BFZ05148.1 | dlaeveM00000351276 | 37.097 | 310 | 1.69e-45 | 178 | 55 |
| LGR5\|mollusc\|Magallana_gigas\|NP_001292277.1 | dlaeveM00000727719 | 50.166 | 903 | 0.0 | 856 | 81 |
| LGR5\|mollusc\|Magallana_gigas\|NP_001292277.1 | dlaeveM00000441839 | 48.394 | 903 | 0.0 | 827 | 81 |
| LGR5\|mollusc\|Magallana_gigas\|NP_001292277.1 | dlaeveM00000308285 | 46.757 | 370 | 1.72e-95 | 328 | 56 |
| LGR5\|mollusc\|Magallana_gigas\|NP_001292277.1 | dlaeveM00000351276 | 29.714 | 525 | 5.53e-41 | 163 | 78 |
| LGR5\|mollusc\|Magallana_gigas\|NP_001292277.1 | dlaeveM00000132191 | 28.269 | 520 | 1.85e-38 | 156 | 74 |
| LGR5\|mollusc\|Pomacea_canaliculata\|XP_025085505.1 | dlaeveM00000727719 | 58.758 | 902 | 0.0 | 1065 | 79 |
| LGR5\|mollusc\|Pomacea_canaliculata\|XP_025085505.1 | dlaeveM00000441839 | 57.556 | 900 | 0.0 | 1031 | 79 |
| LGR5\|mollusc\|Pomacea_canaliculata\|XP_025085505.1 | dlaeveM00000308285 | 32.228 | 754 | 7.16e-106 | 358 | 66 |
| LGR5\|mollusc\|Pomacea_canaliculata\|XP_025085505.1 | dlaeveM00000351276 | 30.989 | 526 | 1.23e-52 | 200 | 76 |
| LGR5\|mollusc\|Pomacea_canaliculata\|XP_025085505.1 | dlaeveM00000132191 | 28.571 | 539 | 4.82e-50 | 193 | 77 |

### 3. Tabla del ejercicio 8 con cromosoma, posición y símbolo de cada candidato.

| Gen                | Cromosoma | Posición | Símbolo |
|--------------------|-----------|----------|---------|
| dlaeveM00000132191 | chr2      | 15.7 Mb  | GPRGPH  |
| dlaeveM00000134217 | chr2      | 17.7 Mb  | GPRGPH  |
| dlaeveM00000308285 | chr4      | 45.9 Mb  | TSHR    |
| dlaeveM00000351276 | chr5      | 18.7 Mb  | GPRGPH  |
| dlaeveM00000441839 | chr6      | 30.9 Mb  | LGR4    |
| dlaeveM00000727719 | chr10     | 23.7 Mb  | LGR4    |

### 4.1 ¿cuántos receptores LGR completos tiene la babosa y en qué cromosomas?

![](Downloads/tabla1.png)

\- 239 genes se parecem a LGR5 (censo crudo). -12 pasan E-value \< 1e-30 -6 pasan cobertura \> 60%: (132191, 134217, 308285, 351276, 441839, 727719)

- Num. de receptores de LGR y en qué cromosomas están:

  (apoyo con la tabla del ejercicio 8.

  dlaeveM00000441839 chr6 30.9 Mb LGR4 dlaeveM00000727719 chr10 23.7 Mb LGR4

### 4.2 ¿por qué el gen dlaeveM00000909458 no es uno de ellos a pesar de tener E-values de 10⁻¹⁴ contra LGR5?

![](Downloads/tabla2.png)

- Cobertura (de 18% a 43%) → ninguna llega a 60%.

- LGR5 humano → solo aparece 2 veces. Solo comparte un pedazo (LRR) y no la proteina completa con las 7 hélices transmembranales.

- E-value (de 1.04e-5 a 2.99e-08) → ninguno llega a 1e-30 (filtro de ejercicio 7)

- Identidad (de 25.4% a 30.7%) → baja
