---
layout: default
---

<style>
    body {
        display: flex;
        justify-content: center;
        align-items: center;
        background-color: black;
        margin: 0;
        height: 100vh;
        width: 100vw;
    }
    .container {
        border: 4px solid white;
        padding: 20px;
        text-align: center;
        margin: 20px auto;
        max-width: calc(100vw - 40px);
        max-height: calc(100vh - 40px);
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
    }
    .image-wrapper {
        margin: 20px;
        backgroundd-color: gray;
        padding: 10px;
    }
    .image-wrapper img {
        max-width: 100%;
        height: auto;
        display: block;
        margin: 0 auto;
    }
    .image-container {
        display: flex;
        flex-wrap: wrap;
        justify-content: center;
    }
</style>

<div class = "container">
    <p style = "color: white; font-size: 48px; "><strong> Need a Programmer? </strong></p>
    <p>
        <a href = "https://www.linkedin.com/in/keanu-dane-tibule-4b4009281" target="_blank" style = "color: black; display: block; margin: 0 auto; width: fit-content; background-color: white; padding: 10px 20px; text-decoration: none; border: 1px solid white; border-radius: 5px;"><strong> Click Here! </strong></a>
    </p>
    <div class = "image-container">
        <div class = "image-wrapper">
            <img src="SVGs/c%23.svg" alt="C# Logo" style= "width: 80px; height: auto;">
        </div>
        <div class = "image-wrapper">
            <img src="SVGs/c++.svg" alt="C++ Logo" style= "width: 80px; height: auto;">
        </div>
    </div>
</div>