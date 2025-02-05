<div align="center">
  <h1>Wirebond Detection and Analysis</h1>
  <p>This guide will walk you through the steps to set up and run wirebond detection and analysis.</p>
</div>

---

### Step 1: Set Up the Environment
Create and activate the Conda environment using the provided `environment.yml` file.

<div align="center">
  <pre><code>conda env create -f environment.yml
conda activate Wirebond
</code></pre>
</div>

### Step 2: Run Wirebond Detection
Execute the wirebond detection script to process the data.


<div align="center">
<pre><code>base_dir = os.path.join('/home/hgc-qc-web/Wirebond/', 'Modules')
</code></pre>
</div>

<div align="center">
  <pre><code>python3 wirebonddetect.py
</code></pre>
</div>

### Step 3: Analyze the Results
After running the detection script, analyze the results using the analysis script.

<div align="center">
  <pre><code>python3 analyze_results.py
</code></pre>
</div>

---
