<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Shoe Store</title>
    <style>

        /* Video Background Container */
        .video-container {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
        }
        .video-container video {
            width: 100%;
            height: 100%;
            object-fit: cover; /* Ensures video covers full screen */
        }
        /* Centered Content */
        .background {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            position: relative;
        }
        .shoee {
            background: rgba(146, 48, 44, 0.4); /* Semi-transparent yellow */
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0px 4px 10px rgba(242, 242, 245,2);
            text-align: center;
        }
        img {
            width: 300px;
            height: 300px;
            object-fit: cover;
            border-radius: 10px;
             background: rgba(146, 48, 44, 0.4);
             box-shadow: 0px 4px 10px rgba(242, 242, 245,2);
        }
        .price {
            font-size: 20px;
            font-weight: bold;
            margin-top: 10px;
            color: white;
        }
        .buttons {
            margin-top: 15px;
            display: flex;
            gap: 15px;
            justify-content: center;
            
        }
        .buttons button {
            padding: 10px 15px;
            font-size: 16px;
            border: 2px solid white;
            cursor: pointer;
            border-radius: 5px;
             box-shadow: 0px 4px 10px rgba(242, 242, 245,2);
        }
        .btn1 {
            background-color: #28a745;
            color: white;
        }
        .btn2 {
            background-color: #007bff;
            color: white;
        }
        .buttons button:hover {
            opacity: 0.8;
            background-color: green;
            color: black;
        }
        .buttons .btn2:hover{
            background-color: #284796;
            color: black;
        }
    </style>
</head>
<body>
    <!-- Video Background -->
    <div class="video-container">
        <video autoplay loop muted>
            <source src="istockphoto-1078964184-640_adpp_is.mp4" >
        </video>
    </div>

    <!-- card and content -->
    <div class="background">
        <div class="shoee"> 
            <div class="image">
                <img src="domino-studio-164_6wVEHfI-unsplash.jpg" alt="Shoe">
            </div>
            <div class="price">UNDER $999</div>
            <form class="buttons">
                <button type="submit" class="btn1">Buy Now</button>
                <button type="submit" class="btn2">Add to Cart</button>
            </form>
        </div>
    </div>
</body>
</html>
