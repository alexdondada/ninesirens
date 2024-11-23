<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
    <link rel="stylesheet" href="https://www.w3schools.com/lib/w3-theme-pink.css">    
    <title>Links website</title>
    <script src="https://unpkg.com/feather-icons@4.28.0/dist/feather.min.js"></script>
    <script src="https://codingfree.w3spaces-preview.com/count.js"></script>
    <script src="https://codingfree.w3spaces-preview.com/loc.js"></script>
    <style>
      
    body {
    font-family: Arial, sans-serif;
    background-color: rgb(99, 98, 98);
    background-image: url("https://i.ibb.co/ZXSBw33/ljpfq6vs04vc1.png"), url("https://i.ibb.co/ZXSBw33/ljpfq6vs04vc1.png");
    background-size: cover;
    background-position: center;
    background-repeat: no-repeat;
    background-attachment: fixed;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    margin: 0;
}

    .container {
      width: 100%;
      height: 100%;
      padding-right: 15px;
      padding-left: 15px;
      margin-right: auto;
      margin-left: auto;
    }

    .links-container {
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      gap: 20px;
    }

    .links-container a {
      width: 80%;
    }

    .w3-theme-l1:hover {
      background-color: #f279a1 !important;
    }

    .bottom {
      width: 100%;
      text-align: center;
      width: auto;
      font-weight: bolder;
    }

    .bottom span {
      color: #ed4d82;
    }

    .bottom svg {
      stroke: #ed4d82;
      fill: #ed4d82;
    }

    @media (min-width: 768px) {
      .link {
        width: 100%;
      }
    }
    @media (min-width: 576px) {
      .container {
        max-width: 540px;
      }
    }
.message-button {
    background-color: #12A5EC;
    color: white;
    border: none;
    padding: 10px 25px;
    border-radius: 6px;
    cursor: pointer;
    margin-top: 12px;
    margin-left: 32px;
    width: 80%;
    display: flex;
    align-items: center;
    justify-content: center;
    gap: 12px;
    font-size: 17px;
    font-weight: 600;
    transition: background-color 0.3s ease, transform 0.3s ease;
    text-decoration: none;
}
        .message-button:active {
            background-color: #1094d3;
            transform: scale(1.02);
        }
        .message-button:hover {
            background-color: #1094d3;
            transform: scale(1.02);
        } 
    .profile-card {
    background-color: rgba(255, 255, 255, 0.9);
    border-radius: 25px;
    width: 360px;
    text-align: center;
    box-shadow: 0 6px 12px rgba(0, 0, 0, 0.15);
    position: relative;
}
.profile-picture {
    width: 150px;
    height: 150px;
    border-radius: 50%;
    position: absolute!important;
    top: -75px;
    left: 49%;
    transform: translateX(-50%);
    border: 5px solid white;
    background-size: cover;
    background-position: center;
    background-repeat: no-repeat;
    background-color: #f0f0f0;
    overflow: hidden;
    animation: glow 1s infinite alternate;
}
.user-info {
    display: flex;
    align-items: center;
    justify-content: center;
    gap: 12px;
    margin-bottom: 0px!important;
}
.verified-icon {
    width: 20px;
    height: 20px;
    fill: #1DA1F2;
}
.status {
    background-color: #d4edda;
    color: #155724;
    font-size: 0.85em;
    padding: 4px 10px;
    border-radius: 18px;
    display: inline-flex;
    align-items: center;
    font-weight: bold;
    white-space: nowrap;
}
.status-dot {
    width: 8px;
    height: 8px;
    background-color: #2ecc71;
    border-radius: 50%;
    margin-right: 5px;
}
.info {
    margin: 6px 0;
    font-size: 1.1em;
    color: #777;
    display: flex;
    align-items: center;
    justify-content: center;
    gap: 6px;
}
.icon {
    width: 20px;
    height: 20px;
}
.sale-info {
    font-size: 1.1em;
}
.sale-percentage {
    color: #e80c0c;
    font-weight: bold;
}
.user-info h2 {
    margin: 0;
    font-size: 1.8em;
    color: #e55ca1;
}
h2 {
    font-weight: bold;
}

