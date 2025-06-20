# AI Software Template Gitops

This repository contains the necessary content required for managing GitOps. It was created as part of an AI Software Template. The associated source component is available for reference in the **Overview** tab. You can find an example of this reference in the following image.

![Overview Tab](./images/overview-dependency.png)

# Deployed Resources
Based on the input from the AI Software Template, a deployment with the following characterisics was made:

# Model Server
**Model Server:** [llama.cpp]( https://github.com/redhat-ai-dev/developer-images/tree/main/model-servers/llamacpp_python/0.3.8)

**Port:** 8001

# Application
An application built from https://github.com/mvaldron-rhdh/chatbot-test-app-25 will be stored in [quay.io/mvaldron-rhdh/chatbot-test-app-25](https://quay.io/mvaldron-rhdh/chatbot-test-app-25) and deployed through GitOps. This application is accessible on port **8501**.