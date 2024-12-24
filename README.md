<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Singles Girls</title>
    <style>
        :root {
            --image-height: 200px; /* Change this value to set the image height */
        }

        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            display: flex;
            flex-direction: column;
            align-items: center;
            background-color: #f0f0f0;
            min-height: 100vh;
        }

        header {
            background-color: #fff;
            width: 100%;
            padding: 20px 0;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            text-align: center;
            position: sticky;
            top: 0;
            z-index: 1000;
        }

        header h1 {
            font-size: 12px;
            color: #ff4d4d;
            margin: 0;
        }

        .social-icons {
            margin-top: 10px;
            display: flex;
            justify-content: center;
            gap: 10px;
        }

        .social-icons a {
            text-decoration: none;
            color: #fff;
            font-size: 10px;
            width: 30px;
            height: 30px;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            transition: background-color 0.3s ease;
        }

        .social-icons a.facebook { background-color: #3b5998; }
        .social-icons a.facebook:hover { background-color: #2d4373; }

        .social-icons a.instagram { background-color: #e1306c; }
        .social-icons a.instagram:hover { background-color: #c12b5d; }

        .social-icons a.telegram { background-color: #0088cc; }
        .social-icons a.telegram:hover { background-color: #0077b5; }

        .social-icons a.youtube { background-color: #ff0000; }
        .social-icons a.youtube:hover { background-color: #cc0000; }

        .social-icons a.tiktok { background-color: #010101; }
        .social-icons a.tiktok:hover { background-color: #333333; }

        .social-icons a.whatsapp { background-color: #25D366; }
        .social-icons a.whatsapp:hover { background-color: #1DA851; }

        .social-icons a.twitter { background-color: #1DA1F2; }
        .social-icons a.twitter:hover { background-color: #0D8ECB; }

        #frames-container {
            display: grid;
            grid-template-columns: repeat(3, 1fr); /* 3 columns */
            gap: 20px;
            max-width: 1000px;
            padding: 20px;
            box-sizing: border-box;
        }

        .frame {
            position: relative;
            width: 100%; /* Full width of the grid column */
            background-color: #fff;
            border-radius: 12px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            overflow: hidden;
            text-align: center;
        }

        .frame img {
            width: 100%;
            height: var(--image-height); /* Dynamically set the image height */
            object-fit: cover;
            cursor: pointer;
        }

        .frame .content {
            padding: 16px;
        }

        .frame .content h2 {
            font-size: 5px;
            margin: 0 0 8px;
            color: #333;
        }

        .frame .content button {
            background-color: #ff4d4d;
            border: 1px solid #ccc;
            padding: 10px 25px;
            font-size: 8px;
            color: #fff;
            border-radius: 8px;
            cursor: pointer;
        }

        .frame .content button:hover {
            background-color: #e0e0e0;
        }

        .heart-icon {
            position: absolute;
            top: 10px;
            right: 10px;
            width: 30px;
            height: 30px;
            background-color: #ff4d4d;
            color: white;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            cursor: pointer;
            font-size: 16px;
            font-weight: bold;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            transition: transform 0.2s ease, background-color 0.2s ease;
            text-decoration: none;
        }

        .heart-icon:hover {
            background-color: #d12c2c;
            transform: scale(1.1);
        }

        @media (max-width: 600px) {
            #frames-container {
                grid-template-columns: repeat(2, 1fr); /* 2 columns for smaller screens */
            }
        }

        @media (max-width: 350px) {
            #frames-container {
                grid-template-columns: 1fr; /* 1 column for very small screens */
            }
        }
        .url-button {
            padding: 0.3px 20px;
            border-radius: 8px;
            border: none;
            background: linear-gradient(135deg, #ff6a00, #ee0979);
            color: #fff;
            cursor: pointer;
            margin: 15px;
            text-decoration: none;
            text-align: center;
        }
        .url-button:hover {
            background: linear-gradient(135deg, #ff6a00, #ee0979);
            
            }
        .link-button {
            padding: 0.3px 5px;
            border-radius: 8px;
            border: 1px solid #ccc;
            background: linear-gradient(135deg, #fff, #fff);
            color: #000;
            cursor: pointer;
            margin: 15px;
            text-decoration: none;
            text-align: center;
        }
        .link-button:hover {
            background: linear-gradient(135deg, #ff6a00, #ee0979);
    </style>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css" rel="stylesheet">
</head>
<body>
    <!-- Site title -->
    <header>
        <h1><a href="https://drive.google.com/file/d/15TmwkJd8aAoe8op04SNPn5Fd58g4B-5q/view?usp=drivesdk" target="_blank" class="url-button">Open App</a></h1>
        <div class="social-icons">
            <a href="https://facebook.com" target="_blank" class="facebook"><i class="fab fa-facebook-f"></i></a>
            <a href="https://instagram.com" target="_blank" class="instagram"><i class="fab fa-instagram"></i></a>
            <a href="https://telegram.org" target="_blank" class="telegram"><i class="fab fa-telegram-plane"></i></a>
            <a href="https://youtube.com" target="_blank" class="youtube"><i class="fab fa-youtube"></i></a>
            <a href="https://tiktok.com" target="_blank" class="tiktok"><i class="fab fa-tiktok"></i></a>
            <a href="https://wa.me/" target="_blank" class="whatsapp"><i class="fab fa-whatsapp"></i></a>
            <a href="https://twitter.com" target="_blank" class="twitter"><i class="fab fa-twitter"></i></a>
        </div>
    </header>
    
    <div id="frames-container"></div>

    <script>
        // Array of data with image URLs, titles, button URLs, and heart icon URLs
        const data = [
            {
                imgUrl: "https://bit.ly/4gHMJHL",
                title: "Chat with me and find your true love 💕",
                imgClickUrl: "https://example.com/profile1",
                buttonUrl: "https://example.com/chat1",
                heartUrl: "https://bit.ly/41N5vbO"
            },
            {
                imgUrl: "https://bit.ly/49TAXap",
                title: "Chat with me to discover your soulmate 💖",
                imgClickUrl: "https://example.com/profile2",
                buttonUrl: "https://example.com/chat2",
                heartUrl: "https://example.com/love2"
            },
            {
                imgUrl: "https://bit.ly/4gqlalZ",
                title: "Chat now and uncover your heart’s desire 💗",
                imgClickUrl: "https://example.com/profile3",
                buttonUrl: "https://example.com/chat3",
                heartUrl: "https://example.com/love3"
            },
            {
                imgUrl: "https://bit.ly/4fyTFVW",
                title: "Start a chat and find your true connection 💕",
                imgClickUrl: "https://example.com/profile3",
                buttonUrl: "https://example.com/chat3",
                heartUrl: "https://example.com/love3"
            },
            {
                imgUrl: "https://via.placeholder.com/320x200?text=Image+3",
                title: "Title 3",
                imgClickUrl: "https://example.com/profile3",
                buttonUrl: "https://example.com/chat3",
                heartUrl: "https://example.com/love3"
            },
            {
                imgUrl: "https://via.placeholder.com/320x200?text=Image+3",
                title: "Title 3",
                imgClickUrl: "https://example.com/profile3",
                buttonUrl: "https://example.com/chat3",
                heartUrl: "https://example.com/love3"
            },
            {
                imgUrl: "https://via.placeholder.com/320x200?text=Image+3",
                title: "Title 3",
                imgClickUrl: "https://example.com/profile3",
                buttonUrl: "https://example.com/chat3",
                heartUrl: "https://example.com/love3"
            },
            {
                imgUrl: "https://via.placeholder.com/320x200?text=Image+3",
                title: "Title 3",
                imgClickUrl: "https://example.com/profile3",
                buttonUrl: "https://example.com/chat3",
                heartUrl: "https://example.com/love3"
            }
        ];

        // Function to create and append frames dynamically
        const createFrames = () => {
            const container = document.getElementById('frames-container');

            data.forEach((item, index) => {
                const frame = document.createElement('div');
                frame.className = 'frame';

                const img = document.createElement('img');
                img.src = item.imgUrl;
                img.alt = item.title;
                img.onclick = () => window.location.href = item.imgClickUrl;

                const heartIcon = document.createElement('a');
                heartIcon.className = 'heart-icon';
                heartIcon.href = item.heartUrl;
                heartIcon.target = "_blank";
                heartIcon.innerHTML = "&#9829";

                const content = document.createElement('div');
                content.className = 'content';

                const heading = document.createElement('h2');
                heading.textContent = item.title;

                const button = document.createElement('button');
                button.textContent = 'Start Chat';
                button.onclick = () => window.location.href = item.buttonUrl;

                content.appendChild(heading);
                content.appendChild(button);
                frame.appendChild(img);
                frame.appendChild(heartIcon);
                frame.appendChild(content);
                container.appendChild(frame);
            });
        };

        // Initialize the frames
        createFrames();
    </script>
</body>
</html>
