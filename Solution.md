## Assignment 6.2 — Backgrounds, Borders & Display

### 1. `index.html`

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Pricing Cards</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <h1>Our Plans</h1>

    <div class="card basic">
        <h2>Basic</h2>
        <p>Perfect for beginners.</p>
        <button>Choose Basic</button>
    </div>

    <div class="card standard">
        <h2>Standard</h2>
        <p>Great for students.</p>
        <button>Choose Standard</button>
    </div>

    <div class="card premium">
        <h2>Premium</h2>
        <p>Best for professionals.</p>
        <button>Choose Premium</button>
    </div>

    <h2>Display Examples</h2>
    <span class="block">Block</span>
    <span class="inline">Inline</span>
    <span class="inline-block">Inline-block</span>
</body>
</html>
```

### 2. `style.css`

```css
body {
    font-family: Arial, sans-serif;
    background: #f0f4f8;
    text-align: center;
}

.card {
    display: inline-block;
    width: 250px;
    max-width: 90%;
    min-height: 180px;
    padding: 20px;
    margin: 15px;
    border: 2px solid;
    border-radius: 15px;
}

.basic {
    background: lightblue;
    border-color: blue;
}

.standard {
    background: lightyellow;
    border-color: orange;
}

.premium {
    background: lightgreen;
    border-color: green;
}

button {
    padding: 10px 15px;
    border: none;
    border-radius: 5px;
    background: navy;
    color: white;
    cursor: pointer;
}

.block {
    display: block;
    background: lightcoral;
    margin: 10px;
}

.inline {
    display: inline;
    background: lightblue;
}

.inline-block {
    display: inline-block;
    background: lightgreen;
    width: 120px;
    height: 40px;
    margin: 10px;
    padding: 10px;
}
```

**Submission:** Save both files in the same folder and open `index.html` using Live Server. The page demonstrates three card designs and `block`, `inline`, and `inline-block` displays.