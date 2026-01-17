# Life-Rehab-Center-
Addiction Rehabilitation Center

<!DOCTYPE html>
<html lang="bn">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>মাদকাসক্তি থেকে মুক্তি: একটি পুনর্বাসন যাত্রা</title>
    <link href="https://fonts.googleapis.com/css2?family=Hind+Siliguri:wght@400;500;600;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: 'Hind Siliguri', sans-serif;
            background: linear-gradient(135deg, #0c2461 0%, #1e3799 50%, #4a69bd 100%);
            color: #333;
            line-height: 1.6;
            padding: 20px;
            min-height: 100vh;
        }
        
        .container {
            max-width: 1200px;
            margin: 0 auto;
        }
        
        .center-header {
            background: rgba(255, 255, 255, 0.15);
            border-radius: 15px;
            padding: 20px;
            margin-bottom: 30px;
            text-align: center;
            border: 2px solid rgba(255, 255, 255, 0.2);
            box-shadow: 0 8px 20px rgba(0, 0, 0, 0.2);
        }
        
        .center-header h2 {
            color: white;
            font-size: 2.2rem;
            margin-bottom: 8px;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.3);
        }
        
        .center-header p {
            color: #e0e0e0;
            font-size: 1.3rem;
            opacity: 0.95;
        }
        
        header {
            text-align: center;
            color: white;
            padding: 20px 0 30px;
            margin-bottom: 10px;
        }
        
        h1 {
            font-size: 2.8rem;
            margin-bottom: 15px;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.3);
        }
        
        .tagline {
            font-size: 1.4rem;
            opacity: 0.9;
            max-width: 800px;
            margin: 0 auto;
        }
        
        .word-section {
            background-color: rgba(255, 255, 255, 0.95);
            border-radius: 15px;
            padding: 25px;
            margin-bottom: 40px;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.2);
            transition: transform 0.3s ease;
        }
        
        .word-section:hover {
            transform: translateY(-5px);
        }
        
        .section-title {
            color: #0c2461;
            font-size: 2.2rem;
            text-align: center;
            margin-bottom: 25px;
            padding-bottom: 15px;
            border-bottom: 3px solid #4a69bd;
        }
        
        .buttons-container {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            gap: 12px;
            margin-bottom: 30px;
        }
        
        .letter-btn {
            width: 60px;
            height: 60px;
            border: none;
            background: linear-gradient(145deg, #4a69bd, #1e3799);
            color: white;
            font-size: 1.8rem;
            font-weight: 700;
            border-radius: 50%;
            cursor: pointer;
            transition: all 0.3s ease;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }
        
        .letter-btn:hover {
            transform: scale(1.1);
            background: linear-gradient(145deg, #1e3799, #0c2461);
            box-shadow: 0 6px 12px rgba(0, 0, 0, 0.3);
        }
        
        .letter-btn.active {
            transform: scale(1.1);
            background: linear-gradient(145deg, #e55039, #eb2f06);
            box-shadow: 0 6px 12px rgba(235, 47, 6, 0.4);
        }
        
        .explanation-container {
            background-color: #f8f9fa;
            border-radius: 10px;
            padding: 25px;
            min-height: 200px;
            border-left: 5px solid #4a69bd;
            box-shadow: inset 0 0 10px rgba(0, 0, 0, 0.05);
        }
        
        .explanation-header {
            background: #0c2461;
            color: white;
            padding: 15px;
            border-radius: 8px;
            margin-bottom: 20px;
            text-align: center;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }
        
        .explanation-header h3 {
            font-size: 1.5rem;
            margin-bottom: 5px;
        }
        
        .explanation-header p {
            font-size: 1.1rem;
            opacity: 0.9;
        }
        
        .explanation-title {
            color: #0c2461;
            font-size: 1.8rem;
            margin-bottom: 15px;
            display: flex;
            align-items: center;
            gap: 10px;
        }
        
        .explanation-text {
            font-size: 1.2rem;
            color: #444;
            text-align: justify;
            margin-bottom: 15px;
        }
        
        .highlight {
            color: #e55039;
            font-weight: 700;
        }
        
        .meaning {
            font-style: italic;
            color: #1e3799;
            margin-top: 10px;
            font-size: 1.1rem;
            padding: 10px;
            background-color: rgba(74, 105, 189, 0.1);
            border-radius: 5px;
        }
        
        footer {
            text-align: center;
            color: white;
            padding: 25px 0;
            margin-top: 20px;
            border-top: 1px solid rgba(255, 255, 255, 0.1);
        }
        
        .heart {
            color: #e55039;
            animation: heartbeat 1.5s infinite;
        }
        
        @keyframes heartbeat {
            0%, 100% { transform: scale(1); }
            50% { transform: scale(1.1); }
        }
        
        @media (max-width: 768px) {
            .letter-btn {
                width: 50px;
                height: 50px;
                font-size: 1.5rem;
            }
            
            h1 {
                font-size: 2.2rem;
            }
            
            .section-title {
                font-size: 1.8rem;
            }
            
            .explanation-title {
                font-size: 1.5rem;
            }
            
            .center-header h2 {
                font-size: 1.8rem;
            }
            
            .center-header p {
                font-size: 1.1rem;
            }
        }
        
        @media (max-width: 480px) {
            .buttons-container {
                gap: 8px;
            }
            
            .letter-btn {
                width: 45px;
                height: 45px;
                font-size: 1.3rem;
            }
            
            h1 {
                font-size: 1.8rem;
            }
            
            .center-header {
                padding: 15px;
            }
        }
        
        .instructions {
            color: white;
            text-align: center;
            margin-bottom: 30px;
            font-size: 1.1rem;
            opacity: 0.9;
        }
        
        .section-header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            margin-bottom: 20px;
        }
        
        .back-btn {
            background: #e55039;
            color: white;
            border: none;
            padding: 10px 20px;
            border-radius: 50px;
            cursor: pointer;
            font-size: 1rem;
            font-weight: 600;
            transition: all 0.3s ease;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }
        
        .back-btn:hover {
            background: #eb2f06;
            transform: translateY(-2px);
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="center-header">
            <h2>লাইফ মাদকাসক্ত পূনর্বাসন কেন্দ্র</h2>
            <p>গাইটাল, কিশোরগঞ্জ | সংকলন : আসিফ রাহমান</p>
        </div>
        
        <header>
            <h1>মাদকাসক্তি থেকে মুক্তি: একটি পুনর্বাসন যাত্রা</h1>
            <p class="tagline">প্রতিটি অক্ষরের মধ্যে লুকিয়ে আছে মাদকমুক্ত জীবনের দীক্ষা, সাহস ও সম্ভাবনা</p>
        </header>
        
        <p class="instructions">প্রতিটি বাটনে ক্লিক করে সংশ্লিষ্ট অক্ষরের বিশেষ অর্থ ও ব্যাখ্যা জানুন</p>
        
        <!-- প্রথম অংশ: REHABILITATION -->
        <section class="word-section">
            <h2 class="section-title">REHABILITATION</h2>
            <div class="buttons-container" id="rehabilitation-buttons">
                <!-- বাটনগুলি জাভাস্ক্রিপ্ট দ্বারা যোগ করা হবে -->
            </div>
            <div class="explanation-container" id="rehabilitation-explanation">
                <div class="explanation-header">
                    <h3>লাইফ মাদকাসক্ত পূনর্বাসন কেন্দ্র</h3>
                    <p>গাইটাল, কিশোরগঞ্জ | সংকলন : আসিফ রাহমান</p>
                </div>
                <div class="explanation-title"><i class="fas fa-heartbeat"></i> একটি অক্ষর নির্বাচন করুন</div>
                <p class="explanation-text">উপরের বাটনগুলির যেকোনো একটিতে ক্লিক করে দেখুন কীভাবে <span class="highlight">REHABILITATION</span> শব্দের প্রতিটি অক্ষর মাদকাসক্তি থেকে মুক্তির যাত্রায় একটি বিশেষ গুরুত্ব বহন করে।</p>
            </div>
        </section>
        
        <!-- দ্বিতীয় অংশ: NARCOTICS -->
        <section class="word-section">
            <h2 class="section-title">NARCOTICS</h2>
            <div class="buttons-container" id="narcotics-buttons">
                <!-- বাটনগুলি জাভাস্ক্রিপ্ট দ্বারা যোগ করা হবে -->
            </div>
            <div class="explanation-container" id="narcotics-explanation">
                <div class="explanation-header">
                    <h3>লাইফ মাদকাসক্ত পূনর্বাসন কেন্দ্র</h3>
                    <p>গাইটাল, কিশোরগঞ্জ | সংকলন : আসিফ রাহমান</p>
                </div>
                <div class="explanation-title"><i class="fas fa-pills"></i> একটি অক্ষর নির্বাচন করুন</div>
                <p class="explanation-text">উপরের বাটনগুলির যেকোনো একটিতে ক্লিক করে দেখুন কীভাবে <span class="highlight">NARCOTICS</span> শব্দের প্রতিটি অক্ষর মাদকের ভয়াবহতা এবং এর থেকে মুক্তির পথ বোঝায়।</p>
            </div>
        </section>
        
        <!-- তৃতীয় অংশ: ANONYMOUS -->
        <section class="word-section">
            <h2 class="section-title">ANONYMOUS</h2>
            <div class="buttons-container" id="anonymous-buttons">
                <!-- বাটনগুলি জাভাস্ক্রিপ্ট দ্বারা যোগ করা হবে -->
            </div>
            <div class="explanation-container" id="anonymous-explanation">
                <div class="explanation-header">
                    <h3>লাইফ মাদকাসক্ত পূনর্বাসন কেন্দ্র</h3>
                    <p>গাইটাল, কিশোরগঞ্জ | সংকলন : আসিফ রাহমান</p>
                </div>
                <div class="explanation-title"><i class="fas fa-user-secret"></i> একটি অক্ষর নির্বাচন করুন</div>
                <p class="explanation-text">উপরের বাটনগুলির যেকোনো একটিতে ক্লিক করে দেখুন কীভাবে <span class="highlight">ANONYMOUS</span> শব্দের প্রতিটি অক্ষর গোপনীয়তা ও সমর্থন ব্যবস্থার গুরুত্ব প্রকাশ করে।</p>
            </div>
        </section>
        
        <footer>
            <p>মাদকাসক্তি কোন দুর্বলতা নয়, সাহায্য চাওয়াই হচ্ছে প্রথম ও প্রধান সাফল্য</p>
            <p>প্রতিটি জীবন মূল্যবান <span class="heart">❤</span></p>
            <p>© লাইফ মাদকাসক্ত পূনর্বাসন কেন্দ্র, গাইটাল, কিশোরগঞ্জ</p>
        </footer>
    </div>

    <script>
        // শব্দগুলির তথ্য
        const wordsData = {
            rehabilitation: {
                letters: ['R', 'E', 'H', 'A', 'B', 'I', 'L', 'I', 'T', 'A', 'T', 'I', 'O', 'N'],
                explanations: {
                    'R': {
                        title: 'পুনর্জাগরণ (Renewal)',
                        text: 'মাদকের অন্ধকার জগৎ থেকে বেরিয়ে আসা মানেই হলো জীবনের নতুন এক সূচনা। এটি একটি পুনর্জাগরণ, যেখানে আপনি আপনার হারানো স্বপ্ন, আশা ও সম্ভাবনাকে আবার ফিরে পাবেন। এই যাত্রায় প্রতিটি দিন আপনার জন্য নতুন ভোরের মতো, নতুন সম্ভাবনা নিয়ে আসবে। লাইফ মাদকাসক্ত পূনর্বাসন কেন্দ্র, গাইটাল, কিশোরগঞ্জ এই পুনর্জাগরণের যাত্রায় আপনার পাশে আছে।',
                        meaning: 'জীবনের নতুন সূচনা এবং আত্মার পুনর্জাগরণ'
                    },
                    'E': {
                        title: 'ক্ষমতায়ন (Empowerment)',
                        text: 'মাদকমুক্ত জীবন আপনাকে নতুন করে ক্ষমতায়িত করে। আপনি আবিষ্কার করবেন যে আপনি যা ভেবেছিলেন তার চেয়ে অনেক বেশি শক্তিশালী। আপনার ইচ্ছাশক্তি, দৃঢ়তা ও সিদ্ধান্ত গ্রহণের ক্ষমতা দিন দিন বাড়বে, যা আপনাকে জীবনের যেকোনো চ্যালেঞ্জ মোকাবেলা করতে সাহায্য করবে। লাইফ মাদকাসক্ত পূনর্বাসন কেন্দ্র, গাইটাল, কিশোরগঞ্জ আপনাকে এই ক্ষমতায়নের পথে সহায়তা করে।',
                        meaning: 'অভ্যন্তরীণ শক্তি ও সক্ষমতা অর্জন'
                    },
                    'H': {
                        title: 'আশা (Hope)',
                        text: 'মাদকাসক্তি থেকে মুক্তির পথে সবচেয়ে গুরুত্বপূর্ণ অনুভূতি হলো আশা। যখন মনে হবে সবকিছু অন্ধকার, তখনই এই আশার আলো আপনাকে পথ দেখাবে। মনে রাখবেন, প্রতিটি সূর্যোদয়ের মতো আপনার জীবনেরও নতুন একটি সুন্দর দিন শুরু হওয়ার অপেক্ষায় আছে। লাইফ মাদকাসক্ত পূনর্বাসন কেন্দ্র, গাইটাল, কিশোরগঞ্জ এই আশার বার্তা বহন করে।',
                        meaning: 'ভবিষ্যতের প্রতি ইতিবাচক দৃষ্টিভঙ্গি ও প্রত্যাশা'
                    },
                    'A': {
                        title: 'গ্রহণযোগ্যতা (Acceptance)',
                        text: 'আপনার অতীতকে গ্রহণ করা এবং বর্তমান অবস্থা মেনে নেয়া পুনর্বাসনের প্রথম ধাপ। এটি কোনো দুর্বলতা নয়, বরং সাহসিকতার পরিচয়। যখন আপনি নিজের ভুলগুলো স্বীকার করবেন, তখনই সেগুলো থেকে শিক্ষা নিয়ে সামনে এগিয়ে যাওয়ার পথ তৈরি হবে। লাইফ মাদকাসক্ত পূনর্বাসন কেন্দ্র, গাইটাল, কিশোরগঞ্জ আপনাকে এই গ্রহণযোগ্যতার পথে নিয়ে যায়।',
                        meaning: 'স্ব-স্বীকারোক্তি এবং বাস্তবতা মেনে নেওয়া'
                    },
                    'B': {
                        title: 'বিশ্বাস (Belief)',
                        text: 'নিজের উপর এবং এই পুনর্বাসন প্রক্রিয়ার উপর অগাধ বিশ্বাস রাখুন। বিশ্বাসই সেই শক্তি যা আপনাকে প্রতিটি প্রতিবন্ধকতা অতিক্রম করতে সাহায্য করবে। মনে রাখবেন, আপনি এই কঠিন পথ পার হতে সক্ষম, কারণ আপনার মধ্যে এই শক্তি আছে। লাইফ মাদকাসক্ত পূনর্বাসন কেন্দ্র, গাইটাল, কিশোরগঞ্জ এই বিশ্বাসকে শক্তিশালী করে।',
                        meaning: 'নিজের এবং পুনর্বাসন প্রক্রিয়ার উপর আস্থা'
                    },
                    'I': {
                        title: 'অন্তর্দৃষ্টি (Insight)',
                        text: 'পুনর্বাসনের মাধ্যমে আপনি আপনার ভেতরের জগৎ সম্পর্কে গভীর অন্তর্দৃষ্টি লাভ করবেন। আপনি বুঝতে শিখবেন কী কারণে আপনি মাদকের দিকে ঝুঁকেছিলেন এবং কীভাবে সেই ট্রিগারগুলো এড়িয়ে চলবেন। এই স্ব-সচেতনতা আপনাকে চিরতরে মাদকমুক্ত থাকতে সাহায্য করবে। লাইফ মাদকাসক্ত পূনর্বাসন কেন্দ্র, গাইটাল, কিশোরগঞ্জ এই অন্তর্দৃষ্টি অর্জনে সহায়তা করে।',
                        meaning: 'নিজের সম্পর্কে গভীর উপলব্ধি ও বোঝাপড়া'
                    },
                    'L': {
                        title: 'প্রেম (Love)',
                        text: 'নিজেকে ভালোবাসা শিখুন। মাদকাসক্তির সময় আপনি নিজেকে যে অবহেলা করেছিলেন, এখন সময় এসেছে নিজেকে ক্ষমা করে ভালোবাসার। আপনার পরিবার, বন্ধু এবং পরিচর্যাকারীদের ভালোবাসা আপনাকে এই যাত্রায় শক্তি যোগাবে। লাইফ মাদকাসক্ত পূনর্বাসন কেন্দ্র, গাইটাল, কিশোরগঞ্জ প্রেম ও স্নেহের পরিবেশ তৈরি করে।',
                        meaning: 'স্ব-প্রেম এবং অন্যদের কাছ থেকে ভালোবাসা'
                    },
                    'T': {
                        title: 'স্থিতিশীলতা (Stability)',
                        text: 'পুনর্বাসনের মূল লক্ষ্য হলো একটি স্থিতিশীল, ভারসাম্যপূর্ণ জীবন গড়ে তোলা। যেখানে আবেগীয় অস্থিরতা থাকবে না, বরং থাকবে মনের শান্তি ও জীবনযাপনের নিয়মিততা। এই স্থিতিশীলতা আপনাকে দীর্ঘমেয়াদি সাফল্য এনে দেবে। লাইফ মাদকাসক্ত পূনর্বাসন কেন্দ্র, গাইটাল, কিশোরগঞ্জ স্থিতিশীল জীবনের ভিত গড়ে দিতে সহায়তা করে।',
                        meaning: 'জীবনে ভারসাম্য ও স্থিতিশীলতা অর্জন'
                    },
                    'O': {
                        title: 'সুযোগ (Opportunity)',
                        text: 'মাদকমুক্ত জীবন আপনাকে অসংখ্য নতুন সুযোগের দরজা খুলে দেবে। যা আগে অসম্ভব মনে হতো, এখন সেগুলো অর্জনের পথে এগিয়ে যেতে পারবেন। এই জীবন আপনাকে নতুন দক্ষতা শিখতে, নতুন সম্পর্ক গড়তে এবং নতুন লক্ষ্য নির্ধারণ করতে সাহায্য করবে। লাইফ মাদকাসক্ত পূনর্বাসন কেন্দ্র, গাইটাল, কিশোরগঞ্জ নতুন সুযোগ সৃষ্টিতে সহায়তা করে।',
                        meaning: 'নতুন সম্ভাবনা এবং জীবন পরিবর্তনের সুযোগ'
                    },
                    'N': {
                        title: 'স্বাভাবিকতা (Normalcy)',
                        text: 'পুনর্বাসনের চূড়ান্ত লক্ষ্য হলো একটি স্বাভাবিক, সুস্থ জীবন ফিরে পাওয়া। সেই জীবন যেখানে মাদকের প্রয়োজন হবে না, বরং ছোট ছোট আনন্দগুলোই জীবনকে অর্থবহ করে তুলবে। প্রতিদিনের সাধারণ মুহূর্তগুলোই হয়ে উঠবে অসাধারণ। লাইফ মাদকাসক্ত পূনর্বাসন কেন্দ্র, গাইটাল, কিশোরগঞ্জ এই স্বাভাবিকতা ফিরে পেতে সহায়তা করে।',
                        meaning: 'একটি মাদকমুক্ত স্বাভাবিক জীবন ফিরে পাওয়া'
                    }
                }
            },
            
            narcotics: {
                letters: ['N', 'A', 'R', 'C', 'O', 'T', 'I', 'C', 'S'],
                explanations: {
                    'N': {
                        title: 'বিধ্বংসী (Noxious)',
                        text: 'মাদক হলো এক বিষাক্ত, বিধ্বংসী শক্তি যা ধীরে ধীরে আপনার শারীরিক ও মানসিক স্বাস্থ্যকে গ্রাস করে। এটি আপনার স্নায়ুতন্ত্রকে ধ্বংস করে, মস্তিষ্কের কার্যক্ষমতা কমিয়ে দেয় এবং শেষ পর্যন্ত সম্পূর্ণ ব্যক্তিত্বকে বিলুপ্ত করে দেয়। লাইফ মাদকাসক্ত পূনর্বাসন কেন্দ্র, গাইটাল, কিশোরগঞ্জ এই বিধ্বংসী শক্তির বিরুদ্ধে লড়াইয়ে সাহায্য করে।',
                        meaning: 'বিষাক্ত এবং ধ্বংসাত্মক পদার্থ'
                    },
                    'A': {
                        title: 'নির্ভরশীলতা (Addiction)',
                        text: 'মাদক এক ভয়াবহ নির্ভরশীলতা তৈরি করে যা শিকলের মতো আপনাকে বেঁধে ফেলে। শুরুতে এটি মনে হয় স্বাধীনতার অনুভূতি দিচ্ছে, কিন্তু পরিণতিতে এটি সবচেয়ে বড় দাসত্বে পরিণত হয়, যেখানে আপনার ইচ্ছাশক্তি সম্পূর্ণভাবে মাদকের কাছে জিম্মি হয়ে পড়ে। লাইফ মাদকাসক্ত পূনর্বাসন কেন্দ্র, গাইটাল, কিশোরগঞ্জ এই নির্ভরশীলতা কাটাতে সহায়তা করে।',
                        meaning: 'শারীরিক ও মানসিক নির্ভরশীলতা তৈরি করা'
                    },
                    'R': {
                        title: 'ক্ষতি (Ruin)',
                        text: 'মাদক আপনার জীবনের সবকিছুকে ধ্বংস করে দেয় - সম্পর্ক, ক্যারিয়ার, স্বাস্থ্য, আত্মসম্মান। এটি একের পর এক আপনার জীবনের মূল্যবান সবকিছু কেড়ে নেয়, যতক্ষণ না আপনি একাকী, অসহায় এবং আশাহীন অবস্থায় পৌঁছান। লাইফ মাদকাসক্ত পূনর্বাসন কেন্দ্র, গাইটাল, কিশোরগঞ্জ এই ক্ষতি পূরণে সহায়তা করে।',
                        meaning: 'জীবনের সব ক্ষেত্রে ধ্বংস ও ক্ষতি সাধন'
                    },
                    'C': {
                        title: 'বন্দিত্ব (Confinement)',
                        text: 'মাদক আসলে একটি অদৃশ্য কারাগার তৈরি করে, যেখানে আপনি নিজের ইচ্ছায় বন্দি হন। এই কারাগারে শারীরিক বেড়াল নেই, কিন্তু মানসিক শৃঙ্খল এতটাই শক্ত যে তা ভাঙা প্রায় অসম্ভব মনে হয়। আপনি স্বাধীন মনে হলেও আসলে মাদকের গোলামে পরিণত হন। লাইফ মাদকাসক্ত পূনর্বাসন কেন্দ্র, গাইটাল, কিশোরগঞ্জ এই বন্দিত্ব থেকে মুক্তির পথ দেখায়।',
                        meaning: 'মানসিক ও শারীরিক বন্দিত্ব তৈরি করা'
                    },
                    'O': {
                        title: 'মৃত্যু (Oblivion)',
                        text: 'মাদকের অতিরিক্ত সেবন সরাসরি মৃত্যুর দিকে নিয়ে যায়। ধীরে ধীরে এটি আপনার অঙ্গপ্রত্যঙ্গগুলোকে অকেজো করে, রোগ প্রতিরোধ ক্ষমতা নষ্ট করে এবং শেষ পর্যন্ত একটি করুণ মৃত্যু ডেকে আনে। মাদক সেবন আসলে আত্মহননেরই একটি ধীর প্রক্রিয়া। লাইফ মাদকাসক্ত পূনর্বাসন কেন্দ্র, গাইটাল, কিশোরগঞ্জ এই মৃত্যুর পথ থেকে ফিরিয়ে আনে।',
                        meaning: 'ধ্বংস, বিস্মৃতি এবং শেষ পর্যন্ত মৃত্যুর দিকে নিয়ে যাওয়া'
                    },
                    'T': {
                        title: 'বিশ্বাসঘাতকতা (Treachery)',
                        text: 'মাদক হলো এক চরম বিশ্বাসঘাতক। এটি প্রথমে আপনাকে সুখ, স্বস্তি ও মুক্তির মিথ্যা প্রতিশ্রুতি দেয়, কিন্তু পরে সেই সুখের বদলে দেয় অসহনীয় যন্ত্রণা, শূন্যতা ও হতাশা। এটি আপনার সবচেয়ে খারাপ শত্রু যে আপনাকে ধোঁকা দেয়। লাইফ মাদকাসক্ত পূনর্বাসন কেন্দ্র, গাইটাল, কিশোরগঞ্জ এই বিশ্বাসঘাতকতার বিরুদ্ধে সচেতন করে।',
                        meaning: 'মিথ্যা আশ্বাস দিয়ে ধোঁকা দেওয়া'
                    },
                    'I': {
                        title: 'অসহায়ত্ব (Impotence)',
                        text: 'মাদক আপনাকে ধীরে ধীরে সম্পূর্ণ অসহায় করে তোলে। এটি আপনার সিদ্ধান্ত নেওয়ার ক্ষমতা, যুক্তিবোধ এবং নৈতিকতাকে ধ্বংস করে। আপনি এমন এক অবস্থায় পৌঁছান যেখানে নিজের ইচ্ছাশক্তির উপর আপনার কোনো নিয়ন্ত্রণ থাকে না। লাইফ মাদকাসক্ত পূনর্বাসন কেন্দ্র, গাইটাল, কিশোরগঞ্জ এই অসহায়ত্ব কাটাতে সহায়তা করে।',
                        meaning: 'ইচ্ছাশক্তি ও সিদ্ধান্ত নেওয়ার ক্ষমতা হারানো'
                    },
                    'S': {
                        title: 'দুর্ভোগ (Suffering)',
                        text: 'মাদকের চূড়ান্ত পরিণতি হলো অপরিমেয় দুর্ভোগ। এটি শুধু সেবনকারীকেই নয়, তার পরিবার, বন্ধু এবং সমাজকেও কষ্ট দেয়। এই দুর্ভোগ শারীরিক, মানসিক, আর্থিক এবং সামাজিক - সব দিক থেকে জীবনকে দুর্বিষহ করে তোলে। লাইফ মাদকাসক্ত পূনর্বাসন কেন্দ্র, গাইটাল, কিশোরগঞ্জ এই দুর্ভোগ থেকে মুক্তির পথ দেখায়।',
                        meaning: 'অসহনীয় শারীরিক ও মানসিক কষ্ট প্রদান'
                    }
                }
            },
            
            anonymous: {
                letters: ['A', 'N', 'O', 'N', 'Y', 'M', 'O', 'U', 'S'],
                explanations: {
                    'A': {
                        title: 'অ-নাম প্রকাশ (Anonymous)',
                        text: 'মাদকাসক্তি থেকে মুক্তির যাত্রায় গোপনীয়তা রক্ষা করা অত্যন্ত গুরুত্বপূর্ণ। অনেকেই সামাজিক ভয় ও লজ্জার কারণে সাহায্য নিতে দ্বিধাবোধ করেন। গোপনীয়তা এই ভয় দূর করে এবং নিরাপদ পরিবেশ তৈরি করে যেখানে ব্যক্তি নিজের সমস্যা নিয়ে খোলামনে কথা বলতে পারেন। লাইফ মাদকাসক্ত পূনর্বাসন কেন্দ্র, গাইটাল, কিশোরগঞ্জ গোপনীয়তা রক্ষার অঙ্গীকার করে।',
                        meaning: 'গোপনীয়তা রক্ষা এবং পরিচয় লুকিয়ে রাখা'
                    },
                    'N': {
                        title: 'নিরাপত্তা (Security)',
                        text: 'এই গোপনীয়তা ব্যক্তিকে নিরাপত্তার অনুভূতি দেয়। তারা জানেন যে তাদের ব্যক্তিগত তথ্য এবং সংগ্রামের গল্প নিরাপদ হাতে থাকবে। এই নিরাপত্তা তাদের চিকিৎসা প্রক্রিয়ায় সম্পূর্ণরূপে মনোযোগ দিতে সাহায্য করে, কারণ তারা সামাজিক বিচারের ভয়ে ভুগছেন না। লাইফ মাদকাসক্ত পূনর্বাসন কেন্দ্র, গাইটাল, কিশোরগঞ্জ সম্পূর্ণ নিরাপদ পরিবেশ প্রদান করে।',
                        meaning: 'নিরাপদ ও গোপন পরিবেশ তৈরি করা'
                    },
                    'O': {
                        title: 'খোলামন (Openness)',
                        text: 'গোপনীয়তার পরিবেশে ব্যক্তি নিজের সবচেয়ে গভীর ভয়, দুঃখ ও দুর্বলতা খোলামনে প্রকাশ করতে পারেন। তারা নিজের সমস্ত সত্য কথা বলতে পারেন, কোনো প্রকার ছলনা বা লুকোচুরি ছাড়াই। এই খোলামনতা পুনর্বাসন প্রক্রিয়াকে অনেক বেশি কার্যকর করে তোলে। লাইফ মাদকাসক্ত পূনর্বাসন কেন্দ্র, গাইটাল, কিশোরগঞ্জ খোলামনের পরিবেশ তৈরি করে।',
                        meaning: 'নিরাপদ পরিবেশে নিজেকে সম্পূর্ণভাবে উন্মুক্ত করা'
                    },
                    'Y': {
                        title: 'আপনি (You)',
                        text: 'এই পুরো প্রক্রিয়ার কেন্দ্রে রয়েছেন আপনি। গোপনীয়তা এই বার্তা দেয় যে এখানে আপনি গুরুত্বপূর্ণ, আপনার পরিচয় নয়। আপনার সংগ্রাম, আপনার অনুভূতি, আপনার পুনরুদ্ধার - এই সবকিছুই মুখ্য, বাইরের দুনিয়ার মতামত নয়। লাইফ মাদকাসক্ত পূনর্বাসন কেন্দ্র, গাইটাল, কিশোরগঞ্জ আপনাকে কেন্দ্রে রেখেই কাজ করে।',
                        meaning: 'ব্যক্তি হিসেবে আপনার মূল্য ও গুরুত্ব'
                    },
                    'M': {
                        title: 'সংহতি (Mutual Support)',
                        text: 'গোপনীয়তার মাধ্যমে তৈরি হয় এক অনন্য সংহতি। যখন সবাই নামহীন, তখন আসক্তি ছাড়ার সংগ্রামে একে অপরের জন্য শক্ত সমর্থন ব্যবস্থা গড়ে উঠে। এই সংহতি অজানা মানুষদের মধ্যে একটি গভীর বন্ধন তৈরি করে, যারা একই যুদ্ধে লড়ছেন। লাইফ মাদকাসক্ত পূনর্বাসন কেন্দ্র, গাইটাল, কিশোরগঞ্জ এই সংহতি তৈরি করে।',
                        meaning: 'গোপনীয়তার মধ্য দিয়ে পারস্পরিক সমর্থন তৈরি'
                    },
                    'U': {
                        title: 'স্বীকৃতি (Understanding)',
                        text: 'গোপনীয়তার পরিবেশে আপনি এমন মানুষের সাথে মিশছেন যারা আপনার সংগ্রাম বুঝতে পারেন, কারণ তারা নিজেরাও একই পথ অতিক্রম করছেন। এই পারস্পরিক স্বীকৃতি ও বোঝাপড়া অনেক বেশি শক্তিশালী, কারণ এখানে কোনো ভণ্ডামি বা বিচার নেই। লাইফ মাদকাসক্ত পূনর্বাসন কেন্দ্র, গাইটাল, কিশোরগঞ্জ পারস্পরিক বোঝাপড়ার পরিবেশ তৈরি করে।',
                        meaning: 'একই সংগ্রামের মানুষদের মধ্যে পারস্পরিক বোঝাপড়া'
                    },
                    'S': {
                        title: 'গোপনতা (Secrecy)',
                        text: 'এই গোপনীয়তা আসলে একটি পবিত্র বিশ্বাসের প্রতীক। এটি প্রতিটি ব্যক্তিকে আশ্বাস দেয় যে তাদের গোপন তথ্য কখনোই প্রকাশ পাবে না। এই গোপনতা রক্ষা করা পুনর্বাসন প্রক্রিয়ার একটি মৌলিক নীতি এবং সমস্ত অংশগ্রহণকারীর দায়িত্ব। লাইফ মাদকাসক্ত পূনর্বাসন কেন্দ্র, গাইটাল, কিশোরগঞ্জ গোপনতা রক্ষার অঙ্গীকারবদ্ধ।',
                        meaning: 'গোপন তথ্য রক্ষা করার পবিত্র দায়িত্ব'
                    }
                }
            }
        };

        // DOM কন্টেন্ট লোড হওয়ার পর
        document.addEventListener('DOMContentLoaded', function() {
            // প্রতিটি শব্দের জন্য বাটন তৈরি করুন
            createButtonsForWord('rehabilitation');
            createButtonsForWord('narcotics');
            createButtonsForWord('anonymous');
            
            // প্রথম বাটনটি সক্রিয় করুন
            const firstBtnRehab = document.querySelector('#rehabilitation-buttons .letter-btn');
            const firstBtnNarc = document.querySelector('#narcotics-buttons .letter-btn');
            const firstBtnAnon = document.querySelector('#anonymous-buttons .letter-btn');
            
            if(firstBtnRehab) firstBtnRehab.click();
            if(firstBtnNarc) firstBtnNarc.click();
            if(firstBtnAnon) firstBtnAnon.click();
        });

        // একটি শব্দের জন্য বাটন তৈরি করার ফাংশন
        function createButtonsForWord(wordKey) {
            const wordData = wordsData[wordKey];
            const buttonsContainer = document.getElementById(`${wordKey}-buttons`);
            
            // বাটন তৈরি করুন
            wordData.letters.forEach(letter => {
                const button = document.createElement('button');
                button.className = 'letter-btn';
                button.textContent = letter;
                button.dataset.letter = letter;
                button.dataset.word = wordKey;
                
                button.addEventListener('click', function() {
                    // একই শব্দের অন্যান্য বাটন থেকে সক্রিয় ক্লাস সরান
                    document.querySelectorAll(`#${wordKey}-buttons .letter-btn`).forEach(btn => {
                        btn.classList.remove('active');
                    });
                    
                    // বর্তমান বাটনে সক্রিয় ক্লাস যোগ করুন
                    this.classList.add('active');
                    
                    // ব্যাখ্যা প্রদর্শন করুন
                    showExplanation(wordKey, letter);
                });
                
                buttonsContainer.appendChild(button);
            });
        }

        // ব্যাখ্যা প্রদর্শনের ফাংশন
        function showExplanation(wordKey, letter) {
            const wordData = wordsData[wordKey];
            const explanation = wordData.explanations[letter];
            const explanationContainer = document.getElementById(`${wordKey}-explanation`);
            
            if (explanation) {
                explanationContainer.innerHTML = `
                    <div class="explanation-header">
                        <h3>লাইফ মাদকাসক্ত পূনর্বাসন কেন্দ্র</h3>
                        <p>গাইটাল, কিশোরগঞ্জ | সংকলন : আসিফ রাহমান</p>
                    </div>
                    <div class="explanation-title"><i class="fas fa-star"></i> ${explanation.title}</div>
                    <p class="explanation-text">${explanation.text}</p>
                    <p class="meaning"><strong>অর্থ:</strong> ${explanation.meaning}</p>
                `;
            } else {
                explanationContainer.innerHTML = `
                    <div class="explanation-header">
                        <h3>লাইফ মাদকাসক্ত পূনর্বাসন কেন্দ্র</h3>
                        <p>গাইটাল, কিশোরগঞ্জ | সংকলন : আসিফ রাহমান</p>
                    </div>
                    <div class="explanation-title"><i class="fas fa-question-circle"></i> তথ্য প্রস্তুত হচ্ছে</div>
                    <p class="explanation-text">এই অক্ষরের জন্য ব্যাখ্যা খুব শীঘ্রই যোগ করা হবে।</p>
                `;
            }
        }
    </script>
</body>
</html>
