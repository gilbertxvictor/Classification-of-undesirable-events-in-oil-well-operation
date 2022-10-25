# Classification-of-undesirable-events-in-oil-well-operation
A realistic and public dataset with rare undesirable real events in oil wells published in the Journal of Petroleum Science and Engineering

# ABSTRACT

Detection of undesirable events in oil and gas wells can help prevent production losses, environmental accidents, and human casualties and reduce maintenance costs. 
The scarcity of measurements in such processes is a drawback due to the low reliability of instrumentation in such hostile environments. 
Another issue is the absence of adequately structured data related to events that should be detected. 
To contribute to providing a priori knowledge about undesirable events for diagnostic algorithms in offshore naturally flowing wells, this work presents an original and valuable dataset with instances of eight types of undesirable events characterized by eight process variables. 

**AIM**
- To establish relationship between variables
- Build an ML model that accurately predict the state of flow in a well

# DATA INFORMATION
![image](https://user-images.githubusercontent.com/98072583/197747127-97c2706b-b535-49f9-9071-d78ed1b353f3.png)

|ATTRIBUTES  |Description                                               |
|----------- |----------------------------------------------------------|
|T-JUS-CKGL	 |Temperature downstream of Gas lift Choke(CKGL)            |
|P-JUS-CKGL	 |Pressure downstream of Gas lift Choke(CKGL)               |
|QGL	       |Gas lift Flow rate                                        |
|T-TPT	     |Temp. @ Temperature Pressure Transducer(TPT)              |
|P-TPT	     |Pressure @ Temperature Pressure Transducer(TPT)           |
|T-JUS-CKP   |Temperature downstream of Production Choke(CPK)           |
|P-MON-CKP	 |Pressure upstream of Production choke(CPK)                |
|P-PDG	     |Pressure at Permanent Downhole Guage                      |
|class	     |Condition of flow                                         |
|timestamp   |Time of occurance(Collected per second for each instance  |                                      |

# Class

|Class  | Number Type of event Real Simulated Total    |
|-------|----------------------------------------------|
|0      | Normal                                       |
|1      | Abrupt Increase of BSW                       |
|2      | Spurious Closure of DHSV                     |
|3      | Severe Slugging                              |
|4      | Flow Instability                             |
|5      | Rapid Productivity Loss                      | 
|6      | Quick Restriction in PCK                     |
|7      | Scaling in PCK                               |
|8      | Hydrate in Production Line                   |


# WORKFLOW

- Data was aggegated per minute(60 occurances) and using 'median' as the aggregator
- The resultant data was then cleaned 
- Feature Enginering was employed to classifiy class as Normal, Faulty and Transient
- Data analysis and visualization to understand patterns 
- Machine learning using TensorFlow( Applying a deep leanrning approach)

# CITATION 

If you know any other work that cites this project, I will be grateful if you let me know by email ('victorgilbert88@gmail.com').

1) Vargas, Ricardo; Munaro, Celso; Ciarelli, Patrick; Medeiros, André; Amaral, Bruno; Barrionuevo, Daniel; Araújo, Jean; Ribeiro, Jorge; Magalhães, Lucas (2019), “Data for: A Realistic and Public Dataset with Rare Undesirable Real Events in Oil Wells”, Mendeley Data, v1. http://dx.doi.org/10.17632/r7774rwc7v.1

2) Evren M. Turan, Johannes J¨aschke, Department of Chemical Engineering, Norwegian University of Science and Technology (NTNU), "Classification of undesirable events in oil well operation"
