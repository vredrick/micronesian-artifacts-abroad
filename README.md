# Micronesian Artifacts Abroad

A public catalog of artifacts from the Federated States of Micronesia (Pohnpei, Chuuk, Yap, Kosrae) held in museums abroad, each traced back to the museum record that holds it.

Plain static site, no build step:
- `index.html` – the whole page (HTML, CSS, JS in one file)
- `data/<state>.json` – the catalog records for each state
- `imgpack/<state>.json` and `img/` – the artifact photos

To preview locally: `python3 -m http.server` in this folder, then open http://localhost:8000
