# Dr. Jivika: Revolutionizing Rural Healthcare Access

 **Problem Statement**
Millions of individuals, especially in rural and underserved communities, face limited access to affordable healthcare. With scarce medical facilities, high treatment costs, and language barriers, there is a pressing need for an innovative solution to bridge the healthcare gap.

**How can digital platforms, telemedicine, and AI-powered diagnostics improve healthcare access and affordability for underserved populations?**

 **Our Solution: Dr. Jivika**
Dr. Jivika is a comprehensive web-based healthcare platform designed to address the challenges of rural healthcare. By leveraging technology, we aim to enhance accessibility, affordability, and convenience in medical services.

---
### **Setup and Requirements**

**Prerequisites:**
- **Node.js** (v14.x or above) and npm installed.
- MongoDB instance running locally or on a cloud server.
- Internet connection for API integrations (Daily.co, Cohere, etc.).

**Steps to Set Up:**
1. **Clone the Repository:**
   ```bash
   git clone https://github.com/kanishkapan/Codesprint2025.git33
   cd Codesprint2025
   ```

2. **Install Dependencies:**
   ```bash
   npm install
   cd client && npm install
   ```

3. **Environment Variables:**
   Create a `.env` file in the root directory with the following keys:
   ```env
   PORT=<Your Port>
   MONGO_URI=<Your_MongoDB_URI>
   DAILY_API_KEY=<Your_Daily.co_API_Key>
   COHERE_API_KEY=<Your_Cohere_API_Key>
   SECRET_KEY =<Your_secret_key>
   ```

4. **Run the Application:**
   - Start the backend on one server :
     ```bash
     npm run dev
     ```
   - Start the frontend on another server :
     ```bash
     cd client && npm start
     ```

5. **Access the Application:**
   Open your browser and navigate to `http://localhost:<Your Port>`.



 




   

---

**Key Features**

1. **Appointment Booking**
   - Users can seamlessly schedule appointments with healthcare professionals, ensuring timely access to medical services.

2. **Multilingual Support**
   - Designed with inclusivity in mind, our platform supports multiple languages, breaking down language barriers for non-English speaking users.

3. **AI-Powered Diagnosis**
   - An intelligent chatbot offers disease diagnosis and medicine recommendations based on user inputs, making initial consultations quick and efficient.

4. **Telemedicine**
   - Facilitates direct video consultations with doctors through **Daily.co** integration, ensuring quality care from the comfort of users' homes.

5. **Medicine Access**
   - Enables users to order prescribed medicines directly through the platform, reducing the need for unnecessary travel.

---

### **Commits Made**

1. **Project Initialization**: Set up the project structure using Vite.
2. **Minor Fixes**: Addressed early-stage bugs and made small adjustments.
3. **Backend Initialization**: Established the backend foundation.
4. **Component Creation**: Developed essential frontend components.
5. **Feature Implementation**: Integrated key features into the application.
6. **Frontend Completion**: Finalized the UI/UX and overall frontend design.
7. **Appointment Notifications**: Implemented backend logic for appointment alerts.
8. **Dashboard Fixes**: Resolved patient name display issues on the dashboard.

---

### **Technologies Used**

**Frontend:**
- HTML, CSS, JavaScript
- React.js
- TailwindCSS

**Backend:**
- Node.js
- Express.js

**Database:**
- MongoDB

**Additional Tools & APIs:**
- **Vite**: For rapid development and optimized builds.
- **Daily.co**: Seamless video calling for telemedicine.
- **Cohere**: Real-time live chat support.
- **Claude AI**: Enhanced AI-powered functionalities.

---

### **Why Dr. Jivika Stands Out**
- **Innovative Use of AI:** Intelligent diagnostics and live chat functionalities enhance user experience and accessibility.
- **Inclusive Design:** Multilingual support ensures the platform caters to diverse communities.
- **Scalable Solution:** Built using modern frameworks and tools, Dr. Jivika is highly scalable to meet growing healthcare demands.
- **Comprehensive Approach:** Combines telemedicine, AI, and multilingual support in one platform, providing a holistic solution to rural healthcare challenges.

---

### **How Dr. Jivika Impacts Lives**
Dr. Jivika empowers rural communities with timely, affordable, and accessible healthcare services. By leveraging technology, it bridges the gap between underserved populations and quality medical care, ultimately saving lives and improving well-being.

---

### **Future Plans**
- **Expansion to Mobile Apps**: Launching Android and iOS versions for wider reach.
- **Advanced AI Models**: Enhancing diagnosis accuracy with cutting-edge AI algorithms.
- **Integration with Ayushman Card**: Planning to have collaboration with government schemes running in rural areas.

---



**Join us in revolutionizing healthcare accessibility with Dr. Jivika!**

