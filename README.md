# 🚖 Ola Ride Data Analysis – Bangalore  

A data-driven project analyzing Ola ride patterns in Bangalore using a **dummy dataset**, **SQL queries**, and a **Power BI dashboard**. The project demonstrates end-to-end data handling, from querying and extracting insights with SQL to visualizing results in Power BI.  

---

## 📌 Project Overview  
The goal of this project is to simulate real-world Ola ride booking data and uncover meaningful insights. SQL is used to query and aggregate ride data, while Power BI provides interactive dashboards to visualize booking trends, cancellations, and customer-driver behavior.  

---

## 📊 Dataset Details  
The dataset includes:  
- **Date & Time** – Ride booking details  
- **Booking ID** – Unique 10-digit ID (starting with CNR)  
- **Booking Status** – Successful, Cancelled, Incomplete  
- **Customer ID** – Unique identifier  
- **Vehicle Type** – Auto, Prime Sedan, Mini, Bike, eBike, Prime SUV  
- **Pickup & Drop Locations** – 50 dummy Bangalore locations  
- **Avg VTAT & CTAT** – Vehicle and Customer arrival times  
- **Cancelled / Incomplete Rides** – With categorized reasons  
- **Booking Value** – Ride fare distribution  
- **Ride Distance** – Travelled distance  
- **Driver & Customer Ratings** – Performance feedback  

---

## 🗄️ SQL Queries  
The project includes several SQL views for extracting insights:  
1. Retrieve all successful bookings  
2. Find average ride distance by vehicle type  
3. Count cancelled rides by customers  
4. List top 5 customers by total bookings  
5. Driver cancellations due to personal/car issues  
6. Max and min driver ratings for Prime Sedan rides  
7. Rides paid via UPI  
8. Average customer rating per vehicle type  
9. Total booking value of successful rides  
10. Incomplete rides with reasons  

*(See `VIEW.sql` for details.)*  

---

## 📌 Business Rules Applied  
- ✅ 62% successful bookings  
- ❌ ≤ 7% customer cancellations  
- ❌ ≤ 18% driver cancellations  
- ❌ < 6% incomplete rides  
- 📈 Higher bookings on weekends and match days  
- 💰 Fare distribution:  
  - 70% under ₹500  
  - 28% between ₹500–₹1000  
  - Remaining above ₹1000  

---

## 📊 Power BI Dashboard  
The dashboard includes:  
- Booking trends across weekdays, weekends, and match days  
- Cancellation analysis (customer vs driver)  
- Fare distribution and demand spikes  
- Top customers and location-based bookings  
- Customer and driver ratings  

---

## 🛠️ Tech Stack  
- **Database & Queries:** SQL  
- **Data Preparation:** Python / Excel  
- **Visualization:** Power BI  
- **Version Control:** GitHub  

---

## 🎯 Key Insights  
- Demand is highest on weekends and match days  
- Customer cancellations are significantly lower than driver cancellations  
- Most rides are under ₹500, but weekends see higher fare rides  
- Ratings help evaluate driver and customer satisfaction  
- SQL queries combined with Power BI visuals make analysis more powerful  

---

## 📸  Screenshots / Demos
 show what the dashboard looks like. - ![Alt text](https://github.com/mdsajidhussain0786/Ola-Ride-Analytics/blob/f6ebb825eb9bcb4adc28e0d40f256ad53fa0248e/Snapshot%20of%20Ola%20Dashboard.png)

 Example: ![Dashboard Preview](https://github.com/mdsajidhussain0786/Ola-Ride-Analytics/blob/f6ebb825eb9bcb4adc28e0d40f256ad53fa0248e/Snapshot%20of%20Ola%20Dashboard.png)
 

## 🚀 Getting Started  
1. Clone the repository:  
   ```bash
   git clone <repository_url>
