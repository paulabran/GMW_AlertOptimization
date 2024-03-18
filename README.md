# Global Mangrove Watch Alert Optimization

# Background
The background is that along with the Global Mangrove Watch Mapping initiative, there is also the Global Mangrove Watch Loss Alerts. Every month through satellite images, mangrove vegetation values are compared to check if deforestation happened or not. 
One of the problem that arises, it is that high tides sometimes end up covering some mangroves, and for the model that looks for differences in the vegetation of mangroves, this may seem as deforestation. But it is not. And that is how we get false positive deforestation alerts. 
Since the platform must be truthful in presenting these alerts, there is no space for false positives, and they all must be removed manually as of now. This code is the result of an internship project in Wetlands International, which tried to create water masks, and use geospatial functions to remove false positives while keeping true positive deforestation alerts. 

# Running the code 
Unfortunately this code is not reproducible for all mangrove areas worldwide of now. It only runs for eight specific areas, which you need to choose.  Another drawback is that you need to signed up in Microsoft's Planetary Computer to access the sattelite data. When completed, it is signaled where you should insert your credentials. 
