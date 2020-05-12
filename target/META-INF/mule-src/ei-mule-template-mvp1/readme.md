## Enterprise Integrations: Mule4 template (MVP1)



**Summary:**
The goal of this base template is to serve as the foundation for your project. We have save you some time and pre-build a sample project that can be easily adapted to. your needs. Following the C4E best practices, this template contains:

- All global elements are grouped in a single file, **global.xml**
- All errors default to a single flow in **error.xml** to isolate it for the other files and flows
- The environment variable (**mule.env**) will load all the files, properties and variables for that specific environment.
- No hardcoded properties in mule elements, it load them from the YAML properties file
---

**How to use it?**

- Import it into Anypoint Studio 7
- Change the mule.env global element for **dev** or **prod**
- Deploy it
- Hit the endpoint http://localhost:8081/template

---
**What now?**

Please build your project following the methods and best practices, for more info, visit [this](https://confluence.internal.salesforce.com/display/ITEI/C4E+Best+Practices) link


Cheers!
