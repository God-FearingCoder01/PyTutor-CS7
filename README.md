# Offline Python Tutor for CS7

A locally-hosted version of Python Tutor for environment diagram visualization, adapted for Emzini We Code students studying CS7: Introduction to Computer Science and Programming.  

> 📌 **Note:** This is a maintained fork of the original [OnlinePythonTutor](https://github.com/pgbovine/OnlinePythonTutor) by [Philip Guo](https://pg.ucsd.edu), whose repository is now private.

## ✨ Enhanced Features
- **Auto-launches browser** when server starts
- **Python 3.x compatibility** fixes
- **Offline-capable** for uninterrupted study sessions

## 🚀 Quick Start  

    **NB:** All the following are to be executed on git bash terminal, HOME (~) directory would be fine!

1. Clone the repository  
    ```bash
    git clone https://github.com/God-FearingCoder01/PyTutor-CS7.git
    ```
2. **cd** into the **PyTutor-CS7/v5-unity** directory
    ```bash
    cd PyTutor-CS7/v5-unity
    ```
3. Install dependencies
    ```bash
    npm install
    ```
    requires you to already have **node.js** installed in your computer.

    *Alternatively*
    ```bash
    pip install bottle
    ```
    
4. Start the server
    ```bash
    npm start
    ```

    *OR (if you chose alternative route in step 3.)*
    ```bash
    py bottle_server.py
    ```
    
5. (Nothing for you to do here) Your browser should automatically open to 
    ```text
    http://localhost:8003/visualize.html
    ```

# 📚 Usage Guide

* Write your python code in the editor
* Click "Visualize Execution" to see environment diagrams
* Use the Next/Prev buttons to step through execution

# 🛠 Techinical Details

+ **Port:** 8003 (configuarble in bottle_server.py)
+ **Tested with:**  
    * Python 3.11+
    * Node.js v22.17.0
    * Chrome/Edge browsers
    * Windows 10 Computer (64-bit)

# 🙏 Attribution

This fork was made possible by:  

- Original work by [@pgbovine](https://github.com/pgbovine)
- Previous fork by [@seamile](https://github.com/seamile)
- Adaptations for Emzini We Code community  

🌍 **Offline. Open. For Everyone.**  
*Because great CS education shouldn't depend on an internet connection.*  

🚀 **Happy Coding!**
> *Zvambuka lomyaka* :laughing:    

***
## 🏛️ Repository Status  
🔒 **Public Archive**  
This repository is archived as a stable reference for:  
- CS7 students studying environment diagrams  
- Offline Python Tutor implementations  
- Educational fork preservation  

While you can **fork** and **clone**, please note:  
- No active maintenance or PRs will be merged   
- Frozen as of {July 2025} 
- For active development, see [@pgbovine's latest work](https://pythontutor.com/)  

> *Adapted for environment diagrams: "Debugging is understanding the gap between intention and implementation."*