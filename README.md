🚀 Terraform AWS S3 Static Website

Automated deployment of a static portfolio website on Amazon S3 using Terraform (Infrastructure as Code).
This project provisions, configures, and deploys a fully functional static website with public access enabled — completely managed through Terraform.

📌 Project Overview

This project demonstrates:
```
✅ Infrastructure as Code using Terraform
✅ AWS S3 static website hosting
✅ Public access bucket configuration
✅ Automated file uploads (HTML & assets)
✅ Clean Git best practices for DevOps workflows
```
The entire infrastructure is reproducible using Terraform commands.

🛠 Tech Stack
```
*Terraform
*AWS S3
*AWS Provider
*HTML / CSS
*Infrastructure as Code (IaC)
```

📂 Project Structure

```
terraform-aws-s3-static-website/
│
├── main.tf
├── providers.tf
├── variables.tf
├── output.tf
├── .gitignore
├── index.html
├── error.html
└── profile.jpeg

```

⚙️ How to Run This Project
1️⃣ Clone the Repository

    git clone https://github.com/adriannaa-anand/terraform-aws-s3-static-website.git
    cd terraform-aws-s3-static-website

2️⃣ Initialize Terraform

    terraform init

3️⃣ Apply Configuration

    terraform apply

Type yes when prompted.

Terraform will:

Create the S3 bucket
Enable static website hosting
Configure bucket policy
Upload website files
Output the website endpoint

4️⃣ Access the Website

After deployment completes, Terraform outputs:
      website_endpoint = http://your-bucket-name.s3-website-region.amazonaws.com

Open that URL in your browser to view the live website.

🔐 Security & Best Practices

The following files are excluded using .gitignore:

    .terraform/
    *.tfstate
    *.tfstate.*

This prevents:
Large provider binaries
Sensitive Terraform state files
Local machine configuration

🌐 Live Demo

After running terraform apply, access the live website via the S3 website endpoint generated in the output.
      
      http://adria-terraform-website-2026.s3-website-us-east-1.amazonaws.com/

📸 Website Features

   Modern responsive UI
   Animated hero section
   Portfolio project section
   Custom 404 error page
   Clean navigation layout

📚 Key Learning Outcomes

  Through this project, I gained hands-on experience with:
  Infrastructure as Code (IaC)
  Terraform resource management
  AWS S3 static website hosting
  Bucket policies & public access configuration
  Terraform state management
  Git best practices for DevOps projects

🚀 Future Improvements

   Add custom domain using Route 53
   Enable HTTPS using CloudFront
   Configure remote Terraform backend (S3 + DynamoDB)
   Add CI/CD deployment using GitHub Actions

👩‍💻 Author

   Adriannaa Anand
   Cloud & DevOps Enthusiast | MERN Stack Developer

   GitHub: https://github.com/adriannaa-anand

<img width="1917" height="910" alt="terra 1" src="https://github.com/user-attachments/assets/12713a31-4267-451d-8de6-5fed3eef7f2a" />

<img width="1918" height="903" alt="terra 2" src="https://github.com/user-attachments/assets/dab9e485-81f4-4327-8738-b5742b662ed8" />

<img width="1900" height="910" alt="terra 3" src="https://github.com/user-attachments/assets/cba0c276-24cc-4344-a4ed-eb69f23d756a" />
   
<img width="1906" height="971" alt="image" src="https://github.com/user-attachments/assets/dfefc58b-ea52-4862-a00e-b8f689e3c97a" />

<img width="1841" height="916" alt="image" src="https://github.com/user-attachments/assets/3ab42fae-6ad6-4ad6-9e47-ced040336040" />

<img width="1819" height="909" alt="image" src="https://github.com/user-attachments/assets/31506307-1a1d-4400-9c7a-8f7f1d978d91" />

<img width="1850" height="897" alt="image" src="https://github.com/user-attachments/assets/5365b8db-9c29-4480-b840-ca58703d4875" />






