+++
author = "Madi"
date = 2019-04-08T00:00:00Z
description = "How we made cardiac rehab sessions in PH faster, safer and more reliable"
tags = ["circuit", "electrical", "electronics", "design", "development", "biomedical", "telemedicine", "startups", "tech"]
title = "CaRE: Cardiac Rehabilitation Equipment (Pre-Clinical Trial Release)"

+++
# **CaRE: Cardiac Rehabilitation Equipment**

Today, cardiac rehabilitation in the Philippines are closely  
supervised by physical therapists; wherein a session duration  
ranges from 40-70 minutes and could be as frequent as daily.  
In the Philippines, only 1,324 physical therapists and 343  
occupational therapists that have been newly registered in  
2013\. As such, the shortage of these professionals remains a  
big problem in the country.

In the Philippines, there is **no stand-alone equipment** to aid  
in the recovery of cardiac patients during rehabilitation.  
Cardiac rehabilitation programs are currently manually  
supervised by the limited number of professional physical  
therapists. In addition, the physical therapists are unable to  
quantitatively evaluate the patient's rehabilitation. Thus, an  
equipment that could be easily operated by medical experts  
and effectively provide the necessary cardiovascular training  
with minimal supervision will be developed.

###### =![](/uploads/care1.PNG)

## **Role**

###### For this biomed venture, my role was **tech maven** and **scrum master**. As an agile product developer, I adopted a hands-on approach while working on improvements to the equipment such as:

* Designed, simulated, developed and lab-tested the consolidated motherboard that enables all the modules to be powered by a single AC source, i.e. an equipment that requires the user to plug only one adapter (PCB design, EAGLE, Simetrix, C++)
* Built and integrated an automated PDF generator of post-exercise reports which includes the csv file of the ECG Data (SQL, Python)
* Integrated Arduino watchdog timer (WDT) to prevent system hangs

![](/uploads/care2.PNG)

Find out more about our solution on this [repo](https://github.com/titaofdata/CaRE-publication "CaRE repo").