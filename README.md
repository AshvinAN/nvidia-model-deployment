\# NVIDIA Model Deployment Project



🚀 \*\*Project Overview\*\*  

This project showcases the deployment of a PyTorch NLP model using TorchScript and Triton Inference Server, as part of NVIDIA DLI training.



⚙️ \*\*Tech Stack\*\*

\- PyTorch, TorchScript

\- HuggingFace Transformers (XLM-Roberta)

\- Triton Inference Server

\- Docker, Linux CLI



📦 \*\*Features\*\*

\- Exported HuggingFace model using TorchScript

\- Created model repository with `config.pbtxt`

\- Deployed model on Triton Inference Server

\- Sent inference requests and received predictions



📁 \*\*Folder Structure\*\*

models/

└── huggingface-model/

├── 1/

│ └── model.pt

└── config.pbtxt



🧪 \*\*How to Run\*\*

```bash

\# Export the model

python export\_model.py



\# Start Triton server

tritonserver --model-repository=models/



\# Send inference request

python client\_infer.py





📝 What I Learned



How to trace PyTorch models using TorchScript



How to configure and run Triton Server



Hands-on practice with model deployment and inference APIs

