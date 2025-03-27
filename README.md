# 🚢 Container OPS V1 🚢  
*Smooth Sailing for Your Operations*  

## 🌟 What is Container OPS?  
Container OPS is a **PyQt6-powered** desktop application designed to streamline vessel operations. It provides an intuitive UI for managing pending jobs, tracking vessels, handling empty gate-out management, and generating operations reports.  

---

## 🛠 How to Use  

### 🖥️ Running the Application  
1. **Download the `.exe` file** from the repository.  
2. **Double-click** the `.exe` to launch the application—No installation needed!  
3. Start managing your vessel operations right away!  

#### 🛠 Running from Source (Optional)  
For developers who want to run the script manually:  

```bash
# Clone the repository
git clone https://TBA
cd container_ops

# Install dependencies
pip install -r requirements.txt

# Run the application
python Container_OPS_VXXX.py
```

---

## ⚡ Main Features (V1.1)  

### ✅ Pending Jobs Manager  
- Track vessel discharge, loading, and EDI statuses.  
- Edit job details **inline** with a dropdown or manual text input.  
- Jobs are auto-sorted, with completed ones moved to the bottom.  

### 🚢 Ops Report & Pre-Payments Generator  
- Process and log discharge & loading data from Excel files.  
- Auto-update ops report and prepayments based on container codes and local/transhipment.  
- Save a **history log** for later reference.  

### 📝Advanced Notepad  
- Save, edit, and manage notes **directly in the app**.  
- Sidebar displays all saved notes.  
- Fast retrieval for easy access!  

### 🔄 Empty Gateout Management  
- Assign **statuses** (`Pending`, `On Hold`, `Completed`, `Canceled`).  
- Beautiful **color-coded** job frames.  
- Status updates **instantly refresh** the view.  

### 🎨 Customizable UI  
- Light & Dark theme modes.  
- Easy navigation with **clean & structured layouts**.  
 
### ☀️ Weather  
- Weather Now supported!
- Based on `OpenWeatherMap`
- Get a free api key and add it on api text file to get the weather of your location!

💙 **Enjoy smoother operations with Container OPS V1.1!** 🚢  
