![](./docs/docs/images/2640-header-dark.png)

# Lab 2640: Create your own AI infused Java apps with Quarkus and LangChain4j

Generative AI has gained significant attention over the past year, and many executive leaders are pushing Java developers to integrate AI into their applications. 
Does this mean we have to abandon what we've built and become data scientists? Not at all. 
Thanks to new projects that simplify the process, we can incorporate AI models developed by experts into our applications without major disruptions. 
Quarkus provides an excellent developer experience, and LangChain4j offers strong AI integration capabilities, so getting started with AI is more straightforward than it might seem. 
This hands-on lab will cover a range of AI features. We’ll begin with the Quarkus DevUI, where you can experiment with AI models before writing any code. 
Then, we’ll dive into coding and explore LangChain4j capabilities, including prompting, chaining, state management, agents, function calling, and retrieval-augmented generation (RAG) for integrating external knowledge. 
We’ll also examine how to run and train models locally using tools like Ollama and Podman AI Lab. Additionally, we’ll discuss observability, fault tolerance, and compiling AI-integrated applications into native binaries. 
Time permitting, we might even try generating images or audio. This lab is an opportunity to learn how to build AI-enhanced Java applications directly from Quarkus experts and engineers working on LangChain4j extensions. 
Attendees can also share feedback with the maintainers of these projects and engage with the community.

**Lab Instructor**
* Daniel Oh / Java Champion | STSM | Senior Principal Developer Advocate Red Hat & IBM
* Don Bourne / STSM - Application Runtimes AI & Technology Incubation Architect, IBM

The workshop is divided into several steps. You can follow the instructions
available in the [workshop
website](https://quarkus.io/quarkus-workshop-langchain4j/). Alternatively,
you may serve the instructions locally by following the [docs/README
file](docs/README.md).

The final state of each step is available in the [step-XX](step-XX) directory.
You can quickly jump to the final state of a step by navigating to the corresponding directory, and then running the following command:

```shell
./mvnw quarkus:dev
```

The application runs on [http://localhost:8080](http://localhost:8080).
