### **Binary Classification for Intrusion Detection with MLP in PyTorch**

---

#### **Overview**
This project presents a **Binary Classification Model** using a **Multi-Layer Perceptron (MLP)** implemented in PyTorch. The model achieves a high-performance **F1 Score of 0.98**, making it a reliable tool for intrusion detection tasks. Leveraging the **CICIDS2017 dataset**, the project addresses the challenges of anomaly-based intrusion detection, where reliable datasets are essential for consistent and accurate performance evaluation.

#### **Problem Statement**
Intrusion Detection Systems (IDSs) and Intrusion Prevention Systems (IPSs) are critical for defending against evolving and sophisticated network attacks. However, the effectiveness of anomaly-based intrusion detection is often undermined by the limitations of existing datasets:
- Lack of traffic diversity and volume.
- Insufficient coverage of modern attack techniques.
- Anonymization of packet payload data, leading to unrealistic simulations.
- Incomplete feature sets and metadata.

#### **Dataset: CICIDS2017**
The CICIDS2017 dataset was chosen for its high-quality representation of real-world network traffic and attacks. Key features include:
- **Diversity**: Contains both benign traffic and the most common attacks, including Brute Force, DoS, DDoS, Botnet, and Web Attacks.
- **Realistic Simulation**: Generated using the B-Profile system to mimic real-world human behavior across multiple protocols (HTTP, HTTPS, FTP, SSH, email).
- **Comprehensive Analysis**: Includes labeled flows with metadata such as timestamps, IP addresses, ports, and protocols.
- **Timeframe**: Captures five days of traffic data (July 3–7, 2017), with a mix of benign and attack traffic.

#### **Key Highlights**
- **Model Architecture**: The MLP architecture is tailored for binary classification, focusing on scalability and efficiency for high-dimensional network data.
- **Performance Metric**: Achieves an F1 Score of 0.98, demonstrating excellent precision and recall in detecting intrusions.
- **Features**: Preprocessed network flow data.

#### **Why This Project?**
- Bridges the gap in reliable performance evaluation for anomaly-based intrusion detection.
- Offers a robust solution for detecting modern network threats with high precision.
- Utilizes a dataset designed to resemble real-world network environments, ensuring practical relevance.

#### **How to Use**
1. **Dataset**: Download the CICIDS2017 dataset from [here](https://www.kaggle.com/datasets/chethuhn/network-intrusion-dataset).
2. **Preprocessing**: Follow the preprocessing steps to extract relevant features and labels.
3. **Model Training**: Train the MLP model using the PyTorch implementation provided in this repository.
4. **Evaluation**: Validate the model’s performance using the provided scripts and verify the F1 Score of 0.98.

---

#### **Getting Started**
Clone this repository and follow the detailed instructions in the [README.md](README.md) to set up the environment and run the model.

```
git clone https://github.com/darinaverk/CIC-IDS-2017-MLP-PyTorch
cd CIC-IDS-2017-MLP-PyTorch
```

#### **Contributors**
This project welcomes contributions from the community! Feel free to submit issues or pull requests to improve or extend this work.

