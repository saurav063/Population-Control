<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Population Control Awareness & Family Planner</title>
    <style>
        /* General Styling */
        body {
            font-family: 'Open Sans', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #dcc48e;
            color: #dcc48e;
        }

        /* Header Styling */
        header {
            background-color: #505168;
            color: dcc 48em; 
            text-align: center;
            padding: 20px 0;
            box-shadow: 0 4px 8px #493628;
        }

        header h1 {
            font-size: 2.5em;
            margin: 0;
        }

        header p {
            font-size: 1.2em;
        }

        /* Section Styling */
        section {
            padding: 30px;
            margin: 30px auto;
            max-width: 1200px;
            background-color: #505168;
            border-radius: 10px;
            box-shadow: 0 6px 15px #493628;
        }

        h2 {
            color: #dcc48e;
            font-size: 2em;
            margin-bottom: 20px;
            text-decoration: underline;
        }

        p {
            font-size: 1.1em;
            line-height: 1.6;
        }

        /* Form Styling */
        form {
            background-color: #8d836d;
            padding: 20px;
            border-radius: 8px;
            margin-top: 30px;
            box-shadow: 0 4px 12px #8d836d;
        }

        label {
            font-weight: bold;
            margin-bottom: 8px;
            display: block;
        }

        input, button {
            width: 100%;
            padding: 12px;
            margin-bottom: 15px;
            border: 1px solid #E4E0E1;
            border-radius: 6px;
            font-size: 1em;
        }

        input:focus {
            border-color: #AB886D ;
            outline: none;
            box-shadow: 0 0 8px #493628;
        }

        button {
            background-color: #E4E0E1;
            color: #493628;
            border: none;
            cursor: pointer;
            transition: background-color 0.3s ease;
            font-weight: bold;
        }

        button:hover {
            background-color: #E4E0E1;
        }

        /* Result Text Styling */
        #result {
            font-size: 1.2em;
            font-weight: bold;
            color: BC7C7C;
            margin-top: 20px;
        }

        /* Footer Styling */
        footer {
            text-align: center;
            padding: 20px;
            background-color: #E4E0E1;
            color: white;
            margin-top: 30px;
            box-shadow: 0 -4px 8px #493628;
        }

        footer p {
            margin: 0;
            font-size: 1.1em;
        }

        /* Responsive Design */
        @media (max-width: 768px) {
            section {
                margin: 20px;
                padding: 20px;
            }

            header h1 {
                font-size: 2em;
            }

            header p {
                font-size: 1em;
            }

            h2 {
                font-size: 1.8em;
            }

            p, form, footer p {
                font-size: 1em;
            }
        }
    </style>
