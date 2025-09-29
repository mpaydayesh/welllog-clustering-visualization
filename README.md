# 🛢️ Well Log Clustering Visualization

An interactive, browser-based educational tool for exploring unsupervised clustering techniques applied to subsurface oil and gas well log data. Built with D3.js for real-time, interactive visualizations.

![Well Log Clustering](https://img.shields.io/badge/Status-Live-brightgreen)
![License](https://img.shields.io/badge/License-MIT-blue)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6-yellow)

## 🌐 Live Demo

**Try it now:** [https://YOUR-USERNAME.github.io/welllog-clustering-visualization/](https://YOUR-USERNAME.github.io/welllog-clustering-visualization/)

*(Replace YOUR-USERNAME with your actual GitHub username)*

## 📊 Features

### Multiple Clustering Algorithms
- **K-Means** - Fast, finds spherical clusters
- **Gaussian Mixture Model (GMM)** - Probabilistic clustering for overlapping formations
- **Hierarchical Clustering** - Complete, Single, and Average linkage methods
- **DBSCAN** - Density-based clustering for irregular shapes
- **Spectral Clustering** - For complex, non-convex formations

### Interactive Visualizations
- **Cross-Plot View** - Compare any two well log parameters with color-coded clusters
- **Depth Profile** - See how clusters distribute along the wellbore
- **Real-time Updates** - Adjust parameters and see immediate results
- **Interactive Tooltips** - Hover over data points for detailed information

### Well Log Parameters
- **AI** - Acoustic Impedance
- **Vp/Vs** - Velocity ratio
- **SW** - Water Saturation
- **phid** - Porosity
- **vcl** - Clay Volume
- **Pressure** - Formation pressure

## 🎯 Use Cases

- **Rock Type Classification** - Identify sandstone, shale, and carbonate formations
- **Reservoir Characterization** - Distinguish pay zones from non-reservoir rock
- **Completion Zone Selection** - Target high-porosity, low-clay intervals
- **Geomechanical Analysis** - Identify zones with similar mechanical properties
- **Educational Tool** - Learn how different clustering algorithms interpret geological data

## 🚀 Getting Started

### Quick Start
1. Visit the [live demo](https://YOUR-USERNAME.github.io/welllog-clustering-visualization/)
2. Select a clustering algorithm from the dropdown
3. Adjust the number of clusters (2-6)
4. Choose which parameters to display on X and Y axes
5. Click "Run Clustering" to see results

### Advanced Usage
- **DBSCAN Parameters**: Adjust epsilon and minimum points for density-based clustering
- **Algorithm Comparison**: Try different algorithms on the same data to compare results
- **Parameter Selection**: Switch between different log combinations to find geological patterns

## 🛠️ Technologies

- **D3.js v7.8.5** - Data visualization library
- **Pure JavaScript** - No frameworks, lightweight and fast
- **HTML5 & CSS3** - Modern, responsive design
- **GitHub Pages** - Free hosting and deployment

## 📖 How It Works

### Data Generation
The tool generates synthetic well log data based on realistic geological formations:
- **Clean Sandstone** - High porosity, low clay content
- **Tight Rock/Carbonate** - High impedance, low porosity
- **Shaly Sandstone** - Higher clay content, moderate properties

### Clustering Process
1. Data normalization across all selected parameters
2. Algorithm-specific clustering computation
3. Visual rendering with color-coded cluster assignments
4. Interactive exploration of results

## 🎓 Educational Value

This tool helps users understand:
- How different clustering algorithms identify patterns in geological data
- The impact of parameter selection on cluster formation
- Relationships between different well log measurements
- Practical applications of unsupervised learning in petroleum engineering

## 📁 Project Structure
welllog-clustering-visualization/
│
├── index.html          # Main application (all-in-one file)
├── README.md           # This file
└── LICENSE             # MIT License
