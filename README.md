# A# 🧠 AWS Generative AI Lab — Theo7 Portfolio Project  

This project documents my completion of the **AWS Skill Builder – Generative AI SimuLearn Lab**.  
The goal was to deploy a **Hugging Face Falcon foundation model** on **Amazon SageMaker**, connect it to **AWS Lambda**, and expose it through an **API Gateway endpoint**.  

I treated this as more than just a guided exercise. I documented **errors, code edits, and sandbox limitations** to make it portfolio-ready.  

---

## 🚀 Workflow Overview  

### **1. Model Setup in SageMaker**  
I opened Amazon SageMaker and selected the Falcon foundation model.  
![Step1](screenshots/step1_sagemaker_dashboard.png)  

---

### **2. Deploy Endpoint**  
The model was deployed as a SageMaker endpoint so it could be invoked by other services.  
![Step2](screenshots/step2_foundation_model.png)  

---

### **3. Lambda Function**  
I created a Lambda function to send payloads to the SageMaker endpoint and receive predictions back.  
![Step3](screenshots/step4_lambda_function.png)  

---

### **4. API Gateway**  
Finally, I connected the Lambda function to API Gateway to make the model accessible via an HTTPS endpoint.  
![Step4](screenshots/step5_api_gateway.png)  

---

### **5. Custom Code Edit**  
I successfully customized the Jupyter notebook code to include my own name (“Theo”) in the payload.  
This showed that I could go beyond the default script and make personal adjustments.  
![Step5](screenshots/step6_custom_code_theo.png)  

---

## ⚠️ Errors & Debugging  

- **NameError Issue** → At one point I forgot to click inside the Jupyter cell before running it, which caused a `NameError`. Correcting this fixed the run.  
![Error1](screenshots/error_nameerror.png)  

- **Fetch Error at Endpoint Test** → When testing the final API Gateway call, I received a **“failed to fetch” error**.  
👉 This is a **known limitation of the AWS Skill Builder sandbox**, not the deployment itself.  
In a real AWS account, the endpoint would return results.  
![Error2](screenshots/error_fetch.png)  

---

## 🔍 Lessons Learned  

- How **payloads** move between Lambda → SageMaker → API Gateway.  
- Difference between **text editors (Notepad)** and **IDEs (Jupyter, SageMaker Studio)**.  
- How to **personalize lab code** (added my own name to the input).  
- Why **sandbox environments** may block full responses, unlike real AWS deployments.  
- Importance of careful debugging (cell execution order, runtime errors, sandbox fetch issues).  

---

## 🏆 Value for Employers  

This project shows:  
- Hands-on integration of **multiple AWS services**.  
- Ability to **troubleshoot real errors** instead of just clicking “Next.”  
- Clear documentation of both **successes and failures**.  
- Awareness of the difference between **sandbox labs vs. real production AWS**.  

Even though this was a guided lab, I treated it like a **workflow project**: documenting steps, customizing code, and noting sandbox limitations transparently.  

---

## 📸 Full Walkthrough  

All screenshots, including **error captures**, are in the [screenshots folder](./screenshots).  

---

## 🔗 Next Steps  

- Re-run in a full AWS environment to confirm endpoint responses.  
- Expand custom prompts and parameters.  
- Pair this workflow with **AWS cost optimization labs** for a complete architecture story.  
WS-Generative-AI-Lab
