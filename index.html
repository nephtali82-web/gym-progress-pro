<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>GymProgress Pro</title>
    <style>
        :root { --blue: #007bff; --bg: #121212; --card: #1e1e1e; --text: #ffffff; --green: #28a745; }
        body { font-family: sans-serif; background: var(--bg); color: var(--text); margin: 0; padding: 15px; }
        .card { background: var(--card); padding: 15px; border-radius: 15px; margin-bottom: 15px; box-shadow: 0 4px 10px rgba(0,0,0,0.3); }
        h1, h2 { color: var(--blue); margin-top: 0; }
        .btn { background: var(--blue); color: white; border: none; padding: 12px; border-radius: 8px; width: 100%; font-weight: bold; margin-top: 10px; cursor: pointer; }
        .btn-upload { background: var(--green); display: block; text-align: center; text-decoration: none; }
        .lib-content { display: none; margin-top: 15px; }
        .muscle-group { border-left: 3px solid var(--blue); padding-left: 10px; margin-bottom: 20px; }
        .exercise { background: #2a2a2a; padding: 8px; margin: 5px 0; border-radius: 5px; font-size: 14px; }
        .photo-preview-grid { display: flex; gap: 10px; overflow-x: auto; padding: 10px 0; }
        .preview-img { width: 120px; height: 120px; object-fit: cover; border-radius: 10px; border: 2px solid #333; }
        input[type="file"] { display: none; }
    </style>
</head>
<body>
    <h1>🏋️ GymPlan GitHub</h1>
    <div class="card">
        <h2>📸 Foto-Doku</h2>
        <label for="img-input" class="btn btn-upload">Foto aus Mediathek</label>
        <input type="file" id="img-input" accept="image/*" multiple>
        <div id="gallery" class="photo-preview-grid"></div>
    </div>
    <div class="card">
        <h2>📚 Bibliothek</h2>
        <button class="btn" id="toggle-lib">Ein-/Ausblenden</button>
        <div id="library" class="lib-content"></div>
    </div>
    <script>
        const data = {
            "Brust": ["Bankdrücken", "KH-Schrägbank", "Fliegende", "Dips", "Liegestütze", "Butterfly", "Cable Cross", "Brustpresse", "Überzüge", "Floor Press"],
            "Rücken": ["Klimmzüge", "Kreuzheben", "Latziehen", "Rudern (LH)", "Rudern (Sitzend)", "Hyperextensions", "Facepulls", "T-Bar Rudern", "Überzüge (Kabel)", "Einarmiges Rudern"],
            "Beine": ["Kniebeugen", "Beinpresse", "Ausfallschritte", "Beinstrecker", "Beinbeuger", "Wadenheben", "Rumänisches Kreuzheben", "Split Squats", "Goblet Squats", "Adduktoren"],
            "Schultern": ["Military Press", "Seitheben", "Frontheben", "Arnold Press", "Reverse Flys", "Shrugs", "Schulterdrücken", "Aufrechtes Rudern", "Nackendrücken", "Facepulls"],
            "Arme": ["Bizeps-Curls", "Hammer-Curls", "Trizeps-Drücken", "Dips (Bank)", "Konzentrations-Curls", "Skullcrusher", "Engbankdrücken", "SZ-Curls", "Trizeps-Kickbacks", "Spider Curls"]
        };
        const lib = document.getElementById('library');
        for (let group in data) {
            let html = `<div class="muscle-group"><h3>${group}</h3>`;
            data[group].forEach(ex => { html += `<div class="exercise">🔹 ${ex}</div>`; });
            lib.innerHTML += html + `</div>`;
        }
        document.getElementById('toggle-lib').onclick = () => {
            lib.style.display = lib.style.display === 'block' ? 'none' : 'block';
        };
        document.getElementById('img-input').onchange = (e) => {
            const gallery = document.getElementById('gallery');
            for (let file of e.target.files) {
                const reader = new FileReader();
                reader.onload = (event) => {
                    const img = document.createElement('img');
                    img.src = event.target.result;
                    img.className = 'preview-img';
                    gallery.appendChild(img);
                };
                reader.readAsDataURL(file);
            }
        };
    </script>
</body>
</html>
