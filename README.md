# TFG — Una mirada al espacio: Exoplanetas K2 con imputación múltiple PCA y ensamblado

**Autor:** Leo Rodríguez • **Grado:** Estadística Aplicada (UCM)  
**Resumen:** Este repo contiene el código y materiales de mi TFG. Uso imputación múltiple, PCA y modelos (logística, árbol, Random Forest, XGBoost) para predecir `dummy_disposition` en el catálogo K2.

## Estructura
- `quarto/`: fuentes `.qmd` del informe y anexos.
- `code/`: funciones y scripts de preparación y modelado.
- `figures/`: gráficos generados.
- `output/`: resultados ligeros (tablas, métricas).
- `data/raw/`: **no versionado**. Ver instrucciones abajo.
- `docs/`: HTML publicado (GitHub Pages).

## Orden de códigos
1. BBDD_mia_k2
2. estructurar_datos
3. analisis_exploratorio
4. exponiendo_descriptivo
5. analizando_missings2
6. repasando_imputacionMultiple
7. modelos_final_final
## Datos
Los datos provienen de **NASA Exoplanet Archive (K2 planets and candidates)**.  
➡️ Instrucciones en `data/raw/README.md` para descargarlos y preparar `data/proc/`.
