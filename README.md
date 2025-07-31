# Code-Review-System
It is a code review system which tells us where we need a manual review or not 
–	Built classifier using CodeBERT, DistilBERT, Qwen 14B to classify whether human review required    
–	Fine tuned models on large scale microsoft open source dataset (328K samples) , ensuring high performance across multiple languages including java, python, cpp etc
–	optimized CI/CD pipelines by implementing a binary classification method to reduce human review overhead
–	Achieved 90.7%+ F1 Score using ensemble techniques
