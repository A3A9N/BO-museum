Dit is de readme file van mij opdracht van nxt museum, de url van de website is : http://127.0.0.1:5501/Code/Bo-museum.html


<style>
        body {
            font-family: 'Roboto', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f8f8f8;
            color: #333;
        }

        header, nav, footer {
            background-color: #000000;
            color: #fff;
            text-align: center;
            padding: 1em;
        }

        header h1 {
            margin: 0;
            font-size: 2em;
            display: flex;
            align-items: center;
            justify-content: center;
        }

        header a {
            color: #fff;
            text-decoration: none;
            margin-right: 10px;
            font-size: 1em;
            transition: color 0.3s ease-in-out;
        }

        header a:hover {
            color: #d3d3d3;
        }

        header img {
            max-width: 70px;
            margin-right: 10px;
        }

        nav a {
            color: #fff;
            text-decoration: none;
            margin: 0 15px;
            font-size: 1.2em;
            transition: color 0.3s ease-in-out;
        }

        nav a:hover {
            color: #848586;
        }

        section {
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
            padding: 30px;
            margin: 20px 0;
            background-color: #fff;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            border-radius: 12px;
        }

        section img {
            max-width: 50%; /* Reduced image size */
            border-radius: 8px;
            margin-bottom: 20px;
            border: 4px solid #000;
        }

        section p {
            max-width: 80%;
            margin: 0 auto;
        }

        footer {
            position: fixed;
            bottom: 0;
            width: 100%;
            font-size: 0.8em;
        }

        /* Add a new style for the active language */
        header button.active {
            background-color: #d3d3d3;
        }
    </style>