# CSS-Day-6
<!DOCTYPE html>
<html>
<head>
    <title>CSS Lists and Links Styling</title>

    <style>
        /* Unordered List with Custom Bullets */
        ul.custom-list {
            list-style-type: square;   /* try: circle or square */
            padding-left: 40px;
        }

        /* Ordered List with Roman Numerals */
        ol.roman-list {
            list-style-type: upper-roman;
            padding-left: 40px;
        }

        /* Link Styles */
        .links a:link {
            color: blue;
            text-decoration: none;
        }

        .links a:visited {
            color: purple;
        }

        .links a:hover {
            text-decoration: underline;
            color: green;
        }

        .links a:active {
            color: red;
        }
    </style>
</head>

<body>

    <h2>Unordered List (Custom Bullets)</h2>
    <ul class="custom-list">
        <li>HTML</li>
        <li>CSS</li>
        <li>JavaScript</li>
    </ul>

    <h2>Ordered List (Upper Roman)</h2>
    <ol class="roman-list">
        <li>Chapter One</li>
        <li>Chapter Two</li>
        <li>Chapter Three</li>
    </ol>

    <h2>Styled Links</h2>
    <div class="links">
        <a href="https://www.google.com">Google</a><br><br>
        <a href="https://www.wikipedia.org">Wikipedia</a><br><br>
        <a href="https://www.github.com">GitHub</a>
    </div>

</body>
</html>
