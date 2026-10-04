Khulna Route Optimizer & CNG Network 🗺️

An interactive, web-based graphing application designed to visualize optimal travel routes and plan infrastructure networks across key locations in Khulna, Bangladesh.

This tool maps 12 major nodes in the city and applies classical Graph Theory algorithms to solve real-world logistical problems, such as finding the fastest travel routes and planning a cost-effective CNG stand network.

🚀 Features

Interactive Graph Visualization: A physics-based, draggable network map of Khulna's major intersections and locations.

Fastest Route Calculator: Select a start and end destination to instantly calculate and highlight the shortest path.

Infrastructure Network Planner (MST): Calculates the most efficient way to connect all locations without redundant loops—ideal for establishing a network of CNG stands.

Algorithm Selector: Choose between Kruskal's or Prim's algorithm for the Minimum Spanning Tree (MST) generation.

Step-by-Step Animation: Watch the MST algorithms build the network live, node by node, with real-time updates on connections and distance costs.

No Server Required: Runs entirely in your browser using pure frontend technologies.

🧠 Algorithms Used

Dijkstra's Algorithm:
Used for the "Fastest Route" feature. It computes the shortest path from a starting node to a target node by iteratively exploring the most promising outward paths.

Kruskal's Algorithm:
Used for establishing the "CNG Network". It sorts all available roads by distance and connects them from shortest to longest, ensuring no cycles (loops) are formed using a Union-Find data structure.

Prim's Algorithm:
An alternative for the "CNG Network". It starts at an arbitrary location (Rupsha Ferry Ghat) and continually adds the shortest possible road that connects a new, unvisited location to the growing network.

🛠️ Technologies

HTML5 / JavaScript (Vanilla) - Core logic and structure.

Tailwind CSS - For rapid UI styling and responsive layout (loaded via CDN).

Vis-Network (vis.js) - For rendering the interactive physics-based network graph (loaded via CDN).

💻 How to Run

Because this project is built as a single, standalone HTML file, there is no complex setup, build process, or server required.

Download or save the khulna_network.html file to your computer.

Double-click the file to open it in any modern web browser (Chrome, Firefox, Edge, Safari).

Ensure you have an active internet connection so the browser can load the Tailwind CSS and Vis-Network libraries.

📖 Usage Instructions

Navigating the Map: Click and drag nodes to rearrange them. Use your mouse wheel or trackpad to zoom in and out.

Finding a Route: In the left panel under "Fastest Route", select your starting location and destination, then click Find Shortest Path.

Establishing a Network: Under "CNG Network", select your preferred algorithm (Kruskal or Prim) from the dropdown and click Establish Network. Watch the animation unfold.

Resetting: Click the Reset Graph button at any time to clear highlights and return the map to its default state.

📍 Mapped Locations

Rupsha Ferry Ghat

Khulna Court

South Central More

Dakbangla More

Royal More

Moylapota More

Gollamari More

Shibbari More

Sonadanga

Boyra Bazar

Daulatpur

Shiromoni
