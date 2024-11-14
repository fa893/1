
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>صفحة شركات الطاقة الشمسية في الأردن</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 0;
            display: flex;
            flex-direction: column;
            align-items: center;
        }
        .header {
            background-color: #004085;
            color: white;
            width: 100%;
            padding: 20px;
            text-align: center;
        }
        .header img {
            width: 100px;
            margin-bottom: 10px;
        }
        .search-container {
            margin: 20px;
            width: 100%;
            max-width: 600px; /* تحديد عرض أقصى للحقل */
        }
        .search-box {
            width: 100%;
            padding: 10px;
            font-size: 16px;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        .company-list {
            width: 100%;
            max-width: 600px; /* تحديد عرض أقصى للقائمة */
            margin: 20px auto;
            background: white;
            border-radius: 10px;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
            padding: 15px;
        }
        .company {
            margin: 10px 0;
            border-bottom: 1px solid #eee;
            padding: 10px 0;
        }
        .company:last-child {
            border-bottom: none; /* إزالة الخط الأخير */
        }
        .company-title {
            font-weight: bold;
            color: #004085;
        }
        .company-email {
            color: #007BFF;
            text-decoration: none;
        }
        .company-email:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>
    <div class="header">
        <h1>شركات الطاقة الشمسية في الأردن</h1>
    </div>

    <div class="search-container">
        <input type="text" id="searchInput" class="search-box" placeholder="ابحث عن شركة..." onkeyup="searchCompanies()">
    </div>

    <div class="company-list" id="companyList">
        <div class="company">
            <span class="company-title">شركة الفنار للطاقة الشمسية</span><br>
            <a href="mailto:info@alfanar.com" class="company-email">info@alfanar.com</a>
        </div>
        <div class="company">
            <span class="company-title">شركة نور الأردن للطاقة الشمسية</span><br>
            <a href="mailto:info@noorjo.com" class="company-email">info@noorjo.com</a>
        </div>
        <div class="company">
            <span class="company-title">شركة إيست كروب للطاقة</span><br>
            <a href="mailto:info@eastgroupenergy.com" class="company-email">info@eastgroupenergy.com</a>
        </div>
        <div class="company">
            <span class="company-title">شركة فينيكس للطاقة الشمسية</span><br>
            <a href="mailto:info@phoenixsolarenergy.com" class="company-email">info@phoenixsolarenergy.com</a>
        </div>
        <div class="company">
            <span class="company-title">شركة الدار للطاقة</span><br>
            <a href="mailto:info@aldarenergy.com" class="company-email">info@aldarenergy.com</a>
        </div>
        <div class="company">
            <span class="company-title">شركة طاقة الرياح والطاقة الشمسية</span><br>
            <a href="mailto:info@wspc.com" class="company-email">info@wspc.com</a>
        </div>
        <div class="company">
            <span class="company-title">شركة ميدل إيست للطاقة</span><br>
            <a href="mailto:info@middleeastenergy.com" class="company-email">info@middleeastenergy.com</a>
        </div>
        <div class="company">
            <span class="company-title">شركة إيفكو للطاقة</span><br>
            <a href="mailto:info@efcoenergy.com" class="company-email">info@efcoenergy.com</a>
        </div>
        <div class="company">
            <span class="company-title">شركة كريستال للطاقة</span><br>
            <a href="mailto:info@crystalenergy.com" class="company-email">info@crystalenergy.com</a>
        </div>
        <div class="company">
            <span class="company-title">شركة طاقة الأردن</span><br>
            <a href="mailto:info@jordanenergy.com" class="company-email">info@jordanenergy.com</a>
        </div>
        <div class="company">
            <span class="company-title">شركة سولار تيك للطاقة الشمسية (SolarTech)</span><br>
            <a href="mailto:info@solartechjo.com" class="company-email">info@solartechjo.com</a>
        </div>
        <div class="company">
            <span class="company-title">شركة أونيرا للطاقة الشمسية (Onira Solar)</span><br>
            <a href="mailto:info@onirasolar.com" class="company-email">info@onirasolar.com</a>
        </div>
        <div class="company">
            <span class="company-title">شركة سكاي لاين للطاقة الشمسية (Skyline Solar)</span><br>
            <a href="mailto:info@skylinesolar.com" class="company-email">info@skylinesolar.com</a>
        </div>
        <div class="company">
            <span class="company-title">شركة أبتيموس للطاقة الشمسية (Optimus Energy)</span><br>
            <a href="mailto:info@optimusenergy.com" class="company-email">info@optimusenergy.com</a>
        </div>
        <div class="company">
            <span class="company-title">شركة فيوتشر للطاقة الشمسية (Future Solar)</span><br>
            <a href="mailto:info@futuresolar.com" class="company-email">info@futuresolar.com</a>
        </div>
        <div class="company">
            <span class="company-title">شركة بتر سولار (Better Solar)</span><br>
            <a href="mailto:info@bettersolar.com" class="company-email">info@bettersolar.com</a>
        </div>
        <div class="company">
            <span class="company-title">شركة بوش للطاقة الشمسية (Bosch Solar)</span><br>
            <a href="mailto:info@boschsolar.com" class="company-email">info@boschsolar.com</a>
        </div>
        <div class="company">
            <span class="company-title">شركة النسر للطاقة الشمسية (Eagle Solar)</span><br>
            <a href="mailto:info@eaglesolar.com" class="company-email">info@eaglesolar.com</a>
        </div>
        <div class="company">
            <span class="company-title">شركة سيبكو للطاقة الشمسية (SEPCO Solar)</span><br>
            <a href="mailto:info@sepcosolar.com" class="company-email">info@sepcosolar.com</a>
        </div>
        <div class="company">
            <span class="company-title">شركة جرين ويف للطاقة الشمسية (Green Wave Energy)</span><br>
            <a href="mailto:info@greenwaveenergy.com" class="company-email">info@greenwaveenergy.com</a>
        </div>
        <div class="company">
            <span class="company-title">شركة المستقبل للطاقة الشمسية (Future Energy Solar)</span><br>
            <a href="mailto:info@futureenergysolar.com" class="company-email">info@futureenergysolar.com</a>
        </div>
        <div class="company">
            <span class="company-title">شركة أومني للطاقة الشمسية (Omni Energy)</span><br>
            <a href="mailto:info@omnienergy.com" class="company-email">info@omnienergy.com</a>
        </div>
        <div class="company">
            <span class="company-title">شركة بيكاسوس للطاقة الشمسية (Pegasus Solar)</span><br>
            <a href="mailto:info@pegasussolar.com" class="company-email">info@pegasussolar.com</a>
        </div>
        <div class="company">
            <span class="company-title">شركة سكاي إنرجي للطاقة الشمسية (Sky Energy)</span><br>
            <a href="mailto:info@skyenergy.com" class="company-email">info@skyenergy.com</a>
        </div>
        <div class="company">
            <span class="company-title">شركة نيوم للطاقة الشمسية (Neom Solar)</span><br>
            <a href="mailto:info@neomsolar.com" class="company-email">info@neomsolar.com</a>
        </div>
        <div class="company">
            <span class="company-title">شركة إل جي للطاقة الشمسية (LG Solar)</span><br>
            <a href="mailto:info@lgsolar.com" class="company-email">info@lgsolar.com</a>
        </div>
        <div class="company">
            <span class="company-title">شركة أكسيس للطاقة الشمسية (Axis Energy)</span><br>
            <a href="mailto:info@axisenergy.com" class="company-email">info@axisenergy.com</a>
        </div>
        <div class="company">
            <span class="company-title">شركة ألفا للطاقة الشمسية (Alpha Solar)</span><br>
            <a href="mailto:info@alphasolar.com" class="company-email">info@alphasolar.com</a>
        </div>
        <div class="company">
            <span class="company-title">شركة إنيرجي تيك للطاقة الشمسية (EnergyTech Solar)</span><br>
            <a href="mailto:info@energytechsolar.com" class="company-email">info@energytechsolar.com</a>
        </div>
        <div class="company">
            <span class="company-title">شركة تروبيكال للطاقة الشمسية (Tropical Solar)</span><br>
            <a href="mailto:info@tropicalsolar.com" class="company-email">info@tropicalsolar.com</a>
        </div>
        <div class="company">
            <span class="company-title">شركة صن باور للطاقة الشمسية (SunPower Solar)</span><br>
            <a href="mailto:info@sunpower.com" class="company-email">info@sunpower.com</a>
        </div>
        <div class="company">
            <span class="company-title">شركة مايكرو سولار للطاقة الشمسية (MicroSolar Energy)</span><br>
            <a href="mailto:info@microsolar.com" class="company-email">info@microsolar.com</a>
        </div>
        <div class="company">
            <span class="company-title">شركة سولار بلس للطاقة الشمسية (SolarPlus Energy)</span><br>
            <a href="mailto:info@solarplus.com" class="company-email">info@solarplus.com</a>
        </div>
        <div class="company">
            <span class="company-title">شركة كلير إنرجي للطاقة الشمسية (Clear Energy)</span><br>
            <a href="mailto:info@clearenergy.com" class="company-email">info@clearenergy.com</a>
        </div>
        <div class="company">
            <span class="company-title">شركة جولدن صن للطاقة الشمسية (Golden Sun Solar)</span><br>
            <a href="mailto:info@goldensun.com" class="company-email">info@goldensun.com</a>
        </div>
        <div class="company">
            <span class="company-title">شركة سيستم سولار للطاقة الشمسية (System Solar)</span><br>
            <a href="mailto:info@systemsolar.com" class="company-email">info@systemsolar.com</a>
        </div>
        <div class="company">
            <span class="company-title">شركة باور سولار للطاقة الشمسية (Power Solar)</span><br>
            <a href="mailto:info@powersolar.com" class="company-email">info@powersolar.com</a>
        </div>
        <div class="company">
            <span class="company-title">شركة سولار ترست للطاقة الشمسية (SolarTrust)</span><br>
            <a href="mailto:info@solartrust.com" class="company-email">info@solartrust.com</a>
        </div>
        <div class="company">
            <span class="company-title">شركة إيليت سولار للطاقة الشمسية (Elite Solar)</span><br>
            <a href="mailto:info@elitesolar.com" class="company-email">info@elitesolar.com</a>
        </div>
        <div class="company">
            <span class="company-title">شركة أدفانسد للطاقة الشمسية (Advanced Solar)</span><br>
            <a href="mailto:info@advancedsolar.com" class="company-email">info@advancedsolar.com</a>
        </div>
        <div class="company">
            <span class="company-title">شركة إيكو سولار للطاقة الشمسية (EcoSolar)</span><br>
            <a href="mailto:info@ecosolar.com" class="company-email">info@ecosolar.com</a>
        </div>
        <div class="company">
            <span class="company-title">شركة سولار إنرجي سولوشنز (Solar Energy Solutions)</span><br>
            <a href="mailto:info@solarenergysolutions.com" class="company-email">info@solarenergysolutions.com</a>
        </div>
        <div class="company">
            <span class="company-title">شركة سولار تكنولوجيز (Solar Technologies)</span><br>
            <a href="mailto:info@solartechnologies.com" class="company-email">info@solartechnologies.com</a>
        </div>
        <div class="company">
            <span class="company-title">شركة إنيرجي كير للطاقة الشمسية (EnergyCare Solar)</span><br>
            <a href="mailto:info@energycaresolar.com" class="company-email">info@energycaresolar.com</a>
        </div>
        <div class="company">
            <span class="company-title">شركة ترو سكيب للطاقة الشمسية (TrueScape Solar)</span><br>
            <a href="mailto:info@truescapesolar.com" class="company-email">info@truescapesolar.com</a>
        </div>
        <div class="company">
            <span class="company-title">شركة إنفينيتي للطاقة الشمسية (Infinity Solar)</span><br>
            <a href="mailto:info@infinitysolar.com" class="company-email">info@infinitysolar.com</a>
        </div>
        <div class="company">
            <span class="company-title">شركة بلو سكاي للطاقة الشمسية (Blue Sky Solar)</span><br>
            <a href="mailto:info@blueskysolar.com" class="company-email">info@blueskysolar.com</a>
        </div>
        <div class="company">
            <span class="company-title">شركة سولايت للطاقة الشمسية (Solight Solar)</span><br>
            <a href="mailto:info@solightsolar.com" class="company-email">info@solightsolar.com</a>
        </div>
        <div class="company">
            <span class="company-title">شركة جي إس للطاقة الشمسية (GS Solar)</span><br>
            <a href="mailto:info@gssolar.com" class="company-email">info@gssolar.com</a>
        </div>
        <div class="company">
            <span class="company-title">شركة تيتان للطاقة الشمسية (Titan Solar)</span><br>
            <a href="mailto:info@titansolar.com" class="company-email">info@titansolar.com</a>
        </div>
        <div class="company">
            <span class="company-title">شركة إنيرجي برو للطاقة الشمسية (EnergyPro Solar)</span><br>
            <a href="mailto:info@energyprosolar.com" class="company-email">info@energyprosolar.com</a>
        </div>
        <div class="company">
            <span class="company-title">شركة بريمير للطاقة الشمسية (Premier Solar)</span><br>
            <a href="mailto:info@premiersolar.com" class="company-email">info@premiersolar.com</a>
        </div>
        <div class="company">
            <span class="company-title">شركة فيجن للطاقة الشمسية (Vision Solar)</span><br>
            <a href="mailto:info@visionsolar.com" class="company-email">info@visionsolar.com</a>
        </div>
        <div class="company">
            <span class="company-title">شركة سولار تك للطاقة الشمسية (Solar Tech)</span><br>
            <a href="mailto:info@solartech.com" class="company-email">info@solartech.com</a>
        </div>
        <div class="company">
            <span class="company-title">شركة إنيشيال للطاقة الشمسية (Initial Solar)</span><br>
            <a href="mailto:info@initialsolar.com" class="company-email">info@initialsolar.com</a>
        </div>
        <div class="company">
            <span class="company-title">شركة سولار إنرجايزر (Solar Energizer)</span><br>
            <a href="mailto:info@solarenergizer.com" class="company-email">info@solarenergizer.com</a>
        </div>
        <div class="company">
            <span class="company-title">شركة إيليت للطاقة الشمسية (Elite Energy)</span><br>
            <a href="mailto:info@eliteenergy.com" class="company-email">info@eliteenergy.com</a>
        </div>
    </div>

    <script>
        function searchCompanies() {
            const input = document.getElementById('searchInput');
            const filter = input.value.toLowerCase();
            const companyList = document.getElementById('companyList');
            const companies = companyList.getElementsByClassName('company');

            for (let i = 0; i < companies.length; i++) {
                const title = companies[i].getElementsByClassName('company-title')[0];
                if (title) {
                    const txtValue = title.textContent || title.innerText;
                    companies[i].style.display = txtValue.toLowerCase().includes(filter) ? '' : 'none';
                }
            }
        }
    </script>
</body>
</html>
