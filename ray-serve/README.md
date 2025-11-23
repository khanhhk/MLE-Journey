Ray is an open source unified framework for scaling AI and Python applications. It provides a simple, universal API for building distributed applications that can scale from a laptop to a cluster.

# What’s Ray?
Ray simplifies distributed computing by providing:

- Scalable compute primitives: Tasks and actors for painless parallel programming

- Specialized AI libraries: Tools for common ML workloads like data processing, model training, hyperparameter tuning, and model serving

- Unified resource management: Seamless scaling from laptop to cloud with automatic resource handling

# Ray Serve: Scalable and Programmable Serving
![](images/ray-serve.svg)
Ray Serve is a scalable model serving library for building online inference APIs. Serve is framework-agnostic, so you can use a single toolkit to serve everything from deep learning models built with frameworks like PyTorch, TensorFlow, and Keras, to Scikit-Learn models, to arbitrary Python business logic. It has several features and performance optimizations for serving Large Language Models such as response streaming, dynamic request batching, multi-node/multi-GPU serving, etc.

Ray Serve is particularly well suited for model composition and multi-model serving, enabling you to build a complex inference service consisting of multiple ML models and business logic all in Python code.

Ray Serve is built on top of Ray, so it easily scales to many machines and offers flexible scheduling support such as fractional GPUs so you can share resources and serve many machine learning models at low cost.

# Quickstart