# Valorant Frontend

A responsive fan-made Valorant website featuring agents, maps, training grounds, and game information.

## Features

- Responsive layout for desktop, tablet, and mobile
- Large agent portrait cards organized by role
- Independent expandable sections for each agent role
- Competitive and training map galleries
- Accessible expandable content controls
- Smooth navigation, hover effects, and animations
- Local image assets with no build dependencies

## Built With

- HTML5
- CSS3
- Font Awesome
- Google Fonts

## Run Locally

Clone the repository:

```bash
git clone https://github.com/itssugabooo-stack/Valorant_project.git
cd Valorant_project
```

Start a local server:

```bash
python -m http.server 8000
```

Open the website:

```text
http://127.0.0.1:8000/
```

You can also open `index.html` directly in a browser, but using a local server is recommended.

## Project Structure

```text
Valorant_project/
|-- image/       # Agent and hero images
|-- mapimage/    # Map images
|-- icon/        # Icon assets
|-- index.html   # Website content and structure
|-- style.css    # Styling and responsive layouts
`-- README.md
```

## Agent Roles

- Controllers
- Duelists
- Initiators
- Sentinels

Each role initially displays three agents. Use its **See more** control to reveal the remaining agents.

## Repository

[github.com/itssugabooo-stack/Valorant_project](https://github.com/itssugabooo-stack/Valorant_project)

## Disclaimer

This is a fan-made educational project and is not affiliated with Riot Games. Valorant and related assets belong to Riot Games and their respective creators.
