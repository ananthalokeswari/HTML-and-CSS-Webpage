# HTML-and-CSS-Webpage
/*This project is a simple frontend webpage designed using HTML and CSS that presents a user interface for visualizing Data Structures and Algorithms. The webpage includes a clean layout with navigation sections and a modern design to introduce algorithm visualization concepts, Technologies Used HTML CSS*/
# CSS

*{
    padding: 0;
    margin: 0;
    box-sizing: border-box;
}
.container{
    height: 100vh;
    width: 100vw;
    background-color: rgb(69, 123, 237);
}
.nav{
    height: 10%;
    width: 100%;
    background-color: rgb(115, 154, 238);
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 35px 55px;
}
.nav h1{
    font-family: Helvetica, sans-serif;
    font-weight: 700;
    font-size: 35px;
}

.nav a{
    text-decoration: none;
    color: black;
    font-family: Helvetica, sans-serif;
    padding-left: 8px;
    padding-right: 20px;
    font-size: larger;
}
img{
    height: 250px;
    width: 600px;
    border: 15px solid #DDDDDD;
}

.main{
    width: 100%;
    height: 86%;
    display: flex;
    align-items: center;
    justify-content: center;
    padding: 0px 120px;
}

.hero h1{
    font-size: 50px;
    color: white;
    font-weight: 500;
}

.hero button{
        background-color: rgb(7, 32,85);
        color: white;
        font-family: Arial, Helvetica, sans-serif;
        width: 160px;
        width: 160px;
        height: 3.5rem;
        border-radius: 15px;
        font-size: 15px;
        margin: 10px;
        border: none;
}

# HTML

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>VizAlgo</title>
    <link rel="stylesheet" href="style.css">
</head>

<body>
    <div class="container">
        <div class="nav">
            <h1>VizAlgo</h1>
            <div class="menu">
                <a href="">Home</a>
                <a href="">Dashboard</a>
                <a href="">Data Structure</a>
                <a href="">Algorithms</a>
                <a href="">About</a>
            </div>
        </div>

        <div class="main">
            <div class="hero">
                <h1>Visualize Data Structures and Algorithms</h1>
                <button>Get Started</button>
            </div>
            <img src="image.png" alt="">
        </div>

    </div>
</body>

</html>
