# Locale_ai interview
## Data science task
#
### **Problem Statement**

The biggest challenge for XRides is to increase the utilization rate of their cabs. However, the demand keeps fluctuating based on the area, time of day, etc. Your task is to device a geo-surge strategy that would help them incentivize their drivers. Identify what areas and at what times get most bookings and how would you increase the price in those areas in order to
meet the demand.

More than any other task, it will be critical for you to get a deep understanding of the dataset,
the business and how you can help them.

Brownie points if you share a recommendation or strategy backed by data that helps them
reduce cancellation, increase revenue or reduce costs.
#
### **Code Implementation**

The explanatory [Jupyter Notebook](https://github.com/madhukumble/locale_ai/blob/main/localeai_interview_task.ipynb) shows the data analyses along with visualizations (EDA).
#
### **GeoSurge pricing strategy / Dynamic Pricing Model:**

* The drivers are incentivize if they go to the location where the demand is very high. In that way both the drivers and the customer requirements are satisfied
* As more and more drivers arrives to the location where there's excess demand, the demand gradually reduces and the prices return to normal
* Other than increasing the supply, increased fare will also results in decrease in the demand (Making the service run more smoother)
* If the demand is low, offering promotions, discounts, coupons etc. helps to boost up demand. Hence, pricing would benefit the company.
#
### **Points to note:**

* Based on the requirement of riders/passengers, they usually expect high supply. But drivers don't work at that time which results in low supply. Let's say drivers prefer not to drive at their current condition like late nights, bad weather, weekends or other personal reasons etc.
* During most peak hours (eg: commuting to and from work), other modes of public transport are also jammed.
* Number of cancelled rides could be because of improper supply like waiting for long period, cabs too far, delay in pickup etc.
#
### **Conclusion:**

* The demand of the cab is high during the office commuting hours i.e. between 9 AM - 10 AM and 6 PM - 7 PM, and least during the midnight (1 AM to 3 AM)
* Despite of cancelling rides, most of the people take a cab during weekends to travel from one location to another
* Frequency of point to point travel is high, and the least is long distance.

Therefore, the utilization rate of the cabs can be maximized by:

* Increasing the fare during office commute period, and during the weekends
* Getting more cabs to do point to point and less on long distance and rental type of travel.
  