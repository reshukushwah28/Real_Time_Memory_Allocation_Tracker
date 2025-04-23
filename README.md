# Real_Time_Memory_Allocation_Tracker
Real-Time Memory Allocation Tracker is an interactive tool that monitors and manages memory allocation dynamically using best-fit and worst-fit strategies. 
It provides real-time visualization of memory usage, fragmentation, and system performance for efficient allocation tracking. Key Features:

Dynamic Allocation: Users request memory; the system assigns optimal blocks using Best-Fit or Worst-Fit strategies.

Smart Deallocation: Freeing memory merges adjacent blocks to minimize fragmentation, updating visualization in real-time.

Live Memory Visualization: A dynamic bar graph displays allocated (red) and free (green) memory, with labeled block IDs.

Fragmentation Insights: Tracks internal (unused space) and external (scattered free blocks) fragmentation for efficiency analysis.

Strategy Comparison: Evaluates Best-Fit vs. Worst-Fit by running allocation cycles and selecting the optimal method.

System Monitoring: Displays real-time CPU & RAM usage, highlighting top memory-consuming processes with psutil.
