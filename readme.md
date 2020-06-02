

Mule application template (MULE4)

![Dont be like homer](https://i.imgur.com/1Ya0fxu.jpg)

**What is this?**

Every project need a strong and solid foundation, when your project grows, this will become critical and the goal of this base template is to serve as the fundation for your project. We have save you some time and pre-build a sample project that can be easily adapted to your needs.

- All global elements are grouped in a single file, **global.xml**
- All errors default to a single flow in **error.xml** to isolate it for the other files and flows
- The environment variable (**mule.env**) will load all the files, properties and variables for that specific environment.
- No hardcoded properties in mule elements, it load them from the YAML properties file
---
**Is there any "minimal" prerequisites?**

 - Anypoint Studio 7.4 with Maven ([link](https://www.mulesoft.com/lp/dl/studio))
 - JDK 8 ([Link](https://adoptopenjdk.net/releases.html?variant=openjdk8&jvmVariant=hotspot)) 
 
---
**Should I do anything about Maven?**

- Anypoint Studio include Maven and **you don't need to re install it**, as for the project dependencies, this project does not require any special or customs dependencies or repositories so no need to change anything on your [settings.xml](https://maven.apache.org/settings.html) file.

---

**How to use it?**

- Import it into Anypoint Studio 7 ([How](https://docs.mulesoft.com/studio/7.5/import-export-packages))
- Change the `mule.env` global element variable for **dev** or **prod**
	- Open the file **global.xml**
	- Click on **"global elements**" tab at the bottom
	- Double click on the Global property "**mule.env**" 
	- Change the value and click on "**OK**"
	- **Save** all changes.
- Deploy it
	- Be sure you are on the **"Message flow" tab** from any of the xml files.
	- **Right click** on the canvas and select "**Run project mule-template-mvp1**"
	- Wait until you see the "**Deployed**" line in the console tab
- Hit the endpoint http://localhost:8081/template 

---

**What now?**

Take some time to check these:
- [Mulesoft "Self-study" classes](https://training.mulesoft.com/category/mulesoftu)
- [Mulesoft API-LED workshop](https://training.mulesoft.com/instructor-led-training/anypoint-platform-technical-workshop-public)
- [What is API-LED?](https://blogs.mulesoft.com/dev/api-dev/what-is-api-led-connectivity/)
- Build awesome applications!
- Follow best practices
- Think in re usability

Cheers!
