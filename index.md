<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>A/B Testing Tutorial</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>A/B Testing Tutorial</h1>
        <p>Learn the art and science of experimentation from real-world experience.</p>
    </header>

    <nav>
        <ul>
            <li><a href="#introduction">Introduction</a></li>
            <li><a href="#control-group">Control Group and Design of Experiments</a></li>
            <li><a href="#calculator">Sample Size Calculator</a></li>
            <li><a href="#ui-testing">UI Testing and Experimentation</a></li>
            <li><a href="#mistakes">Common Mistakes</a></li>
        </ul>
    </nav>

    <main>
        <section id="introduction">
            <h2>Introduction</h2>
            <p>A/B testing is a powerful method for making data-informed decisions. Through this tutorial, I share my experiences designing and analyzing experiments that have driven impactful results.</p>
        </section>

        <section id="control-group">
            <h2>Control Group and Design of Experiments</h2>
            <p>The control group serves as the baseline in any A/B test. Concepts like ANOVA (Analysis of Variance) and factorial design help analyze results when multiple variables are at play.</p>
            <p><strong>Key Tips:</strong></p>
            <ul>
                <li>Ensure random assignment to control and test groups.</li>
                <li>Use factorial designs for complex experiments.</li>
                <li>Analyze results using statistical tools like Python or Excel.</li>
            </ul>
        </section>

        <section id="calculator">
            <h2>Sample Size Calculator</h2>
            <p>Use the calculator below to determine the required sample size for your experiment.</p>
            <form>
                <label for="baseline-conversion">Baseline Conversion Rate (%):</label>
                <input type="number" id="baseline-conversion" step="0.01" placeholder="e.g., 10">
                <br>

                <label for="expected-uplift">Expected Uplift (%):</label>
                <input type="number" id="expected-uplift" step="0.01" placeholder="e.g., 5">
                <br>

                <label for="confidence-level">Confidence Level (%):</label>
                <input type="number" id="confidence-level" step="1" placeholder="e.g., 95">
                <br>

                <label for="power">Statistical Power (%):</label>
                <input type="number" id="power" step="1" placeholder="e.g., 80">
                <br>

                <button type="button" onclick="calculateSampleSize()">Calculate</button>
            </form>
            <p id="sample-size-result"></p>
        </section>

        <section id="ui-testing">
            <h2>UI Testing and Experimentation</h2>
            <p>Experiment with different UI elements such as button colors, headlines, or layouts. Visualize how small changes can impact user behavior.</p>
            <img src="ui-testing-example.jpg" alt="Example of UI Testing">
        </section>

        <section id="mistakes">
            <h2>Common Mistakes in A/B Testing</h2>
            <ul>
                <li>Ending tests too early due to insufficient data.</li>
                <li>Testing multiple changes at once without isolating variables.</li>
                <li>Ignoring statistical significance when interpreting results.</li>
            </ul>
        </section>
    </main>

    <footer>
        <p>Written by Sidharth Oommen | <a href="mailto:sidharthoomman@gmail.com">Contact Me</a> | <a href="https://linkedin.com/in/sidharth84">LinkedIn</a></p>
    </footer>

    <script src="script.js"></script>
</body>
</html>
