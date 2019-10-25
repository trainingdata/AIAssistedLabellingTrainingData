# Documentation

+ [Overview](#overview)
  + [Complete Feature Set](#complete-feature-set)
  + [FAQ](#faq)
  + [Overview](#overview)
  + [Quality Management](#quality-management)
  + [Security and Privacy](#security-and-privacy)



# Overview


# Complete Feature Set
At TrainingData.io, we believe quality of the machine learning model is dependent on the quality of labelling. We empower data-scientists to control the quality of data labelling in the following ways:
## Segmentation and Classification
[/block]
TD.io's application supports following types of annotation work:
1. Segmentation only
2. Classification only
3. Segmentation with Classification.
[block:api-header]
{
  "title": "Pixel Accurate Tools"
}
[/block]
We use advanced image processing to provide pixel accurate tools like
1. [Superpixel-segmentation](https://trainingdata.readme.io/docs/segmentation-tool) with brush and eraser,
2. [Polygon](https://trainingdata.readme.io/docs/polygon-tool) with advanced editing, bounding box, 
3. [Freehand-draw with sculpter](https://trainingdata.readme.io/docs/freehand-draw), and
4. Region of Interest (ROI) growth tool.
[block:api-header]
{
  "title": "AI Assisted Annotation"
}
[/block]
1. AI Assisted Annotation using Data-scientist's ML model
2. AI Assisted Annotation using NVIDIA Clara

[block:api-header]
{
  "title": "Data Security and Privacy Controls"
}
[/block]
On-premises hosting of datasets and annotation tools using Docker and VPN.
[block:api-header]
{
  "title": "Collaboration: Annotator's Performance Management"
}
[/block]
1. Measure, record and analyze annotator's performance on every individual task, asset and label.
2. Compare performance of multiple annotators on same task.
3. Distribute labeling work among multiple labelers and observe consensus among their work.
4. Seed annotation tasks with golden data set. Report performance of annotator on golden data set.
[block:api-header]
{
  "title": "Labeling Instruction Builder"
}
[/block]
[Labeling instruction builder](https://trainingdata.readme.io/docs/define-json) empowers data scientist to define user experience of annotators in fine-detail:
1. Labeling classes and ontology can be defined in fine-detail.
2. WYSIWYG instruction builder enables  data-scientist to view how labeling interface appears to the annotator.

We believe the quality of work performed by annotators depends on the quality of user experience in annotation tools. We build intuitive user experience for annotators.
[block:api-header]
{
  "title": "WorkForce: Humans-in-the-Loop"
}
[/block]
We partner with highest quality workforce from around the world.
# FAQ
**General Questions**
**What is TrainingData.io?**
TrainingData.io application is a AI training-data management platform. Our goal is to  empower data science team to control the training data management workflow.

**What is Data annotation?**
In order to train machines to make decisions on behalf of humans, they must learn to make those decisions. In order to learn about the world around us, machines take input in form of images and text that is labeled for representative features. A label in an image is clearly marked bounding region that represents a real world entity or object. Managing data labeling at very large scale is time consuming and requires special software.

**What can I annotate with TrainingData.io application?**
With our labeling solution you can label any visual dataset including images and videos. We support medical imaging format - DICOM. 

**What kind of data formats are supported by TrainingData.io? **
Our annotation tools support JPEG, PNG, DICOM, mov, avi, mp4, zip, tar, gz

**How Trainingdata.io application will help my data science team deploy Machine Learning/Artificial Intelligence?**
Trainingdata.io is a place where you can start small and scale-up your data management operations with time. We help you manage early-stage AI projects with internal stakeholders. Once your are ready to scale operations we connect you with human-labelers outside your organization. We help you control quality of work produced by third-party human labelers. This helps you improve quality of your machine learning models at fast pace and at fraction of cost. 

****

**How is Trainingdata.io different from managed labeling services?**
Managed Labeling services produce error rates as high as 65%. This is due to low quality and inconsistency of labeling tools. Quality of labels produced by workforce depends on quality of user experience for the human labelers. We empower data science team to control user-experience of human labelers. 

What sets us apart is our focus on:
1. Pixel accurate annotation tools
2. Customizable labeling interface for every task
3. Quality and performance management
4. Data security and privacy protection with on-premises solution.

Compare the two workflows in image below:

**Old (current) Work Flow**
[block:image]
{
  "images": [
    {
      "image": [
        "https://files.readme.io/4108b7a-CurrentWorkflow.png",
        "CurrentWorkflow.png",
        1182,
        654,
        "#f0f0e8"
      ],
      "caption": "Old Work Flow"
    }
  ]
}
[/block]
**New Work Flow**
[block:image]
{
  "images": [
    {
      "image": [
        "https://files.readme.io/2bbda76-NewWorkflow.png",
        "NewWorkflow.png",
        1096,
        650,
        "#e3f2eb"
      ],
      "caption": "New Work Flow"
    }
  ]
}
[/block]
**How do I get started with Trainingdata.io application?**
You can sign up at [login page](https://app.trainingdata.io/v1/td/login).

**Does Trainingdata.io provide support?**
Trainingdata.io provides support to all users. 

**Does TrainingData.io have a discount for academic users?**
Yes, we do

**I have my data annotated by a service. Why would I use TrainingData.io?**
With TrainingData.io you can still outsource your annotating projects as well as leverage your internal team on those same projects. The big differentiator is that with TrainingData.io you can manage the quality and performance of your entire annotating team whether they are outsourced or internal, all in one place.

TrainingData.io does not provide in-house annotating services but we do work with several annotating companies (BPO Firms) that we have vetted and currently work with many of our customers in TrainingData.io. We simply recommend them as a third party to help our customers so you are always free to choose any annotating services company that meets your requirements.

**My company built an internal labeling tool that seems to work okay. Why would I use TrainingData.io?**
It's quick and easy to start annotating data using locally installed tools. For most simple annotation tasks being performed by a single annotator, this solution architecture annotates well. As data annotation needs scale, data management and quality control processes are needed to produce accurate and consistent training data. A common cause of under performing AI systems is low accuracy training data.

**When building data labeling infrastructure, consider the following:**

  * Total Cost of Ownership
Homegrown tools are built to exist and serve a particular function, but with new business, demands come to the cost of upgrades. There is a high cost of ongoing maintenance, both in time and money. Technical debt accrues over time due to engineer turn-over, product neglect, and evolving product demands.

  * Unknown and Evolving Scope
Developing an internal product requires planning, resource allocation, and preparing for the unknown. Because feature flagging platforms are relatively new, it can be difficult to accurately define the scope and construct a solution for needs across engineering and product groups.

  * Minimum Viable Functionality
Internal tools are generally not built for usability, scalability, or cross-team support. They are built to solve an immediate pain point or provide minimum viable functionality as quickly as possible.

  * Data Labeling is Cross Functional
Turning raw data into accurate and consistent training data is a team effort. Engineers, domain experts (annotators), and managers must work together while playing different roles. Data annotation infrastructure must facilitate this by providing information and interfaces unique to these roles.

  * Enterprise Readiness
Productizing AI systems takes fast, reliable, and scaled infrastructure across raw data collection, data labeling, and compute.

**Will TrainingData.io improve the quality and consistency of my labeled data?**
This is one of our core competencies and one of the main reasons we decided to build TrainingData.io application. We saw that all the available options for annotating made it extremely difficult to ensure our training data was high enough in quality for a production-ready machine learning model and it cost us valuable time and money in the end. We developed a world-class quality and performance management interface within our platform to address this.

**Annotation Questions**
**How do I setup a project?**
You can set up a project in three steps:
1. Click “Add Project” and give the project a name.
2. Attach your data set to the project.
3. Customize your labeling interface.
4. Start Labeling!

**Does TrainingData.io work with Cloud buckets data such as Amazon S3 or Google Cloud Storage?**
Check out our guide for Connecting Cloud Data.

**How do I revisit skipped or submitted labels?**
You can do this by Re-Enqueuing them from the Activity Tab. For a guide on Re-Enqueuing labels click here

**Does TrainingData.io work with on-premises data?**
TrainingData.io works with source data hosted on-premises or on a private cloud. The source data is accessed directly from the client computer and never shared (or accessible) by TrainingData.io. Check out our guide here.

**Does TrainingData.io work on mobile devices?**
We do not currently support mobile devices, although we are working on adding this in the future.

**Can I annotate on an iPad?**
Yes .

**Does Trainingdata.io work in all countries?**
Yes, unless your network has a restrictive firewall, or you have internet connectivity issues. We currently only support the English language on our platform.

**Does Trainingdata.io application work without an internet connection?**
No, you must have an internet connection to use trainingdata.io application.

**What browser do you recommend for trainingdata.io application?**
We recommend Chrome. We do not recommend Internet Explorer or Safari due to compatibility issues.

**What formats can I export my annotated data?**
Your annotated data can be exported in JSON, Mask and PNG which should allow  you to import it into any machine learning framework.

**How does Auto Consensus work?**
Auto Consensus ensures consistency and accuracy of the labeled data. When turned on, some or all of the images are labeled by more than one labeler so that a consensus among labelers for each labeled datum can be calculated and ultimately managed. You can configure the percentage of your dataset in a project that will be randomly selected to be labeled more than once by distinct collaborators. You can also configure the number of times this percentage of labels will be labeled. Check out our docs here for more detail.

**Will other labelers see the same data that I'm labeling?**
If Auto Consensus is turned on and configured then yes, otherwise no.

**Does TrainingData.io have an API?**
Yes, we have a fully featured API. Everything you can do with our interface, you can do programmatically through our API. The API is available on our Enterprise tier. You may contact sales at https://trainingdata.io/contact.

If you are a paid user you may request an API key from our support team via the Chat icon (preferred method) or by sending an email to info@trainingdata.io, and title it "API Request".*

**I already have training data. Can I import it into Trainingdata.io application?**
Yes, it can be imported. Simply send us the annotated data and we will reformat it and upload it for you.

**How do I delete a project?**
Open your project then go to settings > Other, and click on the delete button.*
# Overview
TrainingData.io application provides high precision training data labeling for Visual AI. Our SaaS solution uses AI assisted features to give machine learning engineers speed up of several orders of magnitude. Our goal is to "empower data scientists to control quality of training data"
[block:api-header]
{
  "title": "Key Benefits"
}
[/block]
1. High precision labeling tool with Superpixel segmentation, AI-assisted labeling, and active-learning.
2. Custom labeling instructions for every task - delivers productivity enhancing user-experience for annotators.
3. Data security and privacy protection using On-premises, In-cloud or hybrid hosting. (using Docker and VPN)
4. Collaboration with multiple annotator's on same task.
5. Annotator performance and quality management workflow.
6. AI-Assisted annotation using existing ML models.
7. Out of the box support for medical imaging (DICOM).

[block:image]
{
  "images": [
    {
      "image": [
        "https://files.readme.io/2020847-NewWorkflow.png",
        "NewWorkflow.png",
        1096,
        650,
        "#e3f2eb"
      ],
      "caption": "Key Benefits of TrainingData.io"
    }
  ]
}
[/block]

[block:image]
{
  "images": [
    {
      "image": [
        "https://files.readme.io/39f6721-CurrentWorkflow.png",
        "CurrentWorkflow.png",
        1182,
        654,
        "#f0f0e8"
      ],
      "caption": "Old Workflow"
    }
  ]
}
[/block]

[block:api-header]
{
  "title": ""
}
[/block]
#[Click Here For Complete Feature Set](https://trainingdata.readme.io/docs/full-feature-set)
# Quality Management
At TrainingData.io, we believe, quality of the machine learning model is entirely dependent on the quality of labeling for training data. We help you control quality of data labeling in following ways:
[block:api-header]
{
  "title": "Annotator's Performance Management"
}
[/block]
1. Measure, record and analyze annotator's performance on every individual task, asset and label.
2. Compare performance of multiple annotators on same task.
3. Distribute labeling work among multiple labelers and observe consensus among their work.
4. Seed annotation tasks with golden data set. Report performance of annotator on golden data set.
[block:api-header]
{
  "title": "Pixel Accurate tools"
}
[/block]
1. We use advanced image processing to build pixel accurate tools like segmentation, freehand, growth tools.
2. Build high quality user experience for annotators that allows then to do high quality work at fast pace.
3. Enable smooth collaboration between annotators and data-scientists.
[block:api-header]
{
  "title": "State of the art User Experience (UX)"
}
[/block]
1. TD.io believes quality of work performed by annotators depends on quality of user experience in annotation tools
2. We build intuitive user experience for annotators.
[block:api-header]
{
  "title": "Labeling Instruction Builder"
}
[/block]
1. Empowering data scientist to take control user experience of annotators.
2. Labeling classes and ontology needs to be defined in detail.
3. Data scientist needs precise view of how labeling interface appears to the annotator.
# Security and Privacy
At TrainingData.io we take data security and privacy very seriously. 

We allow you to log in to TrainingData.io application using the same identity provider that you use for other services.

# Data Security
We allow data owners to control who accesses their data. Each annotator's (internal or external) activity is recorded and they are not allowed to download training data. We allow data owners to see complete access log of every collaborator's activity. 

# Single Sign-On
TrainingData.io supports single sign-on (SSO), which allows you to log in to TrainingData.io application using the same identity provider that you use for other services.

# On Premises Solution
We  provide our labeling software as Docker image, it can run as hosted solution in your network. Hosted version of annotation tool can access images that are hosted on local machine, images hosted on local web-server or images hosted in cloud. All training data and resulting labels are saved on local infrastructure. Only project definition sits in cloud.

[block:image]
{
  "images": [
    {
      "image": [
        "https://files.readme.io/819bde1-Docker.png",
        "Docker.png",
        884,
        338,
        "#096297"
      ],
      "caption": "On-Prem Solution using Docker Container and VPN"
    }
  ]
}
[/block]
# Cloud Hosted Solution
You can upload your assets (images and videos) to our cloud. Our cloud is secure with equivalent of HIPAA compliance. (We sign BAA agreement if needed).

# Hybrid Solution
We offer hybrid solution where annotation tool is installed on local infrastructure as Docker instance. Training data is hosted in cloud.
