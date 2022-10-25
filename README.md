# Classification-of-undesirable-events-in-oil-well-operation
A realistic and public dataset with rare undesirable real events in oil wells published in the Journal of Petroleum Science and Engineering

*ABSTRACT*
Detection of undesirable events in oil and gas wells can help prevent production losses, environmental accidents, and human casualties and reduce maintenance costs. 
The scarcity of measurements in such processes is a drawback due to the low reliability of instrumentation in such hostile environments. 
Another issue is the absence of adequately structured data related to events that should be detected. 
To contribute to providing a priori knowledge about undesirable events for diagnostic algorithms in offshore naturally flowing wells, this work presents an original and valuable dataset with instances of eight types of undesirable events characterized by eight process variables. 

**AIM**
- To establish relationship between variables
- Build an ML model that accurately predict the state of flow in a well

**DATA INFORMATION**
![image](https://user-images.githubusercontent.com/98072583/197747127-97c2706b-b535-49f9-9071-d78ed1b353f3.png)

![image](https://user-images.githubusercontent.com/98072583/197750660-8cf2118c-3b37-43b4-b6f9-b90437208af1.png)


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
|timestamp   |Time of occurance 	                                      |

