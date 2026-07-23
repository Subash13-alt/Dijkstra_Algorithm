# 🛣️ Dijkstra's Shortest Path Visualizer

An interactive web application built with **Python** and **Streamlit** that demonstrates **Dijkstra's Shortest Path Algorithm** using a **Min-Heap (Priority Queue)**. Users can select a source vertex and view the shortest distance and path to every other vertex in a weighted graph.

---

## 🚀 Features

- Interactive Streamlit web interface
- Select any source vertex
- Computes shortest paths using Dijkstra's Algorithm
- Uses a Min-Heap (Priority Queue) for efficiency
- Displays:
  - Shortest distance
  - Complete path to each vertex
- Beginner-friendly implementation

---

## 🛠️ Technologies Used

- Python 3
- Streamlit
- Heapq (Priority Queue)

---

## 📂 Project Structure

```
Dijkstra-App/
│── app.py
│── requirements.txt
│── README.md
```

---

## 📊 Sample Graph

```python
graph = {
    0: [(1, 4), (2, 1)],
    1: [(3, 1)],
    2: [(1, 2), (3, 5)],
    3: [(4, 3)],
    4: [(5, 2)],
    5: []
}
```

---

## ⚙️ Installation

Clone the repository

```bash
git clone https://github.com/your-username/dijkstra-shortest-path-visualizer.git
```

Move into the project folder

```bash
cd dijkstra-shortest-path-visualizer
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run the application

```bash
streamlit run app.py
```

---

## 📖 How It Works

1. Select the source vertex.
2. Click **Find Shortest Paths**.
3. The application computes the shortest distance from the source to every vertex.
4. Results are displayed in a table showing:
   - Vertex
   - Shortest Distance
   - Shortest Path

---

## ⏱️ Time Complexity

Using a **Min-Heap (Priority Queue):**

- **Time Complexity:** `O((V + E) log V)`
- **Space Complexity:** `O(V)`

Where:

- **V** = Number of vertices
- **E** = Number of edges

---

## 🌐 Live Demo

Deploy on **Streamlit Community Cloud** and add your link here:

```
https://your-app-name.streamlit.app
```

---

## 📚 Learning Outcomes

This project helps in understanding:

- Graph Data Structure
- Greedy Algorithms
- Dijkstra's Algorithm
- Priority Queue (Heap)
- Path Reconstruction
- Streamlit Web Development

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository.
2. Create a new feature branch.
3. Commit your changes.
4. Push the branch.
5. Open a Pull Request.

---

## 📄 License

This project is licensed under the MIT License.

