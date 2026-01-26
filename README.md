# Angela-Kim-Profile-Data-Tech-AI-Leader
Professional profile website for Angela Kim
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Angela Kim - Technology, Data & AI Leader</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            color: #2c3e50;
            background: linear-gradient(135deg, #f5f7fa 0%, #e8eef5 100%);
        }
        
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
        }
        
        header {
            background: linear-gradient(135deg, #1e3c72 0%, #2a5298 100%);
            color: white;
            padding: 60px 0;
            text-align: center;
            box-shadow: 0 4px 6px rgba(0,0,0,0.1);
        }
        
        header h1 {
            font-size: 2.8em;
            margin-bottom: 10px;
            font-weight: 600;
        }
        
        header p {
            font-size: 1.3em;
            opacity: 0.95;
            max-width: 900px;
            margin: 0 auto 20px auto;
        }
        
        .contact-info {
            display: flex;
            justify-content: center;
            gap: 30px;
            flex-wrap: wrap;
            margin-top: 20px;
        }
        
        .contact-info a {
            color: white;
            text-decoration: none;
            font-size: 1.1em;
            padding: 10px 20px;
            background: rgba(255, 255, 255, 0.15);
            border-radius: 25px;
            transition: background 0.3s ease;
        }
        
        .contact-info a:hover {
            background: rgba(255, 255, 255, 0.25);
        }
        
        .section {
            background: white;
            margin: 30px auto;
            padding: 50px;
            border-radius: 12px;
            box-shadow: 0 2px 15px rgba(0,0,0,0.08);
        }
        
        .section h2 {
            color: #1e3c72;
            font-size: 2em;
            margin-bottom: 25px;
            padding-bottom: 15px;
            border-bottom: 3px solid #2a5298;
        }
        
        .bio {
            font-size: 1.1em;
            line-height: 1.8;
            color: #34495e;
            text-align: justify;
        }
        
        .bio a {
            color: #2a5298;
            text-decoration: none;
            font-weight: 600;
        }
        
        .bio a:hover {
            text-decoration: underline;
        }
        
        .skills-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 25px;
            margin-top: 30px;
        }
        
        .skill-card {
            background: linear-gradient(135deg, #f8f9fc 0%, #e8eef5 100%);
            padding: 30px;
            border-radius: 10px;
            border-left: 5px solid #2a5298;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }
        
        .skill-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 8px 20px rgba(42,82,152,0.15);
        }
        
        .skill-card h3 {
            color: #1e3c72;
            font-size: 1.3em;
            margin-bottom: 15px;
        }
        
        .skill-card ul {
            list-style: none;
            padding-left: 0;
        }
        
        .skill-card li {
            padding: 8px 0;
            color: #34495e;
            position: relative;
            padding-left: 25px;
        }
        
        .skill-card li:before {
            content: "✓";
            position: absolute;
            left: 0;
            color: #2a5298;
            font-weight: bold;
            font-size: 1.2em;
        }
        
        .resources {
            margin-top: 30px;
        }
        
        .resources h3 {
            color: #1e3c72;
            font-size: 1.5em;
            margin-bottom: 20px;
        }
        
        .resource-links {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
        }
        
        .resource-link {
            background: linear-gradient(135deg, #2a5298 0%, #1e3c72 100%);
            color: white;
            padding: 20px;
            border-radius: 8px;
            text-decoration: none;
            display: block;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }
        
        .resource-link:hover {
            transform: translateY(-3px);
            box-shadow: 0 6px 15px rgba(42,82,152,0.3);
        }
        
        .resource-link strong {
            display: block;
            font-size: 1.1em;
            margin-bottom: 5px;
        }
        
        .contact {
            text-align: center;
            padding: 40px;
        }
        
        .contact a {
            display: inline-block;
            background: linear-gradient(135deg, #2a5298 0%, #1e3c72 100%);
            color: white;
            padding: 15px 40px;
            border-radius: 50px;
            text-decoration: none;
            font-size: 1.2em;
            font-weight: 600;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }
        
        .contact a:hover {
            transform: scale(1.05);
            box-shadow: 0 6px 20px rgba(42,82,152,0.4);
        }
        
        footer {
            text-align: center;
            padding: 30px;
            color: #7f8c8d;
            background: white;
            margin-top: 30px;
        }
        
        @media (max-width: 768px) {
            header h1 {
                font-size: 2em;
            }
            
            header p {
                font-size: 1.1em;
            }
            
            .contact-info {
                flex-direction: column;
                gap: 15px;
            }
            
            .contact-info a {
                font-size: 1em;
            }
            
            .section {
                padding: 30px 20px;
            }
            
            .skills-grid {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <h1>Angela Kim</h1>
            <p>Technology, Data and AI Leader specialised in Transformation Strategy, Implementation and Process Optimisation</p>
            <div class="contact-info">
                <a href="mailto:angela@womeninai.co">📧 angela@womeninai.co</a>
                <a href="tel:+61416153715">📱 +61 416 153 715</a>
                <a href="https://www.linkedin.com/in/angela-kim-b3203a6b/" target="_blank">💼 LinkedIn</a>
            </div>
        </div>
    </header>

    <div class="container">
        <section class="section">
            <h2>About</h2>
            <div class="bio">
                <p>As a data, technology and AI professional with more than 15 years of experience in the consulting, banking, insurance and financial institution, Angela is currently the Head of Data, Technology & AI at AIA and was formerly Director of Data, Technology & AI at Deloitte Australia. She is the APAC Chief and Global Chief Education Officer for WAI (Women in AI) and sits on the ACS Data Sharing and Cyber Security & Responsible and Ethical AI Advisory Board and UNSW AI Institute advisory board.</p>
                
                <p style="margin-top: 15px;">She is the founding member of the Springer Ethics in AI Advisory Group based in the UK and working closely with EU, APAC and EMEA AI institutes on AI for Healthcare especially AI solution for breast cancer and cervical cancer setting up the digital pathology lab and bringing more female researchers in women's health area.</p>
                
                <p style="margin-top: 15px;">Angela works with the under-privileged youth group, refugees and the First Nations artists to democratize AI to achieve diversity and inclusion in AI for community and citizens. Angela delivered 1000 Girls 1000 Futures AI and Tech Literacy programs and <a href="https://www.womeninai.co/waiawards2025apac" target="_blank">Women in AI APAC Awards</a> every year since 2021 to recognize and celebrate amazing women working in the AI industry from Government, Corporate and Research area.</p>
                
                <p style="margin-top: 15px;">Angela specialises in Ethics, Bias, Explainable & Responsible AI and was the recipient of the Top 4 Analytics Leaders in 2020 from the Institute of Analytics Professionals of Australia and the Educator of the Year Award from UAE in 2022. Angela also won the award for 2025 AI advisor for National AI Strategy and Data Centre from the Ministry of Science and
