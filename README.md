# 🚀 Finviz Elite Refresh Overhaul

A custom Tampermonkey script designed specifically for **Finviz Elite** users to solve the biggest pain point of active screening: **slow refresh speeds**. This script injects significantly faster, custom refresh buttons directly into the screener interface.

## 💡 The Problem Solved

Finviz Elite's default automatic refresh minimum is **10 seconds**. For day traders, scalpers, and active market monitors, this latency is unacceptable and can cause missed opportunities.

This script completely bypasses the default Finviz mechanism and implements a custom, highly reliable refresh loop, offering speeds up to **20 times faster** than the default setting.

## ✨ Key Features & Speed Upgrade

This script replaces the default refresh options with a robust set of custom controls:

| New Refresh Speed | Interval (Milliseconds) | Use Case |
| :--- | :--- | :--- |
| **0.5s (500ms)** | 500 | **ULTRA-FAST:** Essential for scalping, catching immediate volume spikes, or monitoring critical real-time criteria. |
| **1s (1000ms)** | 1000 | **FAST:** Excellent for general active day trading and monitoring multiple setups quickly. |
| **5s (5000ms)** | 5000 | **IMPROVED STANDARD:** Faster and more reliable than the original 10s minimum. |
| **10s** | 10000 | (Original option) |
| **1min** | 60000 | (Original option) |
| **off** | N/A | Stop automatic refreshing. |

### Advanced Functionality

* **Persistence:** The script saves your last selected refresh interval to your browser's local storage. If you navigate to a different Finviz page or reload the screener, it automatically reinstates your preferred fast refresh rate.
* **Reliable Refreshing:** The custom logic ensures the refresh interval is maintained regardless of whether the screener table is populated with results or currently empty.
* **Integrated Support Link:** A small, unobtrusive `☕ Support My Work` button is added to the bottom-right corner. Clicking it brings up a small, non-intrusive modal.
    * **Hide Forever Option:** The modal includes a "Hide forever" button that removes the support link permanently via local storage for users who prefer a clean interface.

## 🛠️ Installation Guide (Requires Tampermonkey)

1.  Ensure you have a modern userscript manager installed (e.g., **Tampermonkey** for Chrome/Firefox, or **Violentmonkey**).
2.  Click the direct installation link below:

4.  [download](https://github.com/Anthony-Creates/Finviz-Elite-Refresh-Overhaul/raw/refs/heads/main/Finviz%20Elite%20Refresh%20Overhaul.user.js)

5.  Tampermonkey will open and prompt you to install the script. Click **"Install."**
6.  Navigate to or reload your Finviz Elite Screener page (`https://elite.finviz.com/screener.ashx*`). The new refresh buttons will replace the old ones.

## 🔗 Other Links & Support

* **Greasy Fork Page (Alternative Host):** [https://greasyfork.org/en/scripts/554558-finviz-elite-refresh-overhaul](https://greasyfork.org/en/scripts/554558-finviz-elite-refresh-overhaul)
* **Developer Support:** [https://buymeacoffee.com/anthonycreates](https://buymeacoffee.com/anthonycreates)
