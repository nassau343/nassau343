body {
    font-family: 'Georgia', serif;
    background-color: #2C2F3D; /* Dark background */
    color: #D0A96A; /* Goldish text */
    margin: 0;
    padding: 0;
}

header {
    background-color: #3E3B33;
    text-align: center;
    padding: 50px;
}

header h1 {
    font-size: 3em;
    margin-bottom: 10px;
}

header p {
    font-size: 1.2em;
    font-style: italic;
}

#nft-gallery {
    padding: 40px;
    text-align: center;
}

.gallery {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 20px;
}

.nft-item img {
    width: 100%;
    border-radius: 10px;
    box-shadow: 5px 5px 20px rgba(0, 0, 0, 0.5);
}

.buy-link {
    display: inline-block;
    margin-top: 10px;
    padding: 10px 20px;
    background-color: #F1C232;
    text-decoration: none;
    color: #2C2F3D;
    font-weight: bold;
    border-radius: 5px;
}

#about {
    background-color: #3E3B33;
    color: #D0A96A;
    padding: 40px;
    text-align: center;
}

#contact {
    padding: 40px;
    text-align: center;
}

form {
    display: flex;
    flex-direction: column;
    align-items: center;
}

form input, form textarea {
    width: 300px;
    padding: 10px;
    margin-bottom: 20px;
    border-radius: 5px;
    border: 1px solid #D0A96A;
    background-color: #3E3B33;
    color: #D0A96A;
}

form button {
    padding: 10px 20px;
    background-color: #F1C232;
    color: #2C2F3D;
    font-weight: bold;
    border-radius: 5px;
    border: none;
}

footer {
    text-align: center;
    padding: 20px;
    background-color: #3E3B33;
    color: #D0A96A;
}

footer a {
    color: #F1C232;
    text-decoration: none;
}
