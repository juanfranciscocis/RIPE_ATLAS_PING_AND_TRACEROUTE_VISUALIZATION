# Final project


In this project we will build a network monitoring system. The goal of our system is to measure the latency of a server hosting a web application. We are going to measure latency from different locations. 

## Measurements

### Account creation
- Create an account at [Riple Atlas](https://access.ripe.net/registration])
- Use your personal email to do so
- Send a message on Discord to request credits

### Measurements
- You can run ping or traceroutes for your project. 
- With these measurements you will be able to get latency, hop-count and route.
- You can use the Ripe API to execute the commands
- Pay attention to the location of the probes running your measurements



## Target

- For the target, you should deploy your simple web page to Azure. 
- Make sure that you deploy it to a single location.

## Exercises

1. Determine where your application is deployed
    - Run a ping or nslookup to determine the IP address of your web-page
    - Use the IP to determine the geographical location of the server hosting your web-page


2. Measure the latency of your web-page from different countries in the globe. 

    - Plot the latencies using a visualization that would help us see the relationship between distance and latency
    - Assume that you now have a video application deployed instead of a simple web-page. What would be the problems if the users are from all over the world? What would you propose to improve the experience of your users?


3. Run a traceroute measurement from the same probes you did in (2).

    - From the output of the traceroute, approximate the number of hops from the client and your web-page.
    - Use a visualization to show the relationship between geographical distance and the number of hops. 
    - Does the number of hops have an impact on the experience of the users?
    

4. Deploy your wep-page to the Azure CDN service (Azure Frontdoor).

    - What is a CDN?
    - What do you expect to be the impact of deploying your web-page to the CDN?
    - Run a ping from your personal computer to the web-page in the CDN. Determine the location of the server hosting your web-page.
    - How does this locaiton differ from the one obtained in (1).
    
    
5. Repeat (2) and (3) with the CDN url of your web-page
    - Make the same visualizations as the exercises above
    - What are the results of deploying your web-page to the CDN. 
    
    


```python

```


```python

```
