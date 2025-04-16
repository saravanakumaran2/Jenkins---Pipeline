# My Jenkins Pipeline Project

This repo is where I’ve experimented with **Jenkins Pipelines** using a `Jenkinsfile` to automate steps like build, test, and deploy.  
I kept it simple on how Jenkins works with pipelines.

---

## What I Did in This Project

-  Wrote a `Jenkinsfile` to define a **CI/CD pipeline** using **Declarative Pipeline syntax**
-  Broke the pipeline into multiple stages:
  - **Build** — compile or set things up
  - **Test** — run checks or test scripts
  - **Deploy** — final step, usually pushing to a server or environment

- Used basic `echo` steps to simulate actions (for learning)
- Ran the pipeline on a Jenkins instance (locally or on a VM)
- Tweaked and tested pipeline steps to understand how Jenkins reacts

---

## What’s in This Repo

```bash
.
├── Jenkinsfile        
└── README.md          
```

---

##  How to Use This

1. Make sure Jenkins is up and running
2. Create a new **Pipeline project**
3. Link it to this GitHub repo
4. Jenkins will auto-detect the `Jenkinsfile` and run it!

---

