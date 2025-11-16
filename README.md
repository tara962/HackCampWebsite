# HackCampWebsite

<!DOCTYPE html>

<html>

<head>
    <title>EqualEyes</title>
    <link rel="icon" type="image/x-icon" href="images\logo-removebg-preview.png">
    <link href="style.css" rel="stylesheet" type="text/css">
</head>

<body>

    <div class="top">
        <span class="left">Equal</span>

        <img class="logo" width="80px" height="80px" src="images\logo-removebg-preview.png">
        <!--src is where image is stored-->

        <span class="right">Eyes</span>
    </div>

    <div class="directory">
        <a href="https://www.instagram.com/">Home</a>
        <span>|</span>
        <a href="https://www.instagram.com/">About Us</a>
        <span>|</span>
        <a href="https://www.instagram.com/">Specifications</a>
        <span>|</span>
        <a href="https://www.instagram.com/">Contact Us</a>
        <span>|</span>
        <a href="https://www.instagram.com/">Download Now</a>
    </div>
    <!------------------------------------------->

    <div class="firstsec">
        <h2 class="fontsize">1. Font Size</h2>
        <ul>
            <li class="size">
                <p>Regular text must be at least 16 pixels large</p>
            </li>

            <li class="size">
                <p>Large-scale text must be at least 19 pixels, bolded, or 24 pixels</p>
            </li>
        </ul>

        <p class="goodexamplesize">this size is 16 px; this meets requirements</p>
        <p class="badexamplesize">this size is 12px; this fails to meet requirements</p>
    </div>

    <!-- CHANGE SIZE IS CSS FILE -->
    <!------------------------------------------->
    <div class="sections">
        <h2 class="contrastrequirements">2. Contrast</h2>
        <ul>
            <li class="contrast">
                <p>Text and images of text must have a contrast ratio of at least 4.5:1</p>
            </li>

            <li class="contrast">
                <p>Large-scale text and images of large-scale text have a contrast ratio of at least 3:1</p>
            </li>

            <li class="contrast">
                <p>Text that is part of a logo does not have any contrast requirements</p>
            </li>
        </ul>

        <img width="325px" height="100px" src="images\good contrast.png">
        <img width="300x" height="100px" src="images\bad contrast.png">
    </div>
    <!------------------------------------------->
    <div class="sections">
        <h2 class="spacingrequirements">3. Spacing</h2>
        <ul>
            <li class="spacing">
                <p>Line spacing must be at least 1.5 times the font size</p>
            </li>

            <li class="spacing">
                <p>Spacing following paragraphs must be least 2 times the font size</p>
            </li>

            <li class="spacing">
                <p>Letter spacing must be at least 0.12 times the font size</p>
            </li>

            <li class="spacing">
                <p>Word spacing must be at least 0.16 times the font size</p>
            </li>
        </ul>
    </div>

    <a href="https://www.w3.org/TR/WCAG21/">
        <p>Web Content Accessibility Guidelines</p>
    </a>
</body>

</html>