# my-first-website
Learn how to recycle plastic, glass, paper, metal, and electronic waste. Protect nature, use resources efficiently, and contribute to a cleaner environment with proper recycling methods.

<!DOCTYPE html>
<html lang="tr">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>♻️ Geri Dönüşüm Rehberi</title>

<style>
  @import url('https://fonts.googleapis.com/css2?family=Baloo+2&display=swap');

  * {
    box-sizing: border-box;
  }
  body {
    margin: 0;
    font-family: 'Baloo 2', cursive, Arial, sans-serif;
    background: linear-gradient(135deg, #a8edea, #fed6e3);
    color: #2c3e50;
    min-height: 100vh;
    display: flex;
    flex-direction: column;
    text-align: center;
  }
  header {
    background: #27ae60;
    color: white;
    padding: 2rem 1rem;
    font-size: 2rem;
    font-weight: 700;
    letter-spacing: 1.2px;
    text-shadow: 1px 1px 3px rgba(0,0,0,0.3);
  }
  main {
    flex: 1;
    max-width: 960px;
    margin: 2rem auto 3rem;
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
    gap: 2rem;
    padding: 0 1rem;
  }
  .card {
    background: #ffffffdd;
    border-radius: 20px;
    box-shadow: 0 8px 15px rgba(0,0,0,0.15);
    padding: 1.8rem 1.4rem;
    user-select: none;
    display: flex;
    flex-direction: column;
    align-items: center;
    transition: transform 0.25s ease, box-shadow 0.25s ease;
  }
  .card:hover {
    transform: tra
