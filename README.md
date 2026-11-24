# Paulo Vitor de Campos Souza

Personal academic website of **Paulo Vitor de Campos Souza**, professor and researcher at NOVA IMS, Universidade Nova de Lisboa.

**Website:** https://pdecampossouza.github.io/  
**Contact:** [psouza@novaims.unl.pt](mailto:psouza@novaims.unl.pt)

## Explore the website

The bilingual English/Portuguese website includes Home, About Me, Research, Journey, Publications, Projects, and Teaching & students. It presents research interests, selected publications, academic and teaching experience, recognitions, an interactive conference map, and opportunities for collaboration and student projects.

## Publishing

GitHub Pages serves the **main** branch from **/(root)**. Keep `index.html`, `.nojekyll`, and the `data` directory in the repository root. No build step, package installation, or backend is required. Styles, scripts, photographs, illustrations, and map geometry are embedded in `index.html`.

## Updating the conference map

Edit `data/conferences.json` to add or update a conference. The hosted page loads this file and recalculates its map markers, list, filters, and counters.

Each entry in `visits` uses a unique `id` and includes `event`, `eventFull`, `year`, `city`, `country`, `countryCode`, `region`, `lat`, `lon`, and optional `paper` and `url`. City and country labels use `en` and `pt`. Accepted regions are `americas`, `europe`, `asia`, `africa`, and `oceania`; coordinates represent city locations. Use `null` if the year is unknown. Record future conferences in `upcoming` so they remain separate from completed visits.

The HTML also contains an embedded itinerary for offline use. When updating the downloadable offline version, synchronize its conference data with the JSON file.

## Credits

- World map: [Natural Earth](https://www.naturalearthdata.com/), [public-domain geographic data](https://www.naturalearthdata.com/about/terms-of-use/).
- Portrait: Paulo Souza's [official NOVA IMS faculty profile](https://novaims.unl.pt/en/nova-ims/teaching-staff/d/794), using the [institutional portrait](https://novaims.unl.pt/media/anrkujbf/paulo_souza.jpg).
- The oral health project illustration is conceptual artwork, not a patient photograph or clinical result.
