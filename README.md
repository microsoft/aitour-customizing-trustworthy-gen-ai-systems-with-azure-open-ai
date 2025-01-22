# The Foundation of Generative AI in Azure

This repo is intended as a template for Microsoft AI Tour repositories
<br />
<img src="https://github.com/cole-g-johnson/Interacting-With-LLMs/blob/main/LAB/assets/stack.png" width="400" />
<br />

## Session Desciption

Discover the world of generative AI in Azure! We'll take a look at the newest multimodal models, like GPT-4o and Phi-3. You'll learn how these models work, what they are capable of, and how you can use them in your projects. We'll also give you a tour of the Azure AI ecosystem, showing you the different services available to help you start building your own custom copilots.​

## Learning Outcomes
1. Showcase latest and greatest models available in Azure AI, so developers know what they can use.​

2. Teach how LLM’s work and their capabilities, so developers understand how and when to use them.​

3. Show real-world use cases for LLMs, so developers are sparked with idea’s where to implement LLMs.​

4. Zoom out and show the Azure AI ecosystem, so developers are aware of all the different tools and services, like Azure AI Speech and Florence, they can leverage.​

## Technology Used
1. Azure AI Studio or Azure OpenAI Studio​

2. Speech Studio​

3. Azure OpenAI Service (LLMs)​

4. Phi-3 (SLMs)​

## Additional Resources and Continued Learning

| Resources          | Links                             | Description        |
|:-------------------|:----------------------------------|:-------------------|
| Future Learning 1  | [Link 1](https://www.google.com/) | Learn more about X |
| Future Learning 2  | [Link 2](https://www.google.com/) | Learn more about Y |

## Content Owners

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->

<table>
<tr>
    <td align="center"><a href="https://github.com/cole-g-johnson">
        <img src="https://github.com/cole-g-johnson.png" width="100px;" alt="Cole Johnson"/><br />
        <sub><b>Cole Johnson</b></sub>
    </a><br />
    </td>
</tr></table>

<!-- ALL-CONTRIBUTORS-LIST:END -->

## Responsible AI
Microsoft is committed to helping our customers use our AI products responsibly, sharing our learnings, and building trust-based partnerships through tools like Transparency Notes and Impact Assessments. Many of these resources can be found at [https://aka.ms/RAI](https://aka.ms/RAI). Microsoft’s approach to responsible AI is grounded in our AI principles of fairness, reliability and safety, privacy and security, inclusiveness, transparency, and accountability.

Large-scale natural language, image, and speech models - like the ones used in this sample - can potentially behave in ways that are unfair, unreliable, or offensive, in turn causing harms. Please consult the [Azure OpenAI service Transparency note](https://learn.microsoft.com/legal/cognitive-services/openai/transparency-note?tabs=text) to be informed about risks and limitations.

The recommended approach to mitigating these risks is to include a safety system in your architecture that can detect and prevent harmful behavior. [Azure AI Content Safety](https://learn.microsoft.com/azure/ai-services/content-safety/overview) provides an independent layer of protection, able to detect harmful user-generated and AI-generated content in applications and services. Azure AI Content Safety includes text and image APIs that allow you to detect material that is harmful. Within Azure AI Studio, the Content Safety service allows you to view, explore and try out sample code for detecting harmful content across different modalities. The following [quickstart documentation](https://learn.microsoft.com/azure/ai-services/content-safety/quickstart-text?tabs=visual-studio%2Clinux&pivots=programming-language-rest) guides you through making requests to the service.

Another aspect to take into account is the overall application performance. With multi-modal and multi-models applications, we consider performance to mean that the system performs as you and your users expect, including not generating harmful outputs. It's important to assess the performance of your overall application using [Performance and Quality and Risk and Safety evaluators](https://learn.microsoft.com/azure/ai-studio/concepts/evaluation-metrics-built-in). You also have the ability to create and evaluate with [custom evaluators](https://learn.microsoft.com/azure/ai-studio/how-to/develop/evaluate-sdk#custom-evaluators).

You can evaluate your AI application in your development environment using the [Azure AI Evaluation SDK](https://microsoft.github.io/promptflow/index.html). Given either a test dataset or a target, your generative AI application generations are quantitatively measured with built-in evaluators or custom evaluators of your choice. To get started with the azure ai evaluation sdk to evaluate your system, you can follow the [quickstart guide](https://learn.microsoft.com/azure/ai-studio/how-to/develop/flow-evaluate-sdk). Once you execute an evaluation run, you can [visualize the results in Azure AI Studio](https://learn.microsoft.com/azure/ai-studio/how-to/evaluate-flow-results).


