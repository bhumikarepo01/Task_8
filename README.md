# 🧪 Task 8: Run a Simple Java Maven Build Job in Jenkins

## 📌 Objective
Use Jenkins to build a simple Java application using Maven — the first step in understanding CI/CD pipelines.

## 🛠 Tools Used
- Java (JDK 8)
- Maven
- Jenkins (via Docker)
- Git & GitHub


## ⚙️ Jenkins Job
- **Job Name**: HelloWorldJob
- **Job Type**: Freestyle project
- **Build Step**: `mvn clean package`
- **GitHub Repo**: [Task_8](https://github.com/bhumikarepo01/Task_8)
- ✅ Build Successful (see screenshot below)

## 📸 Console Output Screenshot
-![localhost_8080_job_HelloWorldJob_lastCompletedBuild_console](https://github.com/user-attachments/assets/b0a7742b-b40c-4d32-9d34-cd6f8cb45b08)

## 📝 Notes
- Used UTF-8 encoding warning is safe and expected.
- Make sure `pom.xml` is in the correct working directory.
- Jenkins workspace must clone the folder containing `pom.xml`.


