# Colombo-Travel-Route-Optimizer

## Transport Analytics and Image Processing System

---

## Overview

This project applies mathematical modelling, signal processing, and image processing techniques to analyse transport systems and extract meaningful insights for traffic optimisation. It integrates multivariable calculus, time-series analysis, and computer vision to model travel time, evaluate fare structures, analyse passenger demand patterns, and process vehicle number plate images.

---

## Objectives

- Model travel time based on distance and congestion
- Analyse fare structures using integration
- Identify passenger demand patterns using Fourier analysis
- Detect peak travel periods using series approximation
- Process vehicle plate images using frequency-domain techniques
- Demonstrate applications in traffic monitoring and optimisation

---

## Technologies Used

- Python  
- NumPy  
- SymPy  
- Matplotlib  
- OpenCV  
- NumPy FFT  

---

## Project Structure

### 1. Travel Time Modelling
- Modelled bus and taxi travel time using multivariable functions
- Computed gradients using partial differentiation
- Analysed sensitivity to distance and congestion

### 2. Cost Analysis Using Integration
- Derived total fare functions from fare rate models
- Applied definite integration
- Compared cost behaviour of buses and taxis
- Visualised fare vs distance relationships

### 3. Passenger Demand Analysis
- Modelled passenger volume using a truncated series
- Analysed limitations of series approximation and convergence
- Identified peak travel periods using numerical methods
- Visualised time-based passenger trends

### 4. Frequency-Domain Analysis
- Simulated passenger boarding data
- Applied Fast Fourier Transform (FFT)
- Identified dominant frequencies and travel cycles
- Interpreted periodic demand patterns

### 5. Image Processing for Vehicle Recognition
- Converted images to grayscale
- Applied 2D Fourier Transform and visualised magnitude spectrum
- Applied Discrete Cosine Transform (DCT) for feature extraction
- Performed edge detection and contour-based number plate localisation

---

## Key Concepts Applied

- Partial differentiation and gradient analysis  
- Definite integration and accumulation modelling  
- Series truncation and convergence behaviour  
- Fast Fourier Transform and frequency analysis  
- Discrete Cosine Transform and energy compaction  
- Image preprocessing and feature extraction  

---

## Results and Insights

- Bus travel time is influenced independently by distance and congestion, while taxi travel time depends on their combined effect  
- Taxi fares increase faster than bus fares due to higher coefficients, making buses more affordable for longer distances  
- Passenger demand exhibits strong periodic behaviour with identifiable daily and peak-hour cycles  
- Truncated series approximations are limited over large intervals due to dominance of higher-order terms  
- Fourier analysis reveals dominant demand frequencies useful for scheduling  
- DCT enables compact representation of image features for efficient processing  
- Image processing techniques can successfully identify number plate regions  

---

## Applications

- Traffic flow monitoring  
- Route optimisation  
- Peak demand analysis  
- Transport scheduling  
- Automated vehicle recognition systems  
- Smart traffic management  

---

## Author

Developed as part of coursework in Artificial Intelligence and Data Science, focusing on integrating mathematical modelling with data-driven analysis for real-world transport applications.
