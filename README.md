Full Functional Overview: ArogyaDiet AI
​ArogyaDiet AI is a clinical nutrition web application designed to bridge the gap between complex medical prescriptions, diagnostic laboratory reports, and traditional home kitchens across India. It extracts clinical data from uploaded documents, determines underlying health conditions, calculates energy needs, and formulates authentic regional diet plans in the patient's native language.
​1. Document Ingestion & Optical Recognition (OCR)
​Multi-Format Processing: Accepts doctor prescriptions and clinical lab reports in JPEG, PNG, WebP, and multi-page PDF formats up to 10 MB.
​Client-Side Optical Character Recognition: Utilises browser-based OCR (Tesseract.js) and PDF rendering (pdf.js) to extract handwritten notes, medicine names, strengths, dosages, and numerical laboratory results directly on the user's device without requiring server-side storage.
​Interactive Lightbox Inspection: Features a tap-to-zoom modal allowing patients and caregivers to inspect faint or complex handwriting directly beside the generated analysis.
​2. Indian Pharmacopeia Matching & Verification
​Pre-Loaded Drug Database: Incorporates a database of 120+ common Indian branded formulations and generic molecules across key therapeutic segments (e.g., Glycomet, Telma, Atorva, Thyronorm, Febuxostat, Pan-40, Shelcal, Orofer-XT).
​Fuzzy Parsing & Interactive Medicine Chips: Matches extracted text against generic and brand synonyms, rendering identified drugs into editable tag pills.
​Manual Correction & Quick-Select: Provides an input field and one-tap quick-select chips so users can add, correct, or delete prescription medicines.
​3. Pan-India Laboratory Test Report Analyzer
​The app evaluates over 20 standard diagnostic health markers against standard reference ranges:
​Glycemic Profile: Fasting Blood Sugar (FBS), Post-Prandial Blood Sugar (PPBS), Glycated Haemoglobin (HbA1c).
​Cardiovascular & Vitals: Systolic/Diastolic Blood Pressure (BP).
​Lipid Profile: Total Cholesterol, Serum Triglycerides (TG), LDL Cholesterol.
​Renal Function (KFT/RFT): Serum Creatinine, Serum Uric Acid.
​Liver Function (LFT): SGPT (ALT).
​Endocrine & Hematology: Thyroid Stimulating Hormone (TSH), Haemoglobin (Hb).
​Each detected marker is categorized into an organized clinical table indicating its numeric value, standard reference range, severity badge (High / Elevated, Borderline, Within Range, or Below Normal), and the direct clinical dietary action triggered.
​4. Disease Cross-Referencing & Calorie Calculation
​Clinical Condition Mapping: Correlates identified medicines and abnormal lab tests to pinpoint active conditions such as Type 2 Diabetes Mellitus, Essential Hypertension, Dyslipidemia, Grade 1 Fatty Liver (NAFLD), Hyperuricemia/Gout, Hypothyroidism, Renal Impairment, and Iron Deficiency Anemia.
​Precision Kilocalorie (kcal) Targets: Computes an individualized daily caloric target (e.g., 1,450 kcal for metabolic syndrome/T2D; 1,650 kcal for renal protective protocols) accompanied by specific macronutrient distributions (Carbohydrates, Proteins, and Healthy Fats).
​5. Patient Preferences & Allergy Processing
​The application adapts the diet plan based on the Patient Preferences / Notes input:
​Dietary Lifestyle (Veg / Non-Veg / Vegan): Automatically replaces animal proteins with vegetarian alternatives (fresh chhena, homemade paneer, sprouted legumes, soya) or incorporates light, stomach-friendly fish stews when non-vegetarian preferences are selected.
​Acid Reflux & GERD: Substitutes acidic morning beverages with soothing alkaline drinks (lukewarm fennel and cumin water) and restricts gastric irritants.
​Allergen Exclusions: Filters out specified triggers such as peanuts, dairy/lactose, or eggs.
​Geriatric Adaptation: Softens textures and reduces roughage for elderly patients when senior age markers are supplied.
​6. Regional Staple Localization & Native Language Translation
​State-Specific Kitchen Staples: Formulates meals using local produce and traditional dishes across Eastern, Northern, Western, Southern, Central, and North-Eastern India (e.g., Macher jhol, Dalma, Shukto, Jowar bhakri, Ragi mudde, Sattu, Thoran).
​100% Mother-Tongue Output: Outputs dish names, vegetable names, fruits, and food categories completely in the selected Indian script (Bengali, Hindi, Tamil, Telugu, Marathi, Gujarati, Odia, Punjabi, Kannada, Malayalam, or English) while maintaining clinical markers and medicine names in standard English for clarity.
​7. Core Deliverables Generated
​Clinical Diagnostic Summary: Highlights identified illnesses, verified medicines, and lab findings.
​Factored Preferences Card: Documents how the patient's individual notes altered the nutritional prescription.
​Time-Wise 1-Day Therapeutic Schedule: Covers 7 distinct slots (Early Morning, Breakfast, Mid-Morning, Lunch, Evening Snack, Dinner, Bedtime) with exact dishes, portions, and meal-by-meal kilocalories.
​7-Day Weekly Meal Rotation: A structured Monday-to-Sunday rotation table preventing meal fatigue while preserving nutritional targets.
​Categorized "Eat vs. Strictly Avoid" Matrix: Divides recommended and forbidden foods across 5 groups: Grains, Vegetables & Greens, Fresh Fruits, Pulses & Proteins, and Cooking Mediums & Beverages.
​8. Practice Utilities & Export Tools
​Dietitian / Clinic Watermark: Optional space to add a nutritionist, physician, or clinic name, rendered as an official signature line at the bottom of the chart.
​One-Click Clipboard Copy & Print/PDF Engine: Formats the entire clinical chart for desktop printing or PDF generation while hiding navigation headers, buttons, and system controls.
​Integrated Visitor Counter: Displays global usage numbers via an autonomous CounterAPI endpoint.
​Zero Barrier to Care: Operates entirely without sign-up, user tracking, subscriptions, or external API keys.