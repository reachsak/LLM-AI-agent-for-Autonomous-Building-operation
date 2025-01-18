# LLM-AI-agent-for-Autonomous-Building-operation

# Project Description: LLM-AI-Agent for Autonomous Building Operation

This project introduces an advanced AI agent designed to oversee autonomous building operation and facilities management. The proposed LLM-based autonomous building operation framework combines IoT devices, smart building facilities, LLMs, and blockchain technologies to create a decentralized and automated system for managing building systems.
<img src="/fig3.png" style="float: left; margin-right: 20px; max-width: 200px;">
<img src="/equipment.png" style="float: left; margin-right: 20px; max-width: 200px;">

## Threshold-Based Automation System

The threshold-based automation system utilizes an array of environmental sensors and IoT devices to collect data such as temperature, humidity, luminosity, carbon monoxide levels, energy usage, and occupancy levels. Raspberry Pi devices process these data and relay them to the AI agent via REST API. 

Threshold parameters, including maximum or minimum values for comfort and indoor environmental quality (e.g., temperature and humidity), are defined by building managers and stored in blockchain smart contracts. These values serve as baseline operational limits and ensure secure, transparent, and immutable governance. The AI agent continuously monitors real-time sensor data and compares it with these predefined thresholds. If the environmental conditions exceed these thresholds, the AI agent uses its function-calling capabilities to take action, such as adjusting HVAC setpoints, modifying lighting intensity, or triggering alerts to maintain optimal building conditions.
<img src="/fig1.png" style="float: left; margin-right: 20px; max-width: 200px;">

## Occupancy-Based Automation System

The occupancy-based automation system incorporates contextual decision-making, enabling more dynamic and adaptive building control. The AI agent interprets multiple variables simultaneously, including real-time occupancy data and the current settings of building systems. Based on this analysis, the agent adjusts the performance of systems such as HVAC and lighting to optimize energy consumption while maintaining comfort. 

For example, during low occupancy periods, the AI agent may reduce HVAC intensity or dim the lighting to conserve energy. Conversely, during high occupancy, the agent ensures that environmental conditions are optimal for occupants. The system also accommodates user preferences and feedback through natural language processing, enabling users to provide specific requests or adjust system behaviors dynamically.
<img src="/fig2.png" style="float: left; margin-right: 20px; max-width: 200px;">


## Key Features
- **Integration with IoT and Sensors:** Collects real-time environmental data such as temperature, humidity, and energy usage, as well as occupancy information, using IoT devices and sensors.
- **Threshold-Based Control:** Automates building operations by comparing sensor data against predefined thresholds and triggering actions to maintain comfort and efficiency.
- **Occupancy-Based Decision-Making:** Dynamically adjusts building systems based on occupancy data to optimize energy consumption and environmental quality.

## Benefits
The LLM-based AI agent provides an unprecedented level of flexibility and adaptability, surpassing traditional automation systems. By integrating threshold-based automation and contextual decision-making, this system enhances building efficiency, reduces energy consumption, and delivers a responsive and user-centric approach to smart building management.

### Requirements
- Open-source Large language model (e.g., LLaMA)
- Generative AI inference tool. llama.cpp
- Python 3.10
- Raspberry Pi and IoT sensors
- Smart home devices (e.g., smart lights, smart fan, smart humidifier, smart air purifier)

## Detailed setup guide
Coming soon.....

## License
This project is licensed under the MIT License.

