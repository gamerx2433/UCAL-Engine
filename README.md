# ⚡ UCAL Engine — Adaptive CPU Acceleration Layer

>

---

## 🧠 What is UCAL?

UCAL (Universal Compute Acceleration Layer) is an intelligent execution engine that:

* 🔍 Detects workload type (CPU-bound, moderate, light)
* ⚙️ Automatically selects optimal execution strategy
* 🚀 Improves performance without manual tuning
* 📊 Provides real-time benchmarking & visualization

---

## ✨ Features

* ⚡ Automatic mode switching:

  * Multiprocessing (CPU-heavy tasks)
  * Multithreading (moderate workloads)
  * Sequential (light tasks)
* 📈 Performance comparison (Baseline vs UCAL)
* 🧠 Smart workload detection
* 📊 Interactive UI using Streamlit
* 💻 Real-time system metrics (CPU, RAM)

---

## 🖥️ Demo Preview

* Select workload type
* Adjust data size
* Run UCAL engine
* View:

  * Execution time
  * Speedup
  * Optimization mode used

---

## 🏗️ Project Structure

```
UACL-project/
│
├── app.py              # Main Streamlit app
├── run_app.py          # Launcher script (auto-starts app)
├── requirements.txt    # Dependencies
└── README.md
```

---

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/your-username/ucal-engine.git
cd ucal-engine
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ Running the Project

### Option 1: Direct Streamlit

```bash
streamlit run app.py
```

### Option 2: One-click launcher

```bash
python run_app.py
```

---

## 🧪 Workloads Included

| Workload Type     | Description                    |
| ----------------- | ------------------------------ |
| Heavy Computation | CPU-intensive mathematical ops |
| Data Processing   | Moderate compute workload      |
| File Processing   | Lightweight string operations  |

---

## ⚡ How UCAL Works

1. Samples workload performance
2. Classifies task:

   * CPU-BOUND
   * MODERATE
   * LIGHT
3. Chooses execution model:

   * ProcessPoolExecutor
   * ThreadPoolExecutor
   * Sequential execution
4. Executes and compares performance

---

## 📊 Example Output

* Baseline: 12.4s
* UCAL: 4.8s
* Speedup: **2.6x 🚀**

---

## 🔥 Why This Matters

Most applications:

* Use fixed execution strategies ❌
* Require manual tuning ❌

UCAL:

* Adapts dynamically ✅
* Maximizes CPU utilization ✅
* Improves performance automatically ✅

---

## 🚧 Future Improvements

* 🌐 Distributed execution (multi-machine)
* 🧠 ML-based workload prediction
* 📦 Docker support
* ☁️ Cloud auto-scaling

---

## 👨‍💻 Author

Siddhant (IT Engineering)

---

## ⭐ Give a Star

If you like this project, consider starring ⭐ the repo!
