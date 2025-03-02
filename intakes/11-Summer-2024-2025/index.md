# Student Organiser Intake 11 - Summer 2024/2025

This is the list of projects for this intake. Here you will see:
- Summary of the problem and the work done in the project
- Links to the final presentation slides and/or video for the project
- Links to the github repos that were part of this project
- Links to other documentation, such as technical diary and other project documentation
- Links to the project management tool with the tasks shown


# REDMANE Capacity Planning

The challenge that we were trying to solve was ... ipsum dolor sit amet, consectetur adipiscing elit. Phasellus sit amet turpis lacus. Morbi a risus sed nunc venenatis vehicula sed sit amet tortor. Integer leo metus, scelerisque quis gravida quis, laoreet sed nisl. Duis lacus diam, dapibus id orci nec, pellentesque sollicitudin arcu. Vestibulum auctor nec velit sit amet ornare.

The way we tried to solve this was ... lorem mauris, ut suscipit dui porta at. Aenean elementum risus vel interdum condimentum. Nunc massa turpis, bibendum in leo vitae, dapibus cursus urna. Integer placerat lacinia finibus. Etiam vitae dolor ut tortor consectetur ultrices eu eget nisi. Cras neque massa, vestibulum id purus nec, aliquam molestie dolor. Vivamus sollicitudin, orci ut bibendum viverra, quam felis viverra purus, ut consectetur diam turpis quis eros.

What we learned was ... maximus metus id erat pharetra facilisis. Nullam ac urna ultricies diam volutpat faucibus. Sed feugiat placerat est nec scelerisque. Aenean a nisl sit amet ligula gravida fermentum eget in purus. Praesent a dui quis diam bibendum convallis vel in lacus.

## Key links
- Final presentation slides (if supervisor agrees)
- Final presentation video (if supervisor agrees)
- GitHub repos
- Technical Diary
- Weekly Progress
- Project Management Tools

# REDMANE Clinical Dashboards

The challenge that we were trying to solve was how to utilize publicly available clinical metadata while ensuring patient privacy and addressing any potential security concerns while still making the data useful for research. As an example, sensitive data such as: medicare number, date of birth, location of residence, etc, are often included in clinical data. Therefore the solution is to artificially or 'synthetically' generate clinical data that replicates real world datasets.

The way we tried to solve this was by developing code that renamed public clinical data files from cBioportal and randomly sampled a publicly available .fastq fille from genomeInABottle to generate the corresponding fastq files for each patient in the clinical data file. While these files aren’t real genome sequences, they are in the correct fastq format and can be used for other teams' data workflows.

Not only did we learn about methods for generating synthetic clinical data, but we also gained valuable experience in writing clean, maintainable code that integrates seamlessly into larger team workflows. Since our work was being used by multiple intern teams, it was crucial to distribute data efficiently and document our code thoroughly. We quickly realized that clear cross-team communication and well-structured documentation were essential to the success of both our team and others. While we each improved our technical skills, we found that soft skills—such as collaboration and effective communication—were just as critical. Additionally, developing a strong understanding of the high-level context of our work significantly reduced redundancy and saved time, allowing us to make more informed decisions thorughout the internship.

