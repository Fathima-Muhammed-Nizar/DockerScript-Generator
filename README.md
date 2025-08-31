# DockerScript-Generator

A GenAI powered tool that generates optimized Dockerfiles based on programming language input. This project uses Ollama with the Llama3 model to create Dockerfiles following best practices  

# How It Works
1.The script takes a programming language as input (e.g., Python, Node.js, Java)  
2.Connects to the Ollama API running locally  
3.Generates an optimized Dockerfile with best practices for the specified language  
4.Returns the Dockerfile content with explanatory comments  

# Prerequisites
Download and Install Ollama  
Start Ollama Service  
Pull Llama3 Model  

# Example Usage
python3 generate_dockerfile.py  
Enter programming language: python  
Generated Dockerfile will be displayed...  
