# PlantEmote

### "Bridging the gap between nature and technology, one Mimosa at a time." 
<br>


## Technologies Used
- **Backend**: Python, Flask, PostgreSQL, OpenAI API, Azure Functions
- **Frontend**: HTML, CSS, JavaScript, Chart.js
- **Others**: Azure Blob Storage, Docker, Git

## Problem Statement
Plants are a crucial part of our ecosystem, but their needs and responses are often overlooked. PlantEmote aims to bridge this gap by creating a platform where plants can communicate their status and feelings through visual and textual representations. 
By leveraging technology, we can make plant care more intuitive and engaging.


## collaboration with IoT Device
Our IoT device plays a vital role in the PlantEmote ecosystem. It can generate artistic images based on the electrical signals produced by a Mimosa plant when it is touched. 
These signals are captured in real-time, processed, and transformed into beautiful, unique visual representations. 
The web app can display the newest artistic plot, show previous images stored in the database, and interact with the plant through text-based queries based on the current condition reflected in the signal plot.
- Link to our IoT device github repository: https://github.com/Jingyii800/TECHIN515_PlantEmote.git
<br>


## How to Run
1. **Clone the Repository**:  
   ```bash
   git clone https://github.com/yourusername/plantemote.git
   cd plantemote
   ```
2. **Setup the Environment**:
- Ensure you have Python and Docker installed.
- Create and activate a virtual environment
  ```
  python -m venv venv
  source venv/bin/activate   # On Windows, use `venv\Scripts\activate`
  ```
3. **Install Dependencies**:
  ```
  pip install -r requirements.txt
  ```
4. **Setup Environment Variables**:
  ```
  OPENAI_API_KEY=your_openai_api_key
  AZURE_STORAGE_CONNECTION_STRING=your_azure_storage_connection_string
  DATABASE_URL=your_postgresql_connection_string
  ```
5. **Run the Application**:
  ```
  flask run
  ```

## Reflections
### What We Learned
- Technical Skills: Gained experience in integrating various technologies such as Flask, PostgreSQL, and OpenAI API. Improved our frontend skills using HTML, CSS, and JavaScript.
- Team Collaboration: Enhanced our ability to work collaboratively using Git and Docker for seamless development and deployment.
### Challenges Faced
- API Integration: Integrating the OpenAI API and handling different types of responses was challenging. We had to ensure the prompts and responses were well-structured.
- Real-Time Data Handling: Managing real-time data from the plant sensors and ensuring accurate and timely updates in the web app required careful design and implementation.
- UI/UX Design: Designing a user-friendly and visually appealing interface that accurately represents the plant's status and emotions was a continuous iterative process.