</head>
<body>

    <header>
        <h1>Population Control & Family Planning</h1>
        <p>Promote a sustainable future by planning for your family responsibly.</p>
    </header>

    <section>
        <h2>The Importance of Population Control</h2>
        <p>
            Population control is crucial to ensure a balanced ecosystem and a sustainable future for the next generations. 
            With proper family planning, families can offer each child a better future by focusing on education, healthcare, 
            and environmental resources. Planning the number of children responsibly can help reduce strain on limited resources 
            while ensuring a higher quality of life for every family member.
        </p>
    </section>

    <section>
        <h2>Family Planner: Calculate Your Future Education Fund</h2>
        <form id="planner-form">
            <label for="numChildren">Number of Children</label>
            <input type="number" id="numChildren" placeholder="Enter how many children you're planning for" required>

            <label for="currentCost">Current Annual Education Cost per Child (in USD)</label>
            <input type="number" id="currentCost" placeholder="Enter current yearly education cost per child" required>

            <label for="inflationRate">Expected Inflation Rate (%)</label>
            <input type="number" id="inflationRate" placeholder="Enter the inflation rate for education costs" required>

            <label for="yearsUntilCollege">Years Until Children Start College</label>
            <input type="number" id="yearsUntilCollege" placeholder="Enter the number of years until children go to college" required>

            <button type="button" onclick="calculateEducationFund()">Calculate Total Education Fund</button>

            <p id="result"></p>
        </form>
    </section>

    <p>
        <H3 STYLE="text-decoration-line: underline; COLOR:BLACK"> Some Government Policies</H3>
        <a href="https://pib.gov.in/Pressreleaseshare.aspx?PRID=1740753">NATIONAL POPULATION POLICY</a><BR>
        <a href="https://www.news18.com/news/politics/yogi-adityanaths-hum-do-hamaare-do-push-in-up-as-state-unveils-new-population-policy-to-aid-development-3950399.html">HUM DO HAMARE DO CAMPAIGN</a><BR>
        <a href="https://pib.gov.in/PressReleasePage.aspx?PRID=1495137 href">MISSION PARIVAR VIKAS</a><BR>
    
        <H3 STYLE="text-decoration-line: underline; COLOR:BLACK">SOME MEASURES TO FOLLOW</H3>
        <ol>
            <li><a href="https://www.bing.com/ck/a?!&&p=0d69665a2a4a45ba40544e25e93a8af855a5d87fd4196b67b1233cac72adf779JmltdHM9MTczMDg1MTIwMA&ptn=3&ver=2&hsh=4&fclid=2bb07d53-c2e0-6b17-2f15-69e1c3e66a51&psq=how+does+condom+work&u=a1aHR0cHM6Ly93d3cucGxhbm5lZHBhcmVudGhvb2Qub3JnL2xlYXJuL2JpcnRoLWNvbnRyb2wvY29uZG9t&ntb=1">Condoms and their use</a></li>
        <li><a href="https://www.bing.com/ck/a?!&&p=a8321c0a5b0681e5e50ff10dfe8c78d46f5ff23be47394c830d27d5b6881bec3JmltdHM9MTczMDg1MTIwMA&ptn=3&ver=2&hsh=4&fclid=2bb07d53-c2e0-6b17-2f15-69e1c3e66a51&psq=copper+t+use&u=a1aHR0cHM6Ly93d3cuaGFwcGllc3RoZWFsdGguY29tL2FydGljbGVzL3dvbWVucy13ZWxsbmVzcy9jb3BwZXItaXVkLXNhZmV0eS1hbmQtZWZmaWNhY3kjOn46dGV4dD1Db3BwZXIlMjBJVUQlMjBpcyUyMGElMjBub24taG9ybW9uYWwlMjBjb250cmFjZXB0aXZlJTIwZGV2aWNlJTIwd2hpY2gsdGhyZWUlMjB0byUyMHRlbiUyMHllYXJzJTJDJTIwZGVwZW5kaW5nJTIwb24lMjB0aGUlMjB0eXBlLg&ntb=1">Copper T</a></li>
        <LI><A HREF="https://www.instah.com/women-health/emergency-contraceptive-pills-india/">Anti Pregnancy Pills</A></LI>
        <li><a href="https://www.who.int/news-room/fact-sheets/detail/family-planning-contraception">Other WHO approved methods</a></li>
        
        
        </ol>
    <a href=""
    </p>

    <footer>
        <p>Together we can plan for a brighter future. Start planning for your family today!</p>
    </footer>

    <script>
        function calculateEducationFund() {
            const numChildren = parseInt(document.getElementById("numChildren").value);
            const currentCost = parseFloat(document.getElementById("currentCost").value);
            const inflationRate = parseFloat(document.getElementById("inflationRate").value) / 100;
            const yearsUntilCollege = parseInt(document.getElementById("yearsUntilCollege").value);

            let futureCostPerChild = currentCost * Math.pow((1 + inflationRate), yearsUntilCollege);
            let totalFutureCost = futureCostPerChild * numChildren;

            totalFutureCost = totalFutureCost.toFixed(2);

            document.getElementById("result").innerHTML = `To educate ${numChildren} children, you will need approximately $${totalFutureCost} for their education by the time they reach college.`;
        }
    </script>

</body>
</html>
