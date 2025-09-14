🧠 AWS Skill Builder Lab — Introduction to Generative AI

This project documents the full hands-on lab experience from AWS Skill Builder's “Introduction to Generative AI” using Amazon SageMaker, Lambda, API Gateway, S3, and CloudFront. It includes deploying a Falcon-7B model, testing inference with multiple prompts, and hosting a web frontend.

📁 All screenshots used are real console views — not simulations.

📌 Lab Goals

Deploy a Generative AI model (Falcon-7B) on Amazon SageMaker.

Test prompt generation use cases (translation, summarization, recipe generation, etc.)

Integrate with Lambda & API Gateway.

Host a web frontend using Amazon S3 and CloudFront.
🛠️ Step 1: Launch SageMaker Studio
<img width="1902" height="782" alt="06_Sagemaker_Landing" src="https://github.com/user-attachments/assets/6cdd9623-adeb-43b9-bc4c-31e2601e4860" />
<img width="1887" height="1022" alt="07_Sagemaker_Studio_Interface" src="https://github.com/user-attachments/assets/e94b5c74-d4dd-468c-a214-02baaa594ee1" />
🚀 Step 2: Open the Jupyter Launcher
<img width="1872" height="1002" alt="09_JupyterLab_Setup" src="https://github.com/user-attachments/assets/4517c91a-e226-4294-9727-ffa7153ca2fc" />
<img width="1617" height="987" alt="10_JupyterLab_Running" src="https://github.com/user-attachments/assets/0ccaaed4-d965-4c12-80e1-8d609c0976ad" />
<img width="1822" height="977" alt="11_Jupyter_LauncherScreen" src="https://github.com/user-attachments/assets/33f29722-7241-4cc8-81da-c90a55b283a0" />
📓 Step 3: Select Python 3 Notebook
<img width="1415" height="903" alt="12_GenerativeAI_Notebook_SelectPython3" src="https://github.com/user-attachments/assets/ced8a824-7481-45bc-b423-c86982b192be" />
🌑 Step 4: Dark Mode + Notebook Loaded
<img width="1528" height="1002" alt="13_JupyterLab_Darkmode" src="https://github.com/user-attachments/assets/adf9a622-8795-4cd8-b972-f5a465c54201" />
📘 Step 5: Model Deployment Notebook Open
<img width="1706" height="868" alt="14_IntroToGenAI_Notebookopened" src="https://github.com/user-attachments/assets/c7bc66b8-bcc0-4551-a63c-1985645672d8" />
🧠 Step 6: Upgrade SageMaker + Deploy Model
<img width="758" height="150" alt="Step1_Upgrade_SageMaker_CodeCell" src="https://github.com/user-attachments/assets/1139f6af-6689-4738-99d4-b0b2e21b1b87" />
🧪 Step 7: Test Your Deployed Model
<img width="1398" height="851" alt="Step4_Test_the_Deployed_Model" src="https://github.com/user-attachments/assets/38e0b36e-6c6a-45e2-9fc1-29130fb554c4" />
🧪 Step 8: Run All Use Case Prompts
<img width="1452" height="760" alt="Step4 2_4 2 1_TestUseCases_TestCodeGeneration" src="https://github.com/user-attachments/assets/12d41094-e738-4a3f-acb0-a0b70d4d336f" />
<img width="1447" height="615" alt="Step4 2 2_TestSentenceCompletion" src="https://github.com/user-attachments/assets/a5c0c187-44d9-45f0-8da3-cba48d0f5a3b" />
<img width="1286" height="906" alt="Step4 2 3_SeeTranslation" src="https://github.com/user-attachments/assets/e9d60979-54e0-49f8-ab8d-065909662a92" />
<img width="1357" height="891" alt="Step4 2 4_TestSentimentAnalysis" src="https://github.com/user-attachments/assets/a7e6c780-e121-47fd-aed6-0cb3ea8ce3b8" />
<img width="1401" height="370" alt="Step_4 2 5_Test_QuestioningAndAnswering" src="https://github.com/user-attachments/assets/234bf518-8124-4ba7-afe3-3cc7c5efc57b" />
<img width="1430" height="722" alt="Step_4 2 6_TestRecipeGeneration" src="https://github.com/user-attachments/assets/c16f79c6-652c-41b2-aa23-2ac96e77b038" />
<img width="1457" height="876" alt="Step4 2 7_Test_Summarization" src="https://github.com/user-attachments/assets/3a49893d-deaa-4734-853b-ab2ae870e672" />
📍 Step 9: View Endpoint Summary
<img width="1862" height="432" alt="15_endpoint_list_overview" src="https://github.com/user-attachments/assets/3e641d40-6c0e-4161-a436-ed7f5010be1b" />
<img width="1580" height="747" alt="16_endpoints_summary" src="https://github.com/user-attachments/assets/05e62e2e-20cd-4d88-aa18-5f41b4ed989d" />
⚙️ Step 10: Create & Test Lambda Function
<img width="1911" height="627" alt="17_lambda_endpoint_test_function" src="https://github.com/user-attachments/assets/520c652d-5fa8-4962-bf3d-b5ca8e95b647" />
<img width="1746" height="770" alt="18_test_function_overview" src="https://github.com/user-attachments/assets/971a8498-c931-4c2f-874a-385345daa4c9" />
🔐 Step 11: Set Environment Variables
<img width="1772" height="577" alt="19_Configuration_Environment_variables" src="https://github.com/user-attachments/assets/6a4f1725-dda5-4da7-94dd-f8fd0560916b" />
🧬 Step 12: Review Lambda Source Code
<img width="1888" height="852" alt="20_Code_Source" src="https://github.com/user-attachments/assets/b529a925-7e25-49e3-b4f1-692443f11757" />
<img width="1332" height="713" alt="21_Code_Souce_2" src="https://github.com/user-attachments/assets/2723567f-d27b-4fbb-b672-7da7f49dd65f" />
🌐 Step 13: Create S3 Bucket for Hosting
<img width="1620" height="647" alt="22_Amazon_S3" src="https://github.com/user-attachments/assets/ce8ab618-0bf7-4fe5-bd90-619f38f24df3" />
<img width="1855" height="835" alt="23_Amazon_S3_Index_html" src="https://github.com/user-attachments/assets/7fce9a3f-c822-4b9b-b4f5-c953df561f7f" />
🌀 Step 14: Setup CloudFront Distribution
<img width="1896" height="788" alt="24_Cloudfront_distributions_general" src="https://github.com/user-attachments/assets/b5fda53f-e3d6-44c5-820a-486ad0bb929c" />
💻 Step 15: Web App Interface View
<img width="1902" height="1042" alt="25_generative_ai_webapp_interface" src="https://github.com/user-attachments/assets/4140afad-bf25-43bf-85e3-e797296d53fe" />
<img width="1862" height="602" alt="26_generative_ai_webapp_interface" src="https://github.com/user-attachments/assets/514260d1-171d-4cbf-9146-6802985caf02" />
🌐 Step 16: API Gateway Setup
<img width="1862" height="817" alt="27_api_gateway_stage_deployment" src="https://github.com/user-attachments/assets/b89334cf-b4f4-4bb8-a9a8-50cf7eb36829" />
⚠️ Known Issue: Fetch Error in AWS Sandbox

During testing, I encountered a fetch failed error when trying to use the API Gateway endpoint from the hosted frontend.
💡 Root Cause:

This error was caused by sandbox limitations in the AWS Skill Builder environment — specifically:

External API calls (like from a web frontend to API Gateway) are restricted in the sandbox.

The API Gateway + Lambda integration worked inside the AWS Console, but did not respond to browser fetch requests from the deployed frontend.

In a real AWS environment (non-sandbox), this fetch call would work normally once:

CORS is properly configured in the API Gateway stage.

The Lambda function is deployed in the same region with permissions.

API Gateway is made public and not behind private VPC restrictions.
