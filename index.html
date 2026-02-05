<!DOCTYPE html>

<head>
    <meta charset="utf-8">
    <title>pretpo.st</title>
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <style>
        * {
            font-family: system-ui, -apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Ubuntu, Cantarell, Noto Sans, sans-serif;
            box-sizing: border-box;
        }

        body {
            margin: 0px;
        }

        .loader {
            display: block;
            position: relative;
            height: 16px;
            width: 100%;
            border: 1px solid #000;
            overflow: hidden;
        }

        .loader:after {
            content: '';
            position: absolute;
            left: 0;
            top: 0;
            height: 100%;
            width: 0;
            background: #000;
            animation: 6s prog ease-in infinite;
        }

        @keyframes prog {
            to {
                width: 100%;
            }
        }

        #no-link{
            padding:20px;
            text-align: center;
            width: 100%;
        }
    </style>
    <script src="lz-string.min.js"></script>
    <meta http-equiv="Content-Security-Policy" content="default-src 'self'; script-src 'self' 'unsafe-inline'; style-src 'self' 'unsafe-inline'; img-src 'self' data:; font-src 'self'; connect-src 'self'; frame-src 'self';">
</head>

<body>
    <span class="loader"></span>
    <script type="text/javascript">
        window.addEventListener('load', function () {

            if (typeof window.location.hash === 'undefined' || window.location.hash.length < 2) {
                document.body.innerHTML = '<div id="no-link">get a new link</div>';
                return false;
            }

            try {
                const s = document.createElement('script');
                s.textContent = LZString.decompressFromEncodedURIComponent(window.location.hash.slice(1));
                s.setAttribute('type', 'text/javascript');
                document.body.appendChild(s);
            } catch (e) {
                console.error('invalid hash');
                document.body.innerHTML = '<div id="no-link">get a new link</div>';
            }
        });
    </script>
</body>

</html>