@keyframes glow {
  from {
    box-shadow: 0 0 10px -10px #aef4af;
  }
  to {
    box-shadow: 0 0 4px 4px #aef4af;
  }

    </style>
  </head>
  <body>
    <div class="profile-card">
      
    <div class="profile-picture"><img src="./aaa.png" width="150px" height="150px"></div>
<br><br><br><br>
      <div class="user-info">
            <h2>Alina</h2>
            <svg class="verified-icon" viewBox="0 0 24 24" aria-label="Verified account" role="img">
                <g fill="#1DA1F2">
                    <path d="M22.5 12.5c0-1.58-.875-2.95-2.148-3.6.154-.435.238-.905.238-1.4 0-2.21-1.71-3.998-3.818-3.998-.47 0-.92.084-1.336.25C14.818 2.415 13.51 1.5 12 1.5s-2.816.917-3.437 2.25c-.415-.165-.866-.25-1.336-.25-2.11 0-3.818 1.79-3.818 4 0 .494.083.964.237 1.4-1.272.65-2.147 2.018-2.147 3.6 0 1.495.782 2.798 1.942 3.486-.02.17-.032.34-.032.514 0 2.21 1.708 4 3.818 4 .47 0 .92-.086 1.335-.25.62 1.334 1.926 2.25 3.437 2.25 1.512 0 2.818-.916 3.437-2.25.415.163.865.248 1.336.248 2.11 0 3.818-1.79 3.818-4 0-.174-.012-.344-.033-.513 1.158-.687 1.943-1.99 1.943-3.484zm-6.616-3.334l-4.334 6.5c-.145.217-.382.334-.625.334-.143 0-.288-.04-.416-.126l-.115-.094-2.415-2.415c-.293-.293-.293-.768 0-1.06s.768-.294 1.06 0l1.77 1.767 3.825-5.74c.23-.345.696-.436 1.04-.207.346.23.44.696.21 1.04z"></path>
                </g>
            </svg>
            <span class="status">
                <span class="status-dot"></span>
                Online Now
            </span>
        </div>

<p class="info">
            <svg class="icon" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                <circle cx="12" cy="12" r="10"></circle>
                <polyline points="12 6 12 12 16 14"></polyline>
            </svg>
            Avg response time: 2 minutes
        </p>

<p class="info" id="visitor-location">
                    <svg class="icon" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                        <path d="M21 10c0 7-9 13-9 13s-9-6-9-13a9 9 0 0 1 18 0z"></path>
                        <circle cx="12" cy="10" r="3"></circle>
                    </svg>
                    <span id="location"></span>
                </p>

      <p style="text-align: center; padding-left: 32px; padding-right: 32px;">Hello, I love cooking and shopping. And btw I reply to all messages 👇🏻</p>
      
      

<button class="message-button" onclick="window.location.href='https://onlyspoofer.com';">
            <svg xmlns="http://www.w3.org/2000/svg" width="1em" height="1em" viewBox="0 0 24 24"><path fill="currentColor" d="M24 4.003h-4.015c-3.45 0-5.3.197-6.748 1.957a7.996 7.996 0 1 0 2.103 9.211c3.182-.231 5.39-2.134 6.085-5.173c0 0-2.399.585-4.43 0c4.018-.777 6.333-3.037 7.005-5.995M5.61 11.999A2.391 2.391 0 0 1 9.28 9.97a2.966 2.966 0 0 1 2.998-2.528h.008c-.92 1.778-1.407 3.352-1.998 5.263A2.392 2.392 0 0 1 5.61 12Zm2.386-7.996a7.996 7.996 0 1 0 7.996 7.996a7.996 7.996 0 0 0-7.996-7.996m0 10.394A2.399 2.399 0 1 1 10.395 12a2.396 2.396 0 0 1-2.399 2.398Z"></path></svg>
            Send me a message
        </button> 
    

<p class="sale-info">
            <span class="sale-percentage">80% OFF</span> sale ends in <span id="demo" style="font-weight: 600";></span>
        </p>


      <!-- Bottom section 3 -->
      <div class="bottom margin-top-2 w3-padding w3-round">
        <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="feather feather-heart"><path d="M20.84 4.61a5.5 5.5 0 0 0-7.78 0L12 5.67l-1.06-1.06a5.5 5.5 0 0 0-7.78 7.78l1.06 1.06L12 21.23l7.78-7.78 1.06-1.06a5.5 5.5 0 0 0 0-7.78z"></path></svg>
        <span style="vertical-align: 7px;"> 2021 - Jane Doe</span>
        <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="feather feather-heart"><path d="M20.84 4.61a5.5 5.5 0 0 0-7.78 0L12 5.67l-1.06-1.06a5.5 5.5 0 0 0-7.78 7.78l1.06 1.06L12 21.23l7.78-7.78 1.06-1.06a5.5 5.5 0 0 0 0-7.78z"></path></svg>
      </p>
    </div>
    <script>
      feather.replace()
    </script>
  </body>  
</html>
