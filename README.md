# Around the world in 80 days

Starting from the data contained in `./data/worldcities_ascii.csv` find for each city the 3 cities closest to it.

Compute how long it takes to move from a city to a neighbor according to these rules:

- 2 hours to the nearest city
- 4 hours to the second closest city
- 8 hours to the third closest city

In addition, the trip requires:

- 2 additional hours if the destination city is in another country than the departure city
- 2 additional hours if the destination city has more than 200,000 inhabitants

## Questions
1. Starting from London and always traveling east, is it possible to travel around the world returning to London in 80 days? How long does the shortest path take?

2. If it is not possible to travel around the world starting from London, from which other cities is it possible to travel around the world?

3. Assuming that from each city you can only travel to the 3 closest cities to the east, how does the outcome of the previous questions change?

---

## Installation 

All the project's dependencies are listed in the `requirements.txt` file.

From the following directory run the command:

```
pip install -r requirements.txt
```

If you're developing with **Jupyter Notebook** run the command:

```
jupyter nbextension enable --py --sys-prefix --overwrite ipyleaflet
```

f you're developing with **JupyterLab** and you have JupyterLab <=2, you will also need to install the JupyterLab extension with the command:

```
jupyter labextension install @jupyter-widgets/jupyterlab-manager jupyter-leaflet
```

## Demo



> Tip: Use the map in fullscreen for a better experience
