# my-first-website
Learn how to recycle plastic, glass, paper, metal, and electronic waste. Protect nature, use resources efficiently, and contribute to a cleaner environment with proper recycling methods.
<!DOCTYPE html>
<html lang="tr">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>♻️ Geri Dönüşüm Rehberi</title>

<style>
  /* Google Fonts: Baloo 2 */
  @import url('https://fonts.googleapis.com/css2?family=Baloo+2&display=swap');

  /* Reset ve temel */
  * {
    box-sizing: border-box;
  }
  body {
    margin: 0;
    font-family: 'Baloo 2', cursive, Arial, sans-serif;
    background: linear-gradient(135deg, #a8edea, #fed6e3);
    color: #2c3e50;
    text-align: center;
    min-height: 100vh;
    display: flex;
    flex-direction: column;
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
    display: flex;
    flex-wrap: wrap;
    gap: 1.8rem;
    justify-content: center;
    padding: 0 1rem;
  }
  .card {
    background: #ffffffdd;
    border-radius: 20px;
    box-shadow: 0 8px 15px rgba(0,0,0,0.15);
    width: 200px;
    padding: 1.5rem 1.2rem;
    cursor: pointer;
    transition: transform 0.25s ease, box-shadow 0.25s ease;
    user-select: none;
    display: flex;
    flex-direction: column;
    align-items: center;
  }
  .card:hover {
    transform: translateY(-8px) scale(1.07);
    box-shadow: 0 12px 25px rgba(0,0,0,0.25);
  }
  .card img {
    width: 85px;
    height: 85px;
    margin-bottom: 1.2rem;
    filter: drop-shadow(1px 1px 2px rgba(0,0,0,0.2));
  }
  .card h
