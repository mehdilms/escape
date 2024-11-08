ESCAPE TEST SALES ENGINEER

Answer to corresponding questions : 

PART 1 : 
  Q1 : What can you tell about this application from the scan results ?
The application has a relatively low Scoring (24%), which can be explained by several vulnerabilities identified by Escape, 12 in all. 
It is exposed to risks of external exposure, leakage of sensitive data, and critical vulnerabilities.

Of the 12 vulnerabilities identified, 2 are rated high and 4 medium in terms of severity. Precise details of each vulnerability are presented, with a description of the flaw, the method used to identify it, and a suggestion for improvement.
In addition, the Escape scan identified credentials - 3 email addresses and 2 passwords - thanks to vulnerabilities present on 3 endpoints.

Finally, as things currently stand, this application does not comply with any of the security standards in use for APIs. For each of these standards, a description of the tests carried out and their status (pass or fail) is given, along with a list of possible improvements for each flaw.

To sum up, this application is exposed to numerous risks, some more severe than others, but can we easily handled thanks to Escape recommendations

  Q2 : What do you notice when taking a look at the GET /users/v1 requests in the  “logs” panel? 
The scan of this API call showed that no risk had been identified and that all unit tests had been validated. On the other hand, this endpoint exposes sensitive data such as input email addresses.

Part 2 : 

Setting up Escape Repeater locally went smoothly, and the data streams are transmitted to my Repeater client when I need them. 
"
2024-11-08 10:31:07.366503088 +0000 UTC INFO Processed stream in 9.384012ms (8199160)
2024-11-08 10:31:07.368214705 +0000 UTC DEBUG Received response code 401 (8199159)
2024-11-08 10:31:07.368248525 +0000 UTC INFO Processed stream in 11.441687ms (8199159)
2024-11-08 10:31:07.370799464 +0000 UTC INFO Received incoming stream (8199162)
2024-11-08 10:31:07.370866351 +0000 UTC DEBUG Sending request (8199162)
2024-11-08 10:31:07.375925981 +0000 UTC DEBUG Received response code 401 (8199161)
2024-11-08 10:31:07.375975686 +0000 UTC INFO Processed stream in 12.124134ms (8199161)
2024-11-08 10:31:07.376082579 +0000 UTC INFO Received incoming stream (8199163)
2024-11-08 10:31:07.376144197 +0000 UTC DEBUG Sending request (8199163)
2024-11-08 10:31:07.381572533 +0000 UTC DEBUG Received response code 401 (8199162)
2024-11-08 10:31:07.381641746 +0000 UTC INFO Processed stream in 10.799668ms (8199162)
2024-11-08 10:31:07.429149009 +0000 UTC DEBUG Received response code 401 (8199163)
2024-11-08 10:31:07.429194281 +0000 UTC INFO Processed stream in 53.073006ms (8199163)"


Part 3 : 

## File Contents

- **`main.ipynb`**: The core file of the project, containing all the relevant work and results.

For any questions or clarifications, please feel free to reach out.

Part 4 : 
  Q1 : Considering the process achieved to start a scan, what would you anticipate as the main bottleneck when setting up Escape at the Enterprise scale?

The main point of tension lies in scalability and performance management when Escape has to analyze a large number of APIs, then monitor evolutions - particularly when it comes to managing customized rules and processing large quantities of data.
 The complexity of configuration and coordination between different development, security and DevOps teams can also hamper smooth integration in a large-scale environment.

As a Sales Engineer, I will try to understand the customer's technical environment to identify possible obstacles to Escape deployment, which I will take into account when developing the methodological approach.
Depending on the context, I will then present a strategy that takes into account their mode of governance, so that the deployment can be carried out in the most appropriate way. 
I will consider a modular and progressive deployment when the customer's technical environment is complex. 
In agreement with the account manager, and if I deem it relevant, I may also suggest starting with an initial PoC phase on some of these APIs, so that the customer can experiment with the solution.

Another point of tension may be the technological restrictions a customer may have on using a solution that isn't part of their calatogue of authorized tools. The application process can be lengthy and time-consuming.

As a Sales Engineer, here I'll try to understand their internal tool validation process in depth. Once I've done that, I'll arbitrate whether or not it makes sense for Escape at this stage to pursue the process of obtaining user authorizations. 
  
  Q2 : In a DevOps context, why would it be hard to set up Escape in the CI/CD pipelines?  
Integrating Escape into a CI/CD pipeline can be complex due to the challenges associated with the timing of scans. This can slow down the pipeline and create friction with DevOps teams, which can delay deployments and lead to unhappiness.

As Sales Engineer I would work with DevOps teams to configure Escape so that it integrates seamlessly into existing pipelines without compromising performance. I'd explain the importance of continuous security testing and offer customization options to target the tests that matter most to them. Finally, I would provide advice on integration best practices based on feedback from our existing customers, so that Escape integrates easily and quickly into their CI/CD workflow without slowing down development.
  
  Q3 : If given the opportunity, what would you improve in the UI or the process?
I find Escape's user interface already very intuitive and easy to use, especially for non-technical teams. 
My first recommendation for improvement would concern details of form: certain headings mentioned in the documentation are not exactly the same as those in the interface, which leads to wasted time.

Moreover, if I were in charge of the platform's UI, I'd propose an intuitive presentation of the platform on first connection. This presentation would take the form of dialogue bubbles that open one after the other to explain the user path and each specific feature.

A final recommendation is to rely on more Youtube tutorial videos like Tristan's for the product presentation, to explain the new features and how they work. A short format keeps things simple while giving an overview of what's new and lead to better UX once getting into the platform.

Part of my work as a Sales Engineer would be to identify what's missing in the UX based on discussion with prospects and share it with the technical team to make the corresponding modifications.