## Key links
- [Final presentation slides](https://wehieduau.sharepoint.com/:p:/r/sites/StudentInternGroupatWEHI/_layouts/15/doc2.aspx?sourcedoc=%7B54B430C0-172F-4A54-8646-4CF8F446454C%7D&file=Final%20Presentation%20Clinical%20Dashboards.pptx&action=edit&mobileredirect=true&DefaultItemOpen=1&ct=1739228756479&wdOrigin=OFFICECOM-WEB.MAIN.REC&cid=f2fec12c-1ef1-4987-9c49-467cf8c62039&wdPreviousSessionSrc=HarmonyWeb&wdPreviousSession=e52534ca-978e-481e-a24e-edf0a5050bbc)
- Final presentation video (tbc)
- [WGS Github](https://github.com/onionsp/Synthetic-WGS-Dataset-Generator)
- [Synthetic Clinical Metadata](https://wehieduau.sharepoint.com/:u:/r/sites/StudentInternGroupatWEHI/Shared%20Documents/Clinical%20Dashboards/2025%20Summer/Finalised%20Dataset/sampled_clinical_data.tsv?csf=1&web=1&e=OKrYwX)
- [Data Transfer Agreement](https://wehieduau.sharepoint.com/:w:/r/sites/StudentInternGroupatWEHI/Shared%20Documents/Clinical%20Dashboards/2025%20Summer/Data%20transfer%20agreement.docx?d=wd1c5e1623f0947469fd0cbc0297010b6&csf=1&web=1&e=nIDFHH)
- [Our Early High Level Understanding](https://wehieduau.sharepoint.com/:w:/r/sites/StudentInternGroupatWEHI/Shared%20Documents/Clinical%20Dashboards/2025%20Summer/Jordan%27s%20Understanding.docx?d=wf77f1ae9648b43559146572142039c8c&csf=1&web=1&e=FiVAIM)
- [Weekly Updates]([https://wehieduau.sharepoint.com/:f:/s/StudentInternGroupatWEHI/Evmt-NPbZ09Lq7WXyYhKohsBdIVREOYRZ2ujDZ1Td6K3HA?e=OtLmDL](https://wehieduau.sharepoint.com/:w:/r/sites/StudentInternGroupatWEHI/_layouts/15/Doc.aspx?sourcedoc=%7B86A2D5F1-8DC5-4272-9ABB-77625B1B79A4%7D&file=Weekly%20Email%20Template.docx&action=default&mobileredirect=true)


# REDMANE Data Ingestion

The challenge that we were trying to solve was ensuring that metadata uploaded to the REDMANE data registry and data portals (specifically cBioPortal) were formatted in standardised ways. Different points of data ingestion required different metadata formats. For example, each data portal has its own specific format for metadata, and without a streamlined way to generate these metadata files, users would struggle to verify and upload their data correctly. This lack of consistency could lead to errors in data ingestion and disorganisation in REDMANE’s database.

We solved a part of this by developing a script for registering files onto the REDMANE data registry. This script scans a specified local directory, extracts relevant metadata, and compiles it into a JSON file summary to be uploaded to the registry. This JSON report ensures that the metadata is ingestible to the registry’s standard, which was designed in collaboration with the REDMANE Web Development team. We also looked at converting our JSON report into RO-Crate.

While we gained technical insights into data organisation, including the importance of aligning data ingestion processes with the needs of both users and system components, our key takeaways were among our soft skills. Our work heavily interlinks with other REDMANE processes, enforcing collaboration between the teams implementing those processes. We found that efficient cross-team communication is necessary to create solutions that work seamlessly across an ecosystem. Beyond that, our experience taught us that a deep understanding is crucial for successful implementation. By first addressing the most challenging aspect—grasping the problem’s context at a high level—we can implement a solution more efficiently.

## Key links
- [Final presentation slides](https://www.canva.com/design/DAGeCN7sfwU/BiPaiieLzAlOUA7QfFOMDg/view?utm_content=DAGeCN7sfwU&utm_campaign=designshare&utm_medium=link2&utm_source=uniquelinks&utlId=h73b2165e9d)
- Final presentation video (tbc)
- GitHub repos
    - [redmane-metadata-generator](https://github.com/jerrilynlooi/redmane-metadata-generator)
    - [redmane_metadata_rocrate](https://github.com/irisgood03/redmane_metadata_rocrate)
    - [REDMANE-metadata-generator-with-RO-Crate](https://github.com/lara-pawar/REDMANE-metadata-generator-with-RO-Crate)
- Technical Diary
    - [Technical Notes.docx](https://wehieduau.sharepoint.com/:w:/s/StudentInternGroupatWEHI/ESlG0_iUA81CkkSlZYijvcgBEqb9SFIf4KXlpCMvEiDQmA?e=DR9qCI)
    - [rocrate_notes.docx](https://wehieduau.sharepoint.com/:w:/s/StudentInternGroupatWEHI/EZq-vx0nvIdDiKFcLxkPhPcBC_C1Xb3tZ8tpNeNr__-Wxw?e=F3pnVz)
    - [Technical Notes - Miro](https://miro.com/app/board/uXjVLwa7vak=/)
    - [Whiteboard Presentation - Miro](https://miro.com/app/board/uXjVL5Zf0kw=/)
- [Weekly Reports Folder](https://wehieduau.sharepoint.com/:f:/s/StudentInternGroupatWEHI/Evmt-NPbZ09Lq7WXyYhKohsBdIVREOYRZ2ujDZ1Td6K3HA?e=OtLmDL)
- Project Management Tools
    - [***WEHI REDMANE Data Ingestion Main Directory***](https://wehieduau.sharepoint.com/:f:/s/StudentInternGroupatWEHI/EoVJAN1pGoNNovVFCqwkXtkBIkFW4fgCr6rXFRkElDylZw?e=2diR2u)

# REDMANE Demo and Quality

The challenge we were trying to solve was bridging the gap between proof-of-concept and production by establishing a permanent demo environment that would ensure long-term availability. This environment was designed to mimic the REDMANE ecosystem, allowing other teams to deploy, test, and refine their code in a controlled setting. Key objectives included creating non-expiring VMs, improving quality control through cross-team collaboration, and providing support for integrating new code into the demo environment.

The way we tried to solve this was by setting up permanent VMs on Nectar Research Cloud and making them externally accessible. We dockerised the data registry, implemented SSL connections, set up a Keycloak instance to manage authentication, and tested using synthetic datasets provided by other teams. Our work also included documenting App Store standards to define the criteria for integrating new data portals into the REDMANE ecosystem.

What we learned through this process extended beyond technical skills to include cross-team collaboration and project coordination. We gained hands-on experience with Docker, CI/CD, Nectar VMs, Keycloak, and security protocols, deepening our understanding of software deployment. Working across teams emphasised the importance of clear communication and alignment, ensuring smooth operation within the REDMANE ecosystem. Additionally, we found that having a high-level understanding of system architecture was crucial for effectively implementing solutions and setting up a cohesive demo environment.

## Key links
- [Final presentation slides](https://wehieduau-my.sharepoint.com/:p:/g/personal/guo_t_wehi_edu_au/EXcCW73RXepOl-VICUIX0NQB4CFd3KMq5emNeM_BWXtEQA?e=2gJ8QV)
- Final presentation video (if supervisor agrees)
- GitHub repos
    - [Keycloak Authentication](https://github.com/varshithmee/redmane-auth)
- Technical Diary
    - [App Store Standards](https://wehieduau-my.sharepoint.com/:w:/g/personal/qamar_j_wehi_edu_au/EQbFymUGnghDqHd3pV60Q0YBjixALU9a_aa4kZ5CDSBgEQ?e=He5hAW) 
    - [Demo Environment Set Up](https://wehieduau.sharepoint.com/:w:/s/StudentInternGroupatWEHI/EXhrXywW5VFEojF9wj-UfBIB23Xhc5CgC3iA7yTxDOX-sw?e=14Kcer)
    - [RStudio Set Up](https://wehieduau.sharepoint.com/:w:/s/StudentInternGroupatWEHI/EWjn0EY-YihOqTSzBMFnaQgBC384g3oY4hFjmu39rhho5g?e=uZFAXs)
    - [Weekly Progress](https://wehieduau.sharepoint.com/:w:/s/redmane_demo_and_quality_team/EXn-vzXEMF1DnkrV_kGRFYUBm84mnEpWPwjSrOm8pLGMJw)
    - [NectarVM setup](https://wehieduau.sharepoint.com/:w:/r/sites/StudentInternGroupatWEHI/_layouts/15/Doc.aspx?sourcedoc=%7B98DE0595-08BD-4168-8CD7-2019AA9AA8D8%7D&file=Instantiating%20Virtual%20Machine%20Instances.docx&action=default&mobileredirect=true)

# REDMANE Omero Data Portal

The challenge we were trying to solve was to adapt OMERO to meet the app store requirements outlined by the Demo and Quality teams. This involved automating OMERO’s deployment, integrating secure OIDC-based authentication for seamless Single Sign-On, and efficiently managing image sample data. Achieving consistent configuration across environments while maintaining robust access control in a research setting demanded a secured and scalable approach, including integrating OMERO into the REDMANE project.

The way we tried to solve this was by developing a Docker Compose script to streamline OMERO’s setup and drafting a conceptual Kubernetes installation guide for scalable container orchestration. We integrated OIDC components to synchronize user data between Auth0 and OMERO, enabling users to bypass redundant logins, while concurrently preprocessing and uploading sample images to simulate real-world data workflows.

What we learned was that there are many approaches to deploying OMERO and configuring access controls to meet app store standards. However, hardware constraints limit our options for deployment and data storage, making it challenging—but not impossible—to find the optimal solution. By comparing various options and consulting with other teams, we can refine our approach. Additionally, involving experts in the field could help streamline the process and reduce the time needed to integrate these solutions effectively.

## Key links
- Final presentation
    - [Final presentation slides](https://wehieduau.sharepoint.com/:p:/s/StudentInternGroupatWEHI/EQDMFvyjL8ZIodoMbt_Ck0YB8oGnsdaqSMqImWet1hnoHg?e=ZboIEc)
    - Final presentation video (if supervisor agrees)
- Whiteboard presentation
    - [Whiteboard presentation video](https://wehieduau.sharepoint.com/:u:/s/StudentInternGroupatWEHI/EVYobuKcom1Aqx_Cj7qawSsBd9UGhS7S_oQvg5zOkQaKxg?e=Jw8ndR)
- GitHub repos
    - [Omero DataPortal](https://github.com/DBK333/Omero-DataPortal)
- Technical Diary
    - [NectarVM Setup](https://wehieduau-my.sharepoint.com/:w:/g/personal/kasikumpaiboon_d_wehi_edu_au/EbuTOVm8MwNDrV3lIGVixukBgTxFFvSCCq3v-POA0LWpyA?e=MdpZDm)
    - [Technical Diary Document](https://wehieduau.sharepoint.com/:w:/s/StudentInternGroupatWEHI/ETlszokWPf5CjFXIE2imaDMBq_HXhHTzAS7nailAALxErQ?e=spjzm2)

# REDMANE Web Dev

The challenge that we were trying to solve was creating a web-based platform for the REDMANE project that facilitates efficient data management and user interaction. The project required a scalable, accessible, and well-integrated frontend and backend infrastructure to support research and development efforts. Additionally, ensuring a smooth development workflow with cloud-based hosting was essential.

The way we tried to solve this was by developing a React-based frontend hosted on a Nectar Virtual Machine (VM), enabling researchers and developers to interact with the system seamlessly. We configured security groups for controlled access, implemented port forwarding to resolve connectivity issues, and deployed the application using Vite for optimal performance. On the backend, we integrated API endpoints to manage authentication, data handling, and application logic, ensuring efficient communication between components.

What we learned was the importance of setting up secure and scalable cloud-based infrastructure to support web applications in a research environment. We gained hands-on experience with Nectar VM configuration, network security management, and optimizing frontend-backend integration for a seamless user experience. Overcoming challenges like port forwarding and deployment issues enhanced our problem-solving skills and deepened our understanding of cloud-hosted web applications.

## Key links
- [Final presentation slides](https://wehieduau.sharepoint.com/:p:/r/sites/StudentInternGroupatWEHI/Shared%20Documents/Data%20Commons/2024%20Semester%202%20Intake%20Final%20Presentation%20Data%20Registry.pptx?d=wa0e62184022149958e1e75afce0d4207&csf=1&web=1&e=2wQOd1)
- Final presentation video (if supervisor agrees)
- GitHub repos
    - [Backend](https://github.com/Morganthium/REDMANE_fastapi/blob/main/app/main.py)
    - [Frontend](https://github.com/alexandra5279/REDMANE_react.js/tree/main/src) 
- Technical Diary
    - [Keycloak Set Up](https://wehieduau.sharepoint.com/:w:/r/sites/StudentInternGroupatWEHI/Shared%20Documents/Data%20Commons/2024%20Semester%202/Authentication/KeyCloak%20Set%20Up.docx?d=we5e013c2b59c409f8775dc21e0f98f26&csf=1&web=1&e=zXw3xv)
    - [Auth0 Set Up](https://wehieduau.sharepoint.com/:w:/r/sites/StudentInternGroupatWEHI/Shared%20Documents/Data%20Commons/2024%20Semester%202/Authentication/Auth0%20Okta%20Set%20Up.docx?d=w0f5fb55e3eed4418b4a9a0c502f5fe94&csf=1&web=1&e=vLQ75F)
    - [Get AAF Access](https://wehieduau.sharepoint.com/:w:/r/sites/StudentInternGroupatWEHI/Shared%20Documents/Data%20Commons/2025%20Summer/Web%20Development/Authenticaiton/AAF%20set%20up.docx?d=wac2a0ab50c1c45ea8bd400eda03ab0bd&csf=1&web=1&e=AEnOQY)
    - [AAF Connection](https://wehieduau.sharepoint.com/:w:/r/sites/StudentInternGroupatWEHI/Shared%20Documents/Data%20Commons/2025%20Summer/Web%20Development/Authenticaiton/AAF%20Connection.docx?d=we099b838cfe54d83b01a8ac9e9f10628&csf=1&web=1&e=RgRQoR)
    - [Integrate Keycloak by Using FastAPI](https://wehieduau.sharepoint.com/:w:/r/sites/StudentInternGroupatWEHI/Shared%20Documents/Data%20Commons/2025%20Summer/Web%20Development/Authenticaiton/Integrate%20keyCloak%20by%20using%20fastapi.docx?d=wb36139e263ee42a997a307bbffe90377&csf=1&web=1&e=0vNWWH)
    - [Set up Keycloak on Nectar VM](https://wehieduau.sharepoint.com/:w:/r/sites/StudentInternGroupatWEHI/Shared%20Documents/Data%20Commons/2025%20Summer/Web%20Development/Authenticaiton/Set%20up%20Keycloak%20on%20the%20Nectar%20VM.docx?d=w661b9e6185ee4e6cb55c2c2a5cc3a3c3&csf=1&web=1&e=rJJde7)
    - [Authentication Demo](https://wehieduau.sharepoint.com/:v:/r/sites/StudentInternGroupatWEHI/Shared%20Documents/Data%20Commons/2025%20Summer/Web%20Development/Authenticaiton/Authentication%20Demo.mp4?csf=1&web=1&e=iLGiGr)
- Weekly Progress

# REDMANE Workflows

The challenge that we were trying to convert the raw data files to processed and summarised files.

The way we tried to solve this was:

***1. Through Nextflow and Seqera on Milton HPC***
We learned about the common workflow used in the bioinformatics field, Nextflow, and gained experience with an open-source pipeline designed for variant mapping called nf-core/sarek. This pipeline allowed us to efficiently process WGS data by identifying genetic variants from sequencing datasets. Additionally, we deployed the pipeline on Seqera and executed it on Milton HPC.    

***2. Through Galaxy***
Galaxy is a user-friendly interface where a lot of bioinformatics tools are available and ready to use.

What we learned include reproducibility and scalability for the two platforms, compared barriers of entry, using both established tools to create workflows and trialing known pipelines. To be able to run Nextflow pipelines using Seqera we explored how to set up the environment on HPC, writing config files, and setting parameters. We've also did the conversion from command line manually using packages like bowtie2, samtools and bcftools. We've also learned how to effectively communicate across teams, sharing files as well as sourcing information about topics we knew less about in daily stand ups and co-working sessions.

We've validated the final output (.vcf files) by visualising it using IGV. 

## Key links
- [Final Presentation Slides](https://www.canva.com/design/DAGewhgcjlc/-93DtMN5HbugyU98Hr0V4A/edit)
- Final presentation video (if supervisor agrees)
- Technical Diary
  - [Tish's Galaxy Workflow](https://usegalaxy.org.au/u/tishtar/w/basic-conversions)
  - [GitHub repos](https://github.com/VitaChien/WEHI_Workflow)
  - [Work Summary](https://wehieduau-my.sharepoint.com/:p:/r/personal/zhao_ch_wehi_edu_au/Documents/Work%20Summary.pptx?d=w3f5a83f7dcb444c0b5e84b955c1282ab&csf=1&web=1&e=oh3yJZ) 
- Weekly Progress
- Project Management Tools

# Student Organiser Data Visualisation

The challenge that we were trying to solve was ... ipsum dolor sit amet, consectetur adipiscing elit. Phasellus sit amet turpis lacus. Morbi a risus sed nunc venenatis vehicula sed sit amet tortor. Integer leo metus, scelerisque quis gravida quis, laoreet sed nisl. Duis lacus diam, dapibus id orci nec, pellentesque sollicitudin arcu. Vestibulum auctor nec velit sit amet ornare.

The way we tried to solve this was ... lorem mauris, ut suscipit dui porta at. Aenean elementum risus vel interdum condimentum. Nunc massa turpis, bibendum in leo vitae, dapibus cursus urna. Integer placerat lacinia finibus. Etiam vitae dolor ut tortor consectetur ultrices eu eget nisi. Cras neque massa, vestibulum id purus nec, aliquam molestie dolor. Vivamus sollicitudin, orci ut bibendum viverra, quam felis viverra purus, ut consectetur diam turpis quis eros.

What we learned was ... maximus metus id erat pharetra facilisis. Nullam ac urna ultricies diam volutpat faucibus. Sed feugiat placerat est nec scelerisque. Aenean a nisl sit amet ligula gravida fermentum eget in purus. Praesent a dui quis diam bibendum convallis vel in lacus.

## Key links
- Final presentation slides (if supervisor agrees)
- Final presentation video (if supervisor agrees)
- GitHub repos
- Technical Diary
- Weekly Progress
- Project Management Tools

# Student Organiser PDF Coding

The challenge that we were trying to solve was the time-consuming nature of reviewing internship applications. This involved downloading and sifting through numerous PDF resumes, extracting key information such as skills, experience, and education, and then comparing these across applicants. The process is not only slow but also prone to human error and can make it difficult to identify suitable candidates.

The way we tried to solve this was by creating a web-based application using HTML, CSS, and JavaScript. The application provides a user interface where PDF files can be uploaded, viewed, and highlighted. The intended goal for the site is to streamline the resume review process, by easily being able to comment on selected text, and add categories relating to it. Additionally, being able to connect this application directly to the student organiser in order to easily open resumes and look at previous comments is ideal. All tasks were intended to be completed using open-source tools and libraries.

What we learned was open-source software can either be of great help or a major obstacle. On one side, many open-source projects have communities built around them, so one might be able to find answers easily with just a Google search. On the other hand, it can be hard to find solutions to your specific problems because of outdated information or bad documentations. However, as they are open-source you can read through the source code to get your answers.

## Key links
- [Final presentation slides](https://www.canva.com/design/DAGeA-99sw8/wu8bETDU_Ioi26iVPz-sQQ/view?utm_content=DAGeA-99sw8&utm_campaign=designshare&utm_medium=link2&utm_source=uniquelinks&utlId=h124da5d634)
- Final presentation video (tbc)
- [GitHub repo](https://github.com/WEHI-RCPStudentInternship/pdf-coder)
- Technical Diary
- [Weekly Progress](https://docs.google.com/document/d/11kn7avo8dtpY5Ho_D7bRSergjQzNMw7Q0_5i4YCggHg/edit?usp=sharing)
- Project Management Tools

# Student Organiser RAG LLM

The challenge that we were trying to solve was the difficult navigation of existing WEHI websites, resources and documentation. As a result of this, student interns and open-source contributors found it difficult to quickly answer even basic questions and needed help from a supervisor to be directed in the right direction. Ultimately, this friction significantly slows down the initial onboarding process and thereby delays the whiteboard presentation to Week 4.

The way we tried to solve this was through a Retrieval-Augmented Generation Large Language Model (RAG LLM). By creating a pipeline that connected the user to a vector database of existing WEHI documentation via an LLM, users should be able to seamlessly input their queries into a chatbot interface and retrieve a brief summary response, supported by sources that informed the answer. This would enable the user to quickly answer their logistical questions and thereby focus on the more complex elements in their projects.

What we learned was there are many moving parts to a RAG LLM, all of which can be independently tuned and modified. There is complexity at every stage of the pipeline, therefore we had to critically make judgement on what technologies to implement given our constraints, objectives and high level context. We are excited to see how future cohorts will take the demos that we have made and hopefully create a production-level RAG LLM solution that can be utilised by subsequent cohorts moving forwards.

## Key links
- [Final presentation slides](https://wehieduau.sharepoint.com/:p:/r/sites/StudentInternGroupatWEHI/Shared%20Documents/RAG%20LLM/RAG%20LLM%20Final%20Presentation%20Slide.pptx?d=w3e265a2e52cf42e4b5b559df800037fd&csf=1&web=1&e=FsTJej)
- Final presentation video
- [GitHub repo (Gemini)](https://github.com/arzmos/student-organiser-rag-llm)
- [GitHub repo (Open-source model)](https://github.com/aaronlai-dev/student-organiser-rag-llm)
- [Technical Diary (Gemini)](https://wehieduau.sharepoint.com/:w:/r/sites/StudentInternGroupatWEHI/Shared%20Documents/RAG%20LLM/Arezoo%20Technical%20Diary%20(Gemini%20Model).docx?d=w2bdb5b3362374e4cb7ab3f4455284b21&csf=1&web=1&e=asJNjy)
- [Technical Diary (Open-source model)](https://wehieduau.sharepoint.com/:w:/r/sites/StudentInternGroupatWEHI/Shared%20Documents/RAG%20LLM/Aaron%20Technical%20Diary%20(Open%20Source%20Model).docx?d=w0406f5e77ca44db0a4df04e640c1dd30&csf=1&web=1&e=ishjKh)
- [Weekly Progress](https://wehieduau.sharepoint.com/:f:/r/sites/StudentInternGroupatWEHI/Shared%20Documents/RAG%20LLM/Weekly%20Reports%20and%20diaries?csf=1&web=1&e=FKfX5A)

# Quantum Computing

The challenge that we were trying to solve was ... ipsum dolor sit amet, consectetur adipiscing elit. Phasellus sit amet turpis lacus. Morbi a risus sed nunc venenatis vehicula sed sit amet tortor. Integer leo metus, scelerisque quis gravida quis, laoreet sed nisl. Duis lacus diam, dapibus id orci nec, pellentesque sollicitudin arcu. Vestibulum auctor nec velit sit amet ornare.

The way we tried to solve this was ... lorem mauris, ut suscipit dui porta at. Aenean elementum risus vel interdum condimentum. Nunc massa turpis, bibendum in leo vitae, dapibus cursus urna. Integer placerat lacinia finibus. Etiam vitae dolor ut tortor consectetur ultrices eu eget nisi. Cras neque massa, vestibulum id purus nec, aliquam molestie dolor. Vivamus sollicitudin, orci ut bibendum viverra, quam felis viverra purus, ut consectetur diam turpis quis eros.

What we learned was ... maximus metus id erat pharetra facilisis. Nullam ac urna ultricies diam volutpat faucibus. Sed feugiat placerat est nec scelerisque. Aenean a nisl sit amet ligula gravida fermentum eget in purus. Praesent a dui quis diam bibendum convallis vel in lacus.

## Key links
- Final presentation slides (if supervisor agrees)
- Final presentation video (if supervisor agrees)
- GitHub repos
- Technical Diary
- Weekly Progress
- Project Management Tools

# To update this file

Go to [Github and fork this repo, make changes, and then do a pull request back to the original repo. This is the file you need](https://github.com/WEHI-ResearchComputing/WEHI-ResearchComputing.github.io/tree/main/intakes/11-Summer-2024-2025).
