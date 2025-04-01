<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dr. Sifael Mpolo</title>
    <style>
        /* General Styles */
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            line-height: 1.6;
            background: #f4f4f9;
            color: #333;
        }

        /* Header Styles */
        header {
            background: linear-gradient(90deg, #007BFF, #0056b3);
            color: #FFD700;
            text-align: center;
            padding: 2rem 1rem;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }

        header h1 {
            font-size: 3rem;
            margin: 0;
        }

        header p {
            font-size: 1.2rem;
            margin: 0.5rem 0 0;
        }

        /* Navigation Bar */
        nav {
            background: #0056b3;
            padding: 1rem;
            text-align: center;
            position: sticky;
            top: 0;
            z-index: 1000;
        }

        nav a {
            color: #FFD700;
            text-decoration: none;
            margin: 0 1rem;
            font-weight: bold;
            font-size: 1rem;
        }

        nav a:hover {
            color: #FF5733;
        }

        /* Section Styles */
        section {
            background: white;
            margin: 2rem auto;
            padding: 2rem;
            border-radius: 8px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
            max-width: 800px;
        }

        section h2 {
            color: #FF5733;
            font-size: 2.5rem;
            margin-bottom: 1rem;
            text-transform: uppercase;
            font-weight: bold;
        }

        section h3 {
            color: #007BFF;
            font-size: 1.8rem;
            margin-bottom: 0.8rem;
            font-weight: bold;
        }

        section h4 {
            color: #28A745;
            font-size: 1.5rem;
            margin-bottom: 0.6rem;
            font-weight: bold;
        }

        section p,
        section ul {
            font-size: 1rem;
            margin-bottom: 1rem;
        }

        ul {
            padding-left: 1.5rem;
        }

        ul li {
            margin-bottom: 0.5rem;
        }

        /* Footer Styles */
        footer {
            background: #222;
            color: #ccc;
            text-align: center;
            padding: 1rem 0;
            font-size: 0.9rem;
        }

        /* Responsive Design */
        @media (max-width: 768px) {
            header h1 {
                font-size: 2rem;
            }

            nav a {
                font-size: 0.9rem;
            }

            section {
                padding: 1.5rem;
            }

            section h2 {
                font-size: 2rem;
            }

            section h3 {
                font-size: 1.6rem;
            }

            section h4 {
                font-size: 1.4rem;
            }
        }
    </style>
</head>

<body>
    <header>
        <nav>
            <a href="#home">Home</a>
            <a href="#introduction">Introduction</a>
            <a href="#about">About</a>
            <a href="#services">Services</a>
            <a href="#types-of-diseases">Types of Diseases</a>
            <a href="#contact">Contact</a>
            <a href="#faq">FAQ</a>
        </nav>
        <h1 id="home">Welcome to Dr. Sifael Mpolo's Website</h1>
        <p>Your trusted healthcare provider</p>
    </header>

    <section id="introduction">
        <h2>Introduction</h2>
        <h3>What is a Hospital?</h3>
        <p>A hospital is a healthcare institution that provides medical, surgical, and nursing care to patients. It is equipped with specialized staff and facilities to diagnose, treat, and manage various health conditions.</p>
        <h3>Who is a Doctor?</h3>
        <p>A doctor is a licensed medical professional trained to diagnose and treat illnesses, injuries, and other health conditions. Doctors play a vital role in promoting health and well-being through preventive care, treatment, and patient education.</p>
    </section>

    <section id="about">
        <h2>About Dr. Sifael Mpolo</h2>
        <p>Dr. Sifael Mpolo is a dedicated medical professional with years of experience in providing exceptional healthcare services. Passionate about improving lives, Dr. Mpolo specializes in [insert specialization].</p>
    </section>

    <section id="services">
        <h2>Services</h2>
        <ul>
            <li>General Consultation</li>
            <li>Specialized Treatments</li>
            <li>Health Check-ups</li>
            <li>Emergency Care</li>
        </ul>
        <p>At Dr. Sifael Mpolo's clinic, we are committed to providing comprehensive healthcare services tailored to meet the needs of our patients. Our health sector focuses on preventive care, early diagnosis, and effective treatment plans to ensure optimal health outcomes.</p>
    </section>

    <section id="types-of-diseases">
        <h2>Types of Diseases</h2>

        <h3>1. Infectious Diseases</h3>
        <p>Infectious diseases are caused by pathogens such as viruses, bacteria, fungi, or parasites. They can spread from person to person, through contaminated food or water, or via insect bites.</p>
        <div style="border: 1px solid #007BFF; padding: 1rem; margin-bottom: 1rem; border-radius: 8px;">
            <h4 style="color: #007BFF;">COVID-19</h4>
            <p><strong>Symptoms:</strong> Fever, cough, shortness of breath, fatigue, and loss of taste or smell.</p>
            <p><strong>How it Spreads:</strong> Through respiratory droplets when an infected person coughs, sneezes, or talks.</p>
            <p><strong>Prevention:</strong> Wear masks, maintain social distancing, wash hands frequently, and get vaccinated.</p>
        </div>
        <div style="border: 1px solid #007BFF; padding: 1rem; margin-bottom: 1rem; border-radius: 8px;">
            <h4 style="color: #007BFF;">Tuberculosis (TB)</h4>
            <p><strong>Symptoms:</strong> Persistent cough, chest pain, fever, and weight loss.</p>
            <p><strong>How it Spreads:</strong> Through airborne droplets when an infected person coughs or sneezes.</p>
            <p><strong>Prevention:</strong> Avoid close contact with infected individuals and ensure proper ventilation in living spaces.</p>
        </div>
        <div style="border: 1px solid #007BFF; padding: 1rem; margin-bottom: 1rem; border-radius: 8px;">
            <h4 style="color: #007BFF;">Malaria</h4>
            <p><strong>Symptoms:</strong> Fever, chills, headache, nausea, and muscle pain.</p>
            <p><strong>How it Spreads:</strong> Through the bites of infected female Anopheles mosquitoes.</p>
            <p><strong>Prevention:</strong> Use mosquito nets, eliminate stagnant water, and take antimalarial medications when traveling to endemic areas.</p>
        </div>
        <div style="border: 1px solid #007BFF; padding: 1rem; margin-bottom: 1rem; border-radius: 8px;">
            <h4 style="color: #007BFF;">HIV/AIDS</h4>
            <p><strong>Symptoms:</strong> Fatigue, weight loss, recurrent infections, and night sweats.</p>
            <p><strong>How it Spreads:</strong> Through unprotected sexual contact, sharing needles, or from mother to child during childbirth or breastfeeding.</p>
            <p><strong>Prevention:</strong> Practice safe sex, avoid sharing needles, and get tested regularly.</p>
        </div>
        <div style="border: 1px solid #007BFF; padding: 1rem; margin-bottom: 1rem; border-radius: 8px;">
            <h4 style="color: #007BFF;">Influenza (Flu)</h4>
            <p><strong>Symptoms:</strong> Fever, cough, sore throat, body aches, and fatigue.</p>
            <p><strong>How it Spreads:</strong> Through respiratory droplets when an infected person coughs, sneezes, or talks.</p>
            <p><strong>Prevention:</strong> Get annual flu vaccinations, wash hands frequently, and avoid close contact with sick individuals.</p>
        </div>

        <h3>2. Chronic Diseases</h3>
        <p>Chronic diseases are long-term conditions that require ongoing management and can significantly impact quality of life. These diseases are not contagious.</p>
        <div style="border: 1px solid #28A745; padding: 1rem; margin-bottom: 1rem; border-radius: 8px;">
            <h4 style="color: #28A745;">Diabetes</h4>
            <p><strong>Symptoms:</strong> Increased thirst, frequent urination, fatigue, and blurred vision.</p>
            <p><strong>How it Develops:</strong> Caused by genetic factors, lifestyle choices, or autoimmune destruction of insulin-producing cells.</p>
            <p><strong>Prevention:</strong> Maintain a healthy diet, exercise regularly, and monitor blood sugar levels.</p>
        </div>
        <div style="border: 1px solid #28A745; padding: 1rem; margin-bottom: 1rem; border-radius: 8px;">
            <h4 style="color: #28A745;">Hypertension (High Blood Pressure)</h4>
            <p><strong>Symptoms:</strong> Often asymptomatic but may include headaches, dizziness, and shortness of breath.</p>
            <p><strong>How it Develops:</strong> Caused by genetic predisposition, poor diet, lack of exercise, or stress.</p>
            <p><strong>Prevention:</strong> Reduce salt intake, maintain a healthy weight, and manage stress.</p>
        </div>
        <div style="border: 1px solid #28A745; padding: 1rem; margin-bottom: 1rem; border-radius: 8px;">
            <h4 style="color: #28A745;">Asthma</h4>
            <p><strong>Symptoms:</strong> Wheezing, shortness of breath, chest tightness, and coughing.</p>
            <p><strong>Prevention:</strong> Avoid allergens, use prescribed inhalers, and monitor air quality.</p>
        </div>
        <div style="border: 1px solid #28A745; padding: 1rem; margin-bottom: 1rem; border-radius: 8px;">
            <h4 style="color: #28A745;">Arthritis</h4>
            <p><strong>Symptoms:</strong> Joint pain, swelling, stiffness, and reduced mobility.</p>
            <p><strong>Prevention:</strong> Maintain a healthy weight, stay active, and avoid joint injuries.</p>
        </div>
        <div style="border: 1px solid #28A745; padding: 1rem; margin-bottom: 1rem; border-radius: 8px;">
            <h4 style="color: #28A745;">Cancer</h4>
            <p><strong>Symptoms:</strong> Vary by type but may include lumps, unexplained weight loss, and fatigue.</p>
            <p><strong>Prevention:</strong> Avoid smoking, limit alcohol consumption, and undergo regular screenings.</p>
        </div>

        <h3>3. Genetic & Hereditary Diseases</h3>
        <p>These diseases are passed down through genes and are not contagious.</p>
        <div style="border: 1px solid #FFC107; padding: 1rem; margin-bottom: 1rem; border-radius: 8px;">
            <h4 style="color: #FFC107;">Sickle Cell Anemia</h4>
            <p><strong>Symptoms:</strong> Pain episodes, fatigue, and susceptibility to infections.</p>
            <p><strong>How it Spreads:</strong> Inherited from both parents carrying the sickle cell gene.</p>
            <p><strong>Prevention:</strong> Genetic counseling for at-risk couples.</p>
        </div>
        <div style="border: 1px solid #FFC107; padding: 1rem; margin-bottom: 1rem; border-radius: 8px;">
            <h4 style="color: #FFC107;">Cystic Fibrosis</h4>
            <p><strong>Symptoms:</strong> Persistent cough, lung infections, and difficulty gaining weight.</p>
            <p><strong>Prevention:</strong> Genetic testing and early diagnosis for better management.</p>
        </div>
        <div style="border: 1px solid #FFC107; padding: 1rem; margin-bottom: 1rem; border-radius: 8px;">
            <h4 style="color: #FFC107;">Hemophilia</h4>
            <p><strong>Symptoms:</strong> Excessive bleeding and easy bruising.</p>
            <p><strong>Prevention:</strong> Genetic counseling and avoiding injury.</p>
        </div>
        <div style="border: 1px solid #FFC107; padding: 1rem; margin-bottom: 1rem; border-radius: 8px;">
            <h4 style="color: #FFC107;">Down Syndrome</h4>
            <p><strong>Symptoms:</strong> Distinct facial features, developmental delays, and intellectual disability.</p>
            <p><strong>Prevention:</strong> Prenatal screening and genetic counseling.</p>
        </div>

        <h3>4. Neurological Diseases</h3>
        <p>Neurological diseases affect the brain, spinal cord, and nervous system. These diseases are not contagious.</p>
        <div style="border: 1px solid #6C757D; padding: 1rem; margin-bottom: 1rem; border-radius: 8px;">
            <h4 style="color: #6C757D;">Alzheimer’s Disease</h4>
            <p><strong>Symptoms:</strong> Memory loss, confusion, and difficulty completing familiar tasks.</p>
            <p><strong>How it Develops:</strong> Caused by genetic factors, age, and lifestyle influences.</p>
            <p><strong>Prevention:</strong> Engage in mental exercises, maintain a healthy diet, and stay socially active.</p>
        </div>
        <div style="border: 1px solid #6C757D; padding: 1rem; margin-bottom: 1rem; border-radius: 8px;">
            <h4 style="color: #6C757D;">Parkinson’s Disease</h4>
            <p><strong>Symptoms:</strong> Tremors, stiffness, and slow movement.</p>
            <p><strong>Prevention:</strong> No known prevention, but regular exercise may help manage symptoms.</p>
        </div>
        <div style="border: 1px solid #6C757D; padding: 1rem; margin-bottom: 1rem; border-radius: 8px;">
            <h4 style="color: #6C757D;">Epilepsy</h4>
            <p><strong>Symptoms:</strong> Recurrent seizures, loss of consciousness, and confusion.</p>
            <p><strong>Prevention:</strong> Avoid head injuries and manage underlying conditions.</p>
        </div>
        <div style="border: 1px solid #6C757D; padding: 1rem; margin-bottom: 1rem; border-radius: 8px;">
            <h4 style="color: #6C757D;">Multiple Sclerosis (MS)</h4>
            <p><strong>Symptoms:</strong> Muscle weakness, vision problems, and difficulty with coordination.</p>
            <p><strong>Prevention:</strong> No known prevention, but early diagnosis can help manage symptoms.</p>
        </div>

        <h3>5. Autoimmune Diseases</h3>
        <p>Autoimmune diseases occur when the immune system mistakenly attacks the body’s own cells and tissues. These diseases are not contagious.</p>
        <div style="border: 1px solid #DC3545; padding: 1rem; margin-bottom: 1rem; border-radius: 8px;">
            <h4 style="color: #DC3545;">Lupus</h4>
            <p><strong>Symptoms:</strong> Fatigue, joint pain, and skin rashes.</p>
            <p><strong>How it Develops:</strong> Caused by genetic predisposition and environmental triggers.</p>
            <p><strong>Prevention:</strong> Avoid triggers like sunlight and manage stress.</p>
        </div>
        <div style="border: 1px solid #DC3545; padding: 1rem; margin-bottom: 1rem; border-radius: 8px;">
            <h4 style="color: #DC3545;">Rheumatoid Arthritis</h4>
            <p><strong>Symptoms:</strong> Joint pain, swelling, and stiffness.</p>
            <p><strong>Prevention:</strong> No known prevention, but early treatment can reduce joint damage.</p>
        </div>
        <div style="border: 1px solid #DC3545; padding: 1rem; margin-bottom: 1rem; border-radius: 8px;">
            <h4 style="color: #DC3545;">Type 1 Diabetes</h4>
            <p><strong>Symptoms:</strong> Increased thirst, frequent urination, and weight loss.</p>
            <p><strong>Prevention:</strong> No known prevention, but early diagnosis can help manage the condition.</p>
        </div>

        <h3>6. Mental Health Disorders</h3>
        <p>Mental health disorders affect mood, thinking, and behavior. These disorders are not contagious but may be influenced by genetic and environmental factors.</p>
        <div style="border: 1px solid #17A2B8; padding: 1rem; margin-bottom: 1rem; border-radius: 8px;">
            <h4 style="color: #17A2B8;">Depression</h4>
            <p><strong>Symptoms:</strong> Loss of interest, fatigue, and feelings of hopelessness.</p>
            <p><strong>How it Develops:</strong> Caused by genetic predisposition, life events, or chemical imbalances in the brain.</p>
            <p><strong>Prevention:</strong> Maintain a support network, exercise regularly, and seek professional help when needed.</p>
        </div>
        <div style="border: 1px solid #17A2B8; padding: 1rem; margin-bottom: 1rem; border-radius: 8px;">
            <h4 style="color: #17A2B8;">Anxiety Disorders</h4>
            <p><strong>Symptoms:</strong> Restlessness, rapid heartbeat, and difficulty concentrating.</p>
            <p><strong>Prevention:</strong> Practice relaxation techniques and avoid stressful situations.</p>
        </div>
        <div style="border: 1px solid #17A2B8; padding: 1rem; margin-bottom: 1rem; border-radius: 8px;">
            <h4 style="color: #17A2B8;">Schizophrenia</h4>
            <p><strong>Symptoms:</strong> Hallucinations, delusions, and disorganized thinking.</p>
            <p><strong>Prevention:</strong> No known prevention, but early treatment can improve outcomes.</p>
        </div>
        <div style="border: 1px solid #17A2B8; padding: 1rem; margin-bottom: 1rem; border-radius: 8px;">
            <h4 style="color: #17A2B8;">Bipolar Disorder</h4>
            <p><strong>Symptoms:</strong> Periods of depression alternating with episodes of mania.</p>
            <p><strong>Prevention:</strong> No known prevention, but medication and therapy can help manage symptoms.</p>
        </div>
    </section>

    <section id="contact" class="contact">
        <h2>Contact Information</h2>
        <p>Email: sifaelmpolo239@gmail.com</p>
        <p>Phone: +225 755 437 163</p>
        <p>Address: Ludewa, Njombe</p>
    </section>

    <section id="faq">
        <h2>FAQ</h2>
        <h3><strong style="color: #FF5733;">What are the clinic's operating hours?</strong></h3>
        <p>Our clinic is open from Monday to Sunday, 24 hrs.</p>
        <h3><strong style="color: #28A745;">Do I need an appointment?</strong></h3>
        <p>While walk-ins are welcome, we recommend scheduling an appointment to minimize waiting times and ensure personalized care.</p>
        <h3><strong style="color: #007BFF;">What payment methods are accepted?</strong></h3>
        <p>We accept cash, credit/debit cards, and mobile payment options. Please contact us for more details.</p>
        <h3><strong style="color: #FFC107;">What should I bring to my appointment?</strong></h3>
        <p>Please bring a valid ID, your medical history, any current medications, and your insurance information (if applicable).</p>
        <h3><strong style="color: #6C757D;">Does the clinic offer telemedicine services?</strong></h3>
        <p>Yes, we offer telemedicine consultations for non-emergency cases. Please contact us to schedule a virtual appointment.</p>
        <h3><strong style="color: #17A2B8;">Are vaccinations available at the clinic?</strong></h3>
        <p>Yes, we provide a range of vaccinations for children and adults. Please call ahead to confirm availability.</p>
        <h3><strong style="color: #DC3545;">Can I get a second opinion at the clinic?</strong></h3>
        <p>Absolutely. We encourage patients to seek second opinions and are happy to provide a thorough evaluation of your condition.</p>
        <h3><strong style="color: #20C997;">Is the clinic wheelchair accessible?</strong></h3>
        <p>Yes, our clinic is fully wheelchair accessible, with ramps and elevators to ensure convenience for all patients.</p>
        <h3><strong style="color: #FF5733;">Does the clinic provide emergency services?</strong></h3>
        <p>Yes, we provide 24/7 emergency services to handle urgent medical situations.</p>
        <h3><strong style="color: #28A745;">How can I contact the clinic for inquiries?</strong></h3>
        <p>You can contact us via phone at +225 755437163 or email at sifaelmpolo239@gmail.com.</p>
        <h3><strong style="color: #007BFF;">Are there any health education programs available?</strong></h3>
        <p>Yes, we conduct regular health education programs to promote awareness about common diseases and preventive measures.</p>
        <h3><strong style="color: #FFC107;">Does the clinic accept health insurance?</strong></h3>
        <p>Yes, we accept a variety of health insurance plans. Please contact us to confirm if your insurance is accepted.</p>
        <h3><strong style="color: #6C757D;">What should I do if I need to cancel my appointment?</strong></h3>
        <p>If you need to cancel your appointment, please notify us at least 24 hours in advance to reschedule or free up the slot for other patients.</p>
    </section>

    <footer style="background: #FFD700; color: #0056b3; text-align: center; padding: 1rem 0; font-size: 0.9rem;">
        <p>&copy; 2024 Dr. Sifael Mpolo. All rights reserved.</p>
    </footer>
</body>

</html>
