# Federated-Learning
A part of my Master's Thesis on Gradient Leakage Proof Federated Collaborative Filtering

This explains the initial user-level split of the data, training the Federated Collaborative Filtering model along with using Homomorphic Encryption to prevent gradient leakage

NOTE - This is only about 1/6th of the code for the entire project, but the one that's the most interesting part so there might be some issues with running it because of dependencies on other parts of the project or libraries you might need to install.

The encryption takes a few days of running the code on a standard laptop with 16 GB of RAM and an NVDIA RTX 2090 GPU (although the encryption itself doesn't utilize the GPU and uses CPU instead simply because of the nature of the low level interactions. 

Partially homomorphic encryption provided by (https://github.com/data61/python-paillier library)

E-mail rb622@njit.edu for any questions! I'm currently open for exciting opportunites in data science!
