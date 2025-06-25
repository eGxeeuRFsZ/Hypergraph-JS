# Hypergraph-JS

A JavaScript library for visualizing and manipulating hypergraphs in web applications.

**Features:**
•   WebGL-based rendering for high performance.
•   Easy-to-use API for creating and modifying hypergraphs.
•   Support for various graph layouts.

**Installation:**
bash
npm install hypergraph-js

**Usage:**
javascript
import Hypergraph from 'hypergraph-js';

const container = document.getElementById('hypergraph-container');
const hypergraph = new Hypergraph(container);

// Add nodes and hyperedges
hypergraph.addNode('A');
hypergraph.addNode('B');
hypergraph.addHyperedge(['A', 'B']);

// Render the hypergraph
hypergraph.render();
