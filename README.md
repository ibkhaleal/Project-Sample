[![License](https://img.shields.io/badge/License-Apache2-blue.svg)](https://www.apache.org/licenses/LICENSE-2.0) [![Community](https://img.shields.io/badge/Join-Community-blue)](https://developer.ibm.com/callforcode/solutions/projects/get-started/)
# AgriAccess/Farm360

- [Project summary](#project-summary)
  - [The issue we are hoping to solve](#the-issue-we-are-hoping-to-solve)
  - [How our technology solution can help](#how-our-technology-solution-can-help)
  - [Our idea](#our-idea)
- [Technology implementation](#technology-implementation)
  - [IBM AI service(s) used](#ibm-ai-services-used)
  - [Other IBM technology used](#other-ibm-technology-used)
  - [Solution architecture](#solution-architecture)
- [Presentation materials](#presentation-materials)
  - [Solution demo video](#solution-demo-video)
  - [Project development roadmap](#project-development-roadmap)
- [Additional details](#additional-details)
  - [How to run the project](#how-to-run-the-project)
  - [Live demo](#live-demo)
- [About this template](#about-this-template)
  - [Contributing](#contributing)
  - [Versioning](#versioning)
  - [Authors](#authors)
  - [License](#license)
  - [Acknowledgments](#acknowledgments)

_INSTRUCTIONS: Complete all required deliverable sections below._

## Project summary

### The issue we are hoping to solve

The issue we are hoping to solve is food security, which remains a pressing global challenge. Our solution aims to empower farmers with AI-driven assistance, helping them farm efficiently, store and preserve produce, and respond to crop-threatening weather conditions, ultimately contributing to a more secure and sustainable food supply.

### How our technology solution can help

Our solution empowers farmers with AI assistance for sustainable agriculture.

### Our idea

# mpowering Farmers for Sustainable Agriculture

## The Real-World Problem

The global challenge of food security has become increasingly critical with a growing population and unpredictable weather patterns. It's becoming more challenging for farmers to produce and store food efficiently. Smallholder farmers, in particular, often lack access to the knowledge and tools needed to address these issues effectively.

## Our Technological Solution

Our innovative approach harnesses the power of artificial intelligence (AI) to provide farmers with a comprehensive and user-friendly assistant that guides them through every stage of the agricultural process. Our solution is accessible via mobile devices and web platforms, making it widely accessible. Here's how it works:

1. **Farming Guidance:** The AI assistant offers farmers real-time guidance on planting schedules, irrigation, and pest control. It takes into account local climate data and the specific crops being grown, providing tailored advice to optimize yield and resource use.

2. **Weather Monitoring:** The assistant continuously tracks weather conditions in the farmer's region. When adverse weather is predicted, such as heavy rain, drought, or frost, it sends immediate alerts to help farmers take necessary precautions to protect their crops.

3. **Crop Monitoring:** Farmers can use their smartphones to take pictures of their crops, which the assistant analyzes to identify signs of disease, pest infestations, or nutrient deficiencies. It then provides recommendations for treatment.

4. **Harvesting and Storage Guidance:** The assistant advises farmers on the best time to harvest their crops to maximize freshness and nutritional content. It also offers storage recommendations to prolong shelf life and reduce waste.

5. **Product Quality Assessment:** Farmers can interact with the assistant to assess the quality of their stored produce. By providing information about the condition of their crops, they can make informed decisions on when to sell or use their produce.

6. **Warehouse Locator:** If farmers need additional storage space, the assistant helps them find the nearest warehouses available for rent. It provides information about their capacity, rates, and available services.

## How It's an Improvement

Our solution represents a significant improvement over existing solutions for several reasons:

- **Comprehensive Farming Guidance:** Our AI assistant provides end-to-end support, from planting to storage, integrating critical aspects of farming that traditional solutions often overlook.

- **Personalized Recommendations:** By tailoring advice based on local climate and crop data, we ensure that the recommendations are highly relevant to each farmer's specific needs, optimizing resource use and crop yield.

- **Timely Alerts:** The assistant monitors weather conditions and sends immediate alerts, helping farmers mitigate crop damage in real-time.

- **Crop Health Assessment:** Our solution can analyze images of crops for signs of disease, pest infestations, and nutrient deficiencies, allowing for early intervention and reduced crop loss.

- **Proactive Quality Assessment:** Farmers are prompted to assess the quality of their stored produce, preventing waste and ensuring product quality.

- **Warehouse Locator:** We connect farmers to available storage facilities, addressing the challenge of post-harvest losses due to lack of adequate storage.

Our solution not only empowers farmers to make informed decisions, but it also contributes to sustainable agriculture by reducing resource wastage and enhancing food security. By utilizing the power of AI, we aim to provide smallholder farmers with the tools and knowledge they need to thrive in an increasingly challenging environment.

For additional documentation, including technical specifications and code samples, please refer to our [source code repository](link-to-repository).


More detail is available in our [description document](./docs/DESCRIPTION.md).

## Technology implementation

### IBM AI service(s) used

_INSTRUCTIONS: Included here is a list of commonly used IBM AI services. Remove any services you did not use, or add others from the linked catalog not already listed here. Leave only those included in your solution code. Provide details on where and how you used each IBM AI service to help judges review your implementation. Remove these instructions._

- [IBM Natural Language Understanding](https://cloud.ibm.com/catalog/services/natural-language-understanding) - WHERE AND HOW THIS IS USED IN OUR SOLUTION
- [Watson Assistant](https://cloud.ibm.com/catalog/services/watson-assistant) - WHERE AND HOW THIS IS USED IN OUR SOLUTION
- [Watson Discovery](https://cloud.ibm.com/catalog/services/watson-discovery) - WHERE AND HOW THIS IS USED IN OUR SOLUTION
- [Watson Speech to Text](https://cloud.ibm.com/catalog/services/speech-to-text) - WHERE AND HOW THIS IS USED IN OUR SOLUTION
- [Watson Text to Speech](https://cloud.ibm.com/catalog/services/text-to-speech) - WHERE AND HOW THIS IS USED IN OUR SOLUTION
- List any additional [IBM AI services](https://cloud.ibm.com/catalog?category=ai#services) used or remove this line

### Other IBM technology used

INSTRUCTIONS: List any other IBM technology used in your solution and describe how each component was used. If you can provide links to/details on exactly where these were used in your code, that would help the judges review your submission.

### Solution architecture

Diagram and step-by-step description of the flow of our solution:

![Video transcription/translaftion app](https://developer.ibm.com/developer/tutorials/cfc-starter-kit-speech-to-text-app-example/images/cfc-covid19-remote-education-diagram-2.png)

1. The user navigates to the site and uploads a video file.
2. Watson Speech to Text processes the audio and extracts the text.
3. Watson Translation (optionally) can translate the text to the desired language.
4. The app stores the translated text as a document within Object Storage.

## Presentation materials

_INSTRUCTIONS: The following deliverables should be officially posted to your My Team > Submissions section of the [Call for Code Global Challenge resources site](https://cfc-prod.skillsnetwork.site/), but you can also include them here for completeness. Replace the examples seen here with your own deliverable links._

### Solution demo video

[![Watch the video](https://raw.githubusercontent.com/Liquid-Prep/Liquid-Prep/main/images/readme/IBM-interview-video-image.png)](https://youtu.be/vOgCOoy_Bx0)

### Project development roadmap

The project currently does the following things.

- Feature 1
- Feature 2
- Feature 3

In the future we plan to...

See below for our proposed schedule on next steps after Call for Code 2023 submission.

![Roadmap](./images/roadmap.jpg)

## Additional details

_INSTRUCTIONS: The following deliverables are suggested, but **optional**. Additional details like this can help the judges better review your solution. Remove any sections you are not using._

### How to run the project

INSTRUCTIONS: In this section you add the instructions to run your project on your local machine for development and testing purposes. You can also add instructions on how to deploy the project in production.

### Live demo

You can find a running system to test at...

See our [description document](./docs/DESCRIPTION.md) for log in credentials.

---

_INSTRUCTIONS: You can remove the below section from your specific project README._

## About this template

### Contributing

Please read [CONTRIBUTING.md](CONTRIBUTING.md) for details on our code of conduct, and the process for submitting pull requests to us.

### Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/your/project/tags).

### Authors

<a href="https://github.com/Call-for-Code/Project-Sample/graphs/contributors">
  <img src="https://contributors-img.web.app/image?repo=Call-for-Code/Project-Sample" />
</a>

- **Billie Thompson** - _Initial work_ - [PurpleBooth](https://github.com/PurpleBooth)

### License

This project is licensed under the Apache 2 License - see the [LICENSE](LICENSE) file for details.

### Acknowledgments

- Based on [Billie Thompson's README template](https://gist.github.com/PurpleBooth/109311bb0361f32d87a2).
