# 🛡️ Detections

Welcome to the **Detections** section of my **Threat Intelligence Lab**! This folder is dedicated to storing and documenting detection rules, queries, and methods designed to identify malicious activity in the environment. These detections are based on known adversary tactics, techniques, and procedures (TTPs), and are used to enhance threat detection and response capabilities.

---

## 📌 What’s Included

In this folder, you'll find the following key detection-related content:

- **Detection Rules**  
  Rules designed to identify specific behaviors or activities that may indicate an attack.

- **Custom Queries**  
  Tailored queries for use in security tools (e.g., SIEM, EDR, LogScale, Sigma) to detect malicious activity.

- **Detection Testing**  
  Example cases and tests to validate the effectiveness of detection rules and queries.

---

## 📂 Folder Structure

This folder is organized into the following sections:

- **`rules/`**  
  Detection rules written in various formats (e.g., Sigma, LogScale, Splunk SPL) that can be directly applied to security systems.

- **`queries/`**  
  Custom queries for different platforms (SIEM, EDRs, or cloud security tools) designed to catch suspicious activity.

- **`tests/`**  
  Example cases that show how to test and validate detection rules to ensure they are working as expected.

---

## 📝 Key Files

- **`example_detection.yml`**  
  A sample Sigma detection rule to identify suspicious PowerShell execution patterns.

- **`splunk_detection_example.spl`**  
  A sample Splunk SPL query to detect abnormal network traffic associated with known attack behavior.

- **`logscale_detection_example.cql`**  
  A custom LogScale CQL query designed to identify unauthorized access attempts.

---

## 🔍 How to Use

- **Apply Detection Rules**: Use the detection rules in the **`rules/`** folder and apply them to your SIEM or EDR to detect malicious activity in your environment.
- **Run Queries**: Utilize the queries in the **`queries/`** folder to search for suspicious activity in real-time or as part of your regular threat monitoring process.
- **Test & Validate**: Refer to the **`tests/`** folder for examples on how to test your detection rules to ensure accuracy and minimize false positives.

---

## 🔗 Additional Resources

For deeper learning and further reading on detection methods, here are some external resources:

- [Sigma Rules](https://github.com/SigmaHQ/sigma)
- [Elastic Security: Detection Engine](https://www.elastic.co/security)
- [MITRE ATT&CK Framework](https://attack.mitre.org/)

---

## 💬 Feedback & Collaboration

The detection rules and queries in this folder are continually being refined and updated. If you have suggestions, improvements, or new rules to contribute, feel free to open an issue or submit a pull request.

---

Thank you for exploring the **Detections** section! I hope the rules and queries shared here help enhance your organization's threat detection capabilities.

