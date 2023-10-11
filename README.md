# industry-based-Devops-project

⚡𝐏𝐫𝐨𝐣𝐞𝐜𝐭 𝐓𝐢𝐭𝐥𝐞 :
EKS Kubernetes to deploy Jenkins CI/CD tool using Automated way Operator, & manage Jenkins Pipeline as Code by Jenkins Kubernetes CRD & Application jobs launches in dynamic provisioning node our Kubernetes deployment pods and monitoring of infrastructure log by Grafana Loki & Promtail & Metrics by Prometheus Monitoring Tool.

🛠️ 𝐏𝐫𝐨𝐣𝐞𝐜𝐭 𝐎𝐯𝐞𝐫𝐯𝐢𝐞𝐰:
📚 Software delivery pipelines and enhance our infrastructure monitoring capabilities. The goal was clear: automate 𝐉𝐞𝐧𝐤𝐢𝐧𝐬 𝐂𝐈/𝐂𝐃 𝐭𝐨𝐨𝐥 𝐝𝐞𝐩𝐥𝐨𝐲𝐦𝐞𝐧𝐭, manage Jenkins Pipelines as Code, and leverage Kubernetes to dynamically provision nodes for application jobs. Plus, we aimed to gain deep insights into our system through 𝐏𝐫𝐨𝐦𝐞𝐭𝐡𝐞𝐮𝐬 𝐚𝐧𝐝 𝐆𝐫𝐚𝐟𝐚𝐧𝐚 𝐋𝐨𝐤𝐢 🌈.

**Step By Step**
AWS cloud https://aws.amazon.com/

New User / Account : IAM user -> power : policy : admin access

![jn](https://github.com/Anandprati/industry-based-Devops-project/assets/94226733/e7832607-6fc8-4bfd-80de-1c9dafbd2d1d)


password (key) access / secret key

![2](https://github.com/Anandprati/industry-based-Devops-project/assets/94226733/b0c3598b-154a-48b6-8e5b-7529db967c1c)

download : https://docs.aws.amazon.com/cli/latest/userguide/getting-started-install.html
login in CLI # aws configure


![1](https://github.com/Anandprati/industry-based-Devops-project/assets/94226733/ed760149-c333-4c14-b4f8-f3558dbe778d)

**eksctl tool : install kubernetes**

1.Download the kubectl executable from below link
https://dl.k8s.io/release/v1.28.2/bin/windows/amd64/kubectl.exe
Create a folder in your desktop called kubernetes and move the download file to this folder.

![image](https://github.com/Anandprati/industry-based-Devops-project/assets/94226733/08e4b1a4-7e90-4306-aadf-680d0a523c0c)
Now right click on this file, More Options>Properties. Then copy the Location of this file. 

![image](https://github.com/Anandprati/industry-based-Devops-project/assets/94226733/fbd52160-481e-446e-acf4-0408f5305bf1)

![image](https://github.com/Anandprati/industry-based-Devops-project/assets/94226733/8ea592a5-f984-4a23-962a-a337c2c8a07e)

Now click on Environment Variables Again

Select the Path variable and click on EDIT.

![image](https://github.com/Anandprati/industry-based-Devops-project/assets/94226733/68f73840-aeae-4281-b322-df3296d59ffa)
Now click on NEW and paste the Location of kubectl.exe

![image](https://github.com/Anandprati/industry-based-Devops-project/assets/94226733/d32965af-04e5-400e-8c32-5d431f483586)
9.Click OK>OK>Apply.
10.Now open command prompt and you can run 
$ kubectl version

![image](https://github.com/Anandprati/industry-based-Devops-project/assets/94226733/5b4c6a52-21c7-4092-8830-131f792c5fbd)

11.**The installation of kubectl is successful.**




