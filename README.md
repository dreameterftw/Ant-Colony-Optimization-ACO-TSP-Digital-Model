# Ant Colony Optimization (ACO) – TSP Digital Model

This repository hosts a single-page, interactive digital model demonstrating the **Ant Colony Optimization (ACO)** algorithm applied to the **Travelling Salesman Problem (TSP)**.

Repository: https://github.com/dreameterftw/Ant-Colony-Optimization-ACO-TSP-Digital-Model

The model was created as a college Biology course project on **Biomimicry**, as a post-presentation artifact to show practical implementation and application of a bio-inspired algorithm beyond theoretical explanation.

---

## Project Objective

The objective of this project is to demonstrate that Ant Colony Optimization:
- Can be implemented programmatically from first principles
- Can solve a classic combinatorial optimization problem (TSP)
- Exhibits biologically inspired behaviors such as decentralized decision-making, stigmergy, exploration, and convergence

This model serves as proof of implementation, not just conceptual understanding.

---

## What the Model Does

- Displays cities as draggable nodes on a canvas
- Allows users to generate random city layouts
- Solves the Traveling Salesman Problem using Ant Colony Optimization
- Visualizes the best tour found and its total distance
- Allows real-time tuning of ACO parameters
- Supports reproducible runs using a fixed random seed

The model is entirely client-side and runs instantly in any modern browser.

---

## ACO Parameters Explained

- **Ants**: Number of artificial ants constructing tours per iteration  
- **Iterations**: Total number of learning cycles performed  
- **α (Alpha)**: Weight of pheromone influence (exploitation of learned paths)  
- **β (Beta)**: Weight of distance heuristic (preference for shorter edges)  
- **ρ (Rho)**: Pheromone evaporation rate (memory decay)  
- **Q**: Pheromone deposit factor based on tour quality  
- **Elitism**: Extra reinforcement applied to the best-so-far tour  
- **Seed**: Controls randomness to allow reproducible experiments  

By adjusting these parameters, users can observe changes in convergence speed, solution quality, and exploration behavior.

---

## How to Use the Model

1. Open the live webpage (see link below)
2. Click **Random 10** or add cities manually by clicking on the canvas
3. Optionally drag cities to change the problem layout
4. Set ACO parameters using the sliders
5. Click **Solve (Animate)** or **Solve (Fast)** to run the algorithm
6. Observe convergence and best distance updates in real time

---

## GitHub Pages Deployment

This project is a static client-side site, so it can be hosted free on GitHub Pages.

1. Create a new GitHub repository and push this project to it.
2. In the repository settings, open **Pages**.
3. Select the **main** branch and **root** as the folder.
4. Save the settings and use the provided URL to access your live site.

If you want, you can also host this static project on Netlify, Cloudflare Pages, or Render.

---

## Technology Stack

- HTML5
- CSS3 (embedded)
- Vanilla JavaScript
- HTML Canvas API

No external libraries or frameworks are used.

---

## Educational Context

This project is part of a biomimicry-based study connecting:
- Biological ant foraging behavior
- Swarm intelligence principles
- Engineering optimization techniques
- Applications in cybersecurity and antivirus optimization

---

## License

This project is intended for educational and academic demonstration purposes.
