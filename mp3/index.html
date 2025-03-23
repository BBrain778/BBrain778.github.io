<!DOCTYPE html>
<html>
<head>
    <title>YouTube to MP3 Converter</title>
    <style>
        /* 保持原有樣式 */
    </style>
</head>
<body>
    <h1>YouTube to MP3 Converter</h1>
    <div class="input-container">
        <input type="text" id="youtube_url" placeholder="Enter YouTube URL" required>
        <button onclick="convertVideo()">Convert</button>
    </div>
    <div id="download-link" class="download-link"></div>
    <div id="error" style="color: red;"></div>

    <script>
        async function convertVideo() {
            const url = document.getElementById('youtube_url').value;
            const downloadDiv = document.getElementById('download-link');
            const errorDiv = document.getElementById('error');
            downloadDiv.innerHTML = '';
            errorDiv.innerHTML = '';

            try {
                const response = await fetch('https://your-render-app.com/convert', {
                    method: 'POST',
                    headers: { 'Content-Type': 'application/json' },
                    body: JSON.stringify({ youtube_url: url })
                });
                const data = await response.json();
                
                if (data.download_link) {
                    downloadDiv.innerHTML = `<a href="${data.download_link}" download>Click here to download MP3</a>`;
                } else {
                    errorDiv.innerHTML = data.error;
                }
            } catch (e) {
                errorDiv.innerHTML = 'Error connecting to server';
            }
        }
    </script>
</body>
</html>
