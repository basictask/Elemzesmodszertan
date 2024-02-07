# Budapesti Gazdasági Egyetem
## Üzleti Elemzések Módszertana
Gépi tanulás és mesterséges intelligencia kurzus.

## Feldolgozott témák a kurzus alatt
1. Regresszió: `1_regression`
2. Osztályozás: `2_classification`
3. Regularizáció: `3_regularization`
4. Döntési fák: `4_decision_trees`
5. Együttes tanulás: `5_ensemble`
6. Tartó vektor gépek: `6_svm`
7. Felügyelet nélküli tanulás: `7_unsupervised`
8. Generatív modellezés: `8_generative`
9. Ajánló rendszerek: `9_recommender`
10. Neurális hálózatok: `10_neural`
11. Megerősítéses tanulás: `11_reinforcement`

## Környezet telepítése
Anaconda Prompt segítségével a projekt gyökérmappájában állva a következő paranccsal lehet minden könyvtárat telepíteni: 
```
pip install -r requirements.txt
```

## Mappák struktúrája
A gyökérmappában található scriptek:  
- `merge_pdfs.py`: Konkatenálja az összes pdf-et egy dokumentummá a gyökérmappába.  
- `render_graph.py`: Renderel minden `dot` gráfot az összes mappában.  
- `render_pdf.py`: Renderel minden LaTeX fájlt pdf formátumba.  
    
Minden mappában két almappa található:  
- `code`: Esettanulány, ami megvalósítja a tanult témakört.  
- `doc`: Dokumentáció LaTeX és pdf formátumban.  
	- `images`: Diagramok és képek a dokumentációban. Itt megtalálható egy témának megfelelően elnevezeett Jupyter notebook, ami a képek generálásáért felelős. Az itt található programkód publikus és szabadon felhasználható az órai munka során.  
	- `graphs` (opcionális): Gráfok `dot` formátumban, amit a Graphviz szoftver segítségével lehet lerenderelni.   
