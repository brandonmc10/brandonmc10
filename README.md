<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Daft Brewery Customer Survey</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            color: #333;
            margin: 0;
            padding: 0;
        }
        .container {
            max-width: 600px;
            margin: 2rem auto;
            background: #fff;
            padding: 2rem;
            border-radius: 10px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
        }
        h1 {
            text-align: center;
            color: #d35400;
        }
        p {
            text-align: center;
            font-size: 1.1rem;
        }
        label {
            display: block;
            margin: 1rem 0 0.5rem;
            font-weight: bold;
        }
        input, textarea, select {
            width: 100%;
            padding: 0.5rem;
            margin-bottom: 1rem;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        button {
            background-color: #d35400;
            color: white;
            border: none;
            padding: 0.75rem 1.5rem;
            font-size: 1rem;
            border-radius: 5px;
            cursor: pointer;
        }
        button:hover {
            background-color: #e67e22;
        }
        .rating label {
            display: inline-block;
            margin-right: 0.5rem;
        }
        .rating input {
            margin-right: 0.5rem;
        }
        .footer {
            text-align: center;
            font-size: 0.8rem;
            margin-top: 2rem;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>🍺 Daft Brewery Survey 🍺</h1>
        <p>We want to make your Daft experience even more awesome! Share your thoughts below. 🍻</p>
        <form>
            <label for="name">Name (Optional):</label>
            <input type="text" id="name" name="name" placeholder="Your name (or beer alias)">

            <label for="email">Email (Optional):</label>
            <input type="email" id="email" name="email" placeholder="Your email">

            <label for="rating">How would you rate your experience?</label>
            <div class="rating">
                <label><input type="radio" name="rating" value="1"> 1 (Meh)</label>
                <label><input type="radio" name="rating" value="2"> 2</label>
                <label><input type="radio" name="rating" value="3"> 3</label>
                <label><input type="radio" name="rating" value="4"> 4</label>
                <label><input type="radio" name="rating" value="5"> 5 (Cheers!)</label>
            </div>

            <label for="favorite-beer">What's your favorite Daft brew?</label>
            <input type="text" id="favorite-beer" name="favorite-beer" placeholder="Name of the beer">

            <label for="feedback">What could we do better?</label>
            <textarea id="feedback" name="feedback" rows="4" placeholder="Let us know!"></textarea>

            <label for="visit-frequency">How often do you visit Daft Brewery?</label>
            <select id="visit-frequency" name="visit-frequency">
                <option value="weekly">Weekly</option>
                <option value="monthly">Monthly</option>
                <option value="occasionally">Occasionally</option>
                <option value="first-time">This is my first time!</option>
            </select>

            <button type="submit">Submit Feedback 🍻</button>
        </form>
        <div class="footer">
            <p>Thank you for helping us make Daft Brewery the best place in Kingston! 💛</p>
        </div>
    </div>
</body>
</html>
