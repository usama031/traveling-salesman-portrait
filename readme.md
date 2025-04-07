# Traveling Salesman 

The **Traveling Salesman Portrait** project is a unique intersection of **optimization algorithms** and **creative data visualization**. It uses the classic **Traveling Salesman Problem (TSP)** to generate portraits from image data by treating each pixel (or set of points) as a city that must be visited exactly once in an optimal tour.

## 🎯 Objective

To generate artistic portraits using solutions to the **Traveling Salesman Problem**, where each portrait is formed by plotting the optimal path through a set of points derived from an image (usually grayscale, thresholded).

---

## 📂 Project Structure

```bash
traveling-salesman-portrait/
├── portraits/              # Output generated portraits (images)
├── images/                 # Input images (black & white or thresholded)
├── tsp_solver.py           # Core TSP solving algorithm
├── point_extractor.py      # Extracts point coordinates from images
├── visualize.py            # Creates the portrait based on TSP path
├── README.md               # Project documentation
└── requirements.txt        # Python dependencies
git clone https://github.com/usama031/traveling-salesman-portrait.git
