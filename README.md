# While(1)CareAI

An AI-powered healthcare companion empowering rural clinics and medical interns with advanced medical image analysis, heart monitoring, and risk assessment through a dual-interface system that supports clinical decision-making when senior doctors are unavailable.

## Project Overview

While(1)CareAI is a comprehensive healthcare solution integrating AI for medical image analysis, designed specifically to support healthcare delivery in resource-constrained settings. Our multi-user platform serves both patients and healthcare professionals, providing secure, accessible healthcare analysis at their fingertips.

**Vision:** Making advanced medical diagnostics accessible to everyone, especially in areas with limited specialist access.

## Key Features

- **Medical Image Analysis:** Specialized detection models for various medical conditions
- **Heart Health Tools:** Risk assessment, report analysis, and real-time monitoring
- **Dual Interface System:**
  - Patient Portal: Self-service health analysis and personalized insights
  - Doctor Dashboard: Comprehensive patient management and analysis review
- **AI Chat Assistant:** Medical query support with natural language processing
- **PDF Report Generation:** Professional medical reports with analysis results
- **Hospital Locator:** Maps integration for finding nearby healthcare facilities

## Use Cases

### For Rural Clinics
- Preliminary screening of medical images when specialists aren't available
- AI-assisted interpretation of lab reports and medical data
- Patient education through the AI assistant

### For Medical Interns
- Decision support when senior doctors are unavailable
- Training tool for recognizing medical conditions in images
- Validation of preliminary diagnoses

### For Patients
- Self-monitoring of health parameters
- Understanding medical reports in simplified language
- Access to preliminary screenings without long waiting periods

## Technology Stack

- **Frontend:** Streamlit for intuitive, responsive UI
- **AI/ML:** YOLO for image detection, Google Gemini for natural language processing
- **Database:** Supabase for secure data storage and retrieval
- **Authentication:** Custom user management system with role-based access
- **Integrations:** Google Fit API, geolocation services
- **Report Generation:** ReportLab for PDF generation

## Medical Analysis Capabilities

- **Brain Tumor Detection:** MRI scan analysis
- **Diabetic Retinopathy:** Eye image analysis
- **Heart Disease Prediction:** Cardiac health assessment
- **Additional Analyses:** Bone fracture, skin disease, lung cancer detection

## Getting Started

### Prerequisites
- Python 3.8 or higher
- Git
- Google API keys for Generative AI
- Supabase account for database functionality

### Installation

1. Clone the repository:
   ```
   git clone https://github.com/MadhavDGS/While-1-CareAI.git
   cd While-1-CareAI
   ```

2. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```

3. Set up your environment variables:
   - Create a `.env` file in the project root directory
   - Add your API keys and credentials:
     ```
     GOOGLE_API_KEY=your_google_api_key
     SUPABASE_URL=your_supabase_url
     SUPABASE_KEY=your_supabase_key
     ```

### Running the Application

1. Start the Streamlit application:
   ```
   streamlit run login.py
   ```

2. Access the application in your browser:
   - The application will be available at http://localhost:8501
   - Use the provided login credentials or register a new account

3. Using the system:
   - For patients: Access the home page for medical image analysis
   - For doctors: Use the doctor dashboard to view patient records and analyses
  <img width="1470" alt="Screenshot 2025-04-12 at 9 57 47 PM" src="https://github.com/user-attachments/assets/f98d8a58-8f07-4228-bb15-506df93f8a25" />
<img width="1470" alt="Screenshot 2025-04-12 at 9 04 06 PM" src="https://github.com/user-attachments/assets/8aac5634-e3fa-452a-bc46-e792e4826543" />


   

## Future Roadmap

- Additional disease detection models
- Mobile application development
- Integration with electronic health records
- Enhanced analytics and reporting
- Expanded language support

## Contributing

We welcome contributions to improve While(1)CareAI and make healthcare more accessible worldwide!

## Disclaimer

This tool provides preliminary analysis only and is not intended to replace professional medical advice, diagnosis, or treatment. Always consult qualified healthcare professionals for medical decisions.
