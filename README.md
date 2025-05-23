# 🎬 IMDb Director-Actor Network Analysis

This project explores the collaboration patterns between directors and actors using IMDb data and visualizes the results using network analysis in **Gephi**.

## 📌 Objective

To analyze whether directors consistently work with a similar set of actors, by building a network graph where:
- **Nodes** represent directors and actors.
- **Edges** represent collaborations between them (i.e., a director casting an actor in a movie).

## 📁 Project Structure

```bash
.
├── Gephi_csv_files/
│   ├── Top_director_actor_edges.csv
│   ├── Top_director_actor_edges_hollywood.csv
│   ├── Top_director_actor_nodes.csv
│   └── Top_director_actor_nodes_hollywood.csv
├── Director_actor_nodes_edges.ipynb
├── README.md
└── requirements.txt
```
## 🌐 Network Visualization with Gephi

### Steps to Visualize in Gephi

1. Open **Gephi** and import `Top_director_actor_nodes_hollywood.csv` and `Top_director_actor_edges_hollywood.csv`.
2. Choose **undirected graph** (or **directed**, if appropriate for your analysis).
3. Apply the **ForceAtlas 2** layout for clustering the graph visually.
4. Use the **"Type"** attribute to color or filter nodes (e.g., Actor vs. Director).
5. Apply label filtering:
   - Show labels only for **Directors** or for **nodes with high degree**.
6. Export the final graph as **SVG/PNG**, or explore it interactively within Gephi.

---

## 💡 Insights

- Certain directors work with a recurring set of actors across multiple films.
- Some actors act as **bridges** across clusters, collaborating with many different directors.

## 🙌 Acknowledgements

- [IMDb Dataset](https://www.imdb.com/interfaces/)
- [Gephi – Open Graph Visualization Platform](https://gephi.org)
