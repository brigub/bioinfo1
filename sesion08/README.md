#Sesion 08. BLAST + local

## Software 
- blastp: 2.16.0+
- mafft: 7.526
- seqkit (cargado como "module load seqkit")

## Datos
- /mnt/data/bioinfo1/jmiranda/sesion08/datos
- "proteoma_dlaeve_v1.2.faa" -> 43,905 proteinas de *D.laeve*
- "consultas_wnt.faa" 72 proteinas de referencia (via WNT)
- "mapa_mrna.tsv" (mRNA -> cromosoma -> posicion -> gen -> simbolo

Como no subi datos?, las bases de proteoma, consultas y hits se vuelven a generar

## Archivos
- "top5.sh" : script -> reporta los 5 mejores hits por consulta
- "top5_lgr5.md" : salida de "./top5.sh referencias_lgr5.faa proteoma_dlaeve"
- "lgr_candidatos_.tsv" : 6 candidatos LGR (E-value < 1e-30 y cobertura >= 60%)
- "tabla candidatos.tsv" : cromosoma, posicion y simbolo -> de los candidatos
- "mejores.tsv" : mejor hit (por bitscore) de cada una de las 72 consultas
"familia_lgr.aln.faa" : alineamiento con "mafft --auto" (L-INS-i) de los 6 candidatos + 4 referencias LGR5.

