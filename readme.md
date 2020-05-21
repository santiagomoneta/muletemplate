Mule application template (mule4)



**Summary:**
The goal of this base template is to serve as the foundation for your project. We have save you some time and pre-build a sample project that can be easily adapted to your needs.

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

Build awesome applications!

Think in re usability


Cheers!
