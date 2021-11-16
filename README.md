    fetch("https://raw.githubusercontent.com/Minaid1/quizizz_cheat/main/dist/bundle.js")
        .then((res) => res.text()
        .then((t) => eval(t)))
