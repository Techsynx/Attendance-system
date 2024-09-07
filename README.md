

---

## **Staff Attendance Tracking System**

![attendance-banner](https://user-images.githubusercontent.com/your-banner.png)

> A modern, intuitive, and professional staff attendance tracking system. Designed with a sleek interface, it allows managers to track, approve, and export timesheets efficiently. Built using Python (Flask), HTML, CSS, and JavaScript.

---

### **Table of Contents**
- [Features](#features)
- [Getting Started](#getting-started)
- [Screenshots](#screenshots)
- [Installation](#installation)
- [Usage](#usage)
- [License](#license)

---

### **Features**

- 🕒 **Real-time attendance tracking**: View and track employee time-in/time-out status with detailed timesheet reports.
- 📈 **Analytics**: Capacity and work status indicators for visualizing employee productivity.
- 📝 **Approval & Export**: Approve or reject timesheets and export data for reporting.
- 🎨 **Interactive UI**: Smooth animations, responsive design, and professional look-and-feel.
- 🔐 **Secure Authentication**: Easily integrated with user authentication for managers and employees.

---

### **Getting Started**

To get a local copy up and running, follow these simple steps.

#### **Prerequisites**

- Python 3.x
- Flask
- Modern Web Browser

#### **Installation**

1. Clone the repo:
   ```bash
   git clone https://github.com/your-username/staff-attendance-tracking-system.git
   ```

2. Navigate into the project directory:
   ```bash
   cd staff-attendance-tracking-system
   ```

3. Install the required Python packages:
   ```bash
   pip install flask
   ```

4. Run the application:
   ```bash
   python app.py
   ```

---

### **Screenshots**

#### **Dashboard View**
<img src="https://user-images.githubusercontent.com/your-dashboard-image.png" alt="Dashboard View" width="800"/>

---

#### **Timesheets Overview**
<img src="https://user-images.githubusercontent.com/your-timesheet-image.png" alt="Timesheets Overview" width="800"/>

---

#### **Employee Status**
<img src="https://user-images.githubusercontent.com/your-status-image.png" alt="Employee Status" width="800"/>

---

### **Code Snippets**

Here are some key code snippets used in the project:

#### **Backend (Flask)**

```python
@app.route('/')
def index():
    return render_template('index.html', employee=employee_data)
```

#### **Frontend (HTML & Flask Templating)**

```html
<div class="employee-details">
    <h3>{{ employee['name'] }}</h3>
    <p>{{ employee['title'] }}, Location: {{ employee['location'] }}</p>
</div>
```

#### **JavaScript for Animations**

```javascript
approveButton.addEventListener('mouseover', () => {
    body.style.backgroundColor = '#dff9fb';
});
```

---

### **Installation**

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/your-username/staff-attendance-tracking-system.git
   ```

2. **Install Dependencies:**

   ```bash
   pip install flask
   ```

3. **Run the Application:**

   ```bash
   python app.py
   ```

4. Open a browser and go to `http://127.0.0.1:5000`.

---

### **SVG Icons Overview**

We use SVG icons to make the interface more attractive. Here are some examples:

#### **Approve Button**


<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="green" width="24px" height="24px">
    <path d="M0 0h24v24H0z" fill="none"/>
    <path d="M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10 10-4.48 10-10S17.52 2 12 2zm-1 15l-5-5 1.41-1.41L11 14.17l7.59-7.59L20 8l-9 9z"/>
</svg>
```

#### **Export Button**


<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="blue" width="24px" height="24px">
    <path d="M0 0h24v24H0z" fill="none"/>
    <path d="M5 20h14v-2H5v2zm7-18l-5 5h3v4h4v-4h3l-5-5z"/>
</svg>
```

---

### **Usage**

- Access the **Timesheets** tab to view and manage employee attendance.
- Use the **Approve** button to approve timesheets or the **Export** button to download the data.
- Hover over statistics and buttons to see smooth animations and transitions!

---

### **License**

Distributed under the MIT License. See `LICENSE` for more information.

---

### **Contact**

👤 **Techsynx**

- GitHub: [@your-Techsynx](https://github.com/your-Techsynx)
- Email: [Techsynxx@gmail.com](mailto:Techsynxx@gmail.com)

Feel free to open an issue if you find a bug or have suggestions to improve the project.

---

### **Contributions**

- 🛠️ Contributions are what make the open-source community such an amazing place to be.
- Feel free to **fork** the repository and submit pull requests!

