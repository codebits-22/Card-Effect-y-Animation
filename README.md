cat > README.md << 'EOF'
# Card-Effect-And-Animation

```bash
user@codebits:~$ ./button-effect --run
> Card Efecto y Animación con HTML y CSS puro
```
# Stack

## Código

**index.html**
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <link rel="stylesheet" href="style.css">
    <title>Document</title>
</head>
<body>
    <div class="card">
        <h2>Card Animada</h2>
        <p>Card con animacion y efecto</p>
    </div>
</body>
</html>
```

**style.css**
```css
@import url("https://fonts.googleapis.com/css2?family=Roboto:ital,wght@0,100..900;1,100..900&display=swap");

*{
    --fuente: "Roboto", san-serif;
}

body {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
  background: #0886;
  font-family: var(--fuente);
}

.card {
  background: #f7f6f5;
  padding: 20px;
  border-radius: 10px;
  text-align: center;
  cursor: pointer;
  box-shadow: 0 10px 10px rgba(0, 0, 0, 0.4);
  animation: fadeIn 1s ease-in;
  transition: transform 0.3s;
}

.card:hover {
  transform: scale(1.1);
}

@keyframes fadeIn {
  from {
    opacity: 0;
    transform: translateY(30px);
  }

  to {
    opacity: 1;
    transform: translateY(0);
  }
}
```

## Uso

```bash
git clone https://github.com/codebits-22/Card-Effect-y-Animation.git
cd Card-Effect-And-Animation
open index.html
```

## Canal

https://www.youtube.com/@codebits-22

---

> convierte lo que sabes en habilidades reales.
