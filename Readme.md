# ⚡ TN Power Log

A full-stack **MERN application** designed to help users track, analyze, and manage their electricity consumption — with built-in support for **Tamil Nadu electricity slab rates**.

---

## 🚀 Features

### 🔐 User Authentication
- Secure login & registration system  
- Each user has **isolated data (personal database records)**  

### 📊 Electricity Dashboard
- Track electricity readings over time  
- View:
  - Total units consumed  
  - Consumption trends  
  - Estimated cost  

### 🧮 Smart Billing System
- Automatic calculation based on **slab rates**
- Default slab configuration for **Tamil Nadu users**
- Custom slab editing for users from other states

### 📈 Analytics
- Consumption insights  
- Historical usage tracking  
- Cost breakdown visualization  

### ✏️ Slab Rate Customization
- Edit:
  - Unit ranges  
  - Cost per slab  
- Fully dynamic calculation engine  

### 📷 WhatsApp Sharing (Unique Feature)
- Capture **latest 5 records (history table)** as an image  
- Uses `html2canvas`  
- Share instantly via WhatsApp  

---

## 🛠️ Tech Stack

### Frontend
- React.js  
- Tailwind CSS  
- HTML2Canvas  

### Backend
- Node.js  
- Express.js  

### Database
- MongoDB  

### Tools & Utilities
- REST APIs  
- JWT Authentication  

### 🤖 AI Assistance (Optional)
- ChatGPT used for:
  - Idea refinement  
  - Code suggestions  
  - Debugging  

---

## 🧠 How It Works

1. User logs into the system  
2. Adds electricity readings periodically  
3. System:
   - Calculates units consumed  
   - Applies slab rates  
   - Computes total cost  
4. Dashboard updates with:
   - Usage stats  
   - Analytics  
5. User can:
   - Modify slab rates  
   - Share usage via WhatsApp  

---

## 📸 WhatsApp Sharing Flow

- Select latest records  
- Convert table → image using `html2canvas`  
- Trigger WhatsApp share  
- Send to any contact  

---

## ⚙️ Installation & Setup

```bash
# Clone the repository
git clone https://github.com/srinaveenrajr/TN-PowerLog.git

# Navigate to project
cd TN-PowerLog

# Install backend dependencies
cd BACKEND
npm install

# Install frontend dependencies
cd ../client
npm install
