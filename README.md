# Enhanced-ADRC-for-Mobile-Robot-Trajectory-Tracking-Using-Fuzzy-PD-Controller
An enhanced  ADRC framework by replacing the traditional PD controller with a Fuzzy PD (FPD) controller. Unlike classical PD, the  FPD controller utilizes fuzzy logic to dynamically adjust the proportional gain based on the system’s error, allowing for  improved adaptability and disturbance rejection.

# Abstract

The field of robotics has seen significant advancements in recent years, enabling autonomous systems to efficiently perform complex tasks with minimal human intervention. Control design is one of the most critical aspects of robotics, and one of the biggest challenges in control design remains the provision of robust performance and good disturbance rejection. Active Disturbance Rejection Control (ADRC) has emerged as a very popular control strategy due to its ability to handle uncertainties and external disturbances. However, classical ADRC relies on a Proportional Derivative (PD) controller with fixed gains that may limit adaptability in varying environments. This paper proposes an enhanced ADRC framework by replacing the traditional PD controller with a Fuzzy PD (FPD) controller. Unlike classical PD, the FPD controller utilizes fuzzy logic to dynamically adjust the proportional gain based on the system’s error, allowing for improved adaptability and disturbance rejection. The effectiveness of this approach is evaluated through simulation-based trajectory tracking experiments. The results demonstrate that the ADRC based on FPD (ADRC-FPD) outperforms classical ADRC, achieving lower tracking errors, improved stability, and better disturbance rejection, particularly under varying external disturbances.

# Gallery
General Block Diagram

<img width="6948" height="1910" alt="blockdiagram" src="https://github.com/user-attachments/assets/1c8c3edf-fb6c-4f6f-b403-a525213d16ef" />

ADRC Structure for Linear and Angular Velocity
![ADRC](https://github.com/user-attachments/assets/577ef300-779a-448f-9383-c78fb9844c2c)


Fuzzy PD Controller Structure
<img width="3354" height="994" alt="Fuzzy" src="https://github.com/user-attachments/assets/cc7b0ac0-a212-4e1e-bfd1-d78370689eac" />


# Conclusion
A comparative analysis between the classical ADRC with a PD controller and the ADRC based on FPD for mobile robot control. The simulation results demonstrate that while classical ADRC effectively handles disturbances and uncertainties, the incorporation of fuzzy logic in the ADRC significantly enhances adaptability and robustness. The developed ADRC-FPD dynamically adjusts control gains based on system states and provides control output, leading to improved tracking accuracy, disturbance rejection, and smoother trajectory following compared to the fixed gain classical ADRC. The fuzzy based approach successfully mitigates system non-linearities and external perturbations, making it a more effective solution for real world mobile robot applications where environmental uncertainties are prevalent. 

# Authors

Usama Habib

Ashraf Elnagar

Raouf Fareh

Ahmad M. El-Nagar

Omar M. Gad

