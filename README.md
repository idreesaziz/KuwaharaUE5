# KuwaharaUE5
Unreal Engine 5 Kuwahara Filter Implementation
This repository contains an implementation of the Kuwahara filter for Unreal Engine 5. The Kuwahara filter is an image processing technique that produces a "painterly" effect by reducing noise and preserving edges.

## Getting Started
### 1. Clone the Repository

### 2. Migrate the Materials to your project

### 3. Adjust Radius (Optional)
In the Content Browser, navigate to the imported Materials folder.
Open the Material Instances folder.
Choose the desired Material Instance based on your preference:
> **MAT_Kuwahara_Circular_Kernel_Inst:** Applies the Kuwahara filter with a circular kernel.
> **MAT_Kuwahara_Square_Kernel_Inst:** Applies the Kuwahara filter with a square kernel.
Modify the "Radius" parameter in the Material Instance to control the filter's strength.

### 4. Apply the Filter
Apply the chosen Material Instance onto your Post Process Volume under the Rendering tab.
